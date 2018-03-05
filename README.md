# ocaml/dune #562

First clone this repository.  Then, from the root of the clone:
```
opam pin add a -k git $(pwd)#master
opam pin add b -k git $(pwd)#master
git checkout modified
make
```
