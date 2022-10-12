# Maintainer: Kevadroz <kevinfdezdominguez@gmail.com>
pkgname=resteamed-session-manager
pkgver=0.1
pkgrel=1
pkgdesc='Utilities for switching to/from desktop'
arch=('any')
url="https://github.com/Kevadroz/resteamed-session-manager"
license=('GPL3')
depends=('resteamed-core' 'sddm')
source=("$pkgname-$pkgver::https://github.com/Resteamed-Linux/$pkgname/releases/download/v$pkgver/resteamed-session-manager-$pkgver-tarball.tar.gz")

package() {
	cp -r "$srcdir/usr" "$pkgdir/"
	chmod 755 -R "$pkgdir/"
}

sha256sums=('519e956af42c6d49112a21417ce6cb2c787b33da360c2ce2228ec08f658e5ac1')
