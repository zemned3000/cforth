# Builds CForth for ESP8266

TOPDIR=../..
UPDIR=$(realpath $(TOPDIR)/..)

# CONFIG += -DBITS32 -DT16
CONFIG += -DBITS32

CFLAGS += -m32

CC := gcc

# Change these to reflect the locations of external stuff on your system,
# either here or on the command line, e.g. COMPORT=COM27 make download
SDK_PARENT_PATH ?= $(UPDIR)
NODEMCU_PARENT_PATH ?= $(UPDIR)
COMPORT ?= COM36

XT_COMPILER = $(UPDIR)/xtensa

include $(TOPDIR)/src/app/esp8266/targets.mk
