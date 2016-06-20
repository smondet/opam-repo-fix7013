# opam-repo-fix7013

Opam repository with OCaml 4.03.2 + the fix to the
[`7013`](http://caml.inria.fr/mantis/view.php?id=7013) bug.

## Usage

Add the repo:

    opam repo add fix7013 https://github.com/smondet/opam-repo-fix7013.git
    opam update

Get the compiler:

    opam switch 4.02.3+smondet-fix7013
    eval `opam config env`

