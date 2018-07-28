# Introduction

OpenSherlock is software framework for performing a variety of tasks, including

* Detecting _same subject_ identification for maintaining a _topic map_
* Performing natural language processing \(NLP\) on text to grow and maintain topic maps and higher-order information structures
* Performing question answering tasks

The system emerged during thesis research \(Park, 2010\). In that thesis proposal, the concept of an _Anticipatory Story Reader_  \(ASR\) was introduced. A simulator of that idea was written as a tiny Eclipse Java project, and fed some 600+ answers to questions about climate change. The idea was to detect _same subject_ among those answers.  An illustration of that process is visible when considering two answers to the same question:

```text
Question: What are the causes of climate change?
Answer 1: CO2 causes climate change
Answer 2: Climate change is caused by carbon dioxide
```

In the simplest possible sketch of how ASR works, it conducts a process of _normalizing_ the two sentences, which entails, in that example, two tasks:

* Detect the synonym and chose one as a _canonical_ term
* Detect the difference in predicate _voice_ and normalize to _active voice_

When those tasks are completed, both answers take the same form:

```text
CO2 cause climate change
```

That process is part of the NLP component of OpenSherlock, its ASR. Note that the example also illustrates the _same subject_ detection process in one of its many forms. That is, if we are reading text from online resources and harvesting that into a topic map, the claim that _CO2 causes climate change_ will be mapped into the topic map as three topics:

* The subject which we know has two labels: _CO2_ and _carbon dioxide_
* The subject which has the label _climate change_
* The subject which is the _Causal Relation_ which connects those two subjects

 __

