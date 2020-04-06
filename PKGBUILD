# Maintainer: Ben Standerline <standerlineben(at)g(mail)(dot)c()m>
pkgname=DesktopIcons
pkgver=1.0
pkgrel=2
pkgdesc='A pack of icons that I use in my desktop environment'
arch=('any')
license=('GPL 3.0')
url='https://github.com/thelioncape/DesktopIcons'
depends=('fontconfig' 'xorg-font-utils')

source=("https://github.com/thelioncape/DesktopIcons/archive/v1.0.tar.gz")

sha256sums=('e99ae04d4f51909728a904e32527f5e7dfb74631e3b57d8fb0e078d1a9485914')

package() {
	cd "$srcdir/$pkgname-$pkgver/fonts/fonts"

	install -d $pkgdir/usr/share/fonts/misc/TTF/DesktopIcons

	install -m644 DesktopIcons.ttf $pkgdir/usr/share/fonts/TTF/DesktopIcons
}
