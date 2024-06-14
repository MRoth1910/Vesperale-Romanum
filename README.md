# Vesperale-Romanum
Main repository for the Vesperale Romanum

The Vesperale Romanum is an excerpt of the Antiphonale Romanum, the chant book of the Roman Rite for chanting Vespers and Compline, the evening hours of the Divine Office. The rubrics followed will be Divino Afflatu, following the calendar until the changes of Pope Pius XII (see below).

# Contact

You can open an Issue. Or if you'd like, vesperaleromanum(at)gmail.com

# About

The Vesperale Romanum has thousands of pieces that need to be proofread and then typeset. Some pieces (mostly antiphons of the Proprium Tempore) remain to be transcribed and uploaded to Gregobase or edited there. At that point, they can then be typeset.

Our project builds upon the great work of the Vatican commission, which published the official edition of the Antiphonale Romanum in 1912 (a vesperale followed in 1913) and the monks of the abbey of Saint-Pierre de Solesmes, whose research of medieval manuscripts led to the Vatican commission and to subsequent editions published with the rhythmic signs favored by Solesmes.

# Why a new vesperale?
It is intended as a replacement for print copies, given that neither the full antiphonal nor either vesperale (Vaticana or Solesmes) are in print. Further, we wish to take advantage of Gregorio, which allows for computer typesetting of Gregorian chant via LuaLaTeX; this is superior to relying on scans, since even if a high-quality scan were available, the quality of the printed score would quickly deterioate, which is the case with the republished Liber Usualis and Liber Brevior, where the neumes such as the quilisma or the rhythmic signs (notably the ictus) are not always identifiable.

However, this is not simply a reproduction. We aim to improve upon the traditional books to make the book as easy to use as possible, although a certain familiarity with the office is required due to the nature of a printed book.

# Editorial Principles and Choices Made

The vesperale project follows at its heart the office up to the changes of Pope Pius XII (with some latitude, e.g. including Ss. Anthony and Lawrence Brindisi among the Doctors is less problematic than including the new Common of Popes or the new offices of the Assumption and of May 1 among other changes). For the most part, it is possible to use the Divino Afflatu offices for the 1960 office, which is already the case for most people using a vintage Liber Usualis.

This aims to be a practical book to be put out as soon as possible, and we do not intend to include any melodic restitutions, which also avoids upseting the faithful. Therefore, while we plan to include the ancient hymns in the appendix (the FSSP vesperal for 1960 does as well), we intend to keep mode 3 psalms with a dominant of Do, the newer mode 6 tone, the familiar mode 2 psalm final etc. as in the Vatican Edition and the Solesmes books. We will, however, deviate, because custom has changed with respect to endings for which a * indicates an alternative of a podatus (4A* and 8G*): the endings will be given at the end of the first verse (this deviates even from Solesmes-style practice: Dom Suñol decreed that it was to be sung only at the doxology) 

Since the psalm ending is provided, EUOUAE is commented off in the code for psalm antiphons (and needs to be removed from scores of the Triduum). But as this is a practical edition, the Magnificats will be printed in one block as in the Liber Usualis, and so EUOUAE will be kept there (As of June 2024). 

The rhythmic signs are kept, because although the spacing is different between the Vatican Edition and the Solesmes books (sometimes admittedly obscuring the mora vocis), it is easier to keep all rhythmic signs than to pick and to choose, and given the number of chanters who still use even the ictus (referred to in print sometimes as the "vertical episema"), it is better to abstain and to reproduce the signs, ideally up to the 1960 edition of the Liber antiphonarius (wherein most but not all "redundant cadences" such as in mode 8 antiphons have two dotted puncta before full bars), complyng with the work done to date with Gregobase.

We wish to facilitate chanting, and the direction of chanters by choirmasters, by providing pointed psalms (italics and bolding following the Liber Usualis, with the first verse of the psalm provided in chant) under every antiphon or, for the common and proper of saints and for the variable psalms of major feasts of the temporal cycle, at least once per division of the book so as to reduce repetition but in minimizing the turns needed (and the number of ribbons or bookmarks). 

For the psalter, antiphons are given as in the antiphonal (and Liber Usualis) for Sunday and Saturday Vespers and at Compline; otherwise, the psalms and antiphons are as in the Liber Usualis, with the full antiphon at the beginning of the corresponding psalm (to faciliate chanting on double feasts which use the ferial psalms). For now (as of May 2024),in the psalter, we give the first verse of psalms which have a different first verse from the antiphon (e.g. at Friday Compline, but not on Saturday Vespers). Proper antiphons in the other parts of the book are given before the psalm, as at Tenebrae in the Liber Usualis.

