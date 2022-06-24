dtb-$(CONFIG_MACH_XIAOMI_ULYSSE) += msm8917-pmi8937-mtp-ugglite.dtb
dtb-$(CONFIG_MACH_XIAOMI_ULYSSE) += msm8940-pmi8937-mtp-ugg.dtb
dtb-$(CONFIG_MACH_XIAOMI_RIVA_OREO) += msm8917-pmi8937-qrd-sku5-riva-Oreo.dtb
#dtb-$(CONFIG_MACH_XIAOMI_ROVA) += msm8917-pmi8937-qrd-sku5-riva.dtb
ifneq ($(CONFIG_MACH_XIAOMI_RIVA_OREO),y)
dtb-$(CONFIG_MACH_XIAOMI_ROVA) += msm8917-pmi8937-qrd-sku5-rolex.dtb
endif
dtb-$(CONFIG_MACH_XIAOMI_TIARE) += msm8917-pmi8937-qrd-sku5-tiare.dtb
dtb-$(CONFIG_MACH_XIAOMI_LAND) += msm8937-pmi8950-qrd-land.dtb
dtb-$(CONFIG_MACH_XIAOMI_SANTONI) += msm8940-pmi8950-qrd-sku7-santoni.dtb
dtb-$(CONFIG_MACH_XIAOMI_PRADA) += msm8937-pmi8950-mtp-prada.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
