# NeuCLIR1 Document Collection

NeuCLIR 2022 has released its document collection.  Below we have compiled information about the document collection. This information is also accessible [here](https://docs.google.com/document/d/1BCPyOMwZRV853jhncsHPg5B0nqjZ_ISeBPwvW-yoeB8/edit?usp=sharing).

The NeuCLIR1 document collection is available for download by those registered for TREC 2022 on [the NIST website](https://trec.nist.gov/act_part/tracks2022.html). The document collection consists of documents in three languages: Chinese, Persian, and Russian, drawn from the Common Crawl news collection. They were obtained by Common Crawl between August 1, 2016 and July 31, 2021; most of the documents were published within this five year window. Text was extracted from each source webpage using the Python utility newspaper. The collection is distributed as JSONL – a list of JSON objects representing each document, one per line. Each document JSON structure consists of the following fields:

- `id` (string): document ID assigned by Common Crawl;
- `cc_file` (string): raw Common Crawl document;
- `time` (string or null): time of publication; might be null;
- `title` (string): article headline or title;
- `text` (string): article body;
- `url` (string): address of the source Webpage.

To ascertain the language of each document, its title and text were independently run through two automatic language identification tools, [cld3](https://pypi.org/project/pycld3/) and [VaLID](https://github.com/TomLippincott/VaLID). Documents where the tools agreed on the language, or where one of the tools agreed the language recorded in the webpage metadata, were included in the collection; all others were removed. All documents greater than 24,000 characters (approximately 10 pages of text) were also removed, as were Chinese documents containing 75 or fewer characters, Persian documents containing 100 or fewer characters, and Russian documents containing 200 or fewer characters.


Each collection was limited to 5 million documents. After removing duplicates, the Russian collection was significantly above this threshold. Therefore, we used Scikit-learn's implementation of random sample without replacement to downsample the collection. Final collection statistics are as follows (tokens were identified by the SpaCy tokenizers):

| Language | Docs Count | Avg Chars per Doc | Median Chars per Doc | Avg Tokens Per Doc  | Median Tokens Per Doc |
|:---------|-----------:|------------------:|---------------------:|--------------------:|----------------------:|
| Chinese  |  3,179,209 |             743.1 |                  613 |               427.7 |                   356 |
| Persian  |  2,232,016 |           2,032.1 |                1,427 |               429.3 |                   300 |
| Russian  |  4,627,543 |           1,757.9 |                1,198 |               301.1 |                   204 |


If you have any questions about the document collection, [reply to this thread](https://groups.google.com/g/neuclir-participants/c/Digh8HovAcU) on our mailing list or contact the organizers at [neuclir-organizers@googlegroups.com](mailto:neuclir-organizers@googlegroups.com).
