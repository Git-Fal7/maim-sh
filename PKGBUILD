pkgname="maim-sh"
pkgdesc="bash script for maim"
pkgver=1.0
pkgrel=1
arch=(any)
depends=("maim" "xdotool" "xclip")
source=('maim-sh')
sha256sum=('SKIP')
fileloc=/usr/bin
package() {
 sudo cp ./maim-sh ${fileloc}
 chmod +X ${fileloc}/maim-sh
}
