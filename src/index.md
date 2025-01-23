---
title: Samuel Vivien homepage
author: Samuel Vivien
shortbio: PhD student in Programming Languages (Computer Science)
description-meta: PhD student in PL
og-url: https://samsa1.github.io
location: Cambium - INRIA Paris - France
email: samuel.vivien@inria.fr
picture: img/vivien.jpg
picture-round: false
side-by-side: true
pronouns: He/Him/They/Them
og-picture: https://samsa1.github.io/img/vivien.jpg
orcid: 0000-0003-4224-6132
dblp: https://dblp.org/pid/300/9708.html
scholar: https://scholar.google.co.uk/citations?user=Qf9DN_gAAAAJ
github: samsa1
footer: >-
  Based on the
  [basicpage template](https://github.com/basicpage/basicpage.github.io),
  made to be easy to use! 🎓
---

I am a PhD student, working on Programming Languages. My current work is
related to the OCaml compiler and working towards
[modular implicits](https://www.cl.cam.ac.uk/~jdy22/papers/modular-implicits.pdf).

# Publications

## Conference papers

``` json {.paper}
"title": "PureCake: A Verified Compiler for a Lazy Functional Language",
"authors": "Hrutvik Kanabar, Samuel Vivien, Oskar Abrahamsson, Magnus O Myreen, Michael Norrish, Johannes Åman Pohjola, Riccardo Zanetti",
"venue": "PLDI",
"year": "2023",
"url": "https://dl.acm.org/doi/abs/10.1145/3591259"
```

``` json {.paper}
"title": "Parallel integer multiplication",
"authors": "Samuel Vivien",
"venue": "30th Euromicro International Conference on Parallel, Distributed and Network-based Processing (PDP)",
"year": "2022",
"url": "https://hal.science/hal-03541726v1"
```

## Drafts

``` json {.paper}
"title": "Automated Discovery of New L-Function Relations",
"authors": "Hadrien Barral, Éric Brier, Rémi Géraud-Stewart, Arthur Léonard, David Naccache, Quentin Vermande, Samuel Vivien",
"url": "https://arxiv.org/abs/2206.03604"
```

## Talks

``` json {.papers}
{
  "title": "Tracking which types are principally known in OCaml.",
  "authors" : "Samuel Vivien",
  "venue": "PETITS",
  "year": "2025",
  "url" : "https://www.irif.fr/~scherer/events/petits-2025/announce.html",
  "files": [
    { "text": "Slides", "type" : "pdf", "src" : "files/petits25.pdf" }
  ]
}
```

``` json {.papers}
{
  "title": "On the design and implementation of Modular Explicits",
  "authors": "Samuel Vivien, Didier Rémy",
  "venue": "OCaml@ICFP'24",
  "year": "2024",
  "url": "https://icfp24.sigplan.org/details/ocaml-2024-papers/1/On-the-design-and-implementation-of-Modular-Explicits"
}
```

# Software

## [OCaml](https://github.com/ocaml/ocaml)

I've started working on the OCaml compiler in March 2024. Since then I worked on :


- [#13275](https://github.com/ocaml/ocaml/pull/13275) modular explicits (not merged yet)
- a few bug fix [#13053](https://github.com/ocaml/ocaml/pull/13053) and refactoring
PRs [#13113](https://github.com/ocaml/ocaml/pull/13113),
[#13681](https://github.com/ocaml/ocaml/pull/13681),
[#13682](https://github.com/ocaml/ocaml/pull/13682),
[#13683](https://github.com/ocaml/ocaml/pull/13683),
[#13684](https://github.com/ocaml/ocaml/pull/13684).

## [PureCake](https://github.com/CakeML/pure)

PureCake is a verified compiler for a Haskell-like language. My contribution to
this project was the formalisation and implementation of demands analysis.

For more details see the related section in
[PureCake: A Verified Compiler for a Lazy Functional Language](https://dl.acm.org/doi/abs/10.1145/3591259).

# Teaching

- I've did TD and TP for a course on the "fundamental principle of the binary machine" (binary arithmetic, boolean logic, boolean circuits and a bit of cryptography).
- I'm currently teaching TP in a Java course.
