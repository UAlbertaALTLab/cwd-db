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
   j      |  y   |  y

## Syllabics

Woods Cree uses graphemes in the Syllabic orthography in a slightly different way than other Cree dialects. Woods Cree does not use any of the graphemes for /iː/. Instead, Woods Cree uses /e/ graphemes for the /iː/ sound.

Consonant | i | î | o | ô | a | â | Final
:--------:|:-:|:-:|:-:|:-:|:-:|:-:| :----:
N/A       | ᐁ | ᐃ | ᐅ | ᐆ | ᐊ | ᐋ | N/A
w         | ᐏ | ᐏ | ᐓ | ᐕ | ᐘ | ᐚ | ᐤ
p         | ᐯ | ᐱ | ᐳ | ᐴ | ᐸ | ᐹ | ᑊ
t         | ᑌ | ᑎ | ᑐ | ᑑ | ᑕ | ᑖ | ᐟ
k         | ᑫ | ᑭ | ᑯ | ᑰ | ᑲ | ᑳ | ᐠ
c         | ᒉ | ᒋ | ᒍ | ᒎ | ᒐ | ᒑ | ᐨ
m         | ᒣ | ᒥ | ᒧ | ᒨ | ᒪ | ᒫ | ᒼ
n         | ᓀ | ᓂ | ᓄ | ᓅ | ᓇ | ᓈ | ᐣ
s         | ᓭ | ᓯ | ᓱ | ᓲ | ᓴ | ᓵ | ᐢ
y         | ᔦ | ᔨ | ᔪ | ᔫ | ᔭ | ᔮ | ᐩ<sup><a href=#fn-1>1</a></sup> (ᐝ)
th / ð    | ᖧ | ᖨ | ᖪ | ᖫ | ᖬ | ᖭ | ᙾ
h         |  |   |   |   |   |   | ᐦ
hk        |  |   |   |   |   |   | ᕽ

### Other Symbols

SRO | Syllabary
:--:|:--------:
 l  |     ᓬ
 r  |     ᕒ
 .  |     ᙮
 w  |     ᐧ
 \- |  U+202F

## Sources

ALTLab's dictionary database is / will be aggregated from the following sources:

* the Cree-to-English portion of Colin Charles' Cree Dictionary (a.k.a. the Lac La Ronge Dictionary) (`LLR`)
  - See [Notes on the Lac La Ronge Dictionary](./LLR.md)

* an edited version of Arok Wolvengrey's _Cree: Words_ dictionary database (referred to as simply the "Woods Cree" database) (`CW`)
  - See [Notes on the _Cree: Words_ Dictionary](./CW)

## Footnotes

1. <p id=fn-1>Cree writers overwhelmingly prefer using this character, U+1429 CANADIAN SYLLABICS FINAL PLUS ⟨ᐩ⟩, to U+1540 CANADIAN SYLLABICS WEST-CREE Y ⟨ᕀ⟩.</p>

<!-- LINKS -->
[DaFoDiL]: https://format.digitallinguistics.io
