pkgname=astiankiso
pkgver=25
pkgrel=1
pkgdesc="Tools for creating Astian live and install iso images"
arch=('any')
url="https://github.com/OSAstian/astiankiso"
license=('GPL')
depends=('archiso')

package() {
  cd "$pkgdir"
  install -Dm755 "$srcdir/usr/bin/astiankiso" usr/bin/astiankiso
