#
# Copyright (c) 2021 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-BSD-5-Clause-Nordic
#

target_sources(app PRIVATE
	       ${CMAKE_CURRENT_SOURCE_DIR}/ml_result_event.c
	       ${CMAKE_CURRENT_SOURCE_DIR}/sensor_event.c
)
