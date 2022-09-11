include $(TOPDIR)/rules.mk

PKG_NAME:=ffrn-change-autoupdater-branch-nightly
PKG_VERSION:=v2021.1
PKG_RELEASE:=1

include $(TOPDIR)/../package/gluon.mk


define Package/ffrn-change-autoupdater-branch-nightly
  TITLE:=Change autoupdater branch of all nightly devices
  DEPENDS:=+gluon-core
endef

define Package/ffrn-change-autoupdater-branch-nightly/description
	Change autoupdater branch of devices in the nightly branch to stable
	It has been a long time since the last major stable version and many
	didn't have another option then nightly.
endef

$(eval $(call BuildPackageGluon,ffrn-change-autoupdater-branch-nightly))
