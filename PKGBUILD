# Maintainer: David "davman808" Seyder  <da.seyder@gmail.com>
pkgname=808omz-git
pkgver=5.8.1
pkgrel=1
pkgdesc="this is the oh-my-zsh config that i use"
arch=(any)
url="https://github.com/davman808/808omz-git.git"
license=('MIT-Modern-Variant')
depends=(zsh zsh-autosuggestions  zsh-completions  zsh-history-substring-search  zsh-syntax-highlighting)
makedepends=(git)
provides=(oh-my-zsh-git)
replaces=(oh-my-zsh-git)
source=("git+$url")
md5sums=("SKIP")

package() {
    cd "$srcdir/$pkgname"
}

build() {
    cp -r 808omz-git/.oh-my-zsh ~/
    cp -r 808omz-git/.zshrc ~/
    echo "you can remove any directories related to this package (except .oh-my-zsh of course) and it wont break"
}
