# Maintainer:  Ali <alinuxrc@proton.me>

pkgname=akebi
pkgver=1.0
pkgrel=1
pkgdesc='Simple Bash Script to Show System Information'
arch=('any')
url='https://github.com/herobuxx/akebi'
license=('MIT')
depends=(
		'xorg-xrandr'
		'lsb-release')
source=("$pkgname::https://raw.githubusercontent.com/herobuxx/akebi/main/akebi")
sha256sums=('SKIP')

package() {
	mkdir -p "$pkgdir/usr/bin"
	cp -r "$srcdir/$pkgname" "$pkgdir/usr/bin"
	chmod +x "$pkgdir/usr/bin/$pkgname"
}
