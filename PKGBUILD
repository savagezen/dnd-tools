# Maintainer: Austin Haedicke (gtbjj @ GitHub)

pkgname=dnd-tools
pkgver=1
pkgrel=1
pkgdesc='Interactive CLI tools for Dungeons and Dragons 5e'
depends=('python')
makedepends=('git' 'python')
arch=('i686' 'x86_64')
url='https://github.com/gtbjj/dnd-tools'
license=('AGPLv3')
provides=('dnd-tools')
source=(git://github.com/gtbjj/dnd-tools.git)
sha256sums=('SKIP')

pkgver() {
  cd ${pkgname}
  git rev-parse --short HEAD
}

package() {
  cd ${srcdir}/${pkgname} 
  python setup.py install --root="$pkgdir"
  cp ${srcdir}/${pkgname}/LICENSE /usr/share/licenses/${pkgname}/LICENSE
}
