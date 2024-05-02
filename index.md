---
sidebar: 2024_sidebar.html
---

# 2024 TREC NeuCLIR Track

<div class='register-banner'>
    <div class='register-banner-items'>
    <b>Join us</b> by registering for TREC at <a href='https://trec.nist.gov/pubs/call2024.html'>this webpage</a>.
    </div>
</div>


*Last Updated: 2 May 2024*

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
 - [Cross-Langauge Technical Document Retrieval](#-task-cross-language-technical-document-retrieval)
 - [Multilingual Retrieval](#-task-multilingual-retrieval-mlir)
 - [🆕 Report Generation](#-task-report-generation)

<!-- See full guidelines below:
 - [CLIR and MLIR Tasks](https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing)
 - [Report Generation Task](https://docs.google.com/document/d/1Q4SSwM69kfK2GtYf0N__4eQcsEK0giMky2XG-dPoCYM/edit?usp=sharing) -->


-------


## 🔍 Task: Cross-Language Retrieval (CLIR)

*See the [CLIR & MLIR Guidelines](https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing) for full task details.*

In the **Cross-Language Retrieval (CLIR) task**, systems receive queries in one language (English) and retrieve from
a corpus of news articles written in another language (Chinese, Persian, **or** Russian).

<!-- TODO: image -->

<!-- TODO: data -->



-------


## 🔍 Task: Cross-Language Technical Document Retrieval

*See the [CLIR & MLIR Guidelines](https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing) for full task details.*

Technical language poses a particular problem for cross-language retrieval systems, so the **Cross-Language Technical Document** task focuses
on testing this phenomenon in particular. Systems receive queries in one language (English) and retrieve from a corpus of technical abstracts
written in another language (Chinese).

<!-- TODO: image -->

<!-- TODO: data -->



-------


## 🔍 Task: Multilingual Retrieval (MLIR)

*See the [CLIR & MLIR Guidelines](https://docs.google.com/document/d/1Vy9538kPvyE3mfIhd-stqULbcRCnS_oe5rP6ykqKA-0/edit?usp=sharing) for full task details.*

**The Multilingual Retrieval (MLIR)** task provides systems with queries in one language (English) and a corpus of documents written in **multiple**
languages (Chinese, Persian, **and** Russian). The task is to retrieve and produce a ranked list from all three languages. The queries are written
in a way that there *should* be relevant documents in more than one language.

<!-- TODO: image -->

<!-- TODO: data -->



-------


## 🔍 Task: Report Generation

*See the [Report Generation Guidelines](https://docs.google.com/document/d/1Q4SSwM69kfK2GtYf0N__4eQcsEK0giMky2XG-dPoCYM/edit?usp=sharing) for full details.*

### TL;DR
Participating systems will receive a Chinese, Persian, or Russian document collection and a request for a report to be written in English. They will produce a textual report that fulfills the request in which each sentence points to up to two documents that support it. Scoring will be based on the percentage of main points the report successfully includes, and the precision of the report sentences in describing those main points.

Examples of [report request](https://neuclir.github.io/assets/data/report-generation-sample.request.zh.jsonl) and [evaluation data](https://neuclir.github.io/assets/data/report-generation-sample.evaluation.zh.jsonl) are available as development data.

### Summary

NeuCLIR 2024 is introducing a new Retrieval Augmented Generation (RAG) task of producing a report in one language based on the retrieval of documents in another language. The goals of the task are to stimulate research in cross-language RAG, to identify the best current approaches to automatic cross-language report-writing, to produce a collection that is useful for evaluating future systems, and to examine what parts of this evaluation might be automated to allow future systems to be scored using the same evaluation data. This year report generation is a pilot task, so participants might expect some details of the task to change slightly over time.

The report generation task is to automatically generate a report based on an English description of the desired report and a document collection in Chinese, Persian, or Russian. Generated reports must be responsive to the statements of the information need. A valid report will cite source documents that contain the information discussed within the report. Citations are one of the key attributes of this task. A report length limit will encourage systems to express information succinctly. The generated report must be written in the language of the report request (English) rather than in the language of the documents. Submitted reports created by report-writing systems will be evaluated by assessors. 

| Task                                | Document Language(s) | Query Language            |
| ----------------------------------------- | -------------------- | ------------------------- |
| Report Generation | fas                  | eng                       |
| Report Generation | rus                  | eng                       |
| Report Generation | zho                  | eng                       |



-------

## Important Dates

<ul class="steps steps-vertical">
  <li class="step-item">
    <div class="h4 m-0">March 2022</div>
    <div class="text-secondary">Evaluation document collection released</div>
  </li>
  <li class="step-item active">
    <div class="h4 m-0">25 March 2024</div>
    <div class="text-secondary">Track guidelines released</div>
  </li>
  <li class="step-item">
    <div class="h4 m-0">June 2024</div>
    <div class="text-secondary">CLIR/MLIR Topics and Report Requests to be released</div>
  </li>
  <li class="step-item">
    <div class="h4 m-0">July 2024</div>
    <div class="text-secondary">CLIR Technical Topics to be released</div>
  </li>
  <li class="step-item">
    <div class="h4 m-0">6 August 2024</div>
    <div class="text-secondary">Submissions due to NIST</div>
  </li>
  <li class="step-item">
    <div class="h4 m-0">October 2024</div>
    <div class="text-secondary">Results distributed to participants</div>
  </li>
  <li class="step-item">
    <div class="h4 m-0">November 2024</div>
    <div class="text-secondary">TREC 2024</div>
  </li>
</ul>

-------

## Changes from 2023

- The technical documents pilot has been promoted to a full task.
- Later submission deadline!
- A pilot of a query-driven report generation task (Generative IR) from the multilingual document set.

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
