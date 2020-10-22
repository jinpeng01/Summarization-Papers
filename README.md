# Summarization Papers

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

Contributed by [Xiachong Feng](http://xcfeng.net/), [Yichong Huang](https://github.com/OrangeInSouth) ([Factual Consistency](#factual-consistency)), [Haozheng Yang](https://github.com/hzyang95) ([Multi-Document](#multi-document))

This repo contains a list of summarization papers including various topics. If any error, please open an issue. 

> For more topics, please refer to another repo [xcfcode/What-I-Have-Read](https://github.com/xcfcode/What-I-Have-Read), including Meta Learning, Graph Neural Networks (GNN), Knowledge Distillation, Pre-trained Language Models, Natural Language Generation and several [survey and paper slides](https://github.com/xcfcode/What-I-Have-Read#slides).

## Content
   * [Summarization Papers](#summarization-papers)
      * [Content](#content)
      * [Presentations &amp;&amp; Notes](#presentations--notes)
      * [Survey](#survey) 
      * [Dataset](#dataset)
      * [Scientific Document](#scientific-document)
      * [Factual Consistency](#factual-consistency) 
      * [Sentiment Related](#sentiment-related) 
      * [Pretrain Based](#pretrain-based) 
      * [Style](#style)
      * [Dialogue](#dialogue)
      * [Graph-Based](#graph-based) 
      * [Multi-Document](#multi-document)
      * [Cross-Lingual](#cross-lingual) 
      * [Unsupervised](#unsupervised) 
      * [Multi-modal](#multi-modal-1) 
      * [Concept-map-based](#concept-map-based) 
      * [Timeline](#timeline) 
      * [Opinion](#opinion)
      * [Reinforcement Learning](#reinforcement-learning) 
      * [Reward Learning](#reward-learning)
      * [Controlled](#controlled)
      * [Analysis](#analysis)
      * [Theory](#theory)
      * [Extractive](#extractive) 
      * [Abstractive](#abstractive)
      * [Extractive-Abstractive](#extractive-abstractive)
      * [Syntactic](#syntactic)
      * [QA Related](#qa-related)
      * [Evaluation](#evaluation)
      * [Toolkit](#toolkit)
## Presentations && Notes
> **Presentations** and **Notes** I have made for Summarization in our group.

![](https://img.shields.io/badge/Presentations-presentations-brightgreen) ![](https://img.shields.io/badge/Notes-notes-orange) ![](https://img.shields.io/badge/Papers-papers-blue)

* [Multi-modal Summarization](slides/presentation/Multi-modal-Summarization.pdf) ![](https://img.shields.io/badge/-presentations-brightgreen) 
* [ACL20 Summarization](slides/presentation/acl2020-summarization.pdf) ![](https://img.shields.io/badge/-presentations-brightgreen) 
* [文本摘要简述 (Chinese)](slides/presentation/文本摘要简述.pdf) ![](https://img.shields.io/badge/-presentations-brightgreen) 
* [ACL19 Summarization](slides/presentation/ACL19%20Summarization.pdf) ![](https://img.shields.io/badge/-presentations-brightgreen) 
* [Brief intro to summarization (Chinese)](slides/notes/Brief-intro-to-summarization.pdf) ![](https://img.shields.io/badge/-notes-orange)
* [EMNLP19 Summarization (Chinese)](slides/notes/EMNLP19_Summarization.pdf) ![](https://img.shields.io/badge/-notes-orange)
* [ACL19-A Simple Theoretical Model of Importance for Summarization](slides/paper-slides/A%20Simple%20Theoretical%20Model%20of%20Importance%20for%20Summarization.pdf) ![](https://img.shields.io/badge/-papers-blue)
* [ACL19-Multimodal Abstractive Summarization for How2 Videos](slides/paper-slides/Multimodal%20Abstractive%20Summarization%20for%20How2%20Videos.pdf) ![](https://img.shields.io/badge/-papers-blue)

## Survey
1. **Deep Learning Based Abstractive Text Summarization: Approaches, Datasets, Evaluation Measures, and Challenges** *Dima Suleiman, Arafat A. Awajan* [[pdf]](https://www.semanticscholar.org/paper/Deep-Learning-Based-Abstractive-Text-Summarization%3A-Suleiman-Awajan/b7da726c244287748575ef404009609afde45bea)
2. **A Survey of Knowledge-Enhanced Text Generation** *Wenhao Yu, Chenguang Zhu, Zaitang Li, Zhiting Hu, Qingyun Wang, Heng Ji, Meng Jiang* [[pdf]](https://arxiv.org/abs/2010.04389)
3. **From Standard Summarization to New Tasks and Beyond: Summarization with Manifold Information** *Shen Gao, Xiuying Chen, Zhaochun Ren, Dongyan Zhao, Rui Yan* `IJCAI20` [[pdf]](https://arxiv.org/abs/2005.04684)
4. **Neural Abstractive Text Summarization with Sequence-to-Sequence Models** *Tian Shi, Yaser Keneshloo, Naren Ramakrishnan, Chandan K. Reddy* [[pdf]](https://arxiv.org/abs/1812.02303)
5. **A Survey on Neural Network-Based Summarization Methods** *Yue Dong* [[pdf]](https://arxiv.org/abs/1804.04589)
6. **Automated text summarisation and evidence-based medicine: A survey of two domains** *Abeed Sarker, Diego Molla, Cecile Paris* [[pdf]](https://arxiv.org/abs/1706.08162)
7. **Automatic Keyword Extraction for Text Summarization: A Survey** *Santosh Kumar Bharti, Korra Sathya Babu* [[pdf]](https://arxiv.org/abs/1704.03242)
8. **Text Summarization Techniques: A Brief Survey** *Mehdi Allahyari, Seyedamin Pouriyeh, Mehdi Assefi, Saeid Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys Kochut* [[pdf]](https://arxiv.org/abs/1707.02268)
9. **Recent automatic text summarization techniques: a survey** *Mahak Gambhir, Vishal Gupta* [[pdf]](https://link.springer.com/article/10.1007/s10462-016-9475-9)

## Dataset
|ID|Name|Description|Paper|Conference|
|:---:|:---:|:---:|:---:|:---:|
| 1 | [CNN-DailyMail](https://github.com/harvardnlp/sent-summary) | News | [Abstractive Text Summarization using Sequence\-to\-sequence RNNs and Beyond ](https://www.aclweb.org/anthology/K16-1028/)|SIGNLL16|
| 2 | [New York Times](https://catalog.ldc.upenn.edu/LDC2008T19)| News | [The New York Times Annotated Corpus](https://catalog.ldc.upenn.edu/LDC2008T19) |
| 3 | [DUC](https://duc.nist.gov/data.html)| News | [The Effects Of Human Variation In DUC Summarization Evaluation](https://www.aclweb.org/anthology/W04-1003/) |
| 4 | [Gigaword](https://github.com/harvardnlp/sent-summary) | News | [A Neural Attention Model For Abstractive Sentence Summarization](https://arxiv.org/abs/1509.00685) |EMNLP15|
| 5 | [Newsroom](http://lil.nlp.cornell.edu/newsroom/) | News | [Newsroom: A Dataset of 1\.3 Million Summaries with Diverse Extractive Strategies](https://www.aclweb.org/anthology/N18-1065)|NAACL18|
| 6 | [Xsum](https://github.com/EdinburghNLP/XSum) | News | [Don’t Give Me the Details, Just the Summary\! Topic\-Aware Convolutional Neural Networks for Extreme Summarization](https://www.aclweb.org/anthology/D18-1206/)|EMNLP18|
| 7 | [Multi-News](https://github.com/Alex-Fabbri/Multi-News)| Multi-document News | [Multi\-News: a Large\-Scale Multi\-Document Summarization Dataset and Abstractive Hierarchical Model](https://arxiv.org/abs/1906.01749)|ACL19|
| 8 | [SAMSum](https://arxiv.org/abs/1911.12237)| Multi-party conversation | [SAMSum Corpus: A Human\-annotated Dialogue Dataset for Abstractive Summarization](https://arxiv.org/abs/1911.12237)|EMNLP19|
| 9 | [AMI](http://groups.inf.ed.ac.uk/ami/download/) | Meeting | [The AMI Meeting Corpus: A pre\-announcement\. ](http://groups.inf.ed.ac.uk/ami/download/)|
| 10 | [ICSI](http://groups.inf.ed.ac.uk/ami/icsi/download/)| Meeting | [The ICSI Meeting Corpus](http://groups.inf.ed.ac.uk/ami/icsi/) |
| 11 | [MSMO](http://www.nlpr.ia.ac.cn/cip/jjzhang.htm)| Multi-modal | [MSMO: Multimodal Summarization with Multimodal Output](https://www.aclweb.org/anthology/D18-1448/) |EMNLP18|
| 12 | [How2](https://github.com/srvk/how2-dataset) | Multi-modal | [How2: A Large\-scale Dataset for Multimodal Language Understanding](https://arxiv.org/abs/1811.00347)| NIPS18|
| 13 | [ScisummNet](https://cs.stanford.edu/~myasu/projects/scisumm_net/) | Scientific paper | [ScisummNet: A Large Annotated Corpus and Content\-Impact Models for Scientific Paper Summarization with Citation Networks](https://arxiv.org/abs/1909.01716) |AAAI19|
| 14 | [PubMed, ArXiv](https://github.com/armancohan/long-summarization)| Scientific paper | [A Discourse\-Aware Attention Model for Abstractive Summarization of Long Documents](https://arxiv.org/abs/1804.05685)| NAACL18 |
| 15 | [TALKSUMM](https://github.com/levguy/talksumm) | Scientific paper | [TALKSUMM: A Dataset and Scalable Annotation Method for Scientiﬁc Paper Summarization Based on Conference Talks](https://www.aclweb.org/anthology/P19-1204/) | ACL19 |
| 16 | [BillSum](https://github.com/FiscalNote/BillSum) | Legal | [BillSum: A Corpus for Automatic Summarization of US Legislation](https://www.aclweb.org/anthology/D19-5406/) |EMNLP19|
| 17 | [LCSTS](http://icrc.hitsz.edu.cn/Article/show/139.html)| Chinese Weibo| [LCSTS: A Large Scale Chinese Short Text Summarization Dataset ](https://www.aclweb.org/anthology/D15-1229/)|EMNLP15|
| 18 | [WikiHow](https://github.com/mahnazkoupaee/WikiHow-Dataset)| Online Knowledge Base | [WikiHow: A Large Scale Text Summarization Dataset](https://arxiv.org/abs/1810.09305) |
| 19 | [Concept-map-based MDS Corpus](https://github.com/UKPLab/emnlp2017-cmapsum-corpus/)| Educational Multi-document| [Bringing Structure into Summaries : Crowdsourcing a Benchmark Corpus of Concept Maps](https://www.aclweb.org/anthology/D17-1320/)|EMNLP17|
| 20 | [WikiSum](https://github.com/tensorflow/tensor2tensor/tree/master/tensor2tensor/data_generators/wikisum) | Wikipedia Multi-document | [Generating Wikipedia By Summarizing Long Sequence](https://arxiv.org/abs/1801.10198) |ICLR18|
| 21 | [GameWikiSum](https://github.com/Diego999/GameWikiSum) | Game Multi-document | [GameWikiSum : a Novel Large Multi\-Document Summarization Dataset](https://arxiv.org/abs/2002.06851) |LREC20|
| 22 | [En2Zh CLS, Zh2En CLS](http://www.nlpr.ia.ac.cn/cip/dataset.htm)| Cross-Lingual | [NCLS: Neural Cross\-Lingual Summarization](https://arxiv.org/abs/1909.00156) |EMNLP19|
| 23 | [Timeline Summarization Dataset](https://github.com/yingtaomj/Learning-towards-Abstractive-Timeline-Summarization)| Baidu timeline| [Learning towards Abstractive Timeline Summarization ](https://www.ijcai.org/Proceedings/2019/686)|IJCAI19|
| 24 | [Reddit TIFU](https://github.com/ctr4si/MMN) | online discussion | [Abstractive Summarization of Reddit Posts with Multi\-level Memory Networks](https://arxiv.org/abs/1811.00783)| NAACL19 |
| 25 | [TripAtt](https://github.com/Junjieli0704/ASN) | Review | [Attribute\-aware Sequence Network for Review Summarization](https://www.aclweb.org/anthology/D19-1297/)|EMNLP19|
| 26 | [Reader Comments Summarization Corpus](https://drive.google.com/file/d/1_YH5cBtvNnUNJjGj7kiTMjuHydBqWYQT/view?usp=drive_open) | Comments-based Weibo | [Abstractive Text Summarization by Incorporating Reader Comments ](https://arxiv.org/abs/1812.05407)|AAAI19|
| 27 | [BIGPATENT](https://evasharma.github.io/bigpatent/) | Patent| [BIGPATENT: A Large\-Scale Dataset for Abstractive and Coherent Summarization](https://arxiv.org/abs/1906.03741)|ACL19|
| 28 | [Curation Corpus](https://github.com/CurationCorp/curation-corpus) | News | [Curation Corpus for Abstractive Text Summarisation](https://github.com/CurationCorp/curation-corpus) |
| 29 | [MATINF](https://github.com/WHUIR/MATINF) |Multi-task|[MATINF: A Jointly Labeled Large-Scale Dataset for Classification, Question Answering and Summarization](https://arxiv.org/abs/2004.12302)|ACL20|
| 30 | [MLSUM](https://github.com/recitalAI/MLSUM) |Multi-Lingual Summarization Dataset|[MLSUM: The Multilingual Summarization Corpus](https://arxiv.org/abs/2004.14900)|EMNLP20|
| 31 | Dialogue(Debate)|Argumentative Dialogue Summary Corpus |[Using Summarization to Discover Argument Facets in Online Idealogical Dialog](https://www.aclweb.org/anthology/N15-1046/)|NAACL15|
|32|[WCEP](https://github.com/complementizer/wcep-mds-dataset)|News Multi-document|[A Large-Scale Multi-Document Summarization Dataset from the Wikipedia Current Events Portal](https://arxiv.org/abs/2005.10070)|ACL20 Short|
|33|[ArgKP](https://www.research.ibm.com/haifa/dept/vst/debating_data.shtml)|Argument-to-key Point Mapping|[From Arguments to Key Points: Towards Automatic Argument Summarization](https://arxiv.org/abs/2005.01619)|ACL20|
|34|[CRD3](https://github.com/RevanthRameshkumar/CRD3)|Dialogue|[Storytelling with Dialogue: A Critical Role Dungeons and Dragons Dataset](https://www.aclweb.org/anthology/2020.acl-main.459/)|2020||
|35|[Gazeta](https://github.com/IlyaGusev/gazeta)|Russian news|[Dataset for Automatic Summarization of Russian News](https://arxiv.org/abs/2006.11063)||
|36|[MIND](https://msnews.github.io/)|English news recommendation, Summarization, Classification, Entity|[MIND: A Large-scale Dataset for News Recommendation](https://www.aclweb.org/anthology/2020.acl-main.331/)|ACL20|
|37|[public_meetings](https://github.com/pltrdy/autoalign)|french meeting(test set)|[Align then Summarize: Automatic Alignment Methods for Summarization Corpus Creation](https://www.aclweb.org/anthology/2020.lrec-1.829)|LREC|
|38|Enron|Email|[Building a Dataset for Summarization and Keyword Extraction from Emails](https://www.aclweb.org/anthology/L14-1028/)|2014| 349 emails and threads|
|39|Columbia|Email|[Summarizing Email Threads]([https://www.aclweb.org/anthology/N04-4027.pdf](https://dl.acm.org/doi/10.5555/1613984.1614011))|2004|96 email threads,average of 3.25 email|
|40|BC3|Email|[A publicly available annotated corpus for supervised email summarization](https://www.ufv.ca/media/assets/computer-information-systems/gabriel-murray/publications/aaai08.pdf)||40 email threads (3222 sentences)|
|41|[WikiLingua](https://github.com/esdurmus/Wikilingua)|Cross-Lingual|[WikiLingua- A New Benchmark Dataset for Cross-Lingual Abstractive Summarization](https://arxiv.org/abs/2010.03093)|Findings of EMNLP20|
|42|[LcsPIRT](http://eie.usts.edu.cn/prj/NLPoSUST/LcsPIRT.htm)|Chinese Dialogue|[Global Encoding for Long Chinese Text Summarization](https://dl.acm.org/doi/10.1145/3407911)|TALLIP|
|43|[CLTS](https://github.com/lxj5957/CLTS-Dataset)|Chinese News|[CLTS: A New Chinese Long Text Summarization Dataset](https://link.springer.com/chapter/10.1007/978-3-030-60450-9_42)|NLPCC20|[Data](https://github.com/lxj5957/CLTS-Dataset)|
|44|[VMSMO](https://github.com/yingtaomj/VMSMO)|Multi-modal|[VMSMO: Learning to Generate Multimodal Summary for Video-based News Articles](https://arxiv.org/abs/2010.05406)|EMNLP20 |
|45|[Multi-XScience](https://github.com/yaolu/Multi-XScience)|Multi-document|[Multi-XScience: A Large-scale Dataset for Extreme Multi-document Summarization of Scientiﬁc Articles](http://www.cs.toronto.edu/~lcharlin/papers/Multi-XScience.pdf)|EMNLP20 short|
|46|[SCITLDR](https://github.com/allenai/scitldr)|Scientific Document|[TLDR: Extreme Summarization of Scientific Documents](https://arxiv.org/abs/2004.15011)|Findings of EMNLP20|
|47|[scisumm-corpus](https://github.com/WING-NUS/scisumm-corpus)|Scientific Document|||

## Scientific Document
1. **Dimsum @LaySumm 20: BART-based Approach for Scientific Document Summarization** *Tiezheng Yu, Dan Su, Wenliang Dai, Pascale Fung* [[pdf]](https://arxiv.org/abs/2010.09252) [[code]](https://github.com/TysonYu/Laysumm)
2. **SciSummPip: An Unsupervised Scientific Paper Summarization Pipeline** *Jiaxin Ju, Ming Liu, Longxiang Gao, Shirui Pan* [[pdf]](https://arxiv.org/abs/2010.09190) [[code]](https://github.com/mingzi151/SummPip)
3. **Enhancing Extractive Text Summarization with Topic-Aware Graph Neural Networks** *Peng Cui, Le Hu, Yuanchao Liu* `COLING20` [[pdf]](https://arxiv.org/abs/2010.06253) 
4. **Multi-XScience: A Large-scale Dataset for Extreme Multi-document Summarization of Scientiﬁc Articles** *Yao Lu, Yue Dong, Laurent Charlin* `EMNLP20 Short` [[pdf]](http://www.cs.toronto.edu/~lcharlin/papers/Multi-XScience.pdf) [[data]](https://github.com/yaolu/Multi-XScience)
5. **TLDR: Extreme Summarization of Scientific Documents** *Isabel Cachola, Kyle Lo, Arman Cohan, Daniel S. Weld* `Findings of EMNLP20` [[pdf]](https://arxiv.org/abs/2004.15011) [[data]](https://github.com/allenai/scitldr)
6. **Extractive Summarization of Long Documents by Combining Global and Local Context** *Wen Xiao, Giuseppe Carenini* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.08089) [[code]](https://github.com/Wendy-Xiao/Extsumm_local_global_context)
7. **ScisummNet: A Large Annotated Corpus and Content\-Impact Models for Scientific Paper Summarization with Citation Networks** *Michihiro Yasunaga, Jungo Kasai, Rui Zhang, Alexander R. Fabbri, Irene Li, Dan Friedman, Dragomir R. Radev* `AAAI19` [[pdf]](https://arxiv.org/abs/1909.01716) [[data]](https://cs.stanford.edu/~myasu/projects/scisumm_net/)
8. **TalkSumm: A Dataset and Scalable Annotation Method for Scientific Paper Summarization Based on Conference Talks** *Guy Lev, Michal Shmueli-Scheuer, Jonathan Herzig, Achiya Jerbi, David Konopnicki* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1204/) [[data]](https://github.com/levguy/talksumm)
9. **A Discourse-Aware Attention Model for Abstractive Summarization of Long Documents** *Arman Cohan, Franck Dernoncourt, Doo Soon Kim, Trung Bui, Seokhwan Kim, Walter Chang, Nazli Goharian* `NAACL18` [[pdf]](https://arxiv.org/abs/1804.05685) [[data]](https://github.com/armancohan/long-summarization)

## Factual Consistency
![](https://img.shields.io/badge/How%20to%20evaluate%20factual%20consistency%20of%20summary-evaluation-brightgreen)<br>
![](https://img.shields.io/badge/How%20to%20improve%20factual%20consistency%20of%20summary-improve-orange)<br>
![](https://img.shields.io/badge/analysis%20about%20factual%20consistency%20of%20summary-analysis-blue)<br>
![](https://img.shields.io/badge/How%20to%20correct%20factual%20errors%20in%20summary-correct-red)<br>
1. **Factual Error Correction for Abstractive Summarization Models** *Meng Cao, Yue Dong, Jiapeng Wu, Jackie Chi Kit Cheung* `EMNLP20 short` [[pdf]](https://arxiv.org/abs/2010.08712) [[code]](https://github.com/mcao610/Factual-Error-Correction) ![](https://img.shields.io/badge/-correct-red)
1. **Multi-Fact Correction in Abstractive Text Summarization.** *Yue Dong, Shuohang Wang, Zhe Gan, Yu Cheng, Jackie Chi Kit Cheung, Jingjing Liu* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.02443) ![](https://img.shields.io/badge/-correct-red)
2. **Factual Error Correction for Abstractive Summarization Models** *Cao Meng, Yue Cheung Dong, Jiapeng Wu, and Jackie Chi Kit* `EMNLP20` [[pdf]]() ![](https://img.shields.io/badge/-correct-red)
3. **Evaluating the Factual Consistency of Abstractive Text Summarization** *Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher* `EMNLP20` [[pdf]](https://arxiv.org/abs/1910.12840) [[code]](https://github.com/salesforce/factCC)![](https://img.shields.io/badge/-evaluation-brightgreen)
4. **Reducing Quantity Hallucinations in Abstractive Summarization** *Zheng Zhao, Shay B. Cohen, Bonnie Webber*`EMNLP-Findings20` [[pdf]](https://arxiv.org/abs/2009.13312) ![](https://img.shields.io/badge/-evaluation-brightgreen)
5. **On Faithfulness and Factuality in Abstractive Summarization**  *Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald*`ACL20` [[pdf]](https://arxiv.org/abs/2005.00661) [[data]](https://github.com/google-research-datasets/xsum_hallucination_annotations) ![](https://img.shields.io/badge/-analysis-blue)
6. **Improving Truthfulness of Headline Generation**  *Kazuki Matsumaru, Sho Takase, Naoaki Okazaki* `ACL20`[[pdf]](https://arxiv.org/abs/2005.00882) ![](https://img.shields.io/badge/-improve-orange)
7. **Optimizing the Factual Correctness of a Summary: A Study of Summarizing Radiology Reports**  *Yuhao Zhang, Derek Merck, Emily Bao Tsai, Christopher D. Manning, Curtis P. Langlotz* `ACL20`[[pdf]](https://arxiv.org/abs/1911.02541) ![](https://img.shields.io/badge/-improve-orange)
8. **FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization** *Esin Durmus, He He, Mona Diab* `ACL20` [[pdf]](https://arxiv.org/abs/2005.03754) [[code]](https://github.com/esdurmus/feqa) ![](https://img.shields.io/badge/-evaluation-brightgreen)
9. **Asking and Answering Questions to Evaluate the Factual Consistency of Summaries** *Alex Wang, Kyunghyun Cho, Mike Lewis* `ACL20` [[pdf]](https://arxiv.org/abs/2004.04228) [[code]](https://github.com/W4ngatang/qags)![](https://img.shields.io/badge/-evaluation-brightgreen)
10. **Knowledge Graph-Augmented Abstractive Summarization with Semantic-Driven Cloze Reward** *Luyang Huang, Lingfei Wu, Lu Wang* `ACL20` [[pdf]](https://arxiv.org/abs/2005.01159) ![](https://img.shields.io/badge/-improve-orange)
11. **Boosting Factual Correctness of Abstractive Summarization with Knowledge Graph** *Chenguang Zhu, William Hinthorn, Ruochen Xu, Qingkai Zeng, Michael Zeng, Xuedong Huang, Meng Jiang* `arXiv20` [[pdf]](https://arxiv.org/abs/2003.08612) ![](https://img.shields.io/badge/-improve-orange)
12. **Mind The Facts: Knowledge-Boosted Coherent Abstractive Text Summarization** *Beliz Gunel, Chenguang Zhu, Michael Zeng, Xuedong Huang* `NIPS19` [[pdf]](https://arxiv.org/abs/2006.15435) ![](https://img.shields.io/badge/-improve-orange)
13. **Assessing The Factual Accuracy of Generated Text** *Ben Goodrich, Vinay Rao, Mohammad Saleh, Peter J Liu* `KDD19` [[pdf]](https://arxiv.org/abs/1905.13322) ![](https://img.shields.io/badge/-evaluation-brightgreen)
14. **Ranking Generated Summaries by Correctness: An Interesting but Challenging Application for Natural Language Inference** *Tobias Falke, Leonardo F. R. Ribeiro, Prasetya Ajie Utama, Ido Dagan, Iryna Gurevych* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1213/) [[data]](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/2002) ![](https://img.shields.io/badge/-evaluation-brightgreen)
15. **Ensure the Correctness of the Summary: Incorporate Entailment Knowledge into Abstractive Sentence Summarization** *Haoran Li, Junnan Zhu, Jiajun Zhang, Chengqing Zong* `COLING18` [[pdf]](https://www.aclweb.org/anthology/C18-1121/) [[code]](https://github.com/hrlinlp/entail_sum) ![](https://img.shields.io/badge/-improve-orange)
16. **Faithful to the Original: Fact-Aware Neural Abstractive Summarization** *Ziqiang Cao, Furu Wei, Wenjie Li, Sujian Li* `AAAI18` [[pdf]](https://arxiv.org/abs/1711.04434) ![](https://img.shields.io/badge/-improve-orange)

## Sentiment Related
1. **A Unified Dual-view Model for Review Summarization and Sentiment Classification with Inconsistency Loss** *Hou Pong Chan, Wang Chen, Irwin King* `SIGIR20` [[pdf]](https://arxiv.org/abs/2006.01592) [[code]](https://github.com/kenchan0226/dual_view_review_sum)
2. **A Hierarchical End-to-End Model for Jointly Improving Text Summarization and Sentiment Classification** *Shuming Ma, Xu Sun, Junyang Lin, Xuancheng Ren* `IJCAI18` [[pdf]](https://arxiv.org/abs/1805.01089) 
3. **Two-level Text Summarization from Online News Sources with Sentiment Analysis** *Tarun B. Mirani, Sreela Sasi* `IEEE17` [[pdf]](https://ieeexplore.ieee.org/document/8076735)
4. **Creating Video Summarization From Emotion Perspective** *Yijie Lan, Shikui Wei, Ruoyu Liu, Yao Zhao* `ICSP16` [[pdf]](https://ieeexplore.ieee.org/document/7878001/)

## Pretrain Based
1. **Pre-training for Abstractive Document Summarization by Reinstating Source Text** *Yanyan Zou, Xingxing Zhang, Wei Lu, Furu Wei, Ming Zhou* `EMNLP20` [[pdf]](https://arxiv.org/abs/2004.01853v3) [[code]](https://github.com/zoezou2015/abs_pretraining)
2. **PALM: Pre-training an Autoencoding&Autoregressive Language Model for Context-conditioned Generation** *Bin Bi, Chenliang Li, Chen Wu, Ming Yan, Wei Wang, Songfang Huang, Fei Huang, Luo Si* `EMNLP20` [[pdf]](https://arxiv.org/abs/2004.07159)
3. **TED: A Pretrained Unsupervised Summarization Model with Theme Modeling and Denoising** *Ziyi Yang Chenguang Zhu Robert Gmyr Michael Zeng Xuedong Huang Eric Darve* `Findings of EMNLP20` [[pdf]](https://arxiv.org/abs/2001.00725)
4. **QURIOUS: Question Generation Pretraining for Text Generation** *Shashi Narayan, Gonçalo Simoes, Ji Ma, Hannah Craighead, Ryan Mcdonald* `ACL20 Short` [[pdf]](https://arxiv.org/abs/2004.11026)
5. **PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive Summarization** *Jingqing Zhang, Yao Zhao, Mohammad Saleh, Peter J. Liu* `ICML20` [[pdf]](https://arxiv.org/abs/1912.08777) [[code]](https://github.com/google-research/pegasus)
6. **Abstractive Text Summarization based on Language Model Conditioning and Locality Modeling** *Dmitrii Aksenov, Julián Moreno-Schneider, Peter Bourgonje, Robert Schwarzenberg, Leonhard Hennig, Georg Rehm* `LREC20` [[pdf]](https://arxiv.org/abs/2003.13027)
7. **Abstractive Summarization with Combination of Pre-trained Sequence-to-Sequence and Saliency Models** *Dmitrii Aksenov, Julián Moreno-Schneider, Peter Bourgonje, Robert Schwarzenberg, Leonhard Hennig, Georg Rehm* [[pdf]](https://arxiv.org/abs/2003.13028)
8. **Learning by Semantic Similarity Makes Abstractive Summarization Better** *Wonjin Yoon, Yoon Sun Yeo, Minbyul Jeong, Bong-Jun Yi, Jaewoo Kang* `ICML20` [[pdf]](https://arxiv.org/abs/2002.07767) [[code]](https://github.com/icml-2020-nlp/semsim)
9. **Make Lead Bias in Your Favor: A Simple and Effective Method for News Summarization** *Chenguang Zhu, Ziyi Yang, Robert Gmyr, Michael Zeng, Xuedong Huang* [[pdf]](https://arxiv.org/abs/1912.11602) 
10. **Text Summarization with Pretrained Encoders** *Yang Liu, Mirella Lapata* `EMNLP19` [[pdf]](https://arxiv.org/abs/1908.08345) [[code]](https://github.com/nlpyang/PreSumm)
11. **HIBERT: Document Level Pre-training of Hierarchical Bidirectional Transformers for Document Summarization** *Xingxing Zhang, Furu Wei, Ming Zhou* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1499/)
12. **MASS: Masked Sequence to Sequence Pre-training for Language Generation** *Kaitao Song, Xu Tan, Tao Qin, Jianfeng Lu, Tie-Yan Liu* `ICML19` [[pdf]](https://arxiv.org/abs/1905.02450) [[code]](https://github.com/microsoft/MASS)
13. **Pretraining-Based Natural Language Generation for Text Summarization** *Haoyu Zhang, Jianjun Xu, Ji Wang* [[pdf]](https://arxiv.org/abs/1902.09243) 
14. **Fine-tune BERT for Extractive Summarization** *Yang Liu* [[pdf]](https://arxiv.org/abs/1903.10318) [[code]](https://github.com/nlpyang/BertSum)
15. **Unified Language Model Pre-training for Natural Language Understanding and Generation** *Li Dong, Nan Yang, Wenhui Wang, Furu Wei, Xiaodong Liu, Yu Wang, Jianfeng Gao, Ming Zhou, Hsiao-Wuen Hon* `NIPS19` [[pdf]](https://arxiv.org/abs/1905.03197) [[code]](https://github.com/microsoft/unilm)
16. **Self-Supervised Learning for Contextualized Extractive Summarization** *Hong Wang, Xin Wang, Wenhan Xiong, Mo Yu, Xiaoxiao Guo, Shiyu Chang, William Yang Wang* `ACL19` [[pdf]](https://arxiv.org/abs/1906.04466) [[code]](https://github.com/hongwang600/Summarization)
17. **Efficient Adaptation of Pretrained Transformers for Abstractive Summarization** *Andrew Hoang, Antoine Bosselut, Asli Celikyilmaz, Yejin Choi* [[pdf]](https://arxiv.org/abs/1906.00138) [[code]](https://github.com/Andrew03/transformer-abstractive-summarization)

## Style
1. **Hooks in the Headline: Learning to Generate Headlines with Controlled Styles** *Di Jin, Zhijing Jin, Joey Tianyi Zhou, Lisa Orii, Peter Szolovits* `ACL20` [[pdf]](https://arxiv.org/abs/2004.01980) [[code]](https://github.com/jind11/TitleStylist)

## Dialogue 
### SAMSum
1. **Incorporating Commonsense Knowledge into Abstractive Dialogue Summarization via Heterogeneous Graph Networks** *Xiachong Feng, Xiaocheng Feng, Bing Qin, Ting Liu* [[pdf]](https://arxiv.org/abs/2010.10044) 
2. **Multi-View Sequence-to-Sequence Models with Conversational Structure for Abstractive Dialogue Summarization** *Jiaao Chen, Diyi Yang* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.01672) [[code]](https://github.com/GT-SALT/Multi-View-Seq2Seq) 
3. **SAMSum Corpus: A Human-annotated Dialogue Dataset for Abstractive Summarization** *Bogdan Gliwa, Iwona Mochol, Maciej Biesek, Aleksander Wawer* `EMNLP19` [[pdf]](https://arxiv.org/abs/1911.12237) [[data]](https://arxiv.org/src/1911.12237v2/anc/corpus.7z)

<details><summary>papers</summary><p>

### Medical
| Paper | Conference |
| :---: | :---: |
|[Dr. Summarize: Global Summarization of Medical Dialogue by Exploiting Local Structures](https://arxiv.org/abs/2009.08666)|Findings of EMNLP20|
|[Medical Dialogue Summarization for Automated Reporting in Healthcare](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7225507/)||
|[Alignment Annotation for Clinic Visit Dialogue to Clinical Note Sentence Language Generation](https://www.aclweb.org/anthology/2020.lrec-1.52/)|LREC20||
|[Generating SOAP Notes from Doctor-Patient Conversations](https://arxiv.org/pdf/2005.01795.pdf)||
|[Generating Medical Reports from Patient-Doctor Conversations using Sequence-to-Sequence Models](https://www.aclweb.org/anthology/2020.nlpmc-1.4/)|ACL20 Short||
|[Automatically Generating Psychiatric Case Notes From Digital Transcripts of Doctor-Patient Conversations](https://www.aclweb.org/anthology/W19-1918/)|NAACL19|
| [Topic-aware Pointer-Generator Networks for Summarizing Spoken Conversations](https://arxiv.org/abs/1910.01335) |ASRU19|

### French Meeting
| Paper | Conference |
| :---: | :---: |
|[Align then Summarize: Automatic Alignment Methods for Summarization Corpus Creation](https://www.aclweb.org/anthology/2020.lrec-1.829)|LREC20|
|[Leverage Unlabeled Data for Abstractive Speech Summarization with Self-Supervised Learning and Back-Summarization](https://arxiv.org/abs/2007.15296)|SPECOM20|

### Meeting
| Paper | Conference |
| :---: | :---: |
|[A Study of Text Summarization Techniques for Generating Meeting Minutes](https://link.springer.com/chapter/10.1007/978-3-030-50316-1_33)||
|[Restructuring Conversations using Discourse Relations for Zero-shot Abstractive Dialogue Summarization](https://arxiv.org/abs/1902.01615)||
|[How to Interact and Change? Abstractive Dialogue Summarization with Dialogue Act Weight and Topic Change Info](https://link.springer.com/chapter/10.1007/978-3-030-55393-7_22)|KSEM20|
|[Abstractive Text Summarization of Meetings](https://github.com/Bastian/Abstractive-Summarization-of-Meetings)||
|[A Hierarchical Network for Abstractive Meeting Summarization with Cross-Domain Pretraining](https://www.microsoft.com/en-us/research/uploads/prod/2020/04/MeetingNet_EMNLP_full.pdf)|EMNLP20|
|[Meeting Summarization, A Challenge for Deep Learning](https://link.springer.com/chapter/10.1007/978-3-030-20521-8_53)||
|[End-to-End Abstractive Summarization for Meetings](https://arxiv.org/abs/2004.02016)|2020|
| [Abstractive Meeting Summarization via Hierarchical Adaptive Segmental Network Learning](https://dl.acm.org/doi/10.1145/3308558.3313619) | WWW19 |
| [Abstractive Dialogue Summarization with Sentence-Gated Modeling Optimized by Dialogue Acts](https://arxiv.org/abs/1809.05715) | SLT18 |
| [Unsupervised Abstractive Meeting Summarization with Multi-Sentence Compression and Budgeted Submodular Maximization](https://arxiv.org/abs/1805.05271) | ACL18|
|[Generating Abstractive Summaries from Meeting Transcripts](https://arxiv.org/abs/1609.07033)|||
|[Automatic meeting summarization and topic detection system](https://www.emerald.com/insight/content/doi/10.1108/DTA-09-2017-0062/full/html)||
|[Automatic Community Creation for Abstractive Spoken Conversation Summarization](https://www.aclweb.org/anthology/W17-4506/)|ACL17 workshop||
| [Abstractive Meeting Summarization Using Dependency Graph Fusion](https://arxiv.org/abs/1609.07035) | WWW15 |
|[Domain-Independent Abstract Generation for Focused Meeting Summarization](https://www.aclweb.org/anthology/P13-1137.pdf)|ACL13||
| [Summarizing Decisions in Spoken Meetings](https://arxiv.org/abs/1606.07965) | ACL11 |
|[Automatic analysis of multiparty meetings](https://link.springer.com/article/10.1007/s12046-011-0051-3)|11|
|[A keyphrase based approach to interactive meeting summarization](https://ieeexplore.ieee.org/document/4777863)|08|key phrase guide|
|[What are meeting summaries? An analysis of human extractive summaries in meeting corpus](https://www.aclweb.org/anthology/W08-0112/)|08||
|[Evaluating the effectiveness of features and sampling in extractive meeting summarization](https://ieeexplore.ieee.org/document/4777864)|2008||
|[Automatic Summarization of Conversational Multi-Party Speech](https://www.aaai.org/Papers/AAAI/2006/AAAI06-335.pdf)|AAAI06||
|[Focused Meeting Summarization via Unsupervised Relation Extraction](https://www.aclweb.org/anthology/W12-1642.pdf)||
|[Exploring Speaker Characteristics for Meeting Summarization](https://www.isca-speech.org/archive/archive_papers/interspeech_2010/i10_2518.pdf)|10|
|[A global optimization framework for meeting summarization](https://ieeexplore.ieee.org/document/4960697)|06|
|[Semantic Similarity Applied to Spoken Dialogue Summarization](https://www.semanticscholar.org/paper/Semantic-Similarity-Applied-to-Spoken-Dialogue-Gurevych-Strube/5d7e179f1543108f06f09ba801ae70ba38900c5d)|COLING04|

#### Multi-modal
| Paper | Conference |
| :---: | :---: |
|[A Multimodal Meeting Browser that Implements an Important Utterance Detection Model based on Multimodal Information](https://dl.acm.org/doi/abs/10.1145/3379336.3381491)||
|[Exploring Methods for Predicting Important Utterances Contributing to Meeting Summarization](https://www.mdpi.com/2414-4088/3/3/50)||
| [Keep Meeting Summaries on Topic: Abstractive Multi-Modal Meeting Summarization](https://www.aclweb.org/anthology/P19-1210/)| ACL19 |
|[Fusing Verbal and Nonverbal Information for Extractive Meeting Summarization](https://dl.acm.org/doi/10.1145/3279981.3279987)|GIFT18|
|[Meeting Extracts for Discussion Summarization Based on Multimodal Nonverbal Information](https://dl.acm.org/doi/10.1145/2993148.2993160)|ICMI16|
|[Extractive Summarization of Meeting Recordings](https://pdfs.semanticscholar.org/6159/506bdd368fff24dd12e5c6ed91ba05b44f9e.pdf)||
| [Multimodal Summarization of Meeting Recordings](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.862.6509&rep=rep1&type=pdf)|ICME03|

### Open Domain
| Paper | Conference |
| :---: | :---: |
|[Making Sense of Group Chat through Collaborative Tagging and Summarization](https://homes.cs.washington.edu/~axz/papers/cscw_tilda.pdf)|CSCW18|
|[Collabot: Personalized Group Chat Summarization](https://dl.acm.org/doi/10.1145/3159652.3160588)|WSDM18|

### Customer Service
| Paper | Conference |
| :---: | :---: |
| [Automatic Dialogue Summary Generation for Customer Service](https://dl.acm.org/doi/10.1145/3292500.3330683) |KDD19|

### Email
| Paper | Conference |
| :---: | :---: |
|[Building a Dataset for Summarization and Keyword Extraction from Emails](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1037_Paper.pdf)||
|[Summarizing Online Conversations A Machine Learning Approach](http://web2py.iiit.ac.in/research_centres/publications/download/inproceedings.pdf.8b32440f2dc771c4.323031325f414e445f43616d6572612e706466.pdf)|2010|
|[Task-focused Summarization of Email](https://www.aclweb.org/anthology/W04-1008.pdf)|2004|

### News Review
| Paper | Conference |
| :---: | :---: |
|[The SENSEI Annotated Corpus: Human Summaries of Reader Comment Conversations in On-line News](https://www.aclweb.org/anthology/W16-3605/)|SIGDIAL16|

### Others
| Paper | Conference | Highlights |
| :---: | :---: | :---: |
|[文本摘要:浓缩的才是精华](https://dl.ccf.org.cn/institude/institudeDetail?id=5011489004210176&_ack=1)|||
|[Unsupervised Abstractive Dialogue Summarization for Tete-a-Tetes](https://arxiv.org/abs/2009.06851)|||
|[Storytelling with Dialogue: A Critical Role Dungeons and Dragons Dataset](https://www.aclweb.org/anthology/2020.acl-main.459/)|ACL20|
| [Legal Summarization for Multi-role Debate Dialogue via Controversy Focus Mining and Multi-task Learning](https://dl.acm.org/doi/10.1145/3357384.3357940)|CIKM19|
| [Abstractive Dialog Summarization with Semantic Scaffolds](https://openreview.net/forum?id=B1eibJrtwr) ||
|[Creating a reference data set for the summarization of discussion forum threads](https://link.springer.com/article/10.1007/s10579-017-9389-4)||
|[Summarizing Dialogic Arguments from Social Media](https://arxiv.org/abs/1711.00092)|SemDial 2017|
| [Dial2Desc: End-to-end Dialogue Description Generation](https://arxiv.org/pdf/1811.00185.pdf) | |
|[Using Summarization to Discover Argument Facets in Online Idealogical Dialog](https://www.aclweb.org/anthology/N15-1046.pdf)|NAACL15|
|[Conversation summarization using machine learning and scoring method](http://www.pluto.ai.kyutech.ac.jp/~shimada/paper/pacling2013.pdf)||
|[Plans Toward Automated Chat Summarization](https://www.aclweb.org/anthology/W11-0501/)|ACL11|
|[Domain Adaptation to Summarize Human Conversations](https://www.aclweb.org/anthology/W10-2603/)|ACL2010 workshop|
|[Automatic Text Summarization for Dialogue Style](https://www.semanticscholar.org/paper/Automatic-Text-Summarization-for-Dialogue-Style-Liu-Wang/3b7339228ee4d8dcfc3dcea6f23832659bf0a440)||
|[Adapting Lexical Chaining to Summarize Conversational Dialogues](https://www.semanticscholar.org/paper/Adapting-Lexical-Chaining-to-Summarize-Dialogues-Gurevych-Nahnsen/36f1bc82cc1d814cf5ec9bb8eab6856258e88ab3)||
|[Semantic Similarity Applied to Spoken Dialogue Summarization](https://www.aclweb.org/anthology/C04-1110/)|COLING04||
</p></details>

## Graph-Based
1. **Enhancing Extractive Text Summarization with Topic-Aware Graph Neural Networks** *Peng Cui, Le Hu, Yuanchao Liu* `COLING20` [[pdf]](https://arxiv.org/abs/2010.06253) 
2. **Heterogeneous Graph Neural Networks for Extractive Document Summarization** *Danqing Wang, Pengfei Liu, Yining Zheng, Xipeng Qiu, Xuanjing Huang* `ACL20` [[pdf]](https://arxiv.org/abs/2004.12393) [[code]](https://github.com/brxx122/HeterSUMGraph)
3. **Structured Neural Summarization** *Patrick Fernandes, Miltiadis Allamanis, Marc Brockschmidt* `ICLR19` [[pdf]](https://arxiv.org/abs/1811.01824) [[code]](https://github.com/CoderPat/structured-neural-summarization)
4. **Hierarchical Transformers for Multi-Document Summarization** *Yang Liu, Mirella Lapata* `ACL19` [[pdf]](https://arxiv.org/abs/1905.13164) [[code]](https://github.com/nlpyang/hiersumm)
5. **Learning to Create Sentence Semantic Relation Graphs for Multi-Document Summarization** *Diego Antognini, Boi Faltings* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.12231)
6. **Graph-based Neural Multi-Document Summarization** *Michihiro Yasunaga, Rui Zhang, Kshitijh Meelu, Ayush Pareek, Krishnan Srinivasan, Dragomir Radev* `CoNLL17` [[pdf]](https://www.aclweb.org/anthology/K17-1045/) 
7. **Abstractive Document Summarization with a Graph-Based Attentional Neural Model** *Jiwei Tan, Xiaojun Wan, Jianguo Xiao* `ACL17` [[pdf]](https://www.aclweb.org/anthology/P17-1108/)

## Multi-Document
1. **Multi-document Summarization with Maximal Marginal Relevance-guided Reinforcement Learning** *Yuning Mao, Yanru Qu, Yiqing Xie, Xiang Ren, Jiawei Han* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.00117) [[code]](https://github.com/morningmoni/RL-MMR.git)
2. **Heterogeneous Graph Neural Networks for Extractive Document Summarization** *Danqing Wang, Pengfei Liu, Yining Zheng, Xipeng Qiu, Xuanjing Huang* `ACL20` [[pdf]](https://arxiv.org/abs/2004.12393v1) [[code]](https://github.com/brxx122/HeterSUMGraph)
3. **Multi-Granularity Interaction Network for Extractive and Abstractive Multi-Document Summarization** *Hanqi Jin, Tianming Wang, Xiaojun Wan* `ACL20` [[pdf]](https://www.aclweb.org/anthology/2020.acl-main.556/)
4. **SUPERT: Towards New Frontiers in Unsupervised Evaluation Metrics for Multi-Document Summarization** *Yang Gao, Wei Zhao, Steffen Eger* `ACL20` [[pdf]](https://arxiv.org/abs/2005.03724) [[code]](https://github.com/yg211/acl20-ref-free-eval.git)
5. **Leveraging Graph to Improve Abstractive Multi-Document Summarization** *Wei Li, Xinyan Xiao, Jiachen Liu, Hua Wu, Haifeng Wang, Junping Du* `ACL20` [[pdf]](https://arxiv.org/abs/2005.10043) [[code]](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2020-GraphSum)
6. **Generating Representative Headlines for News Stories** *Xiaotao Gu, Yuning Mao, Jiawei Han, Jialu Liu, Hongkun Yu, You Wu, Cong Yu, Daniel Finnie, Jiaqi Zhai, Nicholas Zukoski* `WWW20` [[pdf]](https://arxiv.org/abs/2001.09386) [[code]](https://github.com/google-research-datasets/NewSHead.git)
7. **Learning to Create Sentence Semantic Relation Graphs for Multi-Document Summarization** *Diego Antognini, Boi Faltings* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.12231)
8. **Improving the Similarity Measure of Determinantal Point Processes for Extractive Multi-Document Summarization** *Sangwoo Cho, Logan Lebanoff, Hassan Foroosh, Fei Liu* `ACL19` [[pdf]](https://arxiv.org/abs/1906.00072) [[code]](https://github.com/ucfnlp/summarization-dpp-capsnet)
9. **Hierarchical Transformers for Multi-Document Summarization** *Yang Liu, Mirella Lapata* `ACL19` [[pdf]](https://arxiv.org/abs/1905.13164) [[code]](https://github.com/nlpyang/hiersumm)
10. **MeanSum: A Neural Model for Unsupervised Multi-Document Abstractive Summarization** *Eric Chu, Peter J. Liu* `ICML19` [[pdf]](https://arxiv.org/abs/1810.05739) [[code]](https://github.com/sosuperic/MeanSum)
11. **Generating Wikipedia By Summarizing Long Sequence** *Peter J. Liu, Mohammad Saleh, Etienne Pot, Ben Goodrich, Ryan Sepassi, Lukasz Kaiser, Noam Shazeer* `ICLR18` [[pdf]](https://arxiv.org/abs/1801.10198) [[code]](https://github.com/lucidrains/memory-compressed-attention.git)
12. **Adapting the Neural Encoder-Decoder Framework from Single to Multi-Document Summarization** *Logan Lebanoff, Kaiqiang Song, Fei Liu* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1446/) [[code]](https://github.com/ucfnlp/multidoc_summarization)
13. **Graph-based Neural Multi-Document Summarization** *Michihiro Yasunaga, Rui Zhang, Kshitijh Meelu, Ayush Pareek, Krishnan Srinivasan, Dragomir Radev* `CoNLL17` [[pdf]](https://www.aclweb.org/anthology/K17-1045/)
14. **Improving Multi-Document Summarization via Text Classification** *Ziqiang Cao, Wenjie Li, Sujian Li, Furu Wei* `AAAI17` [[pdf]](https://arxiv.org/abs/1611.09238)
15. **An Unsupervised Multi-Document Summarization Framework Based on Neural Document Model** *Shulei Ma, Zhi-Hong Deng, Yunlun Yang* `COLING16` [[pdf]](https://www.aclweb.org/anthology/C16-1143/)
16. **Event-Centric Summary Generation** *Lucy Vanderwende Michele Banko Arul Menezes* `ACL04` [[pdf]](https://www.microsoft.com/en-us/research/publication/event-centric-summary-generation/) 

## Cross-Lingual
1. **Mixed-Lingual Pre-training for Cross-lingual Summarization** *Ruochen Xu, Chenguang Zhu, Yu Shi, Michael Zeng, Xuedong Huang* `AACL20` [[pdf]](https://arxiv.org/abs/2010.08892)
2. **Multi-Task Learning for Cross-Lingual Abstractive Summarization** *Sho Takase, Naoaki Okazaki* [[pdf]](https://arxiv.org/abs/2010.07503)
3. **WikiLingua: A New Benchmark Dataset for Cross-Lingual Abstractive Summarization** *Faisal Ladhak, Esin Durmus, Claire Cardie, Kathleen McKeown* `Findings of EMNLP20` [[pdf]](https://arxiv.org/abs/2010.03093) [[data]](https://github.com/esdurmus/Wikilingua)
4. **A Deep Reinforced Model for Zero-Shot Cross-Lingual Summarization with Bilingual Semantic Similarity Rewards** *Zi-Yi Dou, Sachin Kumar, Yulia Tsvetkov* `ACL20 workshop` [[pdf]](https://www.aclweb.org/anthology/2020.ngt-1.7/) [[code]](https://github.com/zdou0830/crosslingual_summarization_semantic)
5. **Jointly Learning to Align and Summarize for Neural Cross-Lingual Summarization** *Yue Cao, Hui Liu, Xiaojun Wan* `ACL20` [[pdf]](https://www.aclweb.org/anthology/2020.acl-main.554/)
6. **Attend, Translate and Summarize: An Efficient Method for Neural Cross-Lingual Summarization** *Junnan Zhu, Yu Zhou, Jiajun Zhang, Chengqing Zong* `ACL20` [[pdf]](https://www.aclweb.org/anthology/2020.acl-main.121/) [[code]](https://github.com/ZNLP/ATSum)
7. **MultiSumm: Towards a Unified Model for Multi-Lingual Abstractive Summarization** *Yue Cao, Xiaojun Wan, Jinge Yao, Dian Yu* `AAAI20` [[pdf]](https://aaai.org/ojs/index.php/AAAI/article/view/5328) [[code]](https://github.com/ycao1996/Multi-Lingual-Summarization)
8. **Global Voices: Crossing Borders in Automatic News Summarization** *Khanh Nguyen, Hal Daumé III* `EMNLP19 workshop ` [[pdf]](https://arxiv.org/abs/1910.00421) [[data]](https://forms.gle/gpkJDT6RJWHM1Ztz9)
9. **NCLS: Neural Cross-Lingual Summarization** *Junnan Zhu, Qian Wang, Yining Wang, Yu Zhou, Jiajun Zhang, Shaonan Wang, Chengqing Zong* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.00156) [[code]](http://www.nlpr.ia.ac.cn/cip/dataset.htm)
10. **Zero-Shot Cross-Lingual Abstractive Sentence Summarization through Teaching Generation and Attention** *Xiangyu Duan, Mingming Yin, Min Zhang, Boxing Chen, Weihua Luo* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1305/) [[code]](https://github.com/KelleyYin/Cross-lingual-Summarization)
11. **A Robust Abstractive System for Cross-Lingual Summarization** *Jessica Ouyang, Boya Song, Kathy McKeown* `NAACL19` [[pdf]](https://www.aclweb.org/anthology/N19-1204/)
12. **Cross-Lingual Korean Speech-to-Text Summarization** *HyoJeon Yoon, Dinh Tuyen Hoang, Ngoc Thanh Nguyen, Dosam Hwang* `ACIIDS19` [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-14799-0_17)
13. **Cross-language document summarization via extraction and ranking of multiple summaries** *Xiaojun Wan, Fuli Luo, Xue Sun, Songfang Huang & Jin-ge Yao* [[pdf]](https://link.springer.com/article/10.1007/s10115-018-1152-7)
14. **Zero-Shot Cross-Lingual Neural Headline Generation** *Shi-qi Shen, Yun Chen, Cheng Yang, Zhi-yuan Liu, Mao-song Sun* `TASLP18` [[pdf]](https://dl.acm.org/doi/10.1109/TASLP.2018.2842432)
15. **Cross-Language Text Summarization using Sentence and Multi-Sentence Compression** *Elvys Linhares Pontes, Stéphane Huet, Juan-Manuel Torres-Moreno, Andréa Carneiro Linhares* `NLDB18` [[pdf]](https://hal.archives-ouvertes.fr/hal-01779465/document)
16. **Abstractive Cross-Language Summarization via Translation Model Enhanced Predicate Argument Structure Fusing** *Jiajun Zhang, Yu Zhou, Chengqing Zong* `TASLP16` [[pdf]](http://www.nlpr.ia.ac.cn/cip/ZhangPublications/zhang-taslp-2016.pdf)
17. **Phrase-based Compressive Cross-Language Summarization** *Jin-ge Yao ,Xiaojun Wan ,Jianguo Xiao* `ACL15` [[pdf]](https://www.aclweb.org/anthology/D15-1012.pdf)
18. **Multilingual Single-Document Summarization with MUSE** *Marina Litvak, Mark Last* `MultiLing13` [[pdf]](https://www.aclweb.org/anthology/W13-3111/)
19. **Using bilingual information for cross-language document summarization** *Xiaojun Wan* `ACL11` [[pdf]](https://www.aclweb.org/anthology/P11-1155.pdf)
20. **Cross-language document summarization based on machine translation quality prediction** *Xiaojun Wan, Huiying Li, Jianguo Xiao* `ACL10` [[pdf]](https://www.aclweb.org/anthology/P10-1094/)

## Unsupervised
1. **Unsupervised Extractive Summarization by Pre-training Hierarchical Transformers** *Shusheng Xu, Xingxing Zhang, Yi Wu, Furu Wei, Ming Zhou* [[pdf]](https://arxiv.org/abs/2010.08242) [[code]](https://github.com/xssstory/STAS)
2. **Q-learning with Language Model for Edit-based Unsupervised Summarization** *Ryosuke Kohita, Akifumi Wachi, Yang Zhao, Ryuki Tachibana* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.04379) [[code]](https://github.com/kohilin/ealm)
3. **Abstractive Document Summarization without Parallel Data** *Nikola I. Nikolov, Richard H.R. Hahnloser* `LREC20` [[pdf]](https://arxiv.org/abs/1907.12951) [[code]](https://github.com/ninikolov/low_resource_summarization)
4. **Unsupervised Neural Single-Document Summarization of Reviews via Learning Latent Discourse Structure and its Ranking** *Masaru Isonuma, Junichiro Mori, Ichiro Sakata* `ACL19` [[pdf]](https://arxiv.org/abs/1906.05691) [[code]](https://github.com/misonuma/strsum)
5. **Sentence Centrality Revisited for Unsupervised Summarization** *Hao Zheng, Mirella Lapata* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1628/) [[code]](https://github.com/mswellhao/PacSum)
6. **Discrete Optimization for Unsupervised Sentence Summarization with Word-Level Extraction** *Raphael Schumann, Lili Mou, Yao Lu, Olga Vechtomova, Katja Markert* `ACL20` [[pdf]](https://arxiv.org/abs/2005.01791) [[code]](https://github.com/raphael-sch/HC_Sentence_Summarization)
7. **MeanSum : A Neural Model for Unsupervised Multi-Document Abstractive Summarization** *Eric Chu, Peter J. Liu* `ICML19` [[pdf]](https://arxiv.org/abs/1810.05739) [[code]](https://github.com/sosuperic/MeanSum)
8. **SEQ3: Differentiable Sequence-to-Sequence-to-Sequence Autoencoder for Unsupervised Abstractive Sentence Compression** *Christos Baziotis, Ion Androutsopoulos, Ioannis Konstas, Alexandros Potamianos* `NAACL19` [[pdf]](https://arxiv.org/abs/1904.03651) [[code]](https://github.com/cbaziotis/seq3)
9. **Learning to Encode Text as Human-Readable Summaries usingGenerative Adversarial Networks** *Yaushian Wang, Hung-Yi Lee* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1451/) [[code]](https://github.com/yaushian/Unparalleled-Text-Summarization-using-GAN)
10. **Unsupervised Abstractive Meeting Summarization with Multi-Sentence Compression and Budgeted Submodular Maximization** *Guokan Shang, Wensi Ding, Zekun Zhang, Antoine Tixier, Polykarpos Meladianos, Michalis Vazirgiannis, Jean-Pierre Lorré* `ACL18` [[pdf]](https://arxiv.org/abs/1805.05271) [[code]](https://bitbucket.org/dascim/acl2018_abssumm)

## Multi-modal

1. **MAST: Multimodal Abstractive Summarization with Trimodal Hierarchical Attention** *Aman Khullar, Udit Arora* `EMNLP20 Workshop` [[pdf]](https://arxiv.org/abs/2010.08021) [[code]](https://github.com/amankhullar/mast)
2. **VMSMO: Learning to Generate Multimodal Summary for Video-based News Articles** *Mingzhe Li, Xiuying Chen, Shen Gao, Zhangming Chan, Dongyan Zhao, Rui Yan* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.05406) [[data]](https://github.com/yingtaomj/VMSMO)
3. **Multi-modal Summarization for Video-containing Documents** *Xiyan Fu, Jun Wang, Zhenglu Yang* [[pdf]](https://arxiv.org/abs/2009.08018)
4. **Text-Image-Video Summary Generation Using Joint Integer Linear Programming** *Anubhav Jangra, Adam Jatowt, Mohammad Hasanuzzaman, Sriparna Saha* `ECIR20` [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-45442-5_24)
5. **Aspect-Aware Multimodal Summarization for Chinese E-Commerce Products** *Haoran Li, Peng Yuan, Song Xu, Youzheng Wu, Xiaodong He, Bowen Zhou* `AAAI20` [[pdf]](https://aaai.org/ojs/index.php/AAAI/article/view/6332/6188)
6. **Convolutional Hierarchical Attention Network for Query-Focused Video Summarization** *Shuwen Xiao, Zhou Zhao, Zijian Zhang, Xiaohui Yan, Min Yang* `AAAI20` [[pdf]](https://arxiv.org/abs/2002.03740)
7. **Multimodal Summarization with Guidance of Multimodal Reference** *Junnan Zhu, Yu Zhou, Jiajun Zhang, Haoran Li, Chengqing Zong, Changliang Li* `AAAI20` [[pdf]](https://aaai.org/ojs/index.php/AAAI/article/view/6525/6381)
8. **EmotionCues: Emotion-Oriented Visual Summarization of Classroom Videos** *Haipeng Zeng, Xinhuan Shu, Yanbang Wang, Yong Wang, Liguo Zhang, Ting-Chuen Pong, Huamin Qu*  [[pdf]](https://ieeexplore.ieee.org/document/8948010) 
9. **A Survey on Automatic Summarization Using Multi-Modal Summarization System for Asynchronous Collections** *Shilpadevi Vasant Bhagwat, Sheetal .S. Thokal* [[pdf]](http://www.ijirset.com/upload/2019/february/4_shilpa_IEEE.pdf)
10. **Extractive summarization of documents with images based on multi-modal RNN** *Jingqiang Chen, Hai Zhuge*  [[pdf]](https://research.aston.ac.uk/en/publications/extractive-summarization-of-documents-with-images-based-on-multi-)
11. **Keep Meeting Summaries on Topic: Abstractive Multi-Modal Meeting Summarization** *Manling Li, Lingyu Zhang, Heng Ji, Richard J. Radke* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1210/)
12. **Multimodal Abstractive Summarization for How2 Videos** *Shruti Palaskar, Jindřich Libovický, Spandana Gella, Florian Metze* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1659/)
13. **MSMO: Multimodal Summarization with Multimodal Output** *Junnan Zhu, Haoran Li, Tianshang Liu, Yu Zhou, Jiajun Zhang, Chengqing Zong* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1448/) [[data]](http://www.nlpr.ia.ac.cn/cip/jjzhang.htm)
14. **Abstractive Text-Image Summarization Using Multi-Modal Attentional Hierarchical RNN** *Jingqiang Chen, Hai Zhuge* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1438/)
15. **Multi-modal Sentence Summarization with Modality Attention and Image Filtering** *Haoran Li, Junnan Zhu, Tianshang Liu, Jiajun Zhang, Chengqing Zong* `IJCAI18` [[pdf]](https://www.ijcai.org/Proceedings/2018/0577.pdf) 
16. **Multimodal Abstractive Summarization for Open-Domain Videos** *Jindrich Libovický, Shruti Palaskar, Spandana Gella, Florian Metze* `NIPS18` [[pdf]](https://nips2018vigil.github.io/static/papers/accepted/8.pdf) [[data]](https://github.com/srvk/how2-dataset)
17. **Read, Watch, Listen, and Summarize: Multi-Modal Summarization for Asynchronous Text, Image, Audio and Video** *Haoran Li, Junnan Zhu, Cong Ma, Jiajun Zhang, Chengqing Zong* [[pdf]](https://ieeexplore.ieee.org/document/8387512)
18. **Fusing Verbal and Nonverbal Information for Extractive Meeting Summarization** *Fumio Nihei, Yukiko  Nakano, Yukiko I. Nakano, Yutaka  Takase, Yutaka Takase* `GIFT18` [[pdf]](https://dl.acm.org/doi/10.1145/3279981.3279987)
19. **Multi-modal Summarization for Asynchronous Collection of Text, Image, Audio and Video** *Haoran Li, Junnan Zhu, Cong Ma, Jiajun Zhang, Chengqing Zong* `EMNLP17` [[pdf]](https://www.aclweb.org/anthology/D17-1114/) 
20. **Meeting Extracts for Discussion Summarization Based on Multimodal Nonverbal Information** *Fumio Nihei, Yukiko  Nakano, Yukiko I. Nakano, Yutaka  Takase, Yutaka Takase* `ICMI16` [[pdf]](https://dl.acm.org/doi/10.1145/2993148.2993160) 
21. **Summarizing a multimodal set of documents in a Smart Room** *Maria Fuentes, Horacio Rodríguez, Jordi Turmo* `LREC12` [[pdf]](https://www.aclweb.org/anthology/L12-1524/)
22. **Multi-modal summarization of key events and top players in sports tournament videos** *Dian Tjondronegoro, Xiaohui Tao, Johannes Sasongko and Cher Han Lau* [[pdf]](https://eprints.qut.edu.au/43479/1/WACV_266_%281%29.pdf) 
23. **Multimodal Summarization of Complex Sentences** *Naushad UzZaman, Jeffrey P. Bigham, James F. Allen* [[pdf]](https://www.cs.cmu.edu/~jbigham/pubs/pdfs/2011/multimodal_summarization.pdf)
24. **Summarization of Multimodal Information** *Saif Ahmad, Paulo C F de Oliveira, Khurshid Ahmad* `LREC04` [[pdf]](http://www.lrec-conf.org/proceedings/lrec2004/pdf/502.pdf)
25. **Multimodal Summarization of Meeting Recordings** *Berna Erol, Dar-Shyang Lee, and Jonathan Hull* `ICME03` [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.862.6509&rep=rep1&type=pdf)

## Concept-map-based

1. **Fast Concept Mention Grouping for Concept Map–based Multi-Document Summarization** ** `NAACL19` [[pdf]](https://www.aclweb.org/anthology/N19-1074/) [[code]](https://github.com/UKPLab/naacl2019-cmaps-lshcw)
2. **Bringing Structure into Summaries : Crowdsourcing a Benchmark Corpus of Concept Maps** ** `EMNLP17` [[pdf]](https://www.aclweb.org/anthology/D17-1320/) [[code]](https://github.com/UKPLab/emnlp2017-cmapsum-corpus/)

## Timeline

1. **Examining the State-of-the-Art in News Timeline Summarization** *Demian Gholipour Ghalandari, Georgiana Ifrim* `ACL20` [[pdf]](https://arxiv.org/abs/2005.10107) [[code]](https://github.com/complementizer/news-tls)
2. **Learning towards Abstractive Timeline Summarization** *Xiuying Chen, Zhangming Chan, Shen Gao, Meng-Hsuan Yu, Dongyan Zhao, Rui Yan* `IJCAI19` [[pdf]](https://www.ijcai.org/Proceedings/2019/686) [[data]](https://github.com/yingtaomj/Learning-towards-Abstractive-Timeline-Summarization)

## Opinion

1. **Few-Shot Learning for Opinion Summarization** *Arthur Bražinskas, Mirella Lapata, Ivan Titov* `EMNLP20` [[pdf]](https://arxiv.org/abs/2004.14884) [[code]](https://github.com/abrazinskas/FewSum)
2. **Unsupervised Opinion Summarization as Copycat-Review Generation** *Arthur Bražinskas, Mirella Lapata, Ivan Titov* `ACL20` [[pdf]](https://arxiv.org/abs/1911.02247) [[code]](https://github.com/abrazinskas/Copycat-abstractive-opinion-summarizer)
3. **Unsupervised Opinion Summarization with Noising and Denoising** *Reinald Kim Amplayo, Mirella Lapata* `ACL20` [[pdf]](https://arxiv.org/abs/2004.10150) [[code]](https://github.com/rktamplayo/DenoiseSum)
4. **OPINIONDIGEST: A Simple Framework for Opinion Summarization** *Yoshihiko Suhara, Xiaolan Wang, Stefanos Angelidis, Wang-Chiew Tan* `ACL20 Short` [[pdf]](https://arxiv.org/abs/2005.01901) [[code]](https://github.com/megagonlabs/opiniondigest)
5. **Weakly-Supervised Opinion Summarization by Leveraging External Information** *Chao Zhao, Snigdha Chaturvedi* `AAAI20` [[pdf]](https://arxiv.org/abs/1911.09844) [[code]](https://github.com/zhaochaocs/AspMem)
6. **MeanSum: A Neural Model for Unsupervised Multi-Document Abstractive Summarization** *Eric Chu, Peter J. Liu* `ICML19` [[pdf]](https://arxiv.org/abs/1810.05739) [[code]](https://github.com/sosuperic/MeanSum)

## Reinforcement Learning
1. **Answers Unite! Unsupervised Metrics for Reinforced Summarization Models** *Thomas Scialom, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.01610)
2. **Deep Reinforcement Learning with Distributional Semantic Rewards for Abstractive Summarization** *Siyao Li, Deren Lei, Pengda Qin, William Yang Wang* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.00141)
3. **Reinforced Extractive Summarization with Question-Focused Rewards** *Kristjan Arumae, Fei Liu* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-3015/) 
4. **Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting** *Yen-Chun Chen, Mohit Bansal* `ACL18` [[pdf]](https://arxiv.org/abs/1805.11080) [[code]](https://github.com/ChenRocks/fast_abs_rl)
5. **Multi-Reward Reinforced Summarization with Saliency and Entailmen** *Ramakanth Pasunuru, Mohit Bansal* `NAACL18` [[pdf]](https://www.aclweb.org/anthology/N18-2102/) 
6. **Deep Communicating Agents for Abstractive Summarization** *Asli Celikyilmaz, Antoine Bosselut, Xiaodong He, Yejin Choi* `NAACL18` [[pdf]](https://arxiv.org/abs/1803.10357)
7. **Ranking Sentences for Extractive Summarization with Reinforcement Learning** *Shashi Narayan, Shay B. Cohen, Mirella Lapata* `NAACL18` [[pdf]](https://www.aclweb.org/anthology/N18-1158/) [[code]](https://github.com/EdinburghNLP/Refresh)
8. **A Deep Reinforced Model For Abstractive Summarization** *Romain Paulus, Caiming Xiong, Richard Socher* `ICLR18` [[pdf]](https://arxiv.org/abs/1705.04304)

## Reward Learning

1. **Learning to summarize from human feedback** *Nisan Stiennon, Long Ouyang, Jeff Wu, Daniel M. Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei, Paul Christiano* [[pdf]](https://arxiv.org/abs/2009.01325) [[code]](https://github.com/openai/summarize-from-feedback)
2. **Better Rewards Yield Better Summaries: Learning to Summarise Without References** *Florian Böhm, Yang Gao, Christian M. Meyer, Ori Shapira, Ido Dagan, Iryna Gurevych* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.01214) [[code]](https://github.com/yg211/summary-reward-no-reference)

## Controlled
1. **GSum: A General Framework for Guided Neural Abstractive Summarization** *Zi-Yi Dou, Pengfei Liu, Hiroaki Hayashi, Zhengbao Jiang, Graham Neubig* [[pdf]](https://arxiv.org/abs/2010.08014) [[code]](https://github.com/neulab/guided_summarization)
2. **Summarizing Text on Any Aspects: A Knowledge-Informed Weakly-Supervised Approach** *Bowen Tan, Lianhui Qin, Eric P. Xing, Zhiting Hu* `EMNLP20 Short` [[pdf]](https://arxiv.org/abs/2010.06792) [[code]](https://github.com/tanyuqian/aspect-based-summarization)
3. **Length-controllable Abstractive Summarization by Guiding with Summary Prototype** *Itsumi Saito, Kyosuke Nishida, Kosuke Nishida, Atsushi Otsuka, Hisako Asano, Junji Tomita, Hiroyuki Shindo, Yuji Matsumoto* [[pdf]](https://arxiv.org/abs/2001.07331)
4. **Positional Encoding to Control Output Sequence Length** *Sho Takase, Naoaki Okazaki* `NAACL19` [[pdf]](https://www.aclweb.org/anthology/N19-1401/) [[code]](https://github.com/takase/control-length)
5. **Query Focused Abstractive Summarization: Incorporating Query Relevance, Multi-Document Coverage, and Summary Length Constraints into seq2seq Models** *Tal Baumel, Matan Eyal, Michael Elhadad* [[pdf]](https://arxiv.org/abs/1801.07704)
6. **Controllable Abstractive Summarization** *Angela Fan, David Grangier, Michael Auli* `ACL2018 Workshop` [[pdf]](https://arxiv.org/abs/1711.05217)
7. **Controlling Length in Abstractive Summarization Using a Convolutional Neural Network** *Yizhu Liu, Zhiyi Luo, Kenny Zhu* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1444/) [[code]](http://202.120.38.146/sumlen)
8. **Controlling Output Length in Neural Encoder-Decoders** *Yuta Kikuchi, Graham Neubig, Ryohei Sasano, Hiroya Takamura, Manabu Okumura* `EMNLP16` [[pdf]](https://www.aclweb.org/anthology/D16-1140/) [[code]](https://github.com/kiyukuta/lencon)

## Analysis
![](https://img.shields.io/badge/Analysis-analysis-red) ![](https://img.shields.io/badge/Meta%20Evaluation-evaluation-brightgreen) ![](https://img.shields.io/badge/Bias-bias-orange) ![](https://img.shields.io/badge/Architecture-architecture-blue)

1. **Understanding Neural Abstractive Summarization Models via Uncertainty** *Jiacheng Xu, Shrey Desai, Greg Durrett* `EMNLP20 Short` [[pdf]](https://arxiv.org/abs/2010.07882) [[code]](https://github.com/jiacheng-xu/text-sum-uncertainty) ![](https://img.shields.io/badge/-analysis-red)
2. **Re-evaluating Evaluation in Text Summarization** *Manik Bhandari, Pranav Gour, Atabak Ashfaq, Pengfei Liu, Graham Neubig* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.07100) [[code]](https://github.com/neulab/REALSumm) ![](https://img.shields.io/badge/-evaluation-brightgreen)
3. **CDEvalSumm: An Empirical Study of Cross-Dataset Evaluation for Neural Summarization Systems** *Yiran Chen, Pengfei Liu, Ming Zhong, Zi-Yi Dou, Danqing Wang, Xipeng Qiu, Xuanjing Huang* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.05139) [[code]](https://github.com/zide05/CDEvalSumm) ![](https://img.shields.io/badge/-evaluation-brightgreen)
4. **What Have We Achieved on Text Summarization?** *Dandan Huang, Leyang Cui, Sen Yang, Guangsheng Bao, Kun Wang, Jun Xie, Yue Zhang* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.04529) ![](https://img.shields.io/badge/-analysis-red)
5. **Conditional Neural Generation using Sub-Aspect Functions for Extractive News Summarization** *Zhengyuan Liu, Ke Shi, Nancy F. Chen* `Findings of EMNLP20` [[pdf]](https://arxiv.org/abs/2004.13983) ![](https://img.shields.io/badge/-bias-orange)
6. **Extractive Summarization as Text Matching** *Ming Zhong, Pengfei Liu, Yiran Chen, Danqing Wang, Xipeng Qiu, Xuanjing Huang* `ACL20` [[pdf]](https://arxiv.org/abs/2004.08795) [[code]](https://github.com/maszhongming/MatchSum) ![](https://img.shields.io/badge/-architecture-blue) ![](https://img.shields.io/badge/-bias-orange)
7. **Neural Text Summarization: A Critical Evaluation** *Wojciech Kryściński, Nitish Shirish Keskar, Bryan McCann, Caiming Xiong, Richard Socher* `EMNLP19` [[pdf]](https://www.aclweb.org/anthology/D19-1051/) ![](https://img.shields.io/badge/-analysis-red)
8. **Earlier Isn’t Always Better:Sub-aspect Analysis on Corpus and System Biases in Summarization** *Taehee Jung, Dongyeop Kang, Lucas Mentch, Eduard Hovy* `EMNLP19` [[pdf]](https://arxiv.org/abs/1908.11723) [[code]](https://github.com/dykang/biassum) ![](https://img.shields.io/badge/-bias-orange)
9. **A Closer Look at Data Bias in Neural Extractive Summarization Models** *Ming Zhong, Danqing Wang, Pengfei Liu, Xipeng Qiu, Xuanjing Huang* `EMNLP19 Workshop` [[pdf]](https://arxiv.org/abs/1909.13705) ![](https://img.shields.io/badge/-bias-orange)
10. **Countering the Effects of Lead Bias in News Summarization via Multi-Stage Training and Auxiliary Losses** *Matt Grenander, Yue Dong, Jackie Chi Kit Cheung, Annie Louis* `EMNLP19 Short` [[pdf]](https://arxiv.org/abs/1909.04028)  ![](https://img.shields.io/badge/-bias-orange)
11. **Searching for Effective Neural Extractive Summarization: What Works and What's Next** *Ming Zhong, Pengfei Liu, Danqing Wang, Xipeng Qiu, Xuanjing Huang* `ACL19` [[pdf]](https://arxiv.org/abs/1907.03491) [[code]](https://github.com/maszhongming/Effective_Extractive_Summarization) ![](https://img.shields.io/badge/-architecture-blue)
12. **Content Selection in Deep Learning Models of Summarization** *Chris Kedzie, Kathleen McKeown, Hal Daumé III* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1208/) [[code]](https://github.com/kedz/nnsum/tree/emnlp18-release) ![](https://img.shields.io/badge/-architecture-blue)

## Theory
1. **KLearn: Background Knowledge Inference from Summarization Data** *Maxime Peyrard, Robert West* `Findings of EMNLP20` [[pdf]](https://arxiv.org/abs/2010.06213) [[code]](https://github.com/epfl-dlab/KLearn)
2. **A Simple Theoretical Model of Importance for Summarization** *Maxime Peyrard* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1101/)
3. **BottleSum: Unsupervised and Self-supervised Sentence Summarization using the Information Bottleneck Principle** *Peter West, Ari Holtzman, Jan Buys, Yejin Choi* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.07405) [[code]](https://github.com/peterwestuw/BottleSum)

## Extractive
1. **Better Highlighting: Creating Sub-Sentence Summary Highlights** *Sangwoo Cho, Kaiqiang Song, Chen Li, Dong Yu, Hassan Foroosh, Fei Liu* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.10566) [[code]](https://github.com/ucfnlp/better-highlighting)
2. **Summarize, Outline, and Elaborate: Long-Text Generation via Hierarchical Supervision from Extractive Summaries** *Xiaofei Sun, Chun Fan, Zijun Sun, Yuxian Meng, Fei Wu, Jiwei Li* [[pdf]](https://arxiv.org/abs/2010.07074) [[code]]() 
2. **SupMMD: A Sentence Importance Model for Extractive Summarization using Maximum Mean Discrepancy** *Umanga Bista, Alexander Patrick Mathews, Aditya Krishna Menon, Lexing Xie* [[pdf]](https://arxiv.org/abs/2010.02568) [[code]](https://github.com/computationalmedia/supmmd) 
3. **Stepwise Extractive Summarization and Planning with Structured Transformers** *Shashi Narayan, Joshua Maynez, Jakub Adamek, Daniele Pighin, Blaž Bratanič, Ryan McDonald* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.02744) [[code]](https://github.com/google-research/google-research/tree/master/etcsum) 
4. **A Discourse-Aware Neural Extractive Model for Text Summarization** *Jiacheng Xu, Zhe Gan, Yu Cheng, Jingjing Liu* `ACL20` [[pdf]](https://arxiv.org/abs/1910.14142) [[code]](https://github.com/jiacheng-xu/DiscoBERT) 
5. **Reading Like HER: Human Reading Inspired Extractive Summarization** *Ling Luo, Xiang Ao, Yan Song, Feiyang Pan, Min Yang, Qing He* `EMNLP19` [[pdf]](https://www.aclweb.org/anthology/D19-1300/)
6. **DeepChannel: Salience Estimation by Contrastive Learning for Extractive Document Summarization** *Jiaxin Shi, Chen Liang, Lei Hou, Juanzi Li, Zhiyuan Liu, Hanwang Zhang* `AAAI19` [[pdf]](https://arxiv.org/abs/1811.02394) [[code]](https://github.com/lliangchenc/DeepChannel)
6. **Extractive Summarization with SWAP-NET: Sentences and Words from Alternating Pointer Networks** *Aishwarya Jadhav, Vaibhav Rajan* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-1014/)
7. **Neural Document Summarization by Jointly Learning to Score and Select Sentences** *Qingyu Zhou, Nan Yang, Furu Wei, Shaohan Huang, Ming Zhou, Tiejun Zhao* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-1061/)
8. **Neural Latent Extractive Document Summarization** *Xingxing Zhang, Mirella Lapata, Furu Wei, Ming Zhou* `ACL18` [[pdf]](https://www.aclweb.org/anthology/D18-1088/)
9. **Generative Adversarial Network for Abstractive Text Summarization** *Linqing Liu, Yao Lu, Min Yang, Qiang Qu, Jia Zhu, Hongyan Li* `AAAI18` [[pdf]](https://arxiv.org/abs/1711.09357) [[code]](https://github.com/iwangjian/textsum-gan)
10. **Improving Neural Abstractive Document Summarization with Explicit Information Selection Modeling** *Wei Li, Xinyan Xiao, Yajuan Lyu, Yuanzhuo Wang* `EMNLP18`[[pdf]](https://www.aclweb.org/anthology/D18-1205/)
11. **Extractive Summarization Using Multi-Task Learning with Document Classification** *Masaru Isonuma, Toru Fujino, Junichiro Mori, Yutaka Matsuo, Ichiro Sakata* `EMNLP17` [[pdf]](https://www.aclweb.org/anthology/D17-1223/) 
12. **SummaRuNNer: A Recurrent Neural Network based Sequence Model for Extractive Summarization of Documents** *Ramesh Nallapati, Feifei Zhai, Bowen Zhou* `AAAI17` [[pdf]](https://arxiv.org/abs/1611.04230) [[code]](https://github.com/hpzhao/SummaRuNNer)
13. **Text Summarization through Entailment-based Minimum Vertex Cover** *Anand Gupta, Manpreet Kaur, Shachar Mirkin, Adarsh Singh, Aseem Goyal* `ENLG13` [[pdf]](https://www.aclweb.org/anthology/S14-1010/)

## Abstractive
1. **Topic-Aware Abstractive Text Summarization** *Chujie Zheng, Kunpeng Zhang, Harry Jiannan Wang, Ling Fan* [[pdf]](https://arxiv.org/abs/2010.10323) [[code]](https://github.com/taas-www21/taas)
2. **Multi-hop Inference for Question-driven Summarization** *Yang Deng, Wenxuan Zhang, Wai Lam* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.03738)
3. **Quantitative Argument Summarization and Beyond-Cross-Domain Key Point Analysis** *Roy Bar-Haim, Yoav Kantor, Lilach Eden, Roni Friedman, Dan Lahav, Noam Slonim* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.05369) 
4. **Learning to Fuse Sentences with Transformers for Summarization** *Logan Lebanoff, Franck Dernoncourt, Doo Soon Kim, Lidan Wang, Walter Chang, Fei Liu* `EMNLP20 short` [[pdf]](https://arxiv.org/abs/2010.03726) [[code]](https://github.com/ucfnlp/sent-fusion-transformers)
5. **A Cascade Approach to Neural Abstractive Summarization with Content Selection and Fusion** *Logan Lebanoff, Franck Dernoncourt, Doo Soon Kim, Walter Chang, Fei Liu* `AACL20` [[pdf]](https://arxiv.org/abs/2010.03722) [[code]](https://github.com/ucfnlp/cascaded-summ) 
5. **AutoSurvey: Automatic Survey Generation based on a Research Draft** *Hen-Hsen Huang* `IJCAI20` [[pdf]](https://www.ijcai.org/Proceedings/2020/0761.pdf) [[code]](http://www.cs.nccu.edu.tw/~hhhuang/auto_survey/)
6. **Neural Abstractive Summarization with Structural Attention** *Tanya Chowdhury, Sachin Kumar, Tanmoy Chakraborty* `IJCAI20` [[pdf]](https://arxiv.org/abs/2004.09739)
7. **A Unified Model for Financial Event Classification, Detection and Summarization** *Quanzhi Li, Qiong Zhang* `IJCAI20 Special Track on AI in FinTech` [[pdf]](https://www.ijcai.org/Proceedings/2020/644)
8. **Keywords-Guided Abstractive Sentence Summarization** *Haoran Li, Junnan Zhu, Jiajun Zhang, Chengqing Zong, Xiaodong He* `AAAI20` [[pdf]](https://www.researchgate.net/publication/342540794_Keywords-Guided_Abstractive_Sentence_Summarization)
9. **Discriminative Adversarial Search for Abstractive Summarization** *Thomas Scialom, Paul-Alexis Dray, Sylvain Lamprier, Benjamin Piwowarski, Jacopo Staiano* `ICML20` [[pdf]](https://arxiv.org/abs/2002.10375)
10. **Controlling the Amount of Verbatim Copying in Abstractive Summarization** *Kaiqiang Song, Bingqing Wang, Zhe Feng, Liu Ren, Fei Liu* `AAAI20` [[pdf]](https://arxiv.org/abs/1911.10390) [[code]](https://github.com/ucfnlp/control-over-copying)
11. **GRET：Global Representation Enhanced Transformer** *Rongxiang Weng, Haoran Wei, Shujian Huang, Heng Yu, Lidong Bing, Weihua Luo, Jiajun Chen* `AAAI20` [[pdf]](https://arxiv.org/abs/2002.10101)
12. **Abstractive Summarization of Spoken and Written Instructions with BERT** *Alexandra Savelieva, Bryan Au-Yeung, Vasanth Ramani* `KDD Converse 2020` [[pdf]](https://arxiv.org/abs/2008.09676)
13. **Concept Pointer Network for Abstractive Summarization** *Wang Wenbo, Gao Yang, Huang Heyan, Zhou Yuxiang* `EMNLP19` [[pdf]](https://arxiv.org/abs/1910.08486) [[code]](https://github.com/wprojectsn/codes)
14. **Co-opNet: Cooperative Generator–Discriminator Networks for Abstractive Summarization with Narrative Flow** *Saadia Gabriel, Antoine Bosselut, Ari Holtzman, Kyle Lo, Asli Celikyilmaz, Yejin Choi* [[pdf]](https://arxiv.org/abs/1907.01272)
15. **Contrastive Attention Mechanism for Abstractive Sentence Summarization** *Xiangyu Duan, Hongfei Yu, Mingming Yin, Min Zhang, Weihua Luo, Yue Zhang* `EMNLP19` [[pdf]](https://www.aclweb.org/anthology/D19-1301/) [[code]](https://github.com/travel-go/Abstractive-Text-Summarization)
16. **An Entity-Driven Framework for Abstractive Summarization** *Eva Sharma, Luyang Huang, Zhe Hu, Lu Wang* `EMNLP19` [[pdf]](https://arxiv.org/abs/1909.02059) [[code]](https://evasharma.github.io/SENECA/)
17. **Abstract Text Summarization: A Low Resource Challenge** *Shantipriya Parida, Petr Motlicek* `EMNLP19` [[pdf]](https://www.aclweb.org/anthology/D19-1616/) [[code]]()
18. **Attention Optimization for Abstractive Document Summarization** *Min Gui, Junfeng Tian, Rui Wang, Zhenglu Yang* `EMNLP19` [[pdf]](https://arxiv.org/abs/1910.11491) [[code]]()
19. **BiSET: Bi-directional Selective Encoding with Template for Abstractive Summarization** *Kai Wang, Xiaojun Quan, Rui Wang* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1207/) [[code]](https://github.com/InitialBug/BiSET)
20. **Scoring Sentence Singletons and Pairs for Abstractive Summarization** *Logan Lebanoff, Kaiqiang Song, Franck Dernoncourt, Doo Soon Kim, Seokhwan Kim, Walter Chang, Fei Liu* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1209/) [[code]](https://github.com/ucfnlp/summarization-sing-pair-mix)
21. **Inducing Document Structure for Aspect-based Summarization** *Lea Frermann, Alexandre Klementiev* `ACL19` [[pdf]](https://www.aclweb.org/anthology/P19-1630/) [[code]](https://github.com/ColiLea/aspect_based_summarization) 
22. **Generating Summaries with Topic Templates and Structured Convolutional Decoders** *Laura Perez-Beltrachini, Yang Liu, Mirella Lapata* `ACL19` [[pdf]](https://arxiv.org/abs/1906.04687) [[code]](https://github.com/lauhaide/WikiCatSum) 
23. **Improving Abstractive Text Summarization with History Aggregation** *Pengcheng Liao, Chuang Zhang, Xiaojun Chen, Xiaofei Zhou* [[pdf]](https://arxiv.org/abs/1912.11046) [[code]](https://github.com/Pc-liao/Transformer_agg) 
24. **Summary Refinement through Denoising** *Nikola I. Nikolov, Alessandro Calmanovici, Richard H.R. Hahnloser* `RANLP19` [[pdf]](https://arxiv.org/abs/1907.10873) [[code]](https://github.com/ninikolov/summary-denoising) 
25. **Closed-Book Training to Improve Summarization Encoder Memory** *Yichen Jiang, Mohit Bansal* `EMNLP18` [[pdf]](https://arxiv.org/abs/1809.04585)
26. **Improving Neural Abstractive Document Summarization with Structural Regularization** *Wei Li, Xinyan Xiao, Yajuan Lyu, Yuanzhuo Wang* `EMNLP18` [[pdf]](https://www.aclweb.org/anthology/D18-1441/)
26. **Bottom-Up Abstractive Summarization** *Sebastian Gehrmann, Yuntian Deng, Alexander M. Rush* `EMNLP18` [[pdf]](https://arxiv.org/abs/1808.10792) [[code]](https://github.com/sebastianGehrmann/bottom-up-summary) 
27. **A Unified Model for Extractive and Abstractive Summarization using Inconsistency Loss** *Wan-Ting Hsu, Chieh-Kai Lin, Ming-Ying Lee, Kerui Min, Jing Tang, Min Sun* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-1013/)
28. **Soft Layer-Specific Multi-Task Summarization with Entailment and Question Generation** *Han Guo, Ramakanth Pasunuru, Mohit Bansal* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-1064/)
29. **Retrieve, Rerank and Rewrite: Soft Template Based Neural Summarization** *Ziqiang Cao, Wenjie Li, Sujian Li, Furu Wei* `ACL18` [[pdf]](https://www.aclweb.org/anthology/P18-1015/)
30. **Abstractive Document Summarization via Bidirectional Decoder** *Xin WanChen LiRuijia WangDing XiaoChuan Shi* `ADMA18` [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-05090-0_31)
31. **Guiding Generation for Abstractive Text Summarization based on Key Information Guide Network** *Chenliang Li, Weiran Xu, Si Li, Sheng Gao* `NAACL18` [[pdf]](https://www.aclweb.org/anthology/N18-2009/) 
32. **Entity Commonsense Representation for Neural Abstractive Summarization** *Reinald Kim Amplayo, Seonjae Lim, Seung-won Hwang* `NAACL18` [[pdf]](https://www.aclweb.org/anthology/N18-1064/)
33. **Get To The Point: Summarization with Pointer-Generator Networks** *Abigail See, Peter J. Liu, Christopher D. Manning* `ACL17` [[pdf]](https://arxiv.org/abs/1704.04368) [[code]](https://github.com/abisee/pointer-generator) 
34. **Selective Encoding for Abstractive Sentence Summarization** *Qingyu Zhou, Nan Yang, Furu Wei, Ming Zhou* `ACL17` [[pdf]](https://arxiv.org/abs/1704.07073)
35. **Abstractive Document Summarization with a Graph-Based Attentional Neural Model** *Jiwei Tan, Xiaojun Wan, Jianguo Xiao* `ACL17` [[pdf]](https://www.aclweb.org/anthology/P17-1108/)
36. **Deep Recurrent Generative Decoder for Abstractive Text Summarization** *Piji Li, Wai Lam, Lidong Bing, Zihao Wang* `EMNL17` [[pdf]](https://www.aclweb.org/anthology/D17-1222/)
39. **Toward Abstractive Summarization Using Semantic Representations** *Fei Liu, Jeffrey Flanigan, Sam Thomson, Norman Sadeh, Noah A. Smith* `NAACL15` [[pdf]](https://www.aclweb.org/anthology/N15-1114/)
40. **Abstractive Meeting Summarization with Entailment and Fusion** *Yashar Mehdad, Giuseppe Carenini, Frank Tompa, Raymond T. Ng* `ENLG13` [[pdf]](https://www.aclweb.org/anthology/W13-2117/)

## Extractive-Abstractive
1. **On Extractive and Abstractive Neural Document Summarization with Transformer Language Models** *Sandeep Subramanian, Raymond Li, Jonathan Pilault, Christopher Pal* `EMNLP20` [[pdf]](https://arxiv.org/abs/1909.03186) 
2. **Jointly Extracting and Compressing Documents with Summary State Representations** *Afonso Mendes, Shashi Narayan, Sebastião Miranda, Zita Marinho, André F. T. Martins, Shay B. Cohen* `NAACL19` [[pdf]](https://arxiv.org/abs/1904.02020) [[code]](https://github.com/Priberam/exconsumm)

## Syntactic
1. **Compressive Summarization with Plausibility and Salience Modeling** *Shrey Desai, Jiacheng Xu, Greg Durrett* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.07886) [[code]](https://github.com/shreydesai/cups)
2. **StructSum: Incorporating Latent and Explicit Sentence Dependencies for Single Document Summarization** *Vidhisha Balachandran, Artidoro Pagnoni, Jay Yoon Lee, Dheeraj Rajagopal, Jaime Carbonell, Yulia Tsvetkov* `` [[pdf]](https://arxiv.org/abs/2003.00576)
3. **Joint Parsing and Generation for Abstractive Summarization** *Kaiqiang Song, Logan Lebanoff, Qipeng Guo, Xipeng Qiu, Xiangyang Xue, Chen Li, Dong Yu, Fei Liu* `AAAI20` [[pdf]](https://arxiv.org/abs/1911.10389) [[code]](https://github.com/KaiQiangSong/joint_parse_summ)
4. **Neural Extractive Text Summarization with Syntactic Compression** *Jiacheng Xu, Greg Durrett* `EMNLP19` [[pdf]](https://arxiv.org/abs/1902.00863) [[code]](https://github.com/jiacheng-xu/neu-compression-sum)
5. **Single Document Summarization as Tree Induction** *Yang Liu, Ivan Titov, Mirella Lapata* `NAACL19` [[pdf]](https://www.aclweb.org/anthology/N19-1173/) [[code]](https://github.com/nlpyang/SUMO)

## QA Related
1. **Towards Question-Answering as an Automatic Metric for Evaluating the Content Quality of a Summary** *Daniel Deutsch, Tania Bedrax-Weiss, Dan Roth* [[pdf]](https://arxiv.org/abs/2010.00490) [[code]](https://github.com/CogComp/qaeval-experiments)
2. **Guiding Extractive Summarization with Question-Answering Rewards** *Kristjan Arumae, Fei Liu* `NAACL19` [[pdf]](https://arxiv.org/abs/1904.02321) [[code]](https://github.com/ucfnlp/summ_qa_rewards)
3. **A Semantic QA-Based Approach for Text Summarization Evaluation** *Ping Chen, Fei Wu, Tong Wang, Wei Ding* `AAAI18` [[pdf]](https://arxiv.org/abs/1704.06259) 
 
## Evaluation
1. **Unsupervised Reference-Free Summary Quality Evaluation via Contrastive Learning** *Hanlu Wu, Tengfei Ma, Lingfei Wu, Tariro Manyumwa, Shouling Ji* `EMNLP20` [[pdf]](https://arxiv.org/abs/2010.01781) [[code]](https://github.com/whl97/LS-Score)
2. **SacreROUGE: An Open-Source Library for Using and Developing Summarization Evaluation Metrics** *Daniel Deutsch, Dan Roth* [[pdf]](https://arxiv.org/abs/2007.05374) [[code]](https://github.com/danieldeutsch/sacrerouge)
3. **SummEval: Re-evaluating Summarization Evaluation** *Alexander R. Fabbri, Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher, Dragomir Radev* [[pdf]](https://arxiv.org/abs/2007.12626) [[code]](https://github.com/Yale-LILY/SummEval)
4. **HIGHRES: Highlight-based Reference-less Evaluation of Summarization** *Hardy, Shashi Narayan, Andreas Vlachos* `ACL19` [[pdf]](https://arxiv.org/abs/1906.01361) [[code]](https://github.com/sheffieldnlp/highres)

## Toolkit

1. **OpenNMT-py: Open-Source Neural Machine Translation** [[pdf]](https://www.aclweb.org/anthology/W18-1817.pdf) [[code]](https://github.com/OpenNMT/OpenNMT-py)
2. **Fairseq: Facebook AI Research Sequence-to-Sequence Toolkit written in Python.**  [[code]](https://github.com/pytorch/fairseq)
3. **LeafNATS: An Open-Source Toolkit and Live Demo System for Neural Abstractive Text Summarization** *Tian Shi, Ping Wang, Chandan K. Reddy* `NAACL19` [[pdf]](https://www.aclweb.org/anthology/N19-4012/) [[code]](https://github.com/tshi04/LeafNATS)
4. **TransformerSum** [[code]](https://github.com/HHousen/TransformerSum)




