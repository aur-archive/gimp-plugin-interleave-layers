# Maintainer: James Reed <supplantr at archlinux dot info>

_basename=interleave-layers
pkgname=gimp-plugin-$_basename
pkgver=0.4
pkgrel=1
pkgdesc="Interleaves or merges two stacks of layers, with a specified mode and opacity for one of the stacks."
arch=('any')
url="http://registry.gimp.org/node/25987"
license=('GPL3')
depends=('gimp')
source=("http://downloads.sourceforge.net/project/gimp-tools/scripts/interleave-layers-0.4.py")
md5sums=('89c4be088c50287ed0c0afb96c0b6287')

package() {
  cd "$srcdir/"
  install -Dm755 $_basename-$pkgver.py "${pkgdir}/usr/lib/gimp/2.0/plug-ins/$_basename-$pkgver.py"
}
