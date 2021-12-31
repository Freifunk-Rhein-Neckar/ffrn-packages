include $(TOPDIR)/rules.mk

PKG_NAME:=ffrn-change-autoupdater-branch-eoldevices
PKG_VERSION:=v2021.1
PKG_RELEASE:=1

include $(TOPDIR)/../package/gluon.mk


define Package/ffrn-change-autoupdater-branch-eoldevices
  TITLE:=Change autoupdater branch of EOL Devices
  DEPENDS:=+gluon-core
endef

define Package/ffrn-change-autoupdater-branch-eoldevices/description
	Change autoupdater branch of EOL devices so that they accumulate in a single branch
endef

$(eval $(call BuildPackageGluon,ffrn-change-autoupdater-branch-eoldevices))
