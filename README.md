# Prakrit Lexicons

This repository will contain data from Prakrit lexicons and glossaries, with the goal of assembling data for a unified search. We can distinguish premodern from modern lexicons:

## Premodern lexicons

### Dhanapāla’s *Pāiyalacchī* (*Prakrit Lakṣmī*)

Composed in Dhārā in 972 for the poet’s sister. It is organized into topical sections, and is a short *Amarakōśa* for Prakrit.

A [TEI version](https://github.com/aso2101/prakrit_texts/blob/master/tei/Dhanap%C4%81la/P%C4%81iLaN%C4%81.xml) and [plain-text version](https://github.com/aso2101/prakrit_texts/blob/master/txt/Dhanap%C4%81la/P%C4%81iLaN%C4%81.txt) of this lexicon are provided on my [Prakrit Digital Texts Project](https://github.com/aso2101/prakrit_texts/tree/master) repository. They use this edition:
> Georg Bühler (ed.). *The Pâiyalachchhî Nâmamâlâ. A Prakrit Kosha by Dhanapâla.* Göttingen: Peppmüller, 1879.

I have tried to put this lexicon into tabular form in [this Google sheet](https://docs.google.com/spreadsheets/d/1V8FNAPufnezwvCK15q-MI1g8GeW14JHp-zioS730AuU/edit?usp=sharing), but lots of fields remain unfilled. **This is one area where help would be appreciated!**

### Hēmacandra’s *Dēśīnāmamālā* (*Garland of Regional Nouns*)

Composed around 1150 around Patan, Gujarat, by Kalikālasarvajña Hēmacandra. This lists so-called *dēśī* words alphabetically and offers Prakrit equivalents (as well as Sanskrit equivalents in his own commentary).

A [TEI version](https://github.com/aso2101/prakrit_texts/blob/master/tei/H%C4%93macandra/D%C4%93N%C4%81M%C4%81.xml)  of this lexicon are provided on my [Prakrit Digital Texts Project](https://github.com/aso2101/prakrit_texts/tree/master) repository. . I have not satisfactorily serialized this to a plain-text format. I used this edition:
> Richard Pischel (ed.). *The Deśînâmamâlâ of Hemachandra: Part I: Text and Critical Notes.* Bombay: Government Central Book Depôt, 1880.

I have tried to put this lexicon into tabular form in [this Google sheet](https://docs.google.com/spreadsheets/d/1pveHVb4Vrzqvx4UrMMEfoPwp-cUdVqg5TT0ia4-icpg/edit?usp=sharing), but lots of fields remain unfilled. **This is one area where help would be appreciated!**

### Trivikrama’s *Prākr̥tānuśāsana* (*Teaching on Prakrit*)

Trivikrama was a Digambara Jain monk who composed his grammar of Prakrit in the 13th century, strongly influenced by Hēmacandra. His grammar contains a useful list of *dēśya* words:
> P. L. Vaidya (ed.). *Prakrit Grammar of Trivikrama with his Own Commentary.* Sholapur: Jaina Saṁskṛti Saṁrakcaka Saṁgha, 1954. Jīvarāja Jaina Granthamālā No. 4.

[This Google sheet](https://docs.google.com/spreadsheets/d/1pTr2E2_QP_iEltDXUTMFRWbcDUccGWZTd4MRO3_Dx_w/edit?usp=sharing) represents these 800-odd words in tabular format. This too could stand to be double-checked.

## Modern lexicons and glossaries

### *Dēśī Śabdakōśa* (1988)

> Ācārya Tulasī (Vācanā-pramukha) and Yuvācārya Mahāprajña (Pradhāna-sampādaka). *Dēśī Śabdakōśa.* Lāḍanūṁ: Jaina Viśva Bhāratī Prēsa, 1988.

### Professor Oberlies’ Glossary of the *Āvaśyaka* stories (1993)

> Thomas Oberlies. *Āvaśyaka-Studien. Glossar ausgewählter Wörter zu E. LEUMANNs Die Āvaśyaka-Erzählungen.* Stuttgart: Franz Steiner, 1993.

### Professor Bollée’s Glossaries

#### On the *Piṇḍa-* and *Oha-nijjutti* (1994)

> Willem Bollée. *Materials for an Edition and Study  of the Piṇḍa- and Oha-Nijjuttis of the Śvetâmbara Jain Tradition. Volume II: Text and Glossary.* Stuttgart: Franz Steiner, 1994.

#### On the *Āyāranga, Dasaveyāliya, Uttarajjāyā* and *Sūyagaḍa Nijjutti* (1995)

> Willem Bollée. *The Nijjuttis on the Seniors of the Śvetâmbara Siddhânta: Āyāranga, Dasaveyāliya, Uttarajjhāyā and Sūyagaḍa. Text and Selective Glossary.* Stuttgart: Franz Steiner, 1995.

#### On the *Br̥hatkalpabhāṣya* (1998)

> Willem Bollée. *Bhadrabāhu, Br̥hat-kalpa-niryukti and Sanghadāsa, Br̥hat-kalpa-bhāṣya: Romanized and Metrically Revised Version, Notes from Related Texts, and Selective Glossary. Part Three: Glossary of Selected Words.* Stuttgart: Franz Steiner, 1998.

This is an important glossary accompanying Professor Bollée’s romanized edition of the *Br̥hatkalpabhāṣya*. With thanks to Professor Oberlies, who provided me with Professor Bollée’s files, I have started to convert the source file into a CSV document. The entire text of the glossary is [here](Bollée-Br̥hatkalpabhāṣya-Glossary/EditedGlossary-Brhatkalpabhasya.txt). You can see that I have not quite finished converting it (basically running a series of regular expression transformations on the source file). The fields I have decided to use are:
1. **Lemma**: The word that is displayed, in *stem form*. If the form is a verbal stem, it is usually given in ALL CAPS.
2. **Cross-references**: Where Bollée indicates that the reader should see another entry.
3. **Notes about dictionaries**: Bollée sometimes indicates that the word in question is not found in the relevant dictionaries.
4. **Explanation of form**: In a few cases, generally those of prefixes or suffixes, Bollée provides some information that is not exactly an etymology, which I include here as “explanation of form.”
5. **Etymology**: The etymology is usually given as a Sanskrit word (in italics), or alternatively `ts.` (for *tatsama*) or `[d.]` (for *dēśī*). Often Bollée will give detailed references here.
6. **Forms**: If there are multiple forms linked to the same lemma (which is usually the case only for verbs), these forms are given in this field.
7. **Additional grammatical notes**: I have put indications such as ‘ppp.’ in this field, not knowing where else to put it.
8. **Citations in the Br̥hatkalpabhāṣya**: The verses from the *Br̥hatkalpabhāṣya* with the form in question are listed here by their verse number in Bollée’s edition, often with context and notes from the commentary.
9. **Compound information**: Bollée lists words with which the current word is compounded (ifc. = *in fine compositi*, at the end of a compound)
10. **Other citations**: Citations of the word in other texts, e.g., from the commentary to the *Br̥hatkalpabhāṣya* itself (cty), or other *niryukti* texts.

I have completed the conversion up to the end of *a*, and the results are in [this CSV document](Bollée-Br̥hatkalpabhāṣya-Glossary/Brhatkalpabhasya_Glossary_a.csv), and from this I have prepared a [Google Sheet](https://docs.google.com/spreadsheets/d/1XrbyvvgHQaPMixcOIUq2mP1N_bdaJgt2ATzVgLf7qaQ/edit?usp=sharing), which we will eventually use as the final data source. Note that even this Google Sheet needs some cleaning up (e.g., stray slashes resulting from LaTeX code). The next steps are:
* Continuing to go through the [glossary](Bollée-Br̥hatkalpabhāṣya-Glossary/EditedGlossary-Brhatkalpabhasya.txt) to create CSV columns from the linear text data (I have used emacs with various regex substitutions, since the text data is not 100% consistent).
* Manually checking each letter and adding its columns to [the CSV document](Bollée-Br̥hatkalpabhāṣya-Glossary/Brhatkalpabhasya_Glossary_a.csv).
* Importing the new columns into the [Google Sheet](https://docs.google.com/spreadsheets/d/1XrbyvvgHQaPMixcOIUq2mP1N_bdaJgt2ATzVgLf7qaQ/edit?usp=sharing).
* Checking the imported data for consistency and adding page numbers.


## Rights/restrictions

The texts are made available under a [CC 4.0 BY-SA license](https://creativecommons.org/licenses/by-sa/4.0/) license unless stated otherwise. Please do let me know if you do anything interesting with these texts.
