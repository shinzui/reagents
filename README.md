reagents — Composable lock-free data and synchronization structures
-------------------------------------------------------------------------------
%%VERSION%%

reagents is TODO

reagents is distributed under the ISC license.

Homepage: https://github.com/ocamllabs/reagents  

## Installation

reagents can be installed with `opam`. You would also need to install the multicore OCaml compiler:

    $ opam remote add multicore https://github.com/ocamllabs/multicore-opam.git
    $ opam switch 4.02.2+multicore
    $ opam install reagents

## Documentation

The documentation and API reference is automatically generated by from
the source interfaces. It can be consulted [online][doc].

[doc]: https://ocamllabs.github.io/reagents/doc

## Sample programs

If you installed reagents with `opam` sample programs are located in
the directory `opam config var reagents:doc`.

In the distribution sample programs and tests are located in the
[`test`](test) directory of the distribution. They can be built and run
with:

    topkg build --tests true && topkg test 