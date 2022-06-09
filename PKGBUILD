# Maintainer:  Ali <alinuxrc@proton.me>

pkgname=akebi
pkgver=1.1
pkgrel=1
pkgdesc='Simple Bash Script to Show System Information'
arch=('any')
url='https://github.com/herobuxx/akebi'
license=('MIT')
depends=('xorg-xrandr' 'lsb-release' 'wget')
source=("$pkgname::https://raw.githubusercontent.com/herobuxx/akebi/main/akebi")
sha256sums=('7af54517090202be16b21441ccfb153f141879d847d5d3d4975487a18b3593d7')

package() {
	install -D -t "$pkgdir/usr/bin" "$srcdir/$pkgname"
}
