pkgname="openutils-map"
pkgver="1.6.0"
pkgrel="3"
pkgdesc="Memory Safe Map Library in C/C++ language."
arch=("x86_64" "i686")
conflicts=('openutils-map')
depends=(gcc)
license=("MIT")
source=("https://raw.githubusercontent.com/Dark-CodeX/map/master/map/map.hh" "https://raw.githubusercontent.com/Dark-CodeX/map/master/map/map.h" "https://raw.githubusercontent.com/Dark-CodeX/map/master/map/prototype_err.h")

sha512sums=("715052e08c2f129e661c846c6c19895ca86cab19a37279eb53abf8efb7ff15754589ef3a208bb5cc9f612fc6fc8dd8652dc33ba0399be3596c361b5b88160957" "bb3c4599fffbd09b0d19b38831fb3c4c9485068c980611a00eba8fb8db997d1312b59571af7aa2d3c66dd3569c72eaf9e7265e839083a0c7bb6b0722a41b77c9" "3dbf476b5ce48eeef9d68d16f3e9a543bc089c3fff8f97dd6d42bc160be0e11976e5f2bcef3927d8340ab1839de802fd8fad90b3ac635285f00d49807fd21a6a")

package() {
  echo "Memory Safe Map Library in C++ language."
  mkdir -p "${pkgdir}/usr/include/openutils/map"
  cp "${srcdir}/map.hh" "${pkgdir}/usr/include/openutils/map/map.hh"
  cp "${srcdir}/map.h" "${pkgdir}/usr/include/openutils/map/map.h"
  cp "${srcdir}/prototype_err.h" "${pkgdir}/usr/include/openutils/map/prototype_err.h"
  echo "Done!"
}
