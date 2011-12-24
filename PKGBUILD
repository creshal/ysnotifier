pkgname=ysnotifier
pkgver=0.5
pkgrel=1
pkgdesc="A minimal notification daemon for Gtk2."
arch=('i686' 'x86_64')
url="http://dev.yaki-syndicate.de/"
license=('GPL')
depends=('dbus-python' 'pygtk' 'python2>=2.7')
makedepends=()
provides=("notification-daemon")
conflicts=("notification-daemon")
source=("http://dev.yaki-syndicate.de/git/cgit.cgi/ysnotifier/plain/ysnotifier?id=${pkgver}")
md5sums=('11719ad4c4e74f946c9bb4ec31a8fd3f')
build() {
  install -Dm755 "${srcdir}/$pkgname?id=${pkgver}" $pkgdir/usr/bin/$pkgname
}

