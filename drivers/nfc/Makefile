#
# Makefile for nfc devices
#

obj-$(CONFIG_NFC_PN544)		+= pn544/
obj-$(CONFIG_NFC_MICROREAD)	+= microread/
obj-$(CONFIG_NFC_PN533)		+= pn533.o
obj-$(CONFIG_NFC_WILINK)	+= nfcwilink.o
obj-$(CONFIG_NFC_MEI_PHY)	+= mei_phy.o
obj-$(CONFIG_NFC_SIM)		+= nfcsim.o
obj-$(CONFIG_NFC_PORT100)	+= port100.o
obj-$(CONFIG_NFC_MRVL)		+= nfcmrvl/
obj-$(CONFIG_NFC_TRF7970A)	+= trf7970a.o
obj-$(CONFIG_NFC_ST21NFCA)  	+= st21nfca/
obj-$(CONFIG_NFC_ST21NFCB)	+= st21nfcb/
ifdef CONFIG_SOC_EXYNOS7880
obj-$(CONFIG_SEC_NFC)		+= sec_nfc_7880.o
else
obj-$(CONFIG_SEC_NFC)		+= sec_nfc.o
endif
obj-$(CONFIG_ESE_P3_LSI)        += ese_p3.o
obj-$(CONFIG_NFC_FELICA)        += bu80003gul.o

ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG
