# Maintainer: Sam Cater <sam@samcater.com>

pkgname=pytbull
pkgver=2.0
pkgrel=1
pkgdesc="Pytbull is a python based flexible IDS/IPS testing framework"
arch=('i686' 'x86_64')
url="http://pytbull.sourceforge.net/"
license=('GPL3')
depends=("scapy" "hping" "python2-feedparser" "python2-cherrypy")
makedepends=('')
source=("https://downloads.sourceforge.net/project/pytbull/pytbull-2.0.tar.bz2")
md5sums=('ea1223c539cd3d96090bc1e0b899eff5')

package(){
	cd ${srcdir}
	tar xvf "$pkgname-$pkgver.tar.bz2"
	mkdir -p ${pkgdir}/opt/pytbull
	cp -rf ${srcdir}/pytbull/* ${pkgdir}/opt/pytbull
	install -d -m755 "${srcdir}/pytbull/" "${pkgdir}/opt/pytbull/"
}
