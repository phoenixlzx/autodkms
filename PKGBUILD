# Maintainer: phoenixlzx <phoenixlzx at archlinuxcn.org>

pkgname=autodkms
pkgver=0.1
pkgrel=1
pkgdesc="mkinitcpio hook to compile all dkms modules"
url=""
arch=('any')
license=('MIT')
depends=('dkms')
install=autodkms.install

package() {
  cd "${srcdir}"
  install -dm 755 "${pkgdir}"/usr/lib/initcpio/install
  install -m 644 autodkms "${pkgdir}"/usr/lib/initcpio/install/autodkms
}
