# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=bbqlinux-artwork
pkgver=1.0.1
pkgrel=1
pkgdesc="BBQLinux Artwork"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-artwork"
license=('GPL')

package() {
    cd "$pkgdir"

    mkdir -p usr/share/bbqlinux
    mkdir -p usr/share/pixmaps

    cp -R "$srcdir/usr/share/bbqlinux" usr/share
    cp -R "$srcdir/usr/share/pixmaps" usr/share
}
