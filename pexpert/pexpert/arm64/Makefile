export MakeInc_cmd=${SRCROOT}/makedefs/MakeInc.cmd
export MakeInc_def=${SRCROOT}/makedefs/MakeInc.def
export MakeInc_rule=${SRCROOT}/makedefs/MakeInc.rule
export MakeInc_dir=${SRCROOT}/makedefs/MakeInc.dir

include $(MakeInc_cmd)
include $(MakeInc_def)

DATAFILES = \
	AIC.h \
	arm64_common.h \
	board_config.h \
	boot.h \
	S3c2410x.h \
	S5L8960X.h \
	T7000.h \
	S8000.h \
	T8010.h \
	cyclone.h \
	typhoon.h \
	twister.h \
	hurricane.h


INSTALL_MD_LIST	= ${DATAFILES}

INSTALL_MD_DIR = pexpert/arm64

EXPORT_MD_LIST	= ${DATAFILES}

EXPORT_MD_DIR = pexpert/arm64

include $(MakeInc_rule)
include $(MakeInc_dir)
