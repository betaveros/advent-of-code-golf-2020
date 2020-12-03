Advent of Code Golf 2020
========================

tl;dr same setup as [last year](https://github.com/betaveros/advent-of-code-golf-2019) and [the year before](https://github.com/betaveros/advent-of-code-golf-2018). In spite of the pandemic, I'm actually way busier this year (or I should be), so I'll be happy if I last longer than last year. And Zarquon help me if we have anything like Intcode.

---

This repository contains [golfed](https://en.wikipedia.org/wiki/Code_golf) solutions to [Advent of Code 2020](https://adventofcode.com/2020) in my personal golfing programming language, [Paradoc](https://github.com/betaveros/paradoc), version 0.6. Hopefully the [Rust](https://github.com/betaveros/paradoc-rust) implementation will sometimes also work and produce an answer much faster.

(These are not the solutions I compete on the leaderboard with; I think there are enough repos with such solutions and my solutions wouldn't be that different. I have also not been careful about preserving my code for level 1 before doing level 2 of each day.)

I could obviously cheat at golf by adding built-ins to Paradoc tailored to each challenge after seeing it, so my programs here ought to run on Paradoc version 0.6, which was pushed just before this year's Advent of Code. I will be using the results here to guide improving Paradoc in the future, though.

Note on byte count: Like a lot of the other golfing languages [seen on the Programming Puzzles & Code Golf StackExchange](https://codegolf.meta.stackexchange.com/questions/5878/what-character-encodings-may-a-submission-use/5879#5879), the byte counts here assume programs were encoded in the Paradoc code page. These programs will almost always take up more than the stated byte count as UTF-8 strings, and for the sake of easy viewability, they are UTF-8 encoded below and in the programs in this repository.

Day-Level | Bytes | Code | Try In-Browser
--- | -- | ---- | ----
1-1 | 12 (−2?) | `y²¨γgŠ2020=Þ` (in 2020: `y²¨γgŠNy=Þ`) | [try](https://betaveros.github.io/paradoc-rust/#ecKywqjOs2fFoDIwMjA9w54=)
1-2 | 13 (−2?) | `y³¨¨γgŠ2020=Þ` (in 2020: `y³¨¨γgŠNy=Þ`) | [try](https://betaveros.github.io/paradoc-rust/#ecKzwqjCqM6zZ8WgMjAyMD3Dng==)
2-1 | 19 | `a{W~\‹#\Ig~M\u]$p}#` | [try](https://betaveros.github.io/paradoc-rust/#YXtXflzigLkjXElnfk1cdV0kcH0j)
2-2 | 20 | `a{W~\oIgLm(m=y^L2=}#` | [try](https://betaveros.github.io/paradoc-rust/#YXtXflxvSWdMbShtPXleTDI9fSM=)
