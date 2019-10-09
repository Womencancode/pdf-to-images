# ico-think-share
ICO think share toolkit


- [x] Install homebrew 
```console
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
- [x] install ghostscript commandline
- [x] install imagemagic commandline
 ```console 
  brew install ghostscript
  brew install imagemagic
  ```
- [x] make directory ico-images
- [x] extract images from pdf and keep the quality

 ```console 
  mkdir ico-images
  convert -density 600  think-check-share-toolkit.pdf -quality 100 ico-images/image.png
  ```
