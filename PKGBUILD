pkgname=crypter
pkgver=0.0.1
pkgrel=1
arch=(x86_64)
url='https://github.com/blackbird-hyprland/apps-crypter'
pkgdesc="KDE's terminal emulator"
license=(CUSTOM)
groups=()
depends=()
makedepends=()
optdepends=()
source=("crypter")
sha256sums=('SKIP')



package(){
    mkdir -p $pkgdir/usr/bin
    mkdir -p $pkgdir/etc/$pkgname
    install -D -m644 $srcdir/config $pkgdir/etc/$pkgname/crypter.conf
    install -D -m755 crypter $pkgdir/usr/bin/$pkgname
}
