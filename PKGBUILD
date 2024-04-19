# Maintainer: Noah Vogt (noahvogt) <noah@noahvogt.com>

pkgname=chromium-extension-keepassxc-browser-bin
pkgver=1.9.0.3
pkgrel=1
pkgdesc="KeePassXC Browser Integration - chromium extension (binary version)"
arch=('any')
url="https://github.com/noahvogt/chromium-extension-keepassxc-browser-aur"
license=('GPL3')
makedepends=('chromium' 'openssl' 'jq')
source=("$url/releases/download/$pkgver-$pkgrel/${pkgname%-*}-$pkgver-$pkgrel-any.pkg.tar.zst")
sha256sums=('4a5157d2fe4db5d820ebeaedbb88c69e463c4fb984d0a7cd8debc565edac921b')
provides=('chromium-extension-keepassxc-browser')
conflicts=('chromium-extension-keepassxc-browser')

package() {
    cp -R "${srcdir}/usr/" "${pkgdir}/usr"
}
