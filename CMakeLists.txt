#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#

if (CONFIG_MCUX_COMPONENT_middleware.tinycbor)
    mcux_add_source(
        SOURCES src/cbor.h src/cborencoder.c src/cborencoder_close_container_checked.c src/cborerrorstrings.c src/cborinternal_p.h src/cborparser.c src/compilersupport_p.h src/tinycbor-version.h src/utf8_p.h
    )
    mcux_add_include(
        INCLUDES src
    )
endif()
