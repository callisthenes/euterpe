# Plain text format
The Euterpe texts are encoded in standard Unicode, and contain no explicit markup. 

## Copyright
All transcriptions (excluding translations) are, unless specified otherwise, licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode). To facilitate reuse, the usual practice of adding the copyright notice at the start of each file has been dispensed with. However, this should _not_ be taken to mean that the license does not apply to it.

## Format of print editions
The formatting of print editions is ignored. Page divisions are removed and the text is allowed to run continuously. Line-breaks and associated hyphens are removed and the words joined up. All textual apparatus and notes are removed. Only formatting intrinsic to the text, such as poetic lines and paragraphs, is preserved.

All texts are encoded the same way to facilitate searching. Editions using different conventions are modified to conform to the conventions described in this document.

## References
Ancient Greek texts are traditionally subdivided on two or three levels: for example, the familiar 'chapter and verse' of the New Testament is a two-level system. However, quite often works are divided by book, chapter and section, for example, in Plato. Euterpe follows these conventions because otherwise existing references to classical texts could not be found in the corpus.

The ordering of references is described in the manifest document provided with each set of texts encoded using the same conventions. References are nested implicitly, not explicitly. For example, the fact that a section is within a chapter can be inferred from the manifest, or from the frequency of chapter and section references.

### File names
The name of a file, minus its extension, is taken as the topmost division of a work. e.g. VI.txt is the name of book 6 or VI of the Iliad. Prose works have the extension .md to force line-wrapping on github, but follow the same plain text format, i.e. they are _not_ in markdown format.

### Chapters and sections
Since Greek texts themselves contain no Arabic numbers or Latin letters, these characters are used as a reference system without recourse to explicit markup. This is so that in future, if any markup technology becomes obsolete, the text will still be readable in the current technology, or can be easily adapted to it. This also ensures that the transcriptions are readable by humans. 

### Default numbering
The default reference system uses alternating Roman and arabic numbers where they are used in the original printed text. Print conventions are followed wherever possible, the default numbering being used if there is no standard between editions. So in the default numbering system 3.V.34 would mean 'book 3, chapter 5, section 34'. This may be overridden in cases where other symbols are consistently used for subdivisions, such as single Roman letters for sections in Plato. Numbers in the Alexandrian numbering system, i.e. Greek lower or uppercase letters followed by prime (′) are normalised as Roman or arabic numbers. 

### Position
References normally appear at the start of a line or paragraph. However, in prose works references may also appear within a line. In print editions a number or letter in the margin indicates a break at the first major punctuation character, but there might be several such marks. Moving references inline, as in the Budé editions, removes this ambiguity. If a section number occurs at line start it is followed by a single space, or two spaces if it marks the start of a new paragraph and the paragraph is not already marked by a preceding blank line. 

### Line numbers
Line numbers need not be supplied for each line. Normally in print editions they are given at five-line intervals. Euterpe follows this convention, except that a single space always follows a line number, and two spaces at the start of a paragraph. Wherever the traditional line-numbering has been altered by the editor, explicit line numbers for the re-ordered lines may be added to reset the usual line-numbering. 

## Titles
Lines containing no Greek text, separated from the surrounding text by a blank line before (or if the title is at the start of a file), and one blank line after, are interpreted as titles of short works.

## Quotations
Quotations on two levels are supported. «...» is used for the first level, and ‹...› for the second level (nested quotations). The reason for using the French convention is that standard English and American usage requires single-quotes for apostrophe, which cannot be distinguished from quotation marks at the first or second level. Although the German use of single quotation marks does distinguish the apostrophe from the closing quotation mark, it is still less clear than the French convention.

Successive paragraphs in a quotation repeat the relevant quotation marks at the start and end of the paragraph. 

## Paragraphs
Paragraphs are marked either by a preceding newline or by two spaces at line-start. If a reference begins the line, two spaces _after_ the reference indicates a new paragraph.

## Proper names
Proper names and proper adjectives start with a capital letter. No other words, not even at sentence or paragraph start, are capitalised. Capitalising only proper names facilitates searching. 

## Accentuation
The accentuation rules follow those specified in Goodwin's Greek grammar (1894, §106-146). Acutes on successive syllables are not permitted. Diaereses are placed over vowels that do not form a diphthong with the preceding vowel (Goodwin §9). 

## Letters
Iota subscript is preferred to adscript. The letter theta θ (Unicode 03B8) is preferred to var-theta ϑ (Unicode 03D1). Var-phi φ (Unicode 03C6) is preferred to ϕ (Unicode 03D5). Beta is β (Unicode 03B2) not ꞵ (Unicode A7B5) or ϐ (Unicode 03D0). Sigma is σ within words (Unicode 03C3) and ς at the end (Unicode  03C2). Lunate sigma ϲ (Unicode 03F2) is not used.

### Apostrophes
The apostrophe character in Greek text is the Greek koronis (Unicode IFBD), _not_ the Greek psili (Unicode IFBF) or closing single quote (Unicode 2019). All breathing marks are combined with the letter to which they refer, e.g. ᾽Α is always encoded as Ἀ.


