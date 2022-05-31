# NumAttach: A Numeral Attachment Dataset for Financial Social Media Data
This dataset is the pilot set of the [NTCIR-2020 FinNum-2 Shared Task](https://sites.google.com/nlg.csie.ntu.edu.tw/finnum2020)
# Introduction
Numeral is the crucial part of financial documents. In order to understand the detail of opinions in financial documents, we should not only analyze the text, but also need to assay the numeric information in depth. Because of the informal writing style, analyzing social media data is more challenging than analyzing news and official documents. NumAttach is a dataset for fine-grained numeral understanding in financial social media data - to detect the relation between cashtag and the numeral.

# Format
The NumAttach dataset is consisted of "tweet", "target_num", "target_cashtag", "relation", and "reason_type" in json format.

# Example
```yaml
{

"tweet": "$SQ is $39 per share with a P/E of over 150 and losing money...should be at least as good as them with a P/E of 30 and making money!!",

"target_num": "39",

"reason_type": "None",

"target_cashtag": "SQ",

"relation": 1

}
```
# Download
Please write us an email with the agreement. Click here to download the agreement of NumAttach.

Email Address: cjchen@nlg.csie.ntu.edu.tw

# How to Cite the Corpus
Please cite the following paper when referring to the NumAttach in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, and Hsin-Hsi Chen. 2019. [Numeral Attachment with Auxiliary Tasks](https://dl.acm.org/citation.cfm?id=3331361). In Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019), Paris, France.
# License
NumAttach is licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
