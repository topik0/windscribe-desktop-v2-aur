# Maintainer: Topik topik@topik.tech
pkgname=windscribe
pkgver=2.3.11_beta
pkgrel=1
pkgdesc="A port of Windscribe's desktop client"
arch=('x86_64')
url="https://github.com/Windscribe/desktop-v2"
license=('GPL-2.0')
depends=('bash' 'iptables')
install=${pkgname}.install
source=("https://github.com/topik0/windscribe-desktop-v2-aur/releases/download/v2.3.11_beta/windscribe_2.3.11_beta_amd64.deb")
sha512sums=('76f94461421c5c9572d05428f054773f7dd71fa08f445f1940bc0930d0a8a755e37143c3ed9ac5d9f54da7a3a3cb103b3233a60b30ba145f605955a4a81eafd5')

package() {
	tar xf data.tar.xz -C "${pkgdir}"
}
