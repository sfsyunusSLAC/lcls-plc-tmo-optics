IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.5
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := lcls-plc-tmo-optics
PROJECT_PATH := ../../lcls-plc-tmo-optics/lcls-plc-tmo-optics.tsproj
PLC := tmo_optics

PYTMC_OPTS := 
PREFIX := PLC:TMO:OPTICS

include $(IOC_TOP)/iocBoot/templates/Makefile.base
