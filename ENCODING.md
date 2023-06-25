# Plain text format
The Euterpe texts are encoded in standard Unicode, and contain no explicit markup. 

## Copyright
All transcriptions (excluding translations) are, unless specified otherwise, licensed under the Creative Commons Attribution 4.0 International License. In layman's terms this means that the transcriptions can be reused for any purpose whatsoever, including commercially, as long as the source of the transcriptions is acknowledged in the derived work. No guarantee as to their accuracy is provided. To facilitate reuse, the usual practice of adding the copyright notice at the start of each file has been dispensed with. However, this should _not_ be taken to mean that the license does not apply to it.

## References
Ancient Greek texts are traditionally subdivided on two or three levels: for example, the familiar 'chapter and verse' of the New Testament. However, quite often we find works divided by book, chapter and section, for example, in Plato. Euterpe follows these conventions because otherwise existing references to classical texts could not be found in the corpus.

### File names
The name of a file, minus its extension, is taken as the topmost division of a work. e.g. VI.txt is the name of book 6 or VI of the Iliad. Prose works have the extension .md to allow for line-wrapping on github, but follow the same plain text format, i.e. they are _not_ in markdown format.

### Chapters and sections
Since Greek texts themselves contain no Arabic numbers or Latin letters, these characters can be used as a reference system without recourse to explicit markup. This is so that in future, if any markup technology becomes obsolete, the text will still be readable in the current technology, or can be easily adapted to it.  This also ensures that the transcriptions are readable by humans.

### Default numbering
The default reference system uses alternating Roman and arabic numbers where they are used in the original printed text. Print conventions are followed wherever possible, the default numbering being used whenever there is no standard between editions. So in the default numbering system 3.V.34 would mean 'book 3, chapter 5, section 34'. This may be overridden in cases where other symbols are consistently used for subdivisions, such as single Roman letters for sections in Plato. Numbers in the Alexandrian numbering system, i.e. Greek lower or uppercase letters followed by prime (′) are normalised as Roman or arabic numbers. 

### Position
References normally appear at the start of a line or paragraph. However, since lines in print editions of prose works are are joined together, and all hyphenation removed, references may also appear within a line. In print editions a number or letter in the margin indicates a break at the first major punctuation character, but there might be several. Moving them inline, as in the Bude editions, removes this ambiguity. Transcriptions of print editions not conforming to this rule have been altered in conformance with it.

### Line numbers
Line numbers need not be supplied for each line. Normally in print editions these are provided at 5-line intervals. Euterpe follows this convention, so a line two lines after one explicitly number 235 is line 237. Exceptions occur when the traditional line-numbering has been altered by the editor. In such cases explicit line numbers for the re-ordered lines can be used, which reset the sequential line-numbering, exactly as in the print edition.

## Titles
Any line separated from the surrounding text by blank lines before and after (or at the start of the text) and containing a majority of Latin characters or arabic numbers are interpreted as titles of short works within one file.

## Quotations
Quotations on two levels are supported. «...» is used for the first level, and ‹...› for the second level (nested quotations). The reason for using the French convention is that standard English and American usage requires single-quotes for apostrope, which cannot be distinguished from quotation marks at the first or second level.

### Apostrophes
The apostrophe character in Greek text is the Greek koronis (Unicode IFBD), _not_ the Greek psili (Unicode IFBF). All breathing marks are combined with the letter, e.g. ᾽Α is always encoded as Ἀ.

## Proper names
Proper names and proper adjectives start with a capital letter. No other words, either at sentence or paragraph start, are capitalised. Capitalising only proper names facilitates searching. Transcriptions of print editions not following this convention have been normalised.

## Accentuation
The accentuation rules follow those specified in Goodwin's Greek grammar (1894). Double-acutes on successive syllables are not allowed. Diaereses are placed over vowels that do not form a diphthong with the preceding vowel (Goodwin §9). Print editions not following these conventions have been normalised.