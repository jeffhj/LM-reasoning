# Reasoning in Large Language Models

[![Awesome](https://awesome.re/badge.svg)](https://github.com/jeffhj/LM-reasoning) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

This repository contains a collection of papers and resources on ***Reasoning in Large Language Models***.

For more details, please refer to [Towards Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2212.10403)

>Feel free to let me know the missing papers (issue or pull request).



Contributor: [Jie Huang](https://jeffhj.github.io/) @UIUC

Thank [Kevin Chen-Chuan Chang](https://cs.illinois.edu/about/people/faculty/kcchang) @UIUC, [Jason Wei](https://www.jasonwei.net/) @Google Brain, [Denny Zhou](https://dennyzhou.github.io/) @Google Brain for insightful discussions and suggestions.



## Contents

- [Survey](#survey)
- [Relevant Survey & Position Paper & Blog](#relevant-survey-and-position-paper-and-blog)
- [Technique](#technique)
  * [Fully Supervised Finetuning](#fully-supervised-finetuning)
  * [Prompting & In-Context Learning](#prompting-and-in-context-learning)
  * [Hybrid Method](#hybrid-method)
- [Evaluation & Analysis](#evaluation-and-analysis)



## Survey

#### [Towards Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2212.10403)	*20 Dec 2022*

Jie Huang, Kevin Chen-Chuan Chang



## Relevant Survey and Position Paper and Blog

#### [Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682)	*15 Jun 2022*

Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus

#### [Language Model Cascades](https://arxiv.org/abs/2207.10342)	*21 Jul 2022*

David Dohan, Winnie Xu, Aitor Lewkowycz, Jacob Austin, David Bieber, Raphael Gontijo Lopes, Yuhuai Wu, Henryk Michalewski, Rif A. Saurous, Jascha Sohl-dickstein, Kevin Murphy, Charles Sutton

#### [How does GPT Obtain its Ability? Tracing Emergent Abilities of Language Models to their Sources](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1)	 *11 Dec 2022*

Yao Fu, Hao Peng, Tushar Shot

#### [Reasoning with Language Model Prompting: A Survey](https://arxiv.org/abs/2212.09597)	 *19 Dec 2022*

Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen

#### [A Survey of Deep Learning for Mathematical Reasoning](https://arxiv.org/abs/2212.10535)	*20 Dec 2022*

Pan Lu, Liang Qiu, Wenhao Yu, Sean Welleck, Kai-Wei Chang

#### [A Survey for In-context Learning](https://arxiv.org/abs/2301.00234)	*31 Dec 2022*

Qingxiu Dong, Lei Li, Damai Dai, Ce Zheng, Zhiyong Wu, Baobao Chang, Xu Sun, Jingjing Xu, Lei Li, Zhifang Sui

#### [Logical Reasoning over Natural Language as Knowledge Representation: A Survey](https://arxiv.org/abs/2303.12023) *21 Mar 2023*

Zonglin Yang, Xinya Du, Rui Mao, Jinjie Ni, Erik Cambria

#### [Nature Language Reasoning, A Survey](https://arxiv.org/abs/2303.14725) *26 Mar 2023*

Fei Yu, Hongbo Zhang, Benyou Wang



## Technique

### Fully Supervised Finetuning

> We mainly focus on techniques that are applicable to improving or eliciting "reasoning" in *large* language models like GPT-3 (175B)

> Papers in this paradigm vary a lot and are usually based on *small* models trained on specific datasets. We list several papers here for reference (that is, the list is not complete). Please refer to [our survey](https://arxiv.org/abs/2212.10403) for some discussion.

#### [Explain Yourself! Leveraging Language Models for Commonsense Reasoning](https://arxiv.org/abs/1906.02361)	*6 Jun 2019*

Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher

#### [Leap-Of-Thought: Teaching Pre-Trained Models to Systematically Reason Over Implicit Knowledge](https://arxiv.org/abs/2006.06609)	*11 Jun 2020*

Alon Talmor, Oyvind Tafjord, Peter Clark, Yoav Goldberg, Jonathan Berant

#### [Measuring Mathematical Problem Solving With the MATH Dataset](https://arxiv.org/abs/2103.03874)	*5 Mar 2021*

Dan Hendrycks, Collin Burns, Saurav Kadavath, Akul Arora, Steven Basart, Eric Tang, Dawn Song, Jacob Steinhardt

#### [Show Your Work: Scratchpads for Intermediate Computation with Language Models](https://arxiv.org/abs/2112.00114)	*30 Nov 2021*

Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena

#### [FaiRR: Faithful and Robust Deductive Reasoning over Natural Language](https://arxiv.org/abs/2203.10261)	*19 Mar 2022*

Soumya Sanyal, Harman Singh, Xiang Ren

#### ......



### Prompting and In-Context Learning

#### Chain of Thought Prompting and Its Variants/Applications

#### [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)	*28 Jan 2022*

Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou

#### [Iteratively Prompt Pre-trained Language Models for Chain of Thought](https://arxiv.org/abs/2203.08383)	*16 Mar 2022*

Boshi Wang, Xiang Deng, Huan Sun

#### [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916)	*24 May 2022*

Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa

#### [Psychologically-informed chain-of-thought prompts for metaphor understanding in large language models](https://arxiv.org/abs/2209.08141)	*16 Sep 2022*

Ben Prystawski, Paul Thibodeau, Noah Goodman

#### [Language Models are Multilingual Chain-of-Thought Reasoners](https://arxiv.org/abs/2210.03057)	*6 Oct 2022*

Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei

#### [Large Language Models are few(1)-shot Table Reasoners](https://arxiv.org/abs/2210.06710)	*13 Oct 2022*

Wenhu Chen

#### [Language Models of Code are Few-Shot Commonsense Learners](https://arxiv.org/abs/2210.07128) *13 Oct 2022*

Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig

#### [PaL: Program-Aided Language Model](https://arxiv.org/abs/2211.10435) *18 Nov 2022*

Luyu Gao*, Aman Madaan*, Shuyan Zhou*, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig

#### [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/abs/2211.12588)	*22 Nov 2022*

Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen

#### [Rethinking with Retrieval: Faithful Large Language Model Inference](https://arxiv.org/abs/2301.00303)	*31 Dec 2022*

Hangfeng He, Hongming Zhang, Dan Roth

#### Rationale Engineering

#### [Training Verifiers to Solve Math Word Problems](https://arxiv.org/abs/2110.14168)	*27 Oct 2021*

Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman

#### [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)	*21 Mar 2022*

Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou

#### [On the Advance of Making Language Models Better Reasoners](https://arxiv.org/abs/2206.02336)	*6 Jun 2022*

Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen

#### [Complexity-Based Prompting for Multi-Step Reasoning](https://arxiv.org/abs/2210.00720)	*3 Oct 2022*

Yao Fu, Hao Peng, Ashish Sabharwal, Peter Clark, Tushar Khot

#### [Automatic Chain of Thought Prompting in Large Language Models](https://arxiv.org/abs/2210.03493)	*7 Oct 2022*

Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola

#### [Teaching Algorithmic Reasoning via In-context Learning](https://arxiv.org/abs/2211.09066)	*15 Nov 2022*

Hattie Zhou, Azade Nova, Hugo Larochelle, Aaron Courville, Behnam Neyshabur, Hanie Sedghi

#### [Large Language Models are reasoners with Self-Verification](https://arxiv.org/abs/2212.09561)	*19 Dec 2022*

Yixuan Weng, Minjun Zhu, Shizhu He, Kang Liu, Jun Zhao

#### Problem Decomposition

#### [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625)	*21 May 2022*

Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi

#### [Compositional Semantic Parsing with Large Language Models](https://arxiv.org/abs/2209.15003)	*29 Sep 2022*

Andrew Drozdov, Nathanael Schärli, Ekin Akyürek, Nathan Scales, Xinying Song, Xinyun Chen, Olivier Bousquet, Denny Zhou

#### [Decomposed Prompting: A Modular Approach for Solving Complex Tasks](https://arxiv.org/abs/2210.02406)	*5 Oct 2022*

Tushar Khot, Harsh Trivedi, Matthew Finlayson, Yao Fu, Kyle Richardson, Peter Clark, Ashish Sabharwal

#### [Measuring and Narrowing the Compositionality Gap in Language Models](https://arxiv.org/abs/2210.03350)	*7 Oct 2022*

Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis

#### [Successive Prompting for Decomposing Complex Questions](https://arxiv.org/abs/2212.04092)	*8 Dec 2022*

Dheeru Dua, Shivanshu Gupta, Sameer Singh, Matt Gardner

#### [Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning](https://arxiv.org/abs/2301.13808)	*31 Jan 2023*

Yunhu Ye, Binyuan Hui, Min Yang, Binhua Li, Fei Huang, Yongbin Li



#### Others

#### [Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents](https://arxiv.org/abs/2201.07207)	*18 Jan 2022*

Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch

#### [Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning](https://arxiv.org/abs/2205.09712)	*19 May 2022*

Antonia Creswell, Murray Shanahan, Irina Higgins

#### [Maieutic Prompting: Logically Consistent Reasoning with Recursive Explanations](https://arxiv.org/abs/2205.11822)	*24 May 2022*

Jaehun Jung, Lianhui Qin, Sean Welleck, Faeze Brahman, Chandra Bhagavatula, Ronan Le Bras, Yejin Choi

#### [Faithful Reasoning Using Large Language Models](https://arxiv.org/abs/2208.14271)	*30 Aug 2022*

Antonia Creswell, Murray Shanahan

#### [Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering](https://arxiv.org/abs/2209.09513)	*20 Sep 2022*

Pan Lu, Swaroop Mishra, Tony Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, Ashwin Kalyan

#### [Explanations from Large Language Models Make Small Reasoners Better](https://arxiv.org/abs/2210.06726)	*13 Oct 2022*

Shiyang Li, Jianshu Chen, Yelong Shen, Zhiyu Chen, Xinlu Zhang, Zekun Li, Hong Wang, Jing Qian, Baolin Peng, Yi Mao, Wenhu Chen, Xifeng Yan

#### [Distilling Multi-Step Reasoning Capabilities of Large Language Models into Smaller Models via Semantic Decompositions](https://arxiv.org/abs/2212.00193)	*1 Dec 2022*

Kumar Shridhar, Alessandro Stolfo, Mrinmaya Sachan

#### [Teaching Small Language Models to Reason](https://arxiv.org/abs/2212.08410)	*16 Dec 2022*

Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn

#### [LAMBADA: Backward Chaining for Automated Reasoning in Natural Language](https://arxiv.org/abs/2212.13894)	*20 Dec 2022*

Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran

#### [Reasoning with Language Model is Planning with World Model](https://arxiv.org/abs/2305.14992) *24 May 2023*

Shibo Hao, Yi Gu, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu



### Hybrid Method

#### Reasoning-Enhanced Training and Prompting

#### [Reasoning Like Program Executors](https://arxiv.org/abs/2201.11473)	*27 Jan 2022*

Xinyu Pi, Qian Liu, Bei Chen, Morteza Ziyadi, Zeqi Lin, Qiang Fu, Yan Gao, Jian-Guang Lou, Weizhu Chen

#### [Solving Quantitative Reasoning Problems with Language Models](https://arxiv.org/abs/2206.14858)	*29 Jun 2022*

Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra

#### [Exploring Length Generalization in Large Language Models](https://arxiv.org/abs/2207.04901)	*11 Jul 2022*

Cem Anil, Yuhuai Wu, Anders Andreassen, Aitor Lewkowycz, Vedant Misra, Vinay Ramasesh, Ambrose Slone, Guy Gur-Ari, Ethan Dyer, Behnam Neyshabur

#### [Scaling Instruction-Finetuned Language Models](https://arxiv.org/abs/2210.11416)	*20 Oct 2022*

Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Yunxuan Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Alex Castro-Ros, Marie Pellat, Kevin Robinson, Dasha Valter, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei

#### [Galactica: A Large Language Model for Science](https://arxiv.org/abs/2211.09085)	*16 Nov 2022*

Ross Taylor, Marcin Kardas, Guillem Cucurull, Thomas Scialom, Anthony Hartshorn, Elvis Saravia, Andrew Poulton, Viktor Kerkez, Robert Stojnic

#### [ALERT: Adapting Language Models to Reasoning Tasks](https://arxiv.org/abs/2212.08286)	*16 Dec 2022*

Ping Yu, Tianlu Wang, Olga Golovneva, Badr Alkhamissy, Gargi Ghosh, Mona Diab, Asli Celikyilmaz

#### Bootstrapping and Self-Improving

#### [STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465)	*28 Mar 2022*

Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman

#### [Language Models Can Teach Themselves to Program Better](https://arxiv.org/abs/2207.14502)	*29 Jul 2022*

Patrick Haluptzok, Matthew Bowers, Adam Tauman Kalai

#### [Large Language Models Can Self-Improve](https://arxiv.org/abs/2210.11610)	*20 Oct 2022*

Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han



## Evaluation and Analysis

#### [Are NLP Models really able to Solve Simple Math Word Problems?](https://arxiv.org/abs/2103.07191)	*12 Mar 2021*

Arkil Patel, Satwik Bhattamishra, Navin Goyal

#### [Impact of Pretraining Term Frequencies on Few-Shot Reasoning](https://arxiv.org/abs/2202.07206)	*15 Feb 2022*

Yasaman Razeghi, Robert L. Logan IV, Matt Gardner, Sameer Singh

#### [Are Large Pre-Trained Language Models Leaking Your Personal Information?](https://arxiv.org/abs/2205.12628)	*25 May 2022*

Jie Huang, Hanyin Shao, Kevin Chen-Chuan Chang

#### [Large Language Models Still Can't Plan (A Benchmark for LLMs on Planning and Reasoning about Change)](https://arxiv.org/abs/2206.10498)	*21 Jun 2022*

Karthik Valmeekam, Alberto Olmo, Sarath Sreedharan, Subbarao Kambhampati

#### [Exploring Length Generalization in Large Language Models](https://arxiv.org/abs/2207.04901)	*11 Jul 2022*

Cem Anil, Yuhuai Wu, Anders Andreassen, Aitor Lewkowycz, Vedant Misra, Vinay Ramasesh, Ambrose Slone, Guy Gur-Ari, Ethan Dyer, Behnam Neyshabur

#### [Language models show human-like content effects on reasoning](https://arxiv.org/abs/2207.07051)	*14 Jul 2022*

Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill

#### [FOLIO: Natural Language Reasoning with First-Order Logic](https://arxiv.org/abs/2209.00840)	*2 Sep 2022*

Simeng Han, Hailey Schoelkopf, Yilun Zhao, Zhenting Qi, Martin Riddell, Luke Benson, Lucy Sun, Ekaterina Zubova, Yujie Qiao, Matthew Burtell, David Peng, Jonathan Fan, Yixin Liu, Brian Wong, Malcolm Sailor, Ansong Ni, Linyong Nan, Jungo Kasai, Tao Yu, Rui Zhang, Shafiq Joty, Alexander R. Fabbri, Wojciech Kryscinski, Xi Victoria Lin, Caiming Xiong, Dragomir Radev

#### [Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought](https://arxiv.org/abs/2210.01240)	*3 Oct 2022*

Abulhair Saparov, He He

#### [Challenging BIG-Bench Tasks and Whether Chain-of-Thought Can Solve Them](https://arxiv.org/abs/2210.09261)	*17 Oct 2022*

Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei

#### [Large language models are not zero-shot communicators](https://arxiv.org/abs/2210.14986)	*26 Oct 2022*

Laura Ruis, Akbir Khan, Stella Biderman, Sara Hooker, Tim Rocktäschel, Edward Grefenstette

#### [ROSCOE: A Suite of Metrics for Scoring Step-by-Step Reasoning](https://arxiv.org/abs/2212.07919)	*15 Dec 2022*

Olga Golovneva, Moya Chen, Spencer Poff, Martin Corredor, Luke Zettlemoyer, Maryam Fazel-Zarandi, Asli Celikyilmaz

#### [Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters](https://arxiv.org/abs/2212.10001)	*20 Dec 2022*

Boshi Wang, Sewon Min, Xiang Deng, Jiaming Shen, You Wu, Luke Zettlemoyer, Huan Sun



## Citation

If you find this repo useful, please kindly cite our survey:

```
@article{huang2022towards,
  title={Towards Reasoning in Large Language Models: A Survey},
  author={Huang, Jie and Chang, Kevin Chen-Chuan},
  journal={arXiv preprint arXiv:2212.10403},
  year={2022}
}
```
