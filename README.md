# 2022 TREC NeuCLIR tarck

Cross-language Information Retrieval (CLIR) has been studied at TREC and subsequent evaluations forums for more than twenty years, but recent advances in the application of deep learning to information retrieval (IR) warrant a new, large scale effort that will enable exploration of classical and modern IR techniques for this task.

This website contains information about the upcoming NeuCLIR track at TREC 2022. We encourage submissions of systems that will help answering the following research questions:

- What are the best neural CLIR approaches?
- How does neural CLIR compare to the combination of machine translation and monolingual IR?
- How does it compare to the strongest statistical approaches to CLIR?
- How do the resource requirements for the various approaches compare?
- Can separate ranking and reranking phases improve performance over a single-phase approach?
- What resources are most useful for training CLIR systems?

In its first year, NeuCLIR will focus on three languages: **Chinese**, **Persian**, and **Russian**.

## Task Description

The main task for the proposed track is ad hoc cross-language retrieval. Documents will be drawn from Common Crawl newswire, and will be written in Chinese, Russian, and Persian. Topics will be in English, and will be expressed in traditional TREC title/description/narrative form. Retrieved documents will be graded as highly relevant, somewhat relevant, and not relevant; we expect to use several metrics to evaluate runs, incluiding nDCG@100 and ERR.

The development and test data created for [SCALE 2021](https://hltcoe.jhu.edu/research/scale/scale-2021/) (60 topics in Chinese and Persian, 40 topics in Russian) will soon be available to the track as development data with relevance judgments. Further, participants are welcome to use any related cross-language and non-English monolingual datasets have been made available (e.g., [CLIRMatrix](https://aclanthology.org/2020.emnlp-main.340/), [MLWIKIR](https://github.com/getalp/wikIR), and others). In addition, the SCALE 2021 effort produced translations of [MS MARCO](https://microsoft.github.io/msmarco/) into Chinese, Russian, and Persian. These translations should be freely redistributable.

## Timeline

While the exact timeline is **not finalized** yet, here's an **approximate** schedule:

- *November 2021*: NeuCLIR track is first discussed at TREC 2021; feedback from potential participants is welcome.
- *December 2021*: Release preliminary track guidelines. Complete download, cleaning and formatting of new document collection.
- *January 2022*: Release of document collection, development data, and a portion of test data. All tools are made available on [NeuCLIR's GitHub](https://github.com/NeuCLIR).
- *February 2022*: Release new document collection.
- *May 2022*: Topic development complete.
- *June 2022*: Release test topics and baseline runs for reranking.
- *July 2022*: Submissions due to NIST
- *October 2022*: Distribute results to participants.
- *November 2022*: TREC 2022.

## Organizers

- [Dawn Lawrie](https://hltcoe.jhu.edu/researcher/dawn-lawrie/), Human Language Technology Center of Excellence, Johns Hopkins University
- [Sean MacAvaney](https://macavaney.us/), University of Glasgow
- [James Mayfield](https://hltcoe.jhu.edu/researcher/james-mayfield/), Human Language Technology Center of Excellence, Johns Hopkins University
- [Paul McNamee](https://pmcnamee.net/), Human Language Technology Center of Excellence, Johns Hopkins University
- [Douglas W. Oard](https://ischool.umd.edu/about/directory/douglas-w-oard), University of Maryland
- [Luca Soldaini](https://soldaini.net), Amazon Alexa AI
- [Eugene Yang](https://www.eugene.zone/), Human Language Technology Center of Excellence, Johns Hopkins University

## Contact

For any questions, please reach out to the organizers at [neuclir-organizers@googlegroups.com](mailto:neuclir-organizers@googlegroups.com).