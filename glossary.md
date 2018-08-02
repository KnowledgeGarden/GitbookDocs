# Glossary

### Anticipatory System

It is said that all living organisms are _anticipatory_. That is, living creatures construct _models_ of their world and use those models in the context of _sensed information_ to anticipate, and to _act_. An example is the single-celled creature which senses a nutrient in its environment; its model causes it to swim in the direction of increasing signal until it finds what it went to find.

Wikipedia says this about [_Anticipation_](https://en.wikipedia.org/wiki/Anticipation_%28artificial_intelligence%29):

> In [artificial intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) \(AI\), **anticipation** occurs when an [agent](https://en.wikipedia.org/wiki/Intelligent_agent) makes decisions based on its explicit beliefs about the future. More broadly, "anticipation" can also refer to the ability to act in appropriate ways that take future events into account, without necessarily explicitly possessing a model of the future events.

### NLP

Acronym for _natural language processing_. [Wikipedia](https://en.wikipedia.org/wiki/Natural_language_processing) says this:

> **Natural language processing** \(**NLP**\) is an area of [computer science](https://en.wikipedia.org/wiki/Computer_science) and [artificial intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) concerned with the interactions between computers and human \(natural\) languages, in particular how to program computers to process and analyze large amounts of [natural language](https://en.wikipedia.org/wiki/Natural_language) data.

### Topic Map

In the simples of definitions, a _topic map_ is a container of _representations_ of topics. Wikipedia says this about [topic maps](https://en.wikipedia.org/wiki/Topic_map):

> A **topic map** is a standard for the representation and interchange of knowledge, with an emphasis on the [findability](https://en.wikipedia.org/wiki/Findability) of information. Topic maps were originally developed in the late 1990s as a way to represent [back-of-the-book index](https://en.wikipedia.org/wiki/Back-of-the-book_index) structures so that multiple indexes from different sources could be merged. However, the developers quickly realized that with a little additional generalization, they could create a [meta-model](https://en.wikipedia.org/wiki/Metamodelling) with potentially far wider application. The [ISO](https://en.wikipedia.org/wiki/International_Organization_for_Standardization) standard is formally known as **ISO/IEC 13250:2003**.

OpenSherlock specifically uses the TopicMaps Reference Model, \(TMRM\) ISO 13250-5, which allows the platform to use a more complex representation system than topic maps built to the XML topic maps TopicMaps Data Model \(TMDM\).

### WordGram

A WordGram is a kind of n-gram which, in OpenSherlock, is a container of a sequence of words as read from sentences. The sequence begins with a single word, and then all sequences of up to 8 words in a row.  WordGrams are constructed with a _sliding window_ which walks along the sentence, left to right, accumulating all possible collections of from 1 to 8 words.

Wikipedia says this about [n-grams](https://en.wikipedia.org/wiki/N-gram):

> In the fields of [computational linguistics](https://en.wikipedia.org/wiki/Computational_linguistics) and [probability](https://en.wikipedia.org/wiki/Probability), an **n-gram** is a contiguous sequence of n items from a given [sample](https://en.wikipedia.org/wiki/Sample_%28statistics%29) of text or speech. The items can be [phonemes](https://en.wikipedia.org/wiki/Phoneme), [syllables](https://en.wikipedia.org/wiki/Syllable), [letters](https://en.wikipedia.org/wiki/Letter_%28alphabet%29), [words](https://en.wikipedia.org/wiki/Word) or [base pairs](https://en.wikipedia.org/wiki/Base_pairs) according to the application. The n-grams typically are collected from a [text](https://en.wikipedia.org/wiki/Text_corpus) or [speech corpus](https://en.wikipedia.org/wiki/Speech_corpus). When the items are words, n-grams may also be called shingles.



