# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2017 NXP

include $(RTE_SDK)/mk/rte.vars.mk

ifeq ($(CONFIG_RTE_LIBRTE_DPAA_BUS),y)
DIRS-$(CONFIG_RTE_LIBRTE_DPAA_MEMPOOL) += dpaa
endif
ifeq ($(CONFIG_RTE_EAL_VFIO)$(CONFIG_RTE_LIBRTE_FSLMC_BUS),yy)
DIRS-$(CONFIG_RTE_LIBRTE_DPAA2_MEMPOOL) += dpaa2
endif
DIRS-$(CONFIG_RTE_DRIVER_MEMPOOL_RING) += ring
DIRS-$(CONFIG_RTE_DRIVER_MEMPOOL_STACK) += stack
DIRS-$(CONFIG_RTE_LIBRTE_OCTEONTX_MEMPOOL) += octeontx

include $(RTE_SDK)/mk/rte.subdir.mk
