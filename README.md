# NLG_Evaluation_Papers


## QA based

- **Question answering as an automatic evaluation metric for news article summarization** *Matan Eyal, Tal Baumel, and Michael Elhadad* `NAACL 2019`
- **FEQA: A question answering evaluation framework for faithfulness assessment in abstractive summarization** *Esin Durmus, He He, and Mona Diab* `ACL 2020`
- **Asking and answering questions to evaluate the factual consistency of summaries** *Alex Wang, Kyunghyun Cho, and Mike Lewis* `ACL 2020`
- **Safeval: Summarization asks for fact-based evaluation** *Thomas Scialom, Paul-Alexis Dray, Gallinari Patrick, Lamprier Sylvain, Piwowarski Benjamin, Staiano Jacopo, and Wang Alex* `EMNLP 2021`
- **Q2: Evaluating Factual Consistency in Knowledge-Grounded Dialogues via Question Generation and Question Answering** *Or Honovich, Leshem Choshen, Roee Aharoni, Ella Neeman, Idan Szpektor, Omri Abend* `EMNLP 2021`
- **QuestEval: Summarization Asks for Fact-based Evaluation** *Thomas Scialom, Paul-Alexis Dray, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano, Alex Wang, Patrick Gallinari* `EMNLP 2021`




- **Benchmarking Answer Verification Methods for Question Answering-Based Summarization Evaluation Metrics** *Daniel Deutsch, Dan Roth* [[pdf]](https://arxiv.org/abs/2204.10206)

- **A Semantic QA-Based Approach for Text Summarization Evaluation** *Ping Chen, Fei Wu, Tong Wang, Wei Ding* `AAAI18` [[pdf]](https://arxiv.org/abs/1704.06259) 





## Pre-trained

- **DiscoScore: Evaluating Text Generation with BERT and Discourse Coherence** *Wei Zhao, Michael Strube, Steffen Eger* [[pdf]](https://arxiv.org/abs/2201.11176) [[code]](https://github.com/AIPHES/DiscoScore)
- **WIDAR -- Weighted Input Document Augmented ROUGE** *Raghav Jain, Vaibhav Mavi, Anubhav Jangra, Sriparna Saha* `ECIR 2022` [[pdf]](https://arxiv.org/abs/2201.09282) [[code]](https://github.com/Raghav10j/WIDAR)
- **InfoLM: A New Metric to Evaluate Summarization & Data2Text Generation** *Pierre Colombo, Chloe Clave, Pablo Piantanida* `AAAI 2022` [[pdf]](https://arxiv.org/abs/2112.01589)


### BERT based

- **BLEURT: Learning Robust Metrics for Text Generation** *Thibault Sellam, Dipanjan Das, Ankur Parikh* `ACL 2020`
- **BERTScore: Evaluating Text Generation with BERT** *Tianyi Zhang, Varsha Kishore, Felix Wu, Kilian Q. Weinberger, Yoav Artzi* `ICLR 2020`
- **MoverScore: Text Generation Evaluating with Contextualized Embeddings and Earth Mover Distance** *Wei Zhao, Maxime Peyrard, Fei Liu, Yang Gao, Christian M. Meyer, Steffen* `EMNLP 2019`

### BART based

- **BARTScore: Evaluating Generated Text as Text Generation** *Weizhe Yuan, Graham Neubig, Pengfei Liu* `NeurIPS 2021`


## NLI based

- **SummaC: Re-Visiting NLI-based Models for Inconsistency Detection in Summarization** *Philippe Laban, Tobias Schnabel, Paul N. Bennett, Marti A. Hearst* `TACL 2021`


## Parsing based or Graph based

- **Evaluating Factuality in Generation with Dependency-level Entailment** *Tanya Goyal, Greg Durrett* `EMNLP 2020`


- **FactGraph: Evaluating Factuality in Summarization with Semantic Graph Representations** *Leonardo F. R. Ribeiro, Mengwen Liu, Iryna Gurevych, Markus Dreyer, Mohit Bansal* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.236/) [[code]](https://github.com/amazon-research/fact-graph)

## Topic-controllable

**Topic-Aware Evaluation and Transformer Methods for Topic-Controllable Summarization** *Tatiana Passali, Grigorios Tsoumakas* `` [[pdf]](https://arxiv.org/abs/2206.04317) 

## Meta-evaluation
- **Evaluating the Efficacy of Summarization Evaluation across Languages** *Fajri Koto, Jey Han Lau, Timothy Baldwin* `Findings of ACL 2021` [[pdf]](https://arxiv.org/abs/2106.01478)
- **SummEval: Re-evaluating Summarization Evaluation** *Alexander R. Fabbri, Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher, Dragomir Radev* [[pdf]](https://arxiv.org/abs/2007.12626) [[code]](https://github.com/Yale-LILY/SummEval)
- **FFCI: A Framework for Interpretable Automatic Evaluation of Summarization** *Fajri Koto, Jey Han Lau, Timothy Baldwin* [[pdf]](https://arxiv.org/abs/2011.13662) [[code]](https://github.com/fajri91/ffci) ![](https://img.shields.io/badge/-evaluation-brightgreen)
- **TRUE: Re-evaluating Factual Consistency Evaluation** `NAACL 2022` [[pdf]](https://arxiv.org/abs/2204.04991)


## Reference-Free

- **Unsupervised Reference-Free Summary Quality Evaluation via Contrastive Learning** *Hanlu Wu, Tengfei Ma, Lingfei Wu, Tariro Manyumwa, Shouling Ji* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.01781) [[code]](https://github.com/whl97/LS-Score)
- **A Training-free and Reference-free Summarization Evaluation Metric via Centrality-weighted Relevance and Self-referenced Redundancy** *Wang Chen, Piji Li, Irwin King* `ACL 2021` [[pdf]](https://aclanthology.org/2021.acl-long.34/) [[code]](https://github.com/Chen-Wang-CUHK/Training-Free-and-Ref-Free-Summ-Evaluation)
- **Reference-free Summarization Evaluation via Semantic Correlation and Compression Ratio** *Yizhu Liu, Qi Jia, Kenny Zhu* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.153/) [[code]](https://github.com/YizhuLiu/summeval) 

## Manual Evaluation

- **HIGHRES: Highlight-based Reference-less Evaluation of Summarization** *Hardy, Shashi Narayan, Andreas Vlachos* `ACL19` [[pdf]](https://arxiv.org/abs/1906.01361) [[code]](https://github.com/sheffieldnlp/highres)
- **Is human scoring the best criteria for summary evaluation?** `Findings of ACL 2021` *Oleg Vasilyev, John Bohannon* [[pdf]](https://arxiv.org/abs/2012.14602)
- **How to Evaluate a Summarizer: Study Design and Statistical Analysis for Manual Linguistic Quality Evaluation** *Julius Steen, Katja Markert* `EACL21` [[pdf]](https://www.aclweb.org/anthology/2021.eacl-main.160/) [[code]](https://github.com/julmaxi/summary_lq_analysis)
- **Understanding Factuality in Abstractive Summarization with FRANK: A Benchmark for Factuality Metrics** *Artidoro Pagnoni, Vidhisha Balachandran and Yulia Tsvetkov* `NAACL21` [[pdf]](https://arxiv.org/abs/2104.13346) [[code]](https://github.com/artidoro/frank) 

## Tool

- **SacreROUGE: An Open-Source Library for Using and Developing Summarization Evaluation Metrics** *Daniel Deutsch, Dan Roth* [[pdf]](https://arxiv.org/abs/2007.05374) [[code]](https://github.com/danieldeutsch/sacrerouge)


