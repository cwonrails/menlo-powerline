#sourced from https://gist.github.com/justinmayer/7537418#file-menlo-for-powerline-zip

pkgname=menlo-powerline-fonts
pkgver=1.0
pkgrel=1
pkgdesc="Powerline patched Menlo fonts"
arch=(any)
depends=(fontconfig xorg-font-utils)
source=("menlo_powerline.ttf"
	"menlo_powerline_bold.ttf"
	"menlo_powerline_italic.ttf"
	"menlo_powerline_bold_italic.ttf")
md5sums=('3860691e0b81184651d1ccde8576b9af'
         '318bd2b512a615d2b571e9ecbcc53b86'
         '954d77967c5fcd421afdf0128d93ed86'
         'dce97134392c3bc671f967b620fa6aac')
install=$pkgname.install

package() {
  install -Dm644 menlo_powerline.ttf "$pkgdir"/usr/share/fonts/menlo_powerline/menlo_powerline.ttf
  install -Dm644 menlo_powerline_bold.ttf "$pkgdir"/usr/share/fonts/menlo_powerline/menlo_powerline_bold.ttf
  install -Dm644 menlo_powerline_italic.ttf "$pkgdir"/usr/share/fonts/menlo_powerline/menlo_powerline_italic.ttf
  install -Dm644 menlo_powerline_bold_italic.ttf "$pkgdir"/usr/share/fonts/menlo_powerline/menlo_powerline_bold_italic.ttf
}

