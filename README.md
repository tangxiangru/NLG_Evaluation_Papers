<p align="center">
<h1 align="center"> <img src="[https://github.com/xcfcode/Summarization-Papers/pic/summary.png](https://github.com/xcfcode/Summarization-Papers/blob/main/pic/summary.png)" width="30" />Papers of NLG Evaluation
</h1>
</p>
with a focus of summarization and factual consistency.


## Contributor
Organized by [Robert Tang](https://xiangrutang.github.io/).


## Survey

- **Repairing the Cracked Foundation: A Survey of Obstacles in Evaluation Practices for Generated Text** *Sebastian Gehrmann, Elizabeth Clark, Thibault Sellam* [[pdf]](https://arxiv.org/pdf/2202.06935.pdf)
- **Understanding Factual Errors in Summarization: Errors, Summarizers, Datasets, Error Detectors** *Liyan Tang, Tanya Goyal, Alexander R. Fabbri, Philippe Laban, Jiacheng Xu, Semih Yahvuz, Wojciech Kryściński, Justin F. Rousseau, Greg Durrett* [[pdf]](https://arxiv.org/abs/2205.12854) [[code]](https://github.com/Liyan06/AggreFact)




## QA based

- **A Semantic QA-Based Approach for Text Summarization Evaluation** *Ping Chen, Fei Wu, Tong Wang, Wei Ding* `AAAI18` [[pdf]](https://arxiv.org/abs/1704.06259) 
- **Answers Unite! Unsupervised Metrics for Reinforced Summarization Models** *Thomas Scialom, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.01610)
- **Question answering as an automatic evaluation metric for news article summarization** *Matan Eyal, Tal Baumel, and Michael Elhadad* `NAACL 2019`
- **FEQA: A question answering evaluation framework for faithfulness assessment in abstractive summarization** *Esin Durmus, He He, and Mona Diab* `ACL 2020`
- **Asking and answering questions to evaluate the factual consistency of summaries** *Alex Wang, Kyunghyun Cho, and Mike Lewis* `ACL 2020`
- **Safeval: Summarization asks for fact-based evaluation** *Thomas Scialom, Paul-Alexis Dray, Gallinari Patrick, Lamprier Sylvain, Piwowarski Benjamin, Staiano Jacopo, and Wang Alex* `EMNLP 2021`
- **Q2: Evaluating Factual Consistency in Knowledge-Grounded Dialogues via Question Generation and Question Answering** *Or Honovich, Leshem Choshen, Roee Aharoni, Ella Neeman, Idan Szpektor, Omri Abend* `EMNLP 2021`
- **QuestEval: Summarization Asks for Fact-based Evaluation** *Thomas Scialom, Paul-Alexis Dray, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano, Alex Wang, Patrick Gallinari* `EMNLP 2021`
- **QAFactEval: Improved QA-Based Factual Consistency Evaluation for Summarization** *Alexander R. Fabbri, Chien-Sheng Wu, Wenhao Liu, Caiming Xiong* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.187/) [[code]](https://github.com/salesforce/QAFactEval) 
- **Answers Unite! Unsupervised Metrics for Reinforced Summarization Models** *Thomas Scialom, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano* `EMNLP 2019`




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
- **Fill in the BLANC: Human-free quality estimation of document summaries** *Oleg Vasilyev, Vedant Dharnidharka, John Bohannon*
- **BERTFaith: Focus Attention: Promoting Faithfulness and Diversity in Summarization** *Rahul Aralikatte, Shashi Narayan, Joshua Maynez, Sascha Rothe, Ryan McDonald* `ACL 2021` [[pdf]](https://aclanthology.org/2021.acl-long.474/) 



### BART based

- **BARTScore: Evaluating Generated Text as Text Generation** *Weizhe Yuan, Graham Neubig, Pengfei Liu* `NeurIPS 2021`


## NLI based

- **(SCConv) SummaC: Re-Visiting NLI-based Models for Inconsistency Detection in Summarization** *Philippe Laban, Tobias Schnabel, Paul N. Bennett, Marti A. Hearst* `TACL 2021`
- **Evaluating the Factual Consistency of Abstractive Text Summarization** *Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher* `EMNLP20` [[pdf]](https://arxiv.org/abs/1910.12840) [[code]](https://github.com/salesforce/factCC)
- **DAE: Annotating and Modeling Fine-grained Factuality in Summarization** *Tanya Goyal, Greg Durrett* `NAACL 2021`

## Others 
### Parsing based or Graph based

- **Evaluating Factuality in Generation with Dependency-level Entailment** *Tanya Goyal, Greg Durrett* `EMNLP 2020`


- **FactGraph: Evaluating Factuality in Summarization with Semantic Graph Representations** *Leonardo F. R. Ribeiro, Mengwen Liu, Iryna Gurevych, Markus Dreyer, Mohit Bansal* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.236/) [[code]](https://github.com/amazon-research/fact-graph)

### Word embeddings based 

- **Sentence Mover’s Similarity: Automatic Evaluation for Multi-Sentence Texts** *Elizabeth Clark, Asli Celikyilmaz, Noah A. Smith* `ACL 2019`

### Counterfactual based
- **Factual Consistency Evaluation for Text Summarization via Counterfactual Estimation** *Yuexiang Xie, Fei Sun, Yang Deng, Yaliang Li, Bolin Ding* `EMNLP 2021 Findings` [[pdf]](https://arxiv.org/abs/2108.13134) [[code]](https://github.com/xieyxclack/factual_coco)


### Topic-controllable

**Topic-Aware Evaluation and Transformer Methods for Topic-Controllable Summarization** *Tatiana Passali, Grigorios Tsoumakas* `` [[pdf]](https://arxiv.org/abs/2206.04317) 

## Augmenting

- **Falsesum: Generating Document-level NLI Examples for Recognizing Factual Inconsistency in Summarization** *Prasetya Ajie Utama, Joshua Bambrick, Nafise Sadat Moosavi, Iryna Gurevych* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.199/) [[code]](https://github.com/joshbambrick/Falsesum) <details> <summary>[Abs]</summary> Neural abstractive summarization models are prone to generate summaries that are factually inconsistent with their source documents. Previous work has introduced the task of recognizing such factual inconsistency as a downstream application of natural language inference (NLI). However, state-of-the-art NLI models perform poorly in this context due to their inability to generalize to the target task. In this work, we show that NLI models can be effective for this task when the training data is augmented with high-quality task-oriented examples. We introduce Falsesum, a data generation pipeline leveraging a controllable text generation model to perturb human-annotated summaries, introducing varying types of factual inconsistencies. Unlike previously introduced document-level NLI datasets, our generated dataset contains examples that are diverse and inconsistent yet plausible. We show that models trained on a Falsesum-augmented NLI dataset improve the state-of-the-art performance across four benchmarks for detecting factual inconsistency in summarization. </details>

- **Gradient-Based Adversarial Factual Consistency Evaluation for Abstractive Summarization** *Zhiyuan Zeng, Jiaze Chen, Weiran Xu, Lei Li* `EMNLP 2021`




## Meta-evaluation
- **Evaluating the Efficacy of Summarization Evaluation across Languages** *Fajri Koto, Jey Han Lau, Timothy Baldwin* `Findings of ACL 2021` [[pdf]](https://arxiv.org/abs/2106.01478)
- **SummEval: Re-evaluating Summarization Evaluation** *Alexander R. Fabbri, Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher, Dragomir Radev* [[pdf]](https://arxiv.org/abs/2007.12626) [[code]](https://github.com/Yale-LILY/SummEval)
- **FFCI: A Framework for Interpretable Automatic Evaluation of Summarization** *Fajri Koto, Jey Han Lau, Timothy Baldwin* [[pdf]](https://arxiv.org/abs/2011.13662) [[code]](https://github.com/fajri91/ffci) ![](https://img.shields.io/badge/-evaluation-brightgreen)
- **TRUE: Re-evaluating Factual Consistency Evaluation** `NAACL 2022` [[pdf]](https://arxiv.org/abs/2204.04991)
- **DialSummEval: Revisiting Summarization Evaluation for Dialogues** *Mingqi Gao, Xiaojun Wan* `NAACL 2022`
- **(CGS) Ranking Generated Summaries by Correctness: An Interesting but Challenging Application for Natural Language Inference** *Tobias Falke, Leonardo F. R. Ribeiro, Prasetya Ajie Utama, Ido Dagan, Iryna Gurevych* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1213/) [[data]](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/2002)  
- **(XSF) On faithfulness and factuality in abstractive summarization** *Joshua Maynez, Shashi Narayan, Bernd Bohnet, and Ryan McDonald*
- **What Have We Achieved on Text Summarization?** *Dandan Huang, Leyang Cui, Sen Yang, Guangsheng Bao, Kun Wang, Jun Xie, Yue Zhang* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.04529) 
- **Understanding Factuality in Abstractive Summarization with FRANK: A Benchmark for Factuality Metrics** *Artidoro Pagnoni, Vidhisha Balachandran and Yulia Tsvetkov* `NAACL21` [[pdf]](https://arxiv.org/abs/2104.13346) [[code]](https://github.com/artidoro/frank) 
- **Asking and answering questions to evaluate the factual consistency of summaries** *Alex Wang, Kyunghyun Cho, and Mike Lewis* `ACL 2020`
- XSF: https://github.com/google-research-datasets/xsum_hallucination_annotations#license

## Reference-Free

- **Unsupervised Reference-Free Summary Quality Evaluation via Contrastive Learning** *Hanlu Wu, Tengfei Ma, Lingfei Wu, Tariro Manyumwa, Shouling Ji* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.01781) [[code]](https://github.com/whl97/LS-Score)
- **A Training-free and Reference-free Summarization Evaluation Metric via Centrality-weighted Relevance and Self-referenced Redundancy** *Wang Chen, Piji Li, Irwin King* `ACL 2021` [[pdf]](https://aclanthology.org/2021.acl-long.34/) [[code]](https://github.com/Chen-Wang-CUHK/Training-Free-and-Ref-Free-Summ-Evaluation)
- **Reference-free Summarization Evaluation via Semantic Correlation and Compression Ratio** *Yizhu Liu, Qi Jia, Kenny Zhu* `NAACL 2022` [[pdf]](https://aclanthology.org/2022.naacl-main.153/) [[code]](https://github.com/YizhuLiu/summeval) 
- **MaskEval: Weighted MLM-Based Evaluation for Text Summarization and Simplification** *Yu Lu Liu, Rachel Bawden, Thomas Scaliom, Benoît Sagot, Jackie Chi Kit Cheung*


## Manual Evaluation

- **HIGHRES: Highlight-based Reference-less Evaluation of Summarization** *Hardy, Shashi Narayan, Andreas Vlachos* `ACL19` [[pdf]](https://arxiv.org/abs/1906.01361) [[code]](https://github.com/sheffieldnlp/highres)
- **Is human scoring the best criteria for summary evaluation?** `Findings of ACL 2021` *Oleg Vasilyev, John Bohannon* [[pdf]](https://arxiv.org/abs/2012.14602)
- **How to Evaluate a Summarizer: Study Design and Statistical Analysis for Manual Linguistic Quality Evaluation** *Julius Steen, Katja Markert* `EACL21` [[pdf]](https://www.aclweb.org/anthology/2021.eacl-main.160/) [[code]](https://github.com/julmaxi/summary_lq_analysis)
- **Understanding Factuality in Abstractive Summarization with FRANK: A Benchmark for Factuality Metrics** *Artidoro Pagnoni, Vidhisha Balachandran and Yulia Tsvetkov* `NAACL21` [[pdf]](https://arxiv.org/abs/2104.13346) [[code]](https://github.com/artidoro/frank) 

## Tool

- **SacreROUGE: An Open-Source Library for Using and Developing Summarization Evaluation Metrics** *Daniel Deutsch, Dan Roth* [[pdf]](https://arxiv.org/abs/2007.05374) [[code]](https://github.com/danieldeutsch/sacrerouge)


