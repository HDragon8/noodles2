# Copyright 2023 MOSSDeF, Stan Grishin (stangri@melmac.ca)
# This is free software, licensed under the GNU General Public License v3.

include $(TOPDIR)/rules.mk

PKG_LICENSE:=GPL-3.0-or-later
PKG_MAINTAINER:=Stan Grishin <stangri@melmac.ca>
PKG_VERSION:=1.1.1-r7

LUCI_TITLE:=AdBlock-Fast Web UI
LUCI_DESCRIPTION:=Provides Web UI for adblock-fast service.
LUCI_DEPENDS:=+luci-base +adblock-fast +jsonfilter
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
