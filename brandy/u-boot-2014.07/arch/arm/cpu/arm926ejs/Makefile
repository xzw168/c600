#
# (C) Copyright 2000-2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# SPDX-License-Identifier:	GPL-2.0+
#

extra-y	:= start.o
extra-y	+= spare_head.o
extra-y	+= uboot_hash.o
obj-y	+= cache.o
obj-y	+= cpu.o 

ifdef	CONFIG_SPL_BUILD
ifdef	CONFIG_SPL_NO_CPU_SUPPORT_CODE
extra-y	:=
endif
endif
