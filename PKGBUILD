pkgname=chsudo
pkgrel=1
pkgver=1.0
pkgdesc="Drop-in replacement for visudo"
arch=('i686' 'x86_64')
url='https://github.com/arcanis/trivia.chsudo/'
license=('BSD')
depends=('sudo')

build() {

    install -d $pkgdir/usr/bin
    cp $startdir/*sudo $pkgdir/usr/bin/

}
