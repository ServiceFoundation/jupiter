# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2017 Intel Corporation

# meson file, for building this example as part of a main DPDK build.
#
# To build this example as a standalone application with an already-installed
# DPDK instance, use 'make'

ext_deps += cc.find_library('pqos')
allow_experimental_apis = true
cflags += '-D_GNU_SOURCE'
cflags += '-I/usr/local/include' # assume pqos lib installed in /usr/local
sources = files(
	'cat.c', 'l2fwd-cat.c'
)
