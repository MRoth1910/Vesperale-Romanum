# Vesperale-Romanum
Main repository for the Vesperale Romanum

The Vesperale Romanum is an excerpt of the Antiphonale Romanum, the chant book of the Roman Rite for chanting Vespers and Compline, the evening hours of the Divine Office. The rubrics followed will be Divino Afflatu, following the calendar until the changes of Pope Pius XII (see below).

# Contact

You can open an Issue. Or if you'd like, vesperaleromanum(at)gmail.com

# About

Our project builds upon the great work of the Vatican commission, which published the official edition of the Antiphonale Romanum in 1912 (a vesperale followed in 1913) and the monks of the abbey of Saint-Pierre de Solesmes, whose research of medieval manuscripts led to the Vatican commission and to subsequent editions published with the rhythmic signs favored by Solesmes.

The Vesperale Romanum has thousands of pieces that need to be proofread and then typeset. Some pieces (mostly antiphons of the Proprium Tempore) remain to be transcribed and uploaded to Gregobase or edited there. At that point, they can then be typeset.

# Why a new vesperale?
It is intended as a replacement for print copies, given that neither the full antiphonal nor either vesperale (Vaticana or Solesmes) are in print or are easily obtained. Further, we wish to take advantage of Gregorio, which allows for computer typesetting of Gregorian chant via LuaLaTeX; this is superior to relying on scans, since even if a high-quality scan were available, the quality of the printed score would quickly deterioate, which is the case with the republished _Liber Usualis_ and _Liber Brevior,_ where the neumes such as the quilisma or the rhythmic signs (notably the ictus) are not always identifiable.

However, this is not simply a reproduction. We aim to improve upon the traditional books to make the book as easy to use as possible, although a certain familiarity with the office is required due to the nature of a printed book.

# Editorial Principles and Choices Made

The vesperale project follows at its heart the office up to the changes of Pope Pius XII. For the most part, it is possible to use the Divino Afflatu offices for the 1960 office, which is already the case for most people using a vintage Liber Usualis.

This aims to be a practical book to be put out as soon as possible, and we do not intend to include any melodic restitutions, which also avoids disturbing the faithful used to the existing melodies.

We plan to include the ancient hymns in the appendix (the FSSP vesperal for 1960 does as well).

We will keep the reciting tone of psalms in mode 3 on Do. The more recent form of tone 6 is paired per custom with the antiphons of mode 6.
The ending of tone 2 psalms is the same as in the Vatican Edition and the Solesmes books.

For tones 4A* and 8G*: we will, however, deviate. The endings with a podatus will be given at the end of the first verse because custom has changed even even from Solesmes-style practice: Dom Suñol decreed that this special ending was to be sung only at the doxology, but in practice, it is sung for every verse.

Since the psalm ending is provided, EUOUAE is largely commented off in the code for psalm antiphons (it will be entirely removed from scores of the Triduum). But as this is a practical edition, the Magnificats will be printed in one block as in the Liber Usualis, and so EUOUAE will be kept there (As of June 2024). In some cases, EUOUAE is given if a page turn to the psalm is necessary (since chanters may wish to turn back to the antiphon before singing the final verse beginning "Sicut erat…").

The rhythmic signs are kept. Although the spacing is different between the Vatican Edition and the Solesmes books (sometimes admittedly obscuring the _mora vocis_), it is easier to keep all rhythmic signs than to pick and to choose, and given the number of chanters who still use even the ictus (sometimes called the "vertical episema"), it is better to abstain from interventions and to simply reproduce the signs, ideally up to the 1960 edition of the _Liber antiphonarius_ wherein most but not all "redundant cadences" where notes on an accent on a penultimate syllable and on the final weak syllable have a dot; most antiphosn in the last versions of the Solesmes editions, and therefore most Gregobase antiphons, have the dot on both notes.

We wish to facilitate chanting, and the direction of chanters by choirmasters, by providing pointed psalms (italics and bolding following the _Liber Usualis,_ with the first verse of the psalm provided in chant) under every antiphon or, for the common and proper of saints and for the variable psalms of major feasts of the temporal cycle, at least once per division of the book so as to reduce repetition but in minimizing the turns needed (and the number of ribbons or bookmarks). 

For the psalter, antiphons are given as in the antiphonal and in the _Liber Usualis_ for Sunday and Saturday Vespers and at Compline; otherwise, the psalms and antiphons are as in the _Liber Usualis,_ with the full antiphon given at the beginning of the corresponding Vespers psalm (to faciliate chanting on double feasts which use the ferial psalms). 

For now (as of May 2024),in the psalter, we give the first verse of psalms which have a different first verse from the antiphon (e.g. at Friday Compline, but not at Saturday Vespers). The first verse is need in the case of Friday Compline sung on Saturday since the antiphon begins with the same words but is not the same text in full. The first psalm of Saturday Vespers presents a problem without an elegant solution: the first word "Benedictus" must be sung with the ordinary intonation, before the rest of the psalm as given, as the antiphon text does not contain the entire first verse. But in the fifth psalm, the intonation needs to be sung on the second verse (just as on Sundays with psalm 109), the antiphon containing the full first verse having been sung in full.

