pkgname=ysnotifier
pkgver=0.3
pkgrel=1
pkgdesc="A minimal notification daemon for Gtk2."
arch=('i686' 'x86_64')
url="http://dev.yaki-syndicate.de/"
license=('GPL')
depends=('dbus-python' 'pygtk' 'python2>=2.7')
makedepends=()
provides=("notification-daemon")
conflicts=("notification-daemon")
source=("http://dev.yaki-syndicate.de/git/cgit.cgi/stuff/tree/ysnotifier")
md5sums=('79bee329bed768c30b4566328e891c1d')
build() {
  install -Dm755 ${srcdir}/$pkgname $pkgdir/usr/bin/$pkgname
}

