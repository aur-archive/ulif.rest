# Maintainer: Tim Hartman <tbhartman at gmail>
pkgname=ulif.rest
pkgver=0.1.0
pkgrel=1
pkgdesc="Python ReStructuredText extensions"
arch=(any)
url="http://pypi.python.org/pypi/ulif.rest"
license=("unknown")
makedepends=('python2-distribute')
depends=('python2>=2.7.2-2')
source=("http://pypi.python.org/packages/source/u/${pkgname}/${pkgname}-${pkgver}.tar.gz")
md5sums=('e5e1909a7ddc851f51b84423f791fb19')

package() {
  mkdir -p "${pkgdir}/usr/lib/python2.7/site-packages" && cd "$_"
  cp -a "${srcdir}/${pkgname}-${pkgver}/src/ulif" .
}
