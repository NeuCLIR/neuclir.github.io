---
sidebar: 2024_sidebar.html
---

# 2024 TREC NeuCLIR Track

<div class='register-banner'>
    <div class='register-banner-items'>
    <b>Join us</b> by registering for TREC at <a href='https://trec.nist.gov/pubs/call2024.html'>this webpage</a>.
    </div>
</div>


*Last Updated: 3 May 2024*

The Neural Cross-Language Information Retrieval (NeuCLIR) track is a [TREC](https://trec.nist.gov/) shared task that
studies the impact of neural approaches in cross-language information retrieval and generation.

You can participate in the shared task by submitting a retrieval or generation system for evaluation. Once completed,
the track provides reusable test collections for future investigations.

## 🎉 NeuCLIR is back for a third year!

This year, we continue the Cross-Language (CLIR) and Multi-lingual (MLIR) news and technical document retrieval tasks.
We also introduce a new Report Generation task.

<!-- Examples of the report generation request and evaluation data can be found
in the [Report Generation](#report-generation-pilot-task) section.  -->

Details on each of the 2024 tasks are provided below:

 - [Cross-Langauge Retrieval](#-task-cross-language-retrieval-clir)
 - [Cross-Langauge Technical Documents](#-task-cross-language-technical-documents)
 - [Multilingual Retrieval](#-task-multilingual-retrieval-mlir)
 - [🆕 Cross-Language Report Generation](#-task-cross-language-report-generation)

<!-- See full guidelines below:
 - [CLIR and MLIR Tasks](https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing)
 - [Report Generation Task](https://docs.google.com/document/d/1Q4SSwM69kfK2GtYf0N__4eQcsEK0giMky2XG-dPoCYM/edit?usp=sharing) -->

Skip to [Important Dates](#important-dates).

<div class="hr-text">Official Tasks</div>


## 🔍 Task: Cross-Language Retrieval (CLIR)

<p style="margin-top: -0.75em"><em>See the <a href="https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing">CLIR & MLIR Guidelines</a> for full task details.</em></p>

In the **Cross-Language Retrieval (CLIR) task**, systems receive queries in one language (English) and retrieve from
a corpus of news articles written in another language (Chinese, Persian, **or** Russian).

<!-- TODO: image -->

<!-- TODO: data -->

<div class="alert alert-success" role="alert">
  <div class="text-secondary small">Access collection, past queries, and qrels on <a href="https://ir-datasets.com/neuclir.html#neuclir/1"><code>ir_datasets</code></a> or <a href="https://trec.nist.gov/data/neuclir.html">TREC website</a>. </div>
  <div class="text-secondary small">Learn more from the overview papers of <a href='https://arxiv.org/abs/2304.12367' title='link to '><i aria-hidden="true" class="fas fa-archive">NeuCLIR 2022</i></a> and <a href='https://arxiv.org/abs/2404.08071' title='link to '><i aria-hidden="true" class="fas fa-archive">NeuCLIR 2023</i></a>. </div>
</div>

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

-------


## 🔍 Task: Cross-Language Technical Documents

<p style="margin-top: -0.75em"><em>See the <a href="https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing">CLIR & MLIR Guidelines</a> for full task details.</em></p>

Technical language poses a particular problem for cross-language retrieval systems, so the **Cross-Language Technical Document** task focuses
on testing this phenomenon in particular. Systems receive queries in one language (English) and retrieve from a corpus of technical abstracts
written in another language (Chinese).

<!-- TODO: image -->

<div class="alert alert-success" role="alert">
  <div class="text-secondary small">Access collection, past queries, and qrels on <a href="https://ir-datasets.com/csl.html"><code>ir_datasets</code></a> or <a href="https://trec.nist.gov/data/neuclir2023.html">TREC website</a>. </div>
  <div class="text-secondary small">Learn more from the overview paper of <a href='https://arxiv.org/abs/2404.08071' title='link to '><i aria-hidden="true" class="fas fa-archive">NeuCLIR 2023</i></a>. </div>
</div>

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

-------


## 🔍 Task: Multilingual Retrieval (MLIR)

<p style="margin-top: -0.75em"><em>See the <a href="https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing">CLIR & MLIR Guidelines</a> for full task details.</em></p>

**The Multilingual Retrieval (MLIR)** task provides systems with queries in one language (English) and a corpus of documents written in **multiple**
languages (Chinese, Persian, **and** Russian). The task is to retrieve and produce a ranked list from all three languages. The queries are written
in a way that there *should* be relevant documents in more than one language.

<!-- TODO: image -->

<div class="alert alert-success" role="alert">
  <div class="text-secondary small">Access collection, past queries, and qrels on <a href="https://ir-datasets.com/neuclir.html#neuclir/1/multi"><code>ir_datasets</code></a> or <a href="https://trec.nist.gov/data/neuclir2023.html">TREC website</a>. </div>
  <div class="text-secondary small">Learn more from overview paper of <a href='https://arxiv.org/abs/2404.08071' title='link to '><i aria-hidden="true" class="fas fa-archive">NeuCLIR 2023</i></a>. </div>
</div>

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

<div class="hr-text">Pilot Task</div>


## 🔍 Task: Cross-Language Report Generation

<p style="margin-top: -0.75em"><em>See the <a href="https://docs.google.com/document/d/1Q4SSwM69kfK2GtYf0N__4eQcsEK0giMky2XG-dPoCYM/edit?usp=sharing">Report Generation Guidelines</a> for full task details.</em></p>

**The Cross Language Report Generation** task asks the system to generate an English report with citations to documents in **one of the news collection used in the CLIR task** (see guideline for destils on length and citation requirements) 
based on a report request ([example report request](https://neuclir.github.io/assets/data/report-generation-sample.request.zh.jsonl)). 
The reports will be evaluated based on the information included in the text and the appropriateness of the citations ([example evalaution data](https://neuclir.github.io/assets/data/report-generation-sample.evaluation.zh.jsonl)). 

<!-- TODO: image -->

<div class="alert alert-success" role="alert">
  <div class="text-secondary small">Access document collection from <a href="https://ir-datasets.com/neuclir.html#neuclir/1/"><code>ir_datasets</code></a> or <a href="https://trec.nist.gov/data/neuclir2022.html">TREC website</a>. </div>
  <div class="text-secondary small">Read our <a href='https://arxiv.org/abs/2405.00982' title='link to '><i aria-hidden="true" class="fas fa-archive">SIGIR perspective paper</i></a> for our vision on report generation.</div>
</div>


<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

<div class="hr-text">Track Information</div>

## Important Dates

<ul class="steps steps-vertical mb-4">
  <li class="step-item">
    <div class="h3 m-0">March 2022</div>
    <div class="h3 m-0">Document Collections Released</div>
    <div class="text-secondary small">CLIR: <br><a style="margin-left: 16px;" href="https://ir-datasets.com/neuclir#neuclir/1/fa"><code>neuclir/1/fa</code></a> (Persian)<br><a style="margin-left: 16px;" href="https://ir-datasets.com/neuclir#neuclir/1/ru"><code>neuclir/1/ru</code></a> (Russian)<br><a style="margin-left: 16px;" href="https://ir-datasets.com/neuclir#neuclir/1/zh"><code>neuclir/1/zh</code></a> (Chinese)</div>
    <div class="text-secondary small">MLIR: <br><a style="margin-left: 16px;" href="https://ir-datasets.com/neuclir#neuclir/1/multi"><code>neuclir/1/multi</code></a> (Persian, Russian, and Chinese)</div>
    <div class="text-secondary small">Technical: <br><a style="margin-left: 16px;" href="https://ir-datasets.com/csl.html"><code>csl</code></a> (Chinese Technical Abstracts)</div>
  </li>
  <li class="step-item active">
    <div class="h3 m-0">25 March 2024</div>
    <div class="h3 m-0">Track Guidelines Released</div>
    <div class="text-secondary small"><a href="https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing">CLIR &amp; MLIR Guidelines</a></div>
    <div class="text-secondary small"><a href="https://docs.google.com/document/d/1Q4SSwM69kfK2GtYf0N__4eQcsEK0giMky2XG-dPoCYM/edit?usp=sharing">Report Generation Guidelines</a></div>
  </li>
  <li class="step-item">
    <div class="h3 m-0">June 2024</div>
    <div class="h3 m-0">CLIR/MLIR Topics and Report Requests to be released</div>
  </li>
  <li class="step-item">
    <div class="h3 m-0">July 2024</div>
    <div class="h3 m-0">CLIR Technical Topics to be released</div>
  </li>
  <li class="step-item">
    <div class="h3 m-0">6 August 2024</div>
    <div class="h3 m-0">Submissions due to NIST</div>
  </li>
  <li class="step-item">
    <div class="h3 m-0">October 2024</div>
    <div class="h3 m-0">Results distributed to participants</div>
  </li>
  <li class="step-item">
    <div class="h3 m-0">November 2024</div>
    <div class="h3 m-0">TREC 2024</div>
  </li>
</ul>

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

-------

## Changes from 2023

- The technical documents pilot has been promoted to a full task.
- Later submission deadline!
- A pilot of a query-driven report generation task (Generative IR) from the multilingual document set.

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

-------

## Organizers

In alphabetical order:

- [Dawn Lawrie](https://hltcoe.jhu.edu/researcher/dawn-lawrie/), Johns Hopkins University, HLTCOE
- [Sean MacAvaney](https://macavaney.us/), University of Glasgow
- [James Mayfield](https://hltcoe.jhu.edu/researcher/james-mayfield/), Johns Hopkins University, HLTCOE
- [Paul McNamee](https://pmcnamee.net/), Johns Hopkins University, HLTCOE
- [Douglas W. Oard](https://ischool.umd.edu/about/directory/douglas-w-oard), University of Maryland
- [Luca Soldaini](https://soldaini.net), Allen Institute for AI
- [Eugene Yang](https://www.eugene.zone/), Johns Hopkins University, HLTCOE

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>

-------

## Contact

- [Mailing List](https://groups.google.com/g/neuclir-participants) (for the latest announcement and news)
- [TREC Slack #neuclir-2024 channel](https://trectalk.slack.com/archives/C04RQC3QJKW) (once [registered for TREC](https://trec.nist.gov/pubs/call2024.html))
- [Twitter @neuclir](https://twitter.com/neuclir)
- Any questions: [neuclir-organizers@googlegroups.com](mailto:neuclir-organizers@googlegroups.com)

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>


-------

## Previous Years

NeuCLIR previously ran in 2022 and 2023. You can find the previous versions of the task below:

- *[2023: Past Track](/2023)*
- *[2022: Past Track](/2022)*

<span class='navigate_toc'><i class="fas fa-arrow-up right-margin"></i><a href='#' class='navigate_toc'>Back to top</a></span>
