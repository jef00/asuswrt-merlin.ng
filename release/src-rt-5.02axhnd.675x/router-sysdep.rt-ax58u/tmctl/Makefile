
EXE = tmctl
ifneq ($(strip $(BUILD_TMCTL)),)
all:
	@cp -f prebuilt/$(EXE) .

install: generic_exe_install
else
all:
install:
endif
clean:

dynamic: all install

include $(BUILD_DIR)/make.common
