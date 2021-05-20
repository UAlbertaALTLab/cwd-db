# Woods Cree Dictionary Database Management

This repository contains scripts and documentation for managing ALTLab's Woods Cree dictionary database.

**This repository does _not_ (and should not) contain the actual dictonary database.** The ALTLab database, and the original sources it is based on, are located in the private ALTLab repo.

The database uses the [Data Format for Digital Linguistics][DaFoDiL] as its underlying data format—a set of recommendations for storing linguistic data in JSON.

## Orthography

The following table shows each grapheme in Woods Cree in the Colin Charles' Modified Roman Orthography (CMRO) and its equivalent in the Standard Roman Orthography (SRO), also with its corresponding value in the International Phonetic Alphabet (IPA).

  IPA     | CMRO | SRO
:--------:|:----:|:--:
   ə      |  u   |  a
  aː      |  a   |  â
t͡ʃ ~ t͡s |  ch  |  c
   h      |  h   |  h
   ɪ      |  i   |  i
  iː      |  e   |  î
   k      |  k   |  k
   m      |  m   |  m
   n      |  n   |  n
 o ~ ʊ    |  o   |  o
oː ~ uː   |  oo  |  ô
   p      |  p   |  p
 s ~ ʃ    |  s   |  s
   t      |  t   |  t
   ð      |  th  | th
   w      |  w   |  w
   y      |  y   |  y

## Sources

ALTLab's dictionary database is / will be aggregated from the following sources:

* the Cree-to-English portion of Colin Charles' Cree Dictionary (a.k.a. the Lac La Ronge Dictionary) (`LLR`)
  - See [Notes on the Lac La Ronge Dictionary](./LLR.md)

* an edited version of Arok Wolvengrey's _Cree: Words_ dictionary database (referred to as simply the "Woods Cree" database) (`CW`)
  - See [Notes on the _Cree: Words_ Dictionary](./CW)

[DaFoDiL]: https://format.digitallinguistics.io
