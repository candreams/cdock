include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = CDockPreferences
CDockPreferences_FILES = cdpRootListController.m
CDockPreferences_INSTALL_PATH = /Library/PreferenceBundles
CDockPreferences_FRAMEWORKS = UIKit
CDockPreferences_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/CDockPreferences.plist$(ECHO_END)
