# A Makefile for cppsupport

include $(LITEOSTOPDIR)/config.mk

MODULE_NAME := $(notdir $(CURDIR))

LOCAL_SRCS := $(wildcard *.c)

LOCAL_INCLUDE := \
	-I $(LITEOSTOPDIR)/kernel/extended/include

LOCAL_FLAGS := $(LOCAL_INCLUDE) $(LITEOS_GCOV_OPTS)

include $(MODULE)