Proper antiphons in the other parts of the book are given before the psalm, as is the case for Matins and Tenebrae in the _Liber Usualis._

In the _Liber Usualis,_ the most commonly used book even today, the singer is forced to turn delicate pages in order to find most of the psalms, and the book is very unbalanced, particularly for Sunday Vespers. We aim to avoid this by moving the psalter to the middle as in postconciliar editions. This should also maximize the life of the binding. Further, the size will hew as closely as possible to that of the modern Solesmes antiphonal.

The tones of the hymns are taken from the 1912 edition as reproduced by Solesmes; the elisions are given per the Solesmes editions, that is to say that hypermetric syllables are left in, to let those chanters who sing them sing them and to let those who omit them do so as well.

The Magnificat will be given in full with all of the tones necessary, as in the Liber Usualis; the antiphonal gives the first half but presumes that the chanter memorized the second half of the text and can correctly apply the tones, which poses a problem with some tones such as 4E.

The common tones will also be reproduced in a dedicated section, at the front of the book (somewhat like in the antiphonal, and therefore not at Sunday/Monday Vespers and Sunday Compline).

We inclue the chants needed for benediction, and a supplement for the 1960 office, as well as the latter changes of Pope Pius XII (e.g. May 31, August 22) will be included (however, this is a secondary task to actually typesetting the book). If possible, the proper for France will be typeset as well (as a secondary task).

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

The punctuation and syllabification of the psalms is to follow the _Liber Antiphonarius_ and especially the _Liber Usualis,_ since bolding and italics are determined by `\textbf` and `\textit` with the text in between curly braces `{}`. For the flex (`†`), a decision will have to be made on a case-by-case basis if problems arise, as the placement may have changed in the 1961 LU. Additionally, Ben Bloomfield seems to have followed the breviary, so commas need deleting, colons need replacing with periods (at the end of verses), etc. and we will add verse numbers following the LU for convenience (this is done in LaTeX using `\item` and an `enumerate` environment controlled with the `enumitem` package)

# Contributions

