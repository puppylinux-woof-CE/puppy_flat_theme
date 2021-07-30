# puppy_flat_theme
flatter icon theme


## Preview

[<img src="PuppyFlat.png" style="width:100%">](PuppyFlat.png)


## Build

First edit (if using a distro other than puppy) then "source" the `build.conf` file then run `make`.


```sh
. ./build.conf
make
```

The icons will be built in `"Puppy Flat"` directory.

To install just type `make install`. `DESTDIR` is supported.

Alternatively, just run the `build_theme` script from the current loacation
if you don't have `make`. The Makefile is just a convenience for packaging;
entirely not necessary.

## Artwork

I am no artist! ( @01micko ). Some of the icons could do with some (a lot?)
of work. Feel free to send in your pull requests but no icons built from InkScape 
or other SVG editors please.

## Note

This theme now depends on PMaterial (also in this repository)

## Thanks

Many thanks to @technosaurus and @zigbert for enlightening me on SVG!
