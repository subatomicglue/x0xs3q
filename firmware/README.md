# Firmware

the firmware for the x0xb0x

## Windows:

... TODO ...

## MacOS: Installing [homebrew-avr](https://github.com/osx-cross/homebrew-avr) formulae

First, make sure you have xcode command line developer tools installed with

```console
$ xcode-select --install
```

Then, just run the following to install the latest version of `avr-gcc`:

```console
$ brew tap osx-cross/avr
$ brew install avr-gcc
```

If you want to install an older version: 

```console
$ brew install avr-gcc@X
```

Where `X` being the version number such as `avr-gcc@6`

**Note**: only the latest version will be available in your `$PATH`. The older ones are `keg-only` and thus won't be availble in `/usr/local/bin`.

You can run `brew info avr-gcc` for more information on the flags available.

# copyright

this modification is built on the hard work of Limor Freid & Adafruit, and the x0xb0x community

These files are all released under the [MIT Open Source license](http://en.wikipedia.org/wiki/MIT_License):

```
Copyright (c) Limor Fried & Adafruit industries

Permission is hereby granted, free of charge, to any person obtaining a copy of this software, firmware, layout and associated documentation files (the "Design files"), to deal in the Design files without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Design, and to permit persons to whom the Design is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Design.

THE DESIGN FILES ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

Notably:
```
If you plan to make, sell or manufacture x0xb0xes please contact us - we request that you credit Adafruit Industries on the documentation, supporting pages and circuit boards "Copyright (c) Limor Fried & Adafruit industries". x0xb0x (TM) is a trademarked name of Adafruit Industries. Please contact support@adafruit.com if you wish to seek permission to use the name for your products or projects, otherwise you cannot call your product "x0xb0x".
```
