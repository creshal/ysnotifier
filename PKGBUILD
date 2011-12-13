pkgname=ysnotifier
pkgver=0.2
pkgrel=1
pkgdesc="A minimal notification daemon for Gtk2."
arch=('i686' 'x86_64')
url="http://dev.yaki-syndicate.de/"
license=('GPL')
depends=('dbus-python' 'pygtk')
makedepends=()
provides=("notification-daemon")
conflicts=("notification-daemon")
source=("http://dev.yaki-syndicate.de/git/cgit.cgi/stuff/tree/ysnotifier")
md5sums=('6473ee214f9134f797f2c13282a20ef2')
build() {
  install -Dm755 ${srcdir}/$pkgname $pkgdir/usr/bin/$pkgname
}

