################################################################################
# FrameBuffer Driver for Display
#
#
################################################################################

######################################
#obj-$(CONFIG_MTK_FB) += common/
ifneq ($(filter y,$(CONFIG_ARCH_MT8127) $(CONFIG_ARCH_MT7623) $(CONFIG_ARCH_MT8590)),)
CONFIG_MTK_PLATFORM := mt8127
endif

obj-$(CONFIG_MTK_FB) += $(subst ",,$(CONFIG_MTK_PLATFORM))/
obj-$(CONFIG_ARCH_MT6735) += common/
obj-$(CONFIG_ARCH_MT6735M) += common/
obj-$(CONFIG_ARCH_MT6753) += common/
obj-$(CONFIG_ARCH_MT6580) += common/
obj-$(CONFIG_ARCH_MT6755) += common/
obj-$(CONFIG_ARCH_MT6797) += common/
