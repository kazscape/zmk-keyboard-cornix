# SPDX-License-Identifier: MIT

# Provide compatibility for external modules that still use the pre-Zephyr-4
# endpoint helper name from older ZMK revisions.
zephyr_compile_definitions(zmk_endpoints_selected=zmk_endpoint_get_selected)
