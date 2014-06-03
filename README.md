You'll want to install a couple of Racket libraries:

    raco pkg install pfds
    raco pkg install graph

The former is Asumu Takikawa's functional, typed data structures library which
contains the priority queue implementation for the PDA2 algorithm.

The later is Stephen Chang's gen:graph library which provides a topological sort
and strongly connected components procedure. The `pda-to-pda-risc` project's
`pda-term` data structure implements enough of gen:graph to run these two
algorithms.
