# Maintainer: Olivier Calzi(@Zwordi) 
# Contributors : Christian Zucchelli (@Chris_Zeta)  <thewebcha@gmail.com>
pkgname=b1-free-archiver
pkgver=1.5.0
pkgrel=1
pkgdesc="Most friendly and simple free file archiver!"
url="http://b1.org"
arch=('x86_64' 'i686')
license=('custom')
depends=()
optdepends=()
makedepends=()
conflicts=()
replaces=()
backup=()
install=''
if [ "$CARCH" == "x86_64" ]; then
  source=("http://b1.org/smart-download/0/os=deb64/b1freearchiver_current_stable_amd64.deb")
  md5sums=("e8fd7a8306b23aa9db6cfbfe55bd2954")
else
  source=("http://b1.org/smart-download/0/os=deb32/b1freearchiver_current_stable_i386.deb")
  md5sums=("0f3c5f0010f9cf67974c1f81f5f1413b")
fi

package() {
  cd "${pkgdir}"
  tar -xf "${srcdir}/data.tar.gz"
  ln -s /usr/lib/libudev.so ${pkgdir}/usr/lib/libudev.so.0
  chmod 755 ${pkgdir}/usr/
  chmod 755 ${pkgdir}/usr/bin/
  chmod 755 ${pkgdir}/usr/share/
  chmod 755 ${pkgdir}/usr/lib/
  chmod 755 ${pkgdir}/usr/lib/nautilus/
  chmod 755 ${pkgdir}/usr/lib/nautilus/extensions-3.0/
  chmod 755 ${pkgdir}/usr/share/icons/
  chmod 755 ${pkgdir}/usr/share/applications/
  chmod 755 ${pkgdir}/usr/share/kde4/
  chmod 755 ${pkgdir}/usr/share/mime/
  chmod 755 ${pkgdir}/usr/share/mime/packages/
  chmod 755 ${pkgdir}/usr/share/kde4/services/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/256x256/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/512x512/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/512x512/apps
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/24x24/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/64x64/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/32x32/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/128x128/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/48x48/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/16x16/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/16x16/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/16x16/apps/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/48x48/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/48x48/apps/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/128x128/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/128x128/apps/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/32x32/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/32x32/apps/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/64x64/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/24x24/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/256x256/mimetypes/
  chmod 755 ${pkgdir}/usr/share/icons/hicolor/256x256/apps/
}
