## Installing homebrew-avr formulae

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

