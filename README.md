# Bilkent CS 491-492 | Senior Design Project t

Find the project website at [cs49x.hubreview.app](https://cs49x.hubreview.app).

## PDF Encryption

On systems lacking Adobe Acrobat, `qpdf` may be used to encrypt PDFss:

```sh
# Replace `[pass]`s with a password
For f in *.pdf; do qpdf --encrypt [pass] [pass] 256 -- "$f" "protected-$f"; done
```






last
