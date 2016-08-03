# Maintainer: Felix Schindler <aur at felixschindler dot net>

pkgname=manjaro-config-basic
pkgver=0.1
pkgrel=1
url=https://github.com/ftalbrecht/manjaro-config-basic
license=('BSD2')
arch=('any')
depends=('gvim' 'base-devel' 'git' 'tk' 'bash-completion' 'vimpager' 'ack' 'openssh' 'x11-ssh-askpass' 'htop' 'perl-net-ssleay' 'multilib-devel' 'unp')
source=("git+https://github.com/ftalbrecht/manjaro-config-basic.git")
md5sums=('SKIP')

package() {
  install -D -m644 "${srcdir}/manjaro-config-basic/LICENSE" "${pkgdir}"/usr/share/licenses/${pkgname}/LICENSE
}

