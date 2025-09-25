# Vesperale-Romanum
Main repository for the Vesperale Romanum

The Vesperale Romanum is an excerpt of the Antiphonale Romanum, the chant book of the Roman Rite for chanting Vespers and Compline, the evening hours of the Divine Office. The rubrics followed will be Divino Afflatu, following the calendar until the changes of Pope Pius XII (but see below for accomodations accounting for the Pius XII and 1960 offices).

# Contact

You can open an Issue. Or if you'd like, vesperaleromanum(at)gmail.com

# About

Our project builds upon the great work of the Vatican commission, which published the official edition of the Antiphonale Romanum in 1912 (a vesperale followed in 1913) and the monks of the abbey of Saint-Pierre de Solesmes, whose research of medieval manuscripts led to the Vatican commission and to subsequent editions published with the rhythmic signs favored by Solesmes.

# Why a new vesperale?
It is intended as a replacement for print copies, given that neither the full antiphonal nor either vesperale (Vaticana or Solesmes) are in print or are easily obtained. Further, we wish to take advantage of Gregorio, which allows for computer typesetting of Gregorian chant via LuaLaTeX; this is superior to relying on scans, since even if a high-quality scan were available, the quality of the printed score would quickly deterioate, which is the case with the republished _Liber Usualis_ and _Liber Brevior,_ where the neumes such as the quilisma or the rhythmic signs (notably the ictus) are not always identifiable.

However, this is not simply a reproduction. We aim to improve upon the traditional books to make the book as easy to use as possible, although a certain familiarity with the office is required due to the nature of a printed book.

# Contributions

Join us! We especially need:

- those who sing Vespers regularly (particularly some form of 1960 or Pius X/XII Vespers) to voice their opinion and submit corrections, including academics and professional church musicians who sing Vespers, and clergy familiar with the traditional office and with chant.
- anyone interested in type (to fix some problems in EB Garamond)
- graphic designers (we need an artist for the title page)
- TeX experts
- anyone with experience printing a chant book (or aa breviary, missal, etc.) in the last ten to twenty years
= Gregorio-specific experts
- someone with a solid understanding of the pre-1955 rubrics
- a Latinist (or a few)


