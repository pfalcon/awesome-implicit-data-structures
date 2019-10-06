# Implicit data structures

https://en.wikipedia.org/wiki/Implicit_data_structure

## Sorted list

* https://en.wikipedia.org/wiki/Binary_search_algorithm

## Binary heap

* https://en.wikipedia.org/wiki/Binary_heap

## D-ary heap (D-heap) and B-heap

* https://en.wikipedia.org/wiki/D-ary_heap
* https://en.wikipedia.org/wiki/B-heap
* https://github.com/valyala/gheap

## Poplar heap

* Description and implementation in https://github.com/Morwenn/poplar-heap

## Post-order heap

Largely similar to poplar heap above.

* Paper: https://people.csail.mit.edu/nickh/Publications/PostOrderHeap/FUN04-PostOrderHeap.pdf

## Min-max heap

* https://en.wikipedia.org/wiki/Min-max_heap

## Binomial list (Bentley-Saxe)

Doesn't support deletes natively, uses "soft deletes" (marking an element
as deleted).

## Beap (Bi-parental heap)

* https://en.wikipedia.org/wiki/Beap
* Implementation in Python: https://github.com/pfalcon/beap

## Rotated sorted lists


# Succint data structures

https://en.wikipedia.org/wiki/Succinct_data_structure

List dedicated to succint structures:

* https://github.com/pombredanne/awesome-succint-data-structures

Libs:

* https://github.com/simongog/sdsl-lite (GPLv3)

## Red-black trees

When storing just left/right node pointers, algorithms exist for one-pass
top-down insertion and deletion. (For comparison, for AVL trees, only
insertion top-down algorithm exists, deletion requires 2-pass algorithm).
