#
# Copyright (C) 2009-2013 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=lualogging
PKG_SOURCE_VERSION:=6d5e40c324c84d9c1453ae88e0ad5bdd0a631448
PKG_VERSION:=1.3.0
PKG_RELEASE:=1

PKG_SOURCE:=$(PKG_NAME)-$(PKG_VERSION).tar.bz2
PKG_SOURCE_URL:=https://github.com/che/aeolus.git
PKG_SOURCE_PROTO:=git
PKG_SOURCE_SUBDIR:=$(PKG_NAME)-$(PKG_VERSION)

include $(INCLUDE_DIR)/package.mk

define Package/lualogging
    SUBMENU:=Lua
    SECTION:=lang
    CATEGORY:=Languages
    TITLE:=LuaLogging
    URL:=https://github.com/che/aeolus
    MAINTAINER:=Pavel Chebotarev <pavel.chebotarev@gmail.com>
    DEPENDS:=+lua
endef

define Package/lualogging/description
endef

define Build/Configure
endef

define Build/Compile
endef


define Package/lualogging/install
endef

$(eval $(call BuildPackage,lualogging))
