# Maintainer: "Douglas Chimento" dougEfresh
pkgname=aws-dyndns
pkgver=1.0.4
pkgrel=1
epoch=1
pkgdesc="${pkgname}"
arch=('any')
url="https://github.com/dougEfresh/aur"
license=('custom')
options=('!strip')
depends=('systemd')
source=("https://github.com/dougEfresh/aws-dyndns/releases/download/v${pkgver}/${pkgname}.gz")
sha256sums=('ea8a19e43f228c0a1bca80134cb09090c1e842b6714ab1eb5f1a4aa522d6e46a')
#install=$pkgname.install

package() {
    install -Dm755 ${srcdir}/${pkgname}  -t "${pkgdir}"/usr/bin/
}





