#Maintainer : Hen H, modified ver of msmtp

pkgname=msmtp-ken
pkgver=1
pkgrel=1
pkgdesc="mod version of pkg msmtp"
arch=('i686' 'x86_64')
makedepends=('gcc>=4.4')

#source=('')
#md5sums=('SKIP')


build() {
  pwd
  cd ..
  autoreconf -i
  ./configure
  make
}


package() {
  make DESTDIR="$pkgdir/" install
}
