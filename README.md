# borland-blue-theme
This theme resembles the Borland/Turbe C IDE with the general idea as golden letters on a blue background.

## Screenshots

![borland-blue](https://github.com/fourier/borland-blue/raw/master/screenshot.png "Emacs with borland-blue theme")


## Installation
Easiest way to install using [MELPA](http://melpa.milkbox.net/#/getting-started). If you have MELPA installed, run
```
    M-x package-install RET borland-blue-theme RET
```

Alternatively put the this directory to the `custom-theme-load` and add the following to your init file:

```
    (push (substitute-in-file-name "~/.emacs.d/borland-blue-theme/") custom-theme-load-path)
    (load-theme 'borland-blue t)
```
