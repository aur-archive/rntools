# Maintainer: trile7 at gmail dot com

pkgname=rntools
pkgver=0.3
pkgrel=3
pkgdesc="Bash script for rename files and folders"
url="http://bashscripts.googlecode.com"
arch=('i686' 'x86_64')
license=('GPL3')
depends=(coreutils bash)
source=($url/files/$pkgname-$pkgver.tar.gz)

package() {
  mkdir -p "$pkgdir/usr/share/$pkgname"
  mkdir -p "$pkgdir/usr/bin"
  cp "$srcdir/$pkgname-$pkgver"/* "$pkgdir/usr/share/$pkgname"
  mv "$pkgdir/usr/share/$pkgname/$pkgname" "$pkgdir/usr/bin"
}

md5sums=('a7f5c5be1747ad9ef904ab839550960c')
