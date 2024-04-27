# Euterpe
Euterpe is a collection of ancient Greek texts in plain Unicode format written before 1453 CE. The initial goal is to transcribe all pre-hellenistic texts and their scholia (which are, admittedly later). Once this initial phase is complete, a search engine will then be added to find Greek phrases or word usages within the collection, including proper names. The texts will also be displayed, one book at a time, syncro-scolled with a number of other text flows such as scholia, or translations. The transcriptions are augmented by an unobtrustive referencing system, based on the traditional names for subdivisions found in print editions, which will allow the works to be cited, or syncro-scrolled to the other views. No markup codes will be used. 

## Motivation
Existing archives and commercial publishers seek to control in some way the patrimony of the ancient Greeks, which belongs to all. Embedding technology that is already obsolete or becoming obsolete into these valuable texts is also a concern. In the spirit of the successful Gutenberg.org collection of plain ASCII texts, this repository offers plain Unicode texts free from any licensing restrictions other than the requirement to acknowledge their source, and licenses their reuse for any purpose whatsoever.

## Inverse Greek-English lexicon
These transcriptions will also form the basis for a series of specialist inverse Greek-English lexica (which could also be later expanded to other languages) which turns inside out the traditional lexicon format by linking word forms as they occur in the text to their headwords, not the other way around. A user of such a lexicon would only have to enter the word they see on the page, perhaps restricted by author, to see its correct part of speech and local meaning. This will greatly reduce the amount of knowledge that people need to acquire before they begin to learn ancient Greek. 

It is also a necessary prequisite for enabling machine translation. If these ancient texts are to survive in a modern world we will have to tell a machine what each word-form, each apostrophised word, and each crasis means. 

## Correction status
There are three correction grades:

1. Bronze — transcription direct from OCR has been edited by a human and proofread. The 
transcription is checked for double accents and corrected if any illegal ones are found.
2. Silver — a vocabulary is built and checked by a human against the original pages
3. Gold — Each word is looked up in a lexicon and its meaning and part of speech determined and 
recorded in the inverse Greek-English lexicon. At this stage the quality of the transcription 
is about the same as that of a print edition, and maybe better.

The manifest.json file in each directory records the source of the transcriptions, and their correction status.
