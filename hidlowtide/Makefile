include $(THEOS)/makefiles/common.mk

# use latest SDK but use iOS 4.0 as deployment target
export TARGET=iphone:latest:6.0

TWEAK_NAME = hidlowtide
hidlowtide_FILES = Tweak.xm
hidlowtide_CFLAGS = -I../3rdParty/RocketBootstrap/include/

include $(FW_MAKEDIR)/tweak.mk
