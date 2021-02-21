# Builds CForth for Teensy 3

TOPDIR=../..

include $(TOPDIR)/src/app/arm-rp2040/targets.mk

default: app.elf app.hex app.nm app.dump check-pico-env


check-pico-env:
ifndef PICO_SDK_PATH
	$(error PICO_SDK_PATH is undefined, please install the PICO SDK)
endif
