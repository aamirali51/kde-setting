# Maintainer: Aamir Abdullah
pkgname=kde-setting
_destname1="/"
pkgver=1.1
pkgrel=1
pkgdesc="KDE RICE @NORDIC FOR PAKOS"
arch=('any')
url="https://github.com/aamirali51/"
license=('GPL3')
makedepends=('git')
depends=()
conflicts=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}
