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
sha512sums=('bb0378f46914fa1f11beb68ae52762ed07a403019730406c095f4fde8032a125c5ca47d505222eeee0e35caf936d01d21dd6154108ad1ab03b5725fb7381c2bd')

package() {
	tar xf data.tar.xz -C "${pkgdir}"
}