In the Liber Usualis, the most common book used even today, the singer is forced to turn delicate pages in order to find most of the psalms, and the book is very unbalanced, particularly for Sunday Vespers. We aim to avoid this by moving the psalter to the middle as in postconciliar editions. This should also maximize the life of the binding. Further, the size will hew as closely as possible to that of the modern Solesmes antiphonal.

The tones of the hymns are taken from the 1912 edition as reproduced by Solesmes; the elisions are given per the Liber antiphonarius/Usualis, that is to say that hypermetric syllables are left in, to let those chanters who sing them sing them and to let those who omit them do so as well.

The Magnificat will be given in full with all of the tones necessary, as in the Liber Usualis; the antiphonal gives the first half but presumes that the chanter memorized the second half of the text and can correctly apply the tones. (When the canticle is sung to tone 4E, the dactyls test even the best chanters.) 

The common tones will also be reproduced in a dedicated section (as in the antiphonal, and therefore not at Sunday/Monday Vespers and Sunday Compline), along with the chants needed for benediction, and a supplement for the 1960 office, as well as the latter changes of Pope Pius XII (e.g. May 31, August 22) will be included (however, this is a secondary task to actually typesetting the book). If possible, the proper for France will be typeset as well (but again as a secondary task).

The verse numbers going from 1 to n are kept from the form of the Liber Usualis as a reference for choirmasters working with singers and organists not sufficiently fluent in Latin, particularly useful in finding their place in rehearsals or keeping track of divisions while singing the office (This is subject to change, but it is a primary practical consideration). The FSSP's vesperal for the 1960 office does the same thing.


# Sources:

