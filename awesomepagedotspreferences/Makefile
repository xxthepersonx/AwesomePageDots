include $(THEOS)/makefiles/common.mk

ARCHS = arm64 arm64e

BUNDLE_NAME = AwesomePageDotsPreferences
AwesomePageDotsPreferences_FILES = APDRootListController.m
AwesomePageDotsPreferences_INSTALL_PATH = /Library/PreferenceBundles
AwesomePageDotsPreferences_FRAMEWORKS = UIKit
AwesomePageDotsPreferences_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/AwesomePageDotsPreferences.plist$(ECHO_END)
