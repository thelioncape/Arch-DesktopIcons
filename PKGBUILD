# Maintainer: Ben Standerline <standerlineben(at)g(mail)(dot)c()m>
pkgname=DesktopIcons
pkgver=1.0.1
pkgrel=1
pkgdesc='A pack of icons that I use in my desktop environment'
arch=('any')
license=('GPL 3.0')
url='https://github.com/thelioncape/DesktopIcons'
optdepends=('fontconfig' 'xorg-font-utils')

source=("https://github.com/thelioncape/DesktopIcons/releases/download/v1.0.1/DesktopIcons.ttf")

sha256sums=('70ef0a590d252485d164f644bb5afd50796f43a8cedaec2ca7dac0d958c07111')

package() {
	cd "$srcdir"

	install -d $pkgdir/usr/share/fonts/TTF/DesktopIcons

	install -m644 DesktopIcons.ttf $pkgdir/usr/share/fonts/TTF/DesktopIcons
}
