# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.13.1)
set(DTC_OVERLAY_FILE "nrf52dk_nrf52832.overlay")
find_package(Zephyr HINTS $ENV{ZEPHYR_BASE})
project(rgb_led)

target_sources(app PRIVATE src/main.c)
