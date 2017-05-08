# quickd

```
brew install haskell-stack
brew install emacs --with-librsvg --with-modules --with-gnutls --with-imagemagick@6
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```

Open emacs and hit `space f e d` add Haskell:

```
(haskell :variables
              haskell-completion-backend 'intero)
```

then hit `space f e R`

Go to a Haskell project and it should just work :tm:
