#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Freifunk DHCP-Splash application
LUCI_DEPENDS:=+luci-compat +luci-lib-nixio +luci-lib-iptparser +luci-lua-runtime +tc +kmod-sched

define Package/luci-app-splash/conffiles
/etc/config/luci_splash
/usr/lib/luci-splash/splashtext.html
/usr/lib/luci-splash/splashtextinclude.html
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
