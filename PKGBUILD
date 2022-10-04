# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-about
pkgver=1
pkgrel=1
pkgdesc="About app for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('MIT')
depends=('yad')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -Dm 755 "$pkgname" "${pkgdir}/usr/bin/$pkgname"
    install -Dm 644 "$pkgname.desktop" "${pkgdir}/usr/share/applications/$pkgname.desktop"
    echo $pkgdir
}