To actually compile documents, you need a working LaTeX distribution and an editor (either a GUI for LaTeX specifically or your text editor of choice. See [here](https://latex-tutorial.com/installation/) for information about MikTeX, [here](https://tug.org/mactex/) for MacTeX (which works very well on macOS), and [here](https://tug.org/texlive/acquire-netinstall.html) for TeXLive. You can also work on [Overleaf](https://www.overleaf.com) if you really want.

It may be helpful to edit gabc files in a visual editor such as [Source and Summit](https://www.sourceandsummit.com/editor/alpha) (but note that it isn't up to date, so some Gregorio features won't work correctly!).

 See below for font information.


# Top-level tasks

- Collect all chants from Gregobase and transcribe missing solemn versicles, etc. common tones; psalms are taken from Ben Bloomfield's Psalm Tone Tool. (This should be done as of Sept. 2025). Correct as necessary (file names, following style guides)
- Collect texts from Divinum Officium or Psalm Tone Tool (should be complete as of Sept. 2025); correct as necessary per style guides.
- Typeset each part of proper of time, of saints, commons, varia, appendices. 1st draft done as of Sept. 2025
- Index chants that need to be indexed: most ants, hymns, varia. (should be complete as of Sept. 2025)
- Index psalms (if we choose). to do.
- Create index of feasts (excluding 1960 and proprium Galliae). 1st revision done as of Sept. 2025.
- Correct Latin rubrics (both for typographical errors and for errors in Latin in new rubrics). To do as of Sept. 2025.
- Revise ONLY to fix typographical errors (following style guide, checked against Solesmes LA1949). To do as of Sept. 2025.
- Tweak Gregorio output (including finalizing where EUOUAE needs to be kept) adjusting page breaks accordingly.
- Add/correct LaTeX sectioning commands and add/change headers (fiest attempt should be complete as of Sept. 2025); correct `pageref` and `label` [(See this thread ](https://groups.google.com/g/gregorio-users/c/WPbwsmIqHrc/m/-Z9RxtYTAgAJ)) which will produce a completed draft.
- Proofread completed book(s) (including ensuring correct pageref to Gregorio scores); finalize page breaks.

# Editorial Principles and Choices Made

The vesperale project follows at its heart the office up to the changes of Pope Pius XII. For the most part, it is possible to use the Divino Afflatu offices for the 1960 office, which is already the case for most people using a vintage _Liber Usualis._

This aims to be a practical book to be put out as soon as possible, and we do not intend to include any melodic restitutions, which also avoids disturbing the faithful used to the existing melodies.

We plan to include the ancient hymns in the appendix; the FSSP vesperal for 1960 does as well.

We will keep the reciting tone of psalms in mode 3 on Do. The more recent form of tone 6 is paired per custom with the antiphons of mode 6.
The ending of tone 2 psalms is the same as in the Vatican Edition and the Solesmes books, and the default tone for the tonus peregrinus is the Solesmes tone in common use.

For tones 4A* and 8G*: we will, however, deviate: the endings with a podatus will be given at the end of the first verse and where EUOUAE is printed.

Since the psalm ending is provided, EUOUAE is usually commented off in the code for psalm antiphons (it will be entirely removed from scores of the Triduum). But as this is a practical edition, the Magnificats will be printed in one block as in the Liber Usualis, and so EUOUAE will be kept there. In some cases, EUOUAE is given if a page turn to the psalm is necessary (since chanters may wish to turn back to the antiphon before singing the final verse beginning "Sicut erat…").

The rhythmic signs are kept. It is easier to keep the rhythmic signs than to pick and choose and to then change the spacing from the Solesmes edition to the Vatican Edition. With a few exceptions where Solesmes had to faithfully observe the Vatican Edition's inclusion of incorrect notation (on first syllables of spondees following a half bar, which should have two longer neumes instead of one ordinary punctum) we simply reproduce the signs and notation, ideally up to the 1960 edition of the _Liber antiphonarius._

Pointed psalms (italics and bolding following the _Liber Usualis,_ with the first verse of the psalm provided in chant) are given under every antiphon or, for the common and proper of saints and for the variable psalms of major feasts of the temporal cycle, at least once per division of the book so as to reduce repetition but in minimizing the turns needed (and the number of ribbons or bookmarks). This makes chanting easier, with fewer page turns.

The verse numbers going from 1 to n are kept from the form of the _Liber Usualis_ as a reference for choirmasters working with singers and organists not sufficiently fluent in Latin, particularly useful in finding their place in rehearsals or keeping track of divisions while singing the office. The FSSP vesperal keeps these numbers as well.

For the psalter, antiphons are given as in the antiphonal and in the _Liber Usualis_ for Sunday and Saturday Vespers and at Compline; otherwise, the psalms and antiphons are as in the _Liber Usualis,_ with the full antiphon given at the beginning of the corresponding Vespers psalm (to faciliate chanting on double feasts which use the ferial psalms and on ferias for those following 1960).

In the psalter, we give the first verse of psalms which have a different first verse from the antiphon (e.g. at Friday Compline). The first verse is need in the case of Friday Compline since the antiphon begins with the same words but is not the same text in full.

The first psalm of Saturday Vespers presents a problem without an elegant solution: the first word "Benedictus" must be sung with the ordinary intonation, before the rest of the psalm as given, as the antiphon text does not contain the entire first verse. Therefore, Saturday, only the first word of psalm 143.I with its intonation is needed for those singing Vespers per annum according to the 1960 office; due to page limitations, and to avoid confusion, we do not print it, but if needed, it is printed in full under Saturdays Vespers in Paschal Time. Note that in the fifth psalm, when following 1960 rubrics, the intonation needs to be sung on the second verse (just as on Sundays with psalm 109, for 1960 practice), the antiphon containing the full first verse having been sung in full.
 
Proper antiphons in the other parts of the book are given before the psalm and are not repeated afterwards, as is the case for Matins and Tenebrae in the _Liber Usualis._

In the _Liber Usualis,_ the most commonly used book even today, the singer is forced to turn delicate pages in order to find most of the psalms, and the book is very unbalanced, particularly for Sunday Vespers. We aim to avoid this by moving the psalter to the middle as in postconciliar editions. This should also maximize the life of the binding. Further, the size will hew as closely as possible to that of the modern Solesmes antiphonal.

The tones of the hymns are taken from the 1912 edition as reproduced by Solesmes; the elisions are given per the Solesmes editions, that is to say that hypermetric syllables are left in, to let those chanters who sing them sing them and to let those who omit them do so as well, except for a few late editions which omit these syllables.

The Magnificat will be given in full with all of the tones necessary, as in the _Liber Usualis;__ the antiphonal gives the first half but presumes that the chanter memorized the second half of the text and can correctly apply the tones, which poses a problem with some tones such as 4E.

The common tones will also be reproduced in a dedicated section, at the front of the book (somewhat like in the antiphonal, and therefore not at Sunday/Monday Vespers and Sunday Compline).

We include a selection of chants needed for benediction.

The ancient hymns, the new feasts, and the proper of France, although printed before the Index Generalis (ToC) (Sept 2025 version) will be essentially an appendix.


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

The punctuation and syllabification of the psalms is to follow the _Liber Antiphonarius_ and especially the _Liber Usualis,_ since bolding and italics are determined by `\textbf` and `\textit` with the text in between curly braces `{}`. For the flex (`†`), a decision will have to be made on a case-by-case basis if problems arise, as the placement may have changed in the 1961 LU. Additionally, Ben Bloomfield seems to have followed the breviary, so commas need deleting, colons need replacing with periods (at the end of verses), etc. and we will add verse numbers following the LU for convenience (this is done in LaTeX using `\item` and an `enumerate` environment controlled with the `enumitem` package)


# Fonts and other things

EB Garamond is the body font (used for anything except the chant scores, for which the fonts are contained in the `gregoriotex` package that comes with a standard TeX distribution or is installed separately).

The fonts are subject to revision since the original designer has returned; the initials font in particular is being completed, but this will take time. If and when this changes, the new fonts will be added and an announcement made.

# Changes to permit celebration of the latter Pius XII and John XIII rubrics

Ss. Anthony and Lawrence of Brindisi are both named among the Doctors in the Magnificat antiphon. A rubric directing one to use either the antiphon of the common as before 1946 or to that of a Doctor is given for the former; the collect of the latter is found in the appendix.

In the appendix, an asterisk indicates the years in which an addition or variation became obligatory, so one may celebrate some but not all of the Pius XII changes and also the John XIII changes.

After consulting the ordo, one celebrates only what is listed as II Vespers of feasts (i.e. most feasts other than those not reduced to commemorations at Lauds only, suppressed from the calendar) as found in the main body of the antiphona. One ignores the rubrics to commemorate the precedeing or following feast, most octaves, or a Sunday (especially on the feasts of the Holy Family, the Trinity, and Christ the King, which are the only feasts fixed to Sunday), as well as the vigil of the Epiphany, per the rubrics.

In conforming with the decree _Cum Sanctissima,_ it seems possible to celebrate Vespers in the evening of a feast reduced originally to a commemoration, both in Lent and outside of it, per the 1960 rubrics. For this reason, simplex feasts reduced to a commemoration in 1955 or 1960 are kept, even in cases where there is no commemoration at Vespers of the previous evening (e.g. Feb. 3, Sept. 9).

# Expressions of gratitude

We wish to thank Matthias Bry for his help with LaTeX, Gregorio, and Github, and especially for his work on the [Nocturnale Romanum](https://github.com/Nocturnale-Romanum/). This project would not be possible without borrowing Matthias's work, so this project is licensed accordingly.

Olivier Berten set up and maintains Gregobase, for which Andrew Hinkley transcribed the Liber Usualis and the Liber Antiphonarius. Jacques Perrière fixes things such as syllabification, spacing, and the placement of rhythmic signs; they walked so that we can run.

The [Gregorio mailing list](https://groups.google.com/g/gregorio-users) and [project](http://gregorio-project.github.io/index.html) allow for high-quality typesetting, so our thanks goes out to developers, including the font designers, skilled users, and others invested in singing and producing books of Gregorian chant.

Gregory DiPippo contributes rubrical assistance and above all corrects the Latin of newly-composed or heavily-edited rubrics.

The schola cantorum with which I sing serves as my testing environment.

We also thank those who inspired us to chant in the first place and our teachers, especially for those who are in the lineage of Dom André Mocquereau and Dom Joseph Gajard, the masters themselves, for we would have no need of a new book without them, and it is Dom Mocquereau in particular who directed the publication of the Solesmes editions as we know them, in whose footsteps Dom Gajard continued after the death of his confrère.

Finally, Georg Duffner and Octavio Pardo designed the font used for the body, and Georg is currently working on improving it (now on hiatus as of 2024 but the initials font is complete enough to be used for drop caps of certain scores).