- [Liber Antiphonarius](https://archive.org/details/liber-antiphonarius-1960) of Solesmes (LA)
- [French edition of the Vesperale Romanum](https://archive.org/details/vesperaleromaum00anonuoft/) according to the Vatican edition (VR or Vaticana)
- [Divinum Officium](http://divinumofficium.com)
- Liber Usualis (various editions, includign the nº 780 of 1934 and the [nº 801 of 1961](https://musicasacra.com/2007/07/liber-usualis-online/)) (LU)
- [Gregobase](https://gregobase.selapa.net)
- [Psalm Tone Tools](http://bbloomf.github.io/jgabc/psalmtone.html) (with substantial modifications to both gabc and tex files) 

Some commentary on style seems necessary, because the sources do not agree entirely.

There are differences in punctuation between the breviary and the chant books. The Liber Antiphonarius and the Vesperale Romanum largely agree except for some placements of the dagger (`†`) and the asterisk (`*`) in the orations (usually, a dagger is present in the Vaticana but absent in the LA, such as for many of the Lenten prayers). We will follow the chant books, and where they differ, one or the other is to be followed according to best judgement; it is more important to get the punctuation right.

The versicle punctuation also comes from the chant books. Ensuring that chanters sing fluently and smoothly requires removing commas.

The punctuation and syllabification of the psalms is to follow the Liber Antiphonarius and especially the Liber Usualis, since bolding and italics are determined by `\textbf` and `\textit` with the text in between curly braces `{}`. For the flex (`†`), a decision will have to be made on a case-by-case basis, as the placement changed in the 1961 LU. Additionally, Ben Bloomfield seems to have followed the breviary, so commas need deleting, colons need replacing with periods (at the end of verses), etc. and we will add verse numbers following the LU for convenience.

# Expressions of gratitude

We wish to thank Matthias Bry for his help with LaTeX, Gregorio, and Github, and especially for his work on the [Nocturnale Romanum](https://github.com/Nocturnale-Romanum/). This project would not be possible without borrowing Matthias's work, so this project is licensed accordingly.

Olivier Berten set up and maintains Gregobase, for which Andrew Hinkley transcribed the Liber Usualis and the Liber Antiphonarius. Jacques Perrière fixes things such as syllabification, spacing, and the placement of rhythmic signs; they walked so that we can run.

The [Gregorio mailing list](https://groups.google.com/g/gregorio-users) and [project](http://gregorio-project.github.io/index.html) allow for high-quality typesetting, so our thanks goes out to developers, including the font designers, skilled users, and others invested in singing and producing books of Gregorian chant

We also thank those who inspired us to chant in the first place and our teachers, especially for those who are in the lineage of Dom André Mocquereau and Dom Joseph Gajard, the masters themselves, for we would have no need of a new book without them, and it is Dom Mocquereau in particular who directed the publication of the Solesmes editions as we know them, in whose footsteps Dom Gajard continued after the death of his confrère.

Finally, Georg Duffner and Octavio Pardo designed the font used for the body, and Georg is currently working on improving it.

# Contributions

- To actually compile documents, you need a working LaTeX distribution and an editor (either a GUI for LaTeX specifically or your text editor of choice. See [here](https://latex-tutorial.com/installation/) for information about MikTeX, [here](https://tug.org/mactex/) for MacTeX (which works very well on macOS), and [here](https://tug.org/texlive/acquire-netinstall.html) for TeXLive. You can also work on [Overleaf](https://www.overleaf.com) if you really want.
- It may be helpful to edit gabc files in a visual editor such as [Source and Summit](https://www.sourceandsummit.com/editor/alpha) (but note that it isn't up to date, so some Gregorio features won't work correctly!).
- See below for font information.

# To Do

- Collect all chants from Gregobase of the psalter, the proper of time, the commons of saints, and the proper of saints as well as the appendix for benediction.
- Index these pieces as well as the psalms (the index of psalms will be complicated due to the pointing and partial repetition so to minimize page turns but to not use up valuable space)
  - Remove `--` in file name and replace with `_` (to allow for easier copying/pasting in some LaTeX editors such as in TeXShop).
- Proofread (add EUOUAE to Magnificat endings, comment off EUOUAE to psalm endings — psalms will need this only when the psalm is not printed below an antiphon), remove space before commas, change `ae` or `oe` `æ` and `œ` respectively as well as `aé` to `ǽ` (U+01fd) (but not, for now `œ` with an acute accent)
- Correct italics of psalm tex files (See this [issue](https://github.com/Nocturnale-Romanum/nocturnale-romanum/issues/17#issue-1714660808).) 
- Transcribe versicles of feasts where the solemn tone is given and create gabc file.
- Build psalter, common tones, proper of time, commons of saints, the proper of saints, and benediction. This means also means copy, insert, and correct (based on Solesmes/Vaticana) collects, chapters, and versicles.
- Finish [table of moveable feasts and perpetual Roman calendar](https://github.com/MRoth1910/Kalendarium) (and insert it into the main PDF)
- Add/correct LaTeX sectioning commands and add/change headers; correct `pageref` and `label` [(See this thread ](https://groups.google.com/g/gregorio-users/c/WPbwsmIqHrc/m/-Z9RxtYTAgAJ)) which will produce a completed draft.
- Proofread completed book(s).
- Along the way: we need someone who is a real LaTeX expert to help, particularly with the table of moveable feasts (which has different requirements than the main project and is quite complex), sectioning commands, widows/orphans (in the proper of saints epecially, the date, the feast name, and the rank plus the text cannot be separated over two pages), spacing of elements on pages (e.g. scores should not stretch too much, and we shouldn't have too much white space between a title and a following score)
  - someone to design a cover (that is, someone who knows how to use software to do it correctly, taking into account the spine etc.)
  - a skilled Latinist to proofread rubrics (mostly taken from the Vaticana, but occasionally emended from the LA) and to help expand abbreviations if this is deemed necessary;
  - an expert (cleric or monk, probably) familiar with syllable divisions in the preconciliar Latin breviary/missal and chant books (should the collects follow the chant or should they follow the missal? Desclée carefully avoids this problem for the most part.)
  -  Since the chants are not being restored, a musicologist seems overkill, but a monk of Fontgombault or one of its foundations as well as a priest from a traditional community who sings Vespers regularly would be helpful.
    -  Ditto consultations with a monk of Solesmes or a monastic of another abbey that has experience with using LuaLaTeX to make an entire book (particularly with Gregorio).

# Fonts and other things

EB Garamond is the body font (used for anything except the chant scores, for which the fonts are contained in the `gregoriotex` package that comes with a standard TeX distribution or is installed separately).

The fonts are subject to revision since the original designer has returned; the initials font in particular is being completed, but this will take time. If and when this changes, the new fonts will be added and an announcement made.


