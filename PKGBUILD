# Maintainer: Obux <obux[AT]obux[DOT]cl>
pkgname=matrilineare-icon-theme
pkgver=0.2
pkgrel=1
pkgdesc="Trying to combine the simplicity of Elementary with the perfection of Faenza"
arch=('any')
url="http://sora-meliae.deviantart.com/art/Matrilineare-version-0-2-321379531"
license=('GPL')
groups=()
depends=()
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("http://www.deviantart.com/download/321379531/matrilineare__version_0_2__by_sora_meliae-d5bca17.zip")
noextract=()
md5sums=('48e9d933b4db1f622cd40cb2f609cd27')

package() {
  install -dm755 "$pkgdir/usr/share/icons/"
  cp -rf $srcdir/$pgkname "$pkgdir/usr/share/icons/"
}