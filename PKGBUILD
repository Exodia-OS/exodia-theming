#
# Maintainer: Mahmoud Mohamed (Ozil) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-themes
pkgver=1.0
pkgrel=6
pkgdesc="Themes For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-themes"
license=('GPL3')

prepare() {

	cp -af ../themes/. ${srcdir}

}

package() {

	local themes_dir=${pkgdir}/usr/share/themes
	mkdir -p "$themes_dir"
	cp -r ${srcdir}/* "$themes_dir"

}
