# Sdraw

Draws cons cell diagrams.

## Usage

There are two version of Sdraw, `sdraw.generic` draws con cell diagram in
terminal or REPL, and `sdraw.gui` draws cons cell diagram in fancier way,
with GUI output.


### sdraw.generic

``` lisp
CL-USER> (load "sdraw.generic")
CL-USER> (sdraw:sdraw '(a b c (d e) f))
```


### sdraw.gui


``` lisp
CL-USER> (ql:quickload :clx)
CL-USER> (load "sdraw.gui")
CL-USER> (sdraw:sdraw '(a b (c d (e) f)))
```


## Author

- [Dave Touretzky](http://www.cs.cmu.edu/~dst/)

## Contributor

- [Daniel Kochmański](https://github.com/dkochmanski) hacked `sdraw.gui` to works with modern Common Lisp.

## License

Distribution of Sdraw allowed by kind permission from Mr.[Dave Touretzky](http://www.cs.cmu.edu/~dst/)
