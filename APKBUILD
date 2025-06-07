# Contributor: Reku Dyu <reku@airmail.cc>
# Maintainer: Reku Dyu <reku@airmail.cc>
pkgname=tt-kmd
pkgver=2.0.0
pkgrel=0
pkgdesc="Tenstorrent Kernel Module"
url="https://github.com/tenstorrent/tt-kmd"
arch="all"
license="GPL-2.0-only"
depends="akms"
makedepends="make"
source="https://github.com/rekudyu/tt-kmd/archive/refs/tags/tt-kmd-"$pkgver".tar.gz"
builddir=""$srcdir"/tt-kmd-tt-kmd-"$pkgver""
options="!check"

package() {
	mkdir -p $pkgdir
	cd "$srcdir"/tt-kmd-tt-kmd-"$pkgver"
	make akms 
}

sha512sums="
fa7c6f4c4e3623102ba1f79ddd81c7143cd6d31b42b2c24c37725bdd1ebf610e78d399cb46d60320a87c331e06a0872f9266a273d88dac59651fdb9c028f4d33  tt-kmd-2.0.0.tar.gz
"