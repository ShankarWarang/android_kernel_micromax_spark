include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-$(CONFIG_MTK_MEMCFG) += mtk_memcfg.o
obj-y += mtk_meminfo.o
ifeq ($(CONFIG_MTK_AEE_MRDUMP),)
obj-$(CONFIG_OF_FLATTREE) += mtk_mrdump_setup.o
endif