- To actually compile documents, you need a working LaTeX distribution and an editor (either a GUI for LaTeX specifically or your text editor of choice. See [here](https://latex-tutorial.com/installation/) for information about MikTeX, [here](https://tug.org/mactex/) for MacTeX (which works very well on macOS), and [here](https://tug.org/texlive/acquire-netinstall.html) for TeXLive. You can also work on [Overleaf](https://www.overleaf.com) if you really want.
- It may be helpful to edit gabc files in a visual editor such as [Source and Summit](https://www.sourceandsummit.com/editor/alpha) (but note that it isn't up to date, so some Gregorio features won't work correctly!).
- See below for font information.

# To Do

- Collect all chants from Gregobase of the psalter, the ~~proper of time,~~ the ~~commons of saints,~~ and the proper of saints (on a rolling basis, i.e. grab what you need as you work on it, edit, commit, and push; as of Sept 2025, May and February are left to do) as well as the ~~appendix for benediction~~ (done as of October 2024) and for the "Hymni Antiqui" (following 1913 VR format; chants to be taken from the existing files with corrected lyrics, or from the *Antiphonale Monasticum* and transcribed for Saint Michael, with our ictus placement) (completed as of September 4, 2025)
- Remove `--` in file name and replace with `_` (to allow for easier copying/pasting) and remove `ant.`, `...`, and `(` or `)`.
- Proofread (add EUOUAE to Magnificat endings, comment off EUOUAE for most antiphon endings — they will need this only when the psalm is not printed below an antiphon).
- remove space before colons (we use Latin options and language for `babel` that inserts a thin space), change `ae` or `oe` `æ` and `œ` respectively as well as `aé` to `ǽ` (U+01fd) and use TeX to create `œ` with an acute accent) (fixed as of October 2024).
- Correct italics of psalm tex files (See this [issue](https://github.com/Nocturnale-Romanum/nocturnale-romanum/issues/17#issue-1714660808).) 
- Transcribe versicles of feasts where the solemn tone is given and create gabc file (now possible with manual intervention required with the Psalm Tone Tool as of October 2024)
-  Build (that is, create subfile and typeset) psalter (draft done as of summer 2024, except for page breaks), common tones, proper of time (draft, except for headers and page breaks done as of summer 2024), commons of saints (drafts done as of autumn 2024), the proper of saints (as of Sept 2025 now complete), proper of France (complete Sept 2025), 1955/60 (done as of Oct 2024, edited as of Sept 2025) and benediction (draft finished as of spring 2025).
-   This means also means copy, insert, and correct (based on Solesmes/Vaticana) collects, chapters, and versicles.
- Index these pieces as well as the psalms (the index of antiphons and esp. that of index of psalms will be complicated due to the pointing and partial repetition so to minimize page turns but to not use up valuable space), based on code from Nocturnale Romanum project.
- Finish [table of moveable feasts and perpetual Roman calendar](https://github.com/MRoth1910/Kalendarium) (and/or insert it into the main PDF)
- Add/correct LaTeX sectioning commands and add/change headers; correct `pageref` and `label` [(See this thread ](https://groups.google.com/g/gregorio-users/c/WPbwsmIqHrc/m/-Z9RxtYTAgAJ)) which will produce a completed draft.
- Proofread completed book(s).


Along the way: we need someone who is a real LaTeX expert to help, particularly with the table of moveable feasts (which has different requirements than the main project and is quite complex), sectioning commands, widows/orphans (in the proper of saints epecially, ~the date, the feast name, and the rank~ (thank you David Carlisle and TeXSE) plus the text cannot be separated over two pages), spacing of elements on pages (e.g. scores should not stretch too much, and we shouldn't have too much white space between a title and a following score)
  - someone to design a cover (that is, someone who knows how to use software to do it correctly, taking into account the spine etc.)
  - a skilled Latinist to proofread rubrics (mostly taken from the Vaticana, but occasionally emended from the LA) and to help expand abbreviations if this is deemed necessary;
  - an expert (cleric or monk, probably) familiar with syllable divisions in the preconciliar Latin breviary/missal and chant books: collects etc. follow Solesmes practice (-ct for example, not c-t, but i-ps, o-mn seem to break convention as a vowel is left alone the end of a line)
  -  Since the chants are not being restored, a musicologist seems overkill, but a monk of Fontgombault or one of its foundations as well as a priest from a traditional community who sings Vespers regularly would be helpful.
    -  Ditto consultations with a monk of Solesmes or a monastic of another abbey that has experience with using LuaLaTeX to make an entire book (particularly with Gregorio).

# Fonts and other things

EB Garamond is the body font (used for anything except the chant scores, for which the fonts are contained in the `gregoriotex` package that comes with a standard TeX distribution or is installed separately).

The fonts are subject to revision since the original designer has returned; the initials font in particular is being completed, but this will take time. If and when this changes, the new fonts will be added and an announcement made.

# Changes to permit celebration of the latter Pius XII and John XIII rubrics

Ss. Anthony and Lawrence of Brindisi are both named among the Doctors in the Magnificat antiphon. A rubric directing one to use either the antiphon of the common as before 1946 or to that of a Doctor is given for the former; the collect of the latter is found in the appendix.

In the appendix, an asterisk indicates the years in which an addition or variation became obligatory, so one may celebrate some but not all of the Pius XII changes and also the John XIII changes.

After consulting the ordo, one celebrates only what is listed as II Vespers of feasts (i.e. most feasts other than those not reduced to commemorations at Lauds only, suppressed from the calendar) as found in the main body of the antiphona. One ignores the rubrics to commemorate the precedeing or following feast, most octaves, or a Sunday (especially on the feasts of the Holy Family, the Trinity, and Christ the King, which are the only feasts fixed to Sunday), as well as the vigil of the Epiphany, per the rubrics.

In conforming with the decree _Cum Sanctissima,_ it seems possible to celebrate Vespers in the evening of a feast reduced originally to a commemoration, both in Lent and outside of it, per the 1960 rubrics.

# Expressions of gratitude

We wish to thank Matthias Bry for his help with LaTeX, Gregorio, and Github, and especially for his work on the [Nocturnale Romanum](https://github.com/Nocturnale-Romanum/). This project would not be possible without borrowing Matthias's work, so this project is licensed accordingly.

Olivier Berten set up and maintains Gregobase, for which Andrew Hinkley transcribed the Liber Usualis and the Liber Antiphonarius. Jacques Perrière fixes things such as syllabification, spacing, and the placement of rhythmic signs; they walked so that we can run.

The [Gregorio mailing list](https://groups.google.com/g/gregorio-users) and [project](http://gregorio-project.github.io/index.html) allow for high-quality typesetting, so our thanks goes out to developers, including the font designers, skilled users, and others invested in singing and producing books of Gregorian chant.

Gregory DiPippo contributes rubrical assistance and above all corrects the Latin of newly-composed or heavily-edited rubrics.

The schola cantorum with which I sing serves as my testing environment.

We also thank those who inspired us to chant in the first place and our teachers, especially for those who are in the lineage of Dom André Mocquereau and Dom Joseph Gajard, the masters themselves, for we would have no need of a new book without them, and it is Dom Mocquereau in particular who directed the publication of the Solesmes editions as we know them, in whose footsteps Dom Gajard continued after the death of his confrère.

Finally, Georg Duffner and Octavio Pardo designed the font used for the body, and Georg is currently working on improving it (now on hiatus as of 2024 but the initials font is complete enough to be used for drop caps of certain scores).
