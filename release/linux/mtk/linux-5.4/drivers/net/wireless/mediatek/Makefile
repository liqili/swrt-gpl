# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_MT7601U)	+= mt7601u/
#obj-$(CONFIG_MT76_CORE)	+= mt76/
#ifneq ($(CONFIG_MODEL_RTAX53U),)
#obj-$(CONFIG_MODEL_RTAX53U) += mt_wifi_7915_v7400/mt_wifi_ap/
#endif
ifneq ($(CONFIG_MODEL_RTAX54),)
obj-$(CONFIG_MODEL_RTAX54) += mt_wifi_7915_v7400/mt_wifi_ap/
endif
ifneq ($(CONFIG_MODEL_RT4GAX56),)
obj-$(CONFIG_MODEL_RT4GAX56) += mt_wifi_7915_v7400/mt_wifi_ap/
endif
obj-$(CONFIG_MODEL_RTAX53U) += mt7915/7.4.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_RTAC85U) += mt7615/5.1.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_RTAC85P) += mt7615/5.1.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_R6800) += mt7615/5.1.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_RMAC2100) += mt7615/5.1.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_RMAC2100) += mt7603/4.1.2.1/mt7603_wifi_ap/
obj-$(CONFIG_MODEL_PGBM1) += mt7915/7.4.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_JCGQ10PRO) += mt7915/7.4.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_H3CTX1801) += mt7915/7.4.0.0/mt_wifi_ap/
obj-$(CONFIG_MODEL_RMAX6000) += mt7986/mt_wifi_ap/
obj-$(CONFIG_MODEL_RMAX6000) += mt7986/warp_driver/warp/
ifeq ($(wildcard drivers/net/wireless/mediatek/conninfra/Makefile),)
obj-$(CONFIG_MODEL_RMAX6000) += mt7986_prebuild/
else
obj-$(CONFIG_MODEL_RMAX6000) += conninfra/
endif
