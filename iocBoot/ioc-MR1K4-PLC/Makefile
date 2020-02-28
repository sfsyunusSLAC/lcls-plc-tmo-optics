IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := MR1K4
PROJECT_PATH := ../../MR1K4/MR1K4.tsproj
PLC := MR1K4_PLC

PYTMC_OPTS := 
PREFIX := PREFIX

include $(IOC_TOP)/iocBoot/templates/Makefile.base
