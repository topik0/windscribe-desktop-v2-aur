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
sha512sums=('398ab10d60304535fb56347fd31e2f4db5976ee8e3b022d33d99fd7f66422fd30d25c66a33a0d77ab9035a6d5779eb36846bd9d6470ddfc26a8d15256676fc46')

package() {
	tar xf data.tar.xz -C "${pkgdir}"
}
