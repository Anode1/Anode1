**Small tools in plain C and plain text, and the papers that measure them.**

Papers, with sources, data and DOIs: [articles](https://github.com/Anode1/articles). Short notes: [notes](https://github.com/Anode1/notes).

| area | project | what it is |
| --- | --- | --- |
| agents | [iac](https://github.com/Anode1/iac) | message board for LLM agents on one machine: one C binary, a plain-text log, a `recv` that wakes on inotify instead of polling, 2026 |
| | [agent-recipes](https://github.com/Anode1/agent-recipes) | short prompts that unlock capabilities coding agents already have, 2026 |
| | [context-renormalization](https://github.com/Anode1/context-renormalization) | a bounded-memory protocol for multi-session agent work, retired: superseded by ais, a private index per agent carries the same bias without the protocol |
| ML | [SMBPANN](https://github.com/Anode1/SMBPANN) | self-modifying backpropagation network: topology and hyper-parameters searched, weights trained, against a matched random-search control |
| | [bpnn](https://github.com/Anode1/bpnn) | a backpropagation feed-forward network in C99 (1997, 2000, 2015, 2026) |
| | [linearr](https://github.com/Anode1/linearr) | least squares in C from a CSV whose header names the terms (2007, 2026) |
| search | [ais](https://github.com/Anode1/ais) | associative memory as an index: save anything under your own keys, recall by keys; plain text on your own disk, 2001 - 2026 |
| | [cjitter](https://github.com/Anode1/cjitter) | four stochastic layout searches in C, and the uniform-random control that says which ones earned their structure |
| | [graphcrawl](https://github.com/Anode1/graphcrawl) | crawl a graph of any size, depth N at a time (1999, 2026) |
| systems | [ljms](https://github.com/Anode1/ljms) | a durable work queue that is one database table (2001, 2026)|
| | [mincdp](https://github.com/Anode1/mincdp) | minimal, dependency-free Chrome DevTools Protocol client in C, 2026 |
| | [aisconfig](https://github.com/Anode1/aisconfig) | a template for ANSI C projects: POSIX args, Makefile (2007, 2017, 2026) |
| | [nid](https://github.com/Anode1/nid) | a UID from a unique string (2015) |
| | [jsp_search_results](https://github.com/Anode1/jsp_search_results) | keyset pagination in JSP and Java (2015) |
| genomics | [aisconvert](https://github.com/Anode1/aisconvert) | personal genomics toolkit (2015) |
| | [aisgedcom](https://github.com/Anode1/aisgedcom) | molecular genealogy over GEDCOM files (2015) |
| | [ped2raw](https://github.com/Anode1/ped2raw) | PED to RAW SNP converter (2015) |


## Papers

Sources, figures and data for each are in [articles](https://github.com/Anode1/articles). (*) marks the papers headed to arXiv and then to a journal; the rest are on Zenodo only.

| paper | where |
| --- | --- |
| (*) When Abstraction Becomes Indirection: Tokens-to-trace, measured on six stacks ([MISRA_C_vs_CPP](https://github.com/Anode1/articles/tree/main/MISRA_C_vs_CPP)) | [10.5281/zenodo.22113993](https://doi.org/10.5281/zenodo.22113993); a shorter version under review at IEEE Software |
| (*) What Holds a Hand-Drawn Diagram? Alignment holds their boxes where the tuned criteria do not ([cjitter](https://github.com/Anode1/articles/tree/main/cjitter)) | [10.5281/zenodo.22313827](https://doi.org/10.5281/zenodo.22313827); targeting GD 2027 |
| (*) The Imposed and Emergent Pieces of Convolution Under an Energy Budget ([smbpann](https://github.com/Anode1/articles/tree/main/smbpann)) | [10.5281/zenodo.21423177](https://doi.org/10.5281/zenodo.21423177); under review at Genetic Programming and Evolvable Machines |
| (*) A Wakeup, Not a Broker: The Minimal Transport for Coordinating Stateless LLM Agents ([iac](https://github.com/Anode1/articles/tree/main/iac)) | [10.5281/zenodo.21206970](https://doi.org/10.5281/zenodo.21206970); arXiv cs.MA pending endorsement |
| (*) Compress the Access, Not the Store ([ais](https://github.com/Anode1/articles/tree/main/ais)) | [10.5281/zenodo.20764255](https://doi.org/10.5281/zenodo.20764255) |
| (*) Artifact Promotion as a Control Model for Stable Cloud Deployment ([ControlModel](https://github.com/Anode1/articles/tree/main/ControlModel)) | [10.5281/zenodo.20451077](https://doi.org/10.5281/zenodo.20451077) (the control-model note), [10.5281/zenodo.20528903](https://doi.org/10.5281/zenodo.20528903) (the implementation case study, with Enkli Ylli; the arXiv submission) |
| The Atree Format: A Scalable Binary-Path Notation for Ancestral Genealogies ([atree](https://github.com/Anode1/articles/tree/main/atree)) | [10.5281/zenodo.20587715](https://doi.org/10.5281/zenodo.20587715) |
| Conditional Probability in Diagnostic Testing: An Isomorphism Between Tree Diagrams, Bayes' Theorem, Contingency Tables and ARR/RRR ([ConditionalProbability](https://github.com/Anode1/articles/tree/main/ConditionalProbability)) | [10.5281/zenodo.20449608](https://doi.org/10.5281/zenodo.20449608) |

## Other articles

Essays, a 1997 seminar report kept for lineage, and one policy piece.

| article | where |
| --- | --- |
| Chaos Makes Many, Compression Keeps Few: Where Innovation Comes From ([innovation_compression](https://github.com/Anode1/articles/tree/main/innovation_compression)) | [10.5281/zenodo.20603482](https://doi.org/10.5281/zenodo.20603482) |
| Intelligence Is the Discovery of Compressors ([intelligence_compressors](https://github.com/Anode1/articles/tree/main/intelligence_compressors)) | [10.5281/zenodo.20440110](https://doi.org/10.5281/zenodo.20440110) |
| Backpropagation Feed-Forward Neural Networks, a 1997 seminar report revised in 2026 ([BPFNN_Coursework](https://github.com/Anode1/articles/tree/main/BPFNN_Coursework)) | [10.5281/zenodo.20450525](https://doi.org/10.5281/zenodo.20450525) |
| Pricing grid power for data centres ([energy](https://github.com/Anode1/articles/tree/main/energy)) | Substack |

Linux since 1994. Plain files over services, one binary over a stack, a measured number over an adjective.
