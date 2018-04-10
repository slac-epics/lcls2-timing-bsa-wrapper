TOP=..

include $(TOP)/configure/CONFIG

CFG += CONFIG_BSA

TARGETS = $(CONFIG_TARGETS)
CONFIGS += $(subst ../,,$(wildcard $(CONFIG_INSTALLS)))

include $(TOP)/configure/RULES
