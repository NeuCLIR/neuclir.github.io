# 2022 TREC NeuCLIR Track

<div id='mailing-list-banner'>
    <div id='inner-banner'>
    <h3 id='mailing-list-title'>Announcements</h3>
    <ul id='mailing-list-items'>
    <!-- <li>We are hosting two information sessions for potential partecipants! Join us on <b>Dec 14th at 9am EST</b> (<a href='https://dateful.com/eventlink/1346891686'>convert to your time zone</a>) or <b>9pm EST</b> (<a href='https://dateful.com/eventlink/2344208524'>convert to your time zone</a>). Please email the organizers at <a href='mailto:neuclir-organizers@googlegroups.com'>neuclir-organizers@googlegroups.com</a> to receive a Zoom meeting ID.</li>
    <div style='margin-bottom: .5em'></div> -->
    <li>Check the <a href='#resources'>resources</a> section to access the data collection and retrieval baselines.</li>
    <li>Join our <a href='https://groups.google.com/g/neuclir-participants'>mailing list</a> to receive the latest announcements about the NeuCLIR track!</li>
    </ul>
    </div>
</div>

Cross-language Information Retrieval (CLIR) has been studied, but recent advances in deep learning methods for information retrieval warrant a new, large-scale effort to explore the effectiveness classical and modern IR techniques.

This Website contains information about the upcoming NeuCLIR track at TREC 2022. We encourage submissions of systems that will help answering the following research questions:

- What are the best neural CLIR approaches?
- How does neural CLIR compare to the combination of machine translation and monolingual IR?
- How does it compare to the strongest statistical approaches to CLIR?
- How do the resource requirements for the various approaches compare?
- Can separate ranking and re-ranking phases improve performance over a single-phase approach?
- What resources are most useful for training CLIR systems?

In its first year, NeuCLIR will focus on three languages: **Chinese**, **Persian**, and **Russian**.

-------

## Getting Started

### Task Description

The main task for the proposed track is ad-hoc cross-language retrieval. Documents will be drawn from Common Crawl newswire, and will be written in Chinese, Russian, and Persian. Topics will be in English, and will be expressed in traditional TREC title/description/narrative form. Retrieved documents will be graded as highly relevant, somewhat relevant, and not relevant; we expect to use several metrics to evaluate runs, including nDCG@100 and ERR.

### Example Notebooks

*We are planning to release example runs as Jupyter notebooks! Subscribe to the [participants' mailing list](https://groups.google.com/g/neuclir-participants) to be notified when they are released.*

### Carbon Neutral Submissions

We aim for NeuCLIR to be the first carbon-neutral track at TREC; therefore, we strongly encourage all participants to track carbon emissions associated with their submission, and, if they are able to, buy carbon offsets to minimize the impact of their submissions. For details, please visit [this page](/carbon-tracking.html).

<!-- The development and test data created for [SCALE 2021](https://hltcoe.jhu.edu/research/scale/scale-2021/) (60 topics in Chinese and Persian, 40 topics in Russian) will soon be available to the track as development data with relevance judgments. Further, participants are welcome to use any related cross-language and non-English monolingual datasets have been made available (e.g., [CLIRMatrix](https://aclanthology.org/2020.emnlp-main.340/), [MLWIKIR](https://github.com/getalp/wikIR), and others). In addition, the SCALE 2021 effort produced translations of [MS MARCO](https://microsoft.github.io/msmarco/) into Chinese, Russian, and Persian. These translations should be freely redistributable. -->

## Resources

- **Overview** of the task: <a href='https://docs.google.com/presentation/d/1hMK1rsOamPaHtfnXuLljXb0FOW4HV4xxr-sOmoyD5UI/' title='link to Google slides'>Google Slides <i aria-hidden="true" class="fas fa-link"></i></a>;  <a href='/assets/pdf/neuclir-trec.pdf' title='link to PDF version of the slides'>PDF version <i aria-hidden="true" class="fas fa-file-pdf"></i></a>.
- **HC4**, a collection to train models for NeuCLIR submissions: <a href='https://github.com/hltcoe/HC4' title='link to github repository'>Code <i aria-hidden="true" class="fab fa-github"></i></a>;  <a href='https://arxiv.org/abs/2201.09992' title='link to arXiv paper detailing the HC4'>Paper (ECIR '22) <i aria-hidden="true" class="fas fa-file-alt"></i></a>
- **Patapsco**, a pipeline to run CLIR expirements: <br/> <a href='https://github.com/hltcoe/patapsco' title='link to github repository'>Code <i aria-hidden="true" class="fab fa-github"></i></a>;  <a href='https://arxiv.org/abs/2201.09996' title='link to arXiv paper detailing the HC4'>Paper (ECIR '22) <i aria-hidden="true" class="fas fa-file-alt"></i></a>

-------

## Timeline

While the exact timeline is **not finalized** yet, here's an **approximate** schedule:

- <div id="past"><i>November 2021</i>: NeuCLIR track is first discussed at TREC 2021; feedback from potential participants is welcome.</div>
- <div id="past"><i>December 2021</i>: Release preliminary track guidelines. Complete download, cleaning and formatting of new document collection.</div>
- *January 2022*: Release of document collection, development data, and a portion of test data. All tools are made available on [NeuCLIR's GitHub](https://github.com/NeuCLIR).
- *February 2022*: Release new document collection.
- *May 2022*: Topic development complete.
- *June 2022*: Release test topics and baseline runs for re-ranking.
- *July 2022*: Submissions due to NIST
- *October 2022*: Distribute results to participants.
- *November 2022*: TREC 2022.

## Organizers

- [Dawn Lawrie](https://hltcoe.jhu.edu/researcher/dawn-lawrie/), Johns Hopkins University, HLTCOE
- [Sean MacAvaney](https://macavaney.us/), University of Glasgow
- [James Mayfield](https://hltcoe.jhu.edu/researcher/james-mayfield/), Johns Hopkins University, HLTCOE
- [Paul McNamee](https://pmcnamee.net/), Johns Hopkins University, HLTCOE
- [Douglas W. Oard](https://ischool.umd.edu/about/directory/douglas-w-oard), University of Maryland
- [Luca Soldaini](https://soldaini.net), Allen Institute for AI
- [Eugene Yang](https://www.eugene.zone/), Johns Hopkins University, HLTCOE

## Contact

- We encourage all interested researchers to join our [mailing list](https://groups.google.com/g/neuclir-participants) for the latest announcement and news.
- For any questions, please reach out to the organizers at [neuclir-organizers@googlegroups.com](mailto:neuclir-organizers@googlegroups.com).
- Follow the hashtag <a href='https://twitter.com/search?q=%23neuclir22&src=typed_query' title='link to Google slides'><i aria-hidden="true" class="fab fa-twitter">#neuclir22</i></a> to connect with other NeuCLIR participants.
