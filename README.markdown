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
1-1 | 12 (−2?) | `y²¨γgŠ2020=Þ` (in 2020: `y²¨γgŠNy=Þ`) | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#ecKywqjOs2fFoDIwMjA9w54=)
1-2 | 13 (−2?) | `y³¨¨γgŠ2020=Þ` (in 2020: `y³¨¨γgŠNy=Þ`) | [![try (slow!)](try-slow.svg)](https://betaveros.github.io/paradoc-rust/#ecKzwqjCqM6zZ8WgMjAyMD3Dng==)
2-1 | 19 | `a{W~\‹#\Ig~M\u]$p}#` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YXtXflzigLkjXElnfk1cdV0kcH0j)
2-2 | 20 | `a{W~\oIgLm(m=y^L2=}#` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YXtXflxvSWdMbShtPXleTDI9fSM=)
3-1 | 10 | `a{Y3*=cÔ}š` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YXtZMyo9Y8OUfcWh)
3-2 | 22 | `a5{!)%Y×(L{Y*=cÔ}vŠ}yÞ` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YTV7ISklWcOXKEx7WSo9Y8OUfXbFoH15w54=)
4-1 | 14 | `iN×/µW‹mXúç}7#` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#aU7Dly/CtVfigLltWMO6w6d9NyM=)
4-2 | 166 | `iN×/µW{4>q(<ŠZú[{I1961±42<}{"amb blu brn gry grn hzl oth"W\#}{DpâqL9=&}{I45²±6<}{('#=\:L6=\ÅhLc-!&&}0_:{I2015±6<}{2m<q>["cm"{I7³½±22<}"in"{I67.5±9<}1_0]s}]=c~}#}7#` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#aU7Dly/CtVd7ND5xKDzFoFrDult7STE5NjHCsTQyPH17ImFtYiBibHUgYnJuIGdyeSBncm4gaHpsIG90aCJXXCN9e0Rww6JxTDk9Jn17STQ1wrLCsTY8fXsoJyM9XDpMNj1cw4VoTGMtISYmfTBfOntJMjAxNcKxNjx9ezJtPHE+WyJjbSJ7STfCs8K9wrEyMjx9ImluIntJNjcuNcKxOTx9MV8wXXN9XT1jfn0jfTcj)
5-1 | 9 | `a7ú2ú2BvÆ` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YTfDujLDujJCdsOG)
5-2 | 13 | `a7ú2ú2Bv)mq-Œ` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YTfDujLDujJCdiltcS3Fkg==)
6-1 | 10 | `iN×/γšW\|rL` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#aU7Dly/Os8WhV3xyTA==)
6-2 | 10 | `iN×/γšW&rL` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#aU7Dly/Os8WhVyZyTA==)
7-1 | 40 | `aµW4÷>o_(µ«»¨}}"shinygold"†\{\&bf‹m}bFL(` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YcK1VzTDtz5vXyjCtcKrwrvCqH19InNoaW55Z29sZCLigKBce1wmYmbigLltfWJGTCg=)
7-2 | 43 | `aεW4÷(2<¨\µ«(I\¨°~}Hu}"shinygold"{H=•š)}–•(` | [![try (slow!)](try-slow.svg)](https://betaveros.github.io/paradoc-rust/#Yc61VzTDtygyPMKoXMK1wqsoSVzCqMKwfn1IdX0ic2hpbnlnb2xkIntIPeKAosWhKX3igJPigKIo) [![try fast var.](try-fast.svg)](https://betaveros.github.io/paradoc-rust/#Yc61VzTDtygyPMKoXMK1wqsoSVzCqOKAoX1IdX0ic2hpbnlnb2xkIntIPc6zxaF+4oCiKil94oCT4oCiKA==)
8-1 | 41 | `a–0:λ:Hzγ;PE&:Ho:•=W~I\‹5%[β;)+_γ\+u)]=~}` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YeKAkzA6zrs6SHrOsztQRSY6SG864oCiPVd+SVzigLk1JVvOsjspK1/Os1wrdSldPX59)
8-2 | 61 | `a·Lχ0:Hj;λ:HzQ_&:•L=γ;PE&:Ho:Z=:o•=W~I\i‹5%^[β;)+_γ\+u):]=~}}` | [![try (slow!)](try-slow.svg)](https://betaveros.github.io/paradoc-rust/#YcK3TM+HMDpIajvOuzpIelFfJjrigKJMPc6zO1BFJjpIbzpaPTpv4oCiPVd+SVxp4oC5NSVeW86yOykrX86zXCt1KTpdPX59fQ==)
9-1 | 18 | `y26W{)\²¨ÛfŠm#!}=›` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YcK1VzTDtz5vXyjCtcKrwrvCqH19InNoaW55Z29sZCLigKBce1wmYmbigLltVX1iRkwo)
9-2 | 44? | `y:26W{)\²¨ÛfŠm#!}=›\<s{>s{:Š\u={ŒqÆ+PE}&}y}y` | [![try (slow!)](try-slow.svg)](https://betaveros.github.io/paradoc-rust/#eToyNld7KVzCssKow5tmxaBtIyF9PeKAulw8c3s+c3s6xaBcdT17xZJxw4YrUEV9Jn15fXk=)
10-1 | 14 | `y0+$¯ä13d#y~)*` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#eTArJMKvw6QxM2QjeX4pKg==)
10-2 | 18 | `y$0Hoε:4-yHzšHu}H›` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#eSQwSG/OtTo0LXlIesWhSHV9SOKAug==)
11-1 | 45 | `aJú3ú{γ0Cfv™×γ3Wv™×µ¨:4=[Ôô_γÔç5<Æ_]=~}m}FÔçš` | [![try (slow!)](try-slow.svg)](https://betaveros.github.io/paradoc-rust/#YUrDujPDunvOszBDZnbihKLDl86zM1d24oSiw5fCtcKoOjQ9W8OUw7RfzrPDlMOnNTzDhl9dPX59bX1Gw5TDp8Wh)
11-2 | 80–119? | see file (all sols too slow to solve actual input now). | ←
12-1 | 57 | `aγ^j*0–0\1\ε(AúIu[β*k¸:β6ò•/j_¦βAò•M_*j_{}]=~\+u};~jLd+=i` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#Yc6zXmoqMOKAkzBcMVzOtShBw7pJdVvOsiprwrg6zrI2w7LigKIval/Cps6yQcOy4oCiTV8qal97fV09flwrdX07fmpMZCs9aQ==)
12-1 | 57 | `a0\1jAá\ε(AúIu[γ*q;+u:γ6ò^j*-j_¦γAò^j*-_+j_+_]=~};~jLd+=i` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#YTBcMWpBw6FczrUoQcO6SXVbzrMqcTsrdTrOszbDsl5qKi1qX8KmzrNBw7JeaiotXytqXytfXT1+fTt+akxkKz1p)
13-1 | 14 | `iIg(M{\%X]}vŒÞ` | [![try](try.svg)](https://betaveros.github.io/paradoc-rust/#aUlnKE17XCVYXX12xZLDng==)
13-1 | 37 | `i'x'0ZtIg»1\0\ε{:oX*yÁ{Y+X#}gX\*u}&}¸` | need impl
14-1 | 34 | `aε:'k#γ7>–{Ig~•23dγyÚ2B~\|u&Hu}?}HŠ` | tbd
14-2 | 60 | `aε:'k#γ7>–{Ig~\•D{Bú[γ;2,{Y>sÔ†}γ;1†]=c~}yDβ×u+Bbr\Huv;}?}HŠ` | tbd
