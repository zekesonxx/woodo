# shellcheck shell=bash
# shellcheck disable=SC2034,SC2148,SC2154
# Maintainer: Zeke Sonxx <zeke@zekesonxx.com>
pkgname=sudowoodo
pkgver=1.0
pkgrel=1
pkgdesc="sudowoodo"
arch=('any')
url="https://github.com/zekesonxx/woodo"
license=('ZPL')
groups=()
depends=()
makedepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
source=("woodo.sh")
noextract=()
md5sums=('7c3036d16ccfcbbbb7bd57123da01e20')
sha512sums=('90131b0cb5580b20172f3918f7aa7be16d87fe4a99920f043ecaab9876c8337c73f4cca4d87fd90228368eba231f3525d525703475c350e15b2c1f5d34071ad3')

package() {
	install -D -m755 "${srcdir}/woodo.sh" "${pkgdir}/usr/bin/woodo"
}
