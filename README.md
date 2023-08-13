# exdege

Ruby wrapper around `xdg-open`, allowing one to watch a specific directory for
changes and use `xdg-open` on the new files added. Uses the Ruby `listen` gem.

## Installing

```
$ git clone https://github.com/gavinlaking/exdege.git ~/bin/
```

## Rationale

A testing script writes screenshots to my application directory `tmp/`
directory, and I don't want to type `xdg-open tmp/screenshots/longfilename.png`

Instead, I clone this repository to my `$HOME/bin` directory which is in my
`$PATH` then run:

```
$ exdege /some/path/tmp
```


