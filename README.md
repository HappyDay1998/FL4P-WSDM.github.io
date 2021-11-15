## FL4P-WSDM
![avatar](C:/Desktop/Page.png)
FL4P-WSDM, which stands for Federated Learning for Private Web Search and Data Mining

<div align='center' ><font size='120'>Introduction</font></div>

<font face="Droid Serif">Using data from multiple parties is becoming popular in AI model learning. The algorithm research serving this purpose is known as
federated learning, which has received increasing attention from both academic and industry. As a generic solution to data insufficiency, federated learning has demonstrated high potential in numerous web search and data mining problems. Moreover, the widespread data use in web search and data mining services and products has aroused concern on data privacy protection. Therefore, we propose to organize a workshop discussing the relevant issues. In this proposal we introduce the detail of the workshop motivation, topics, rational, format, and organizers’ information.

We propose to organize this Federated and Privacy-Preserving Web Search and Data Mining: Theories, Algorithms and Applications Workshop, aiming to gather the academic and industry community together to tackle the theory, algorithm and application issues of using decentralized data in web search and data mining applications.</font>

#### Motivation

AI services have been ubiquitous in web search and data mining applications. The accuracy, generalization and robustness of an AI model heavily rely on learning from sufficient training data. However, in many cases, the data owned by one individual AI practitioner is insufficient to train a high-performance model. For example, one healthcare institution typically only has the clinical data collected from the local patients, leading to potential model bias if only local data is used for model training. As another example, one individual or business organization usually has multiple accounts in different financial agencies. The fraud detection model can not make accurate predictions if financial transaction data from only one bank is used for training and inference. Recently, there are extensive efforts from both academia and industry dedicated to tackling the above challenges. One prominent branch is generally known as collaborative learning or federated learning. The main theme is to utilize data from multiple parties for model learning and prediction. In the past few years we have seen an explosive number of research publications relevant to these topics, and several pioneering industry deployments that apply the relevant technologies such as personalized Siri service in Apple’s iOS 13 and next word prediction function in Google’s Gboard. Despite the encouraging progress, there are still several significant research questions which have not been completely addressed, including but not limited to the following points.

* **Data privacy.** Privacy is viewed as an essential human right. The widespread use of personal data in AI services and products has aroused increasing concerns for user privacy and data ownership violation. This concern is even more serious towards multi-party computing applications. There have been increasing legislation endeavors on data privacy protection, e.g. European Union General Data Protection Regulation and California Consumer Privacy Act. Every data use for AI purpose is also subject to these regulations.

* **Data statistical heterogeneity.** Traditional multi-machine learning algorithms, e.g. distributed machine learning generally assumes the training data is independently and identically distributed on the involved data centers or machines, but such assumption may not be effective in collaborative and federated learning. The non-iid data distribution scenario has inspired extensive research attention in algorithm design and algorithm property analysis.

* **Algorithm communication efficiency.** The time cost of a federated learning algorithm mainly comes from on-device computation and inter-device communication. Compared to
the well-studied single-machine model training speedup solutions like efficient optimization algorithms and high-speed hardwares, inter-device communication is more prone to be
a bottleneck for deploying a federated learning algorithm. How to deal with the communication efficiency issues such as network or participant delay, especially when there are
a huge number of involved devices, needs further research efforts.

* **Applications in web search and data mining.** Federated learning was originally proposed in 2016. As a novel and generic solution to data insufficiency problem, there will
definitely be much broader use in web search and data mining. Therefore it deserves creating more channels so that the concept can be well introduced to domain practitioners.
The workshop we plan to organize is targeted on the above and other relevant issues, aiming to create a platform for people from academia and industry to communicate their insights and recent results.

### Topics

Specifically, the workshop will focus on the following topics:

* Novel distributed, collaborative and federated learning algorithms design and analysis;
* Novel multi-party secure computing algorithms;
* Social and legislation issues about privacy in web search and data mining;
* Privacy-preserving web search and data mining algorithms and applications;
* Federated learning algorithm applications in web search and data mining;
* Attacks on data privacy in web search and data mining;
* Datasets and open-source tools for federated and privacy preserving web search and data mining.

### Previous similar workshops
Workshops with similar topics have been seen in recent AI and machine learning conferences. We list part of them as follows.

* NIPS 2020: International Workshop on Scalability, Privacy, and Security in Federated Learning
* ICML 2020: International Workshop on Federated Learning for User Privacy and Data Confidentiality
* AAAI 2020: The AAAI Workshop on Privacy-Preserving Artificial Intelligence
* ICML 2021: International Workshop on Federated Learning for User Privacy and Data Confidentiality
* CIKM 2021: International Workshop on Privacy, Security and Trust in Computational Intelligence
* IJCAI 2021: International Workshop on Federated and Transfer Learning for Data Sparsity and Confidentiality
The major difference between our proposal and these previous workshops is that we will focus on web search and data mining related problems, which is consistent with the theme of the conference.


## Target audience
The targeted audience of the workshop include web search and data mining practitioners from both academia and industry, whose research interest is relevant to multi-machine or federated learning algorithm and data privacy protection. We expect to have 50 participants including organizers, keynote speakers, paper authors and audiences.

## Schedule
08:45AM-09:00AM   &ensp; Opening

09:00AM-09:45AM  &ensp; Keynote Talk 1

09:45AM-10:00AM   &ensp; Coffee Break

10:00AM-10:45AM  &ensp; Keynote Talk 2

10:45AM-11:00AM   &ensp; Coffee Break

11:00AM-11:45AM  &ensp; Keynote Talk 3

11:45AM-12:45PM  &ensp; Lunch Break

12:45PM-01:45PM   &ensp; Panel Seesion

01:45PM-02:00PM  &ensp; Concluding Remarks

##  Preliminary format of the workshop
We plan to organize a half-day workshop, consisting of keynote presentations, paper presentations and a panel discussion.
### Keynote Presentations

For the keynote presentation track, we will invite domain experts from both industry and academia. Each speaker will give a 40-minute talk about their recent work and insights on future directions. The following speakers have confirmed that they will give keynote presentations.
* Dr. Liefeng Bo, Director, JD Technology Silicon Valley R&D Lab;
* Dr. Ameet Talwalkar, Assistant Professor, Carnegie Mellon University;
* Dr. Mehrdad Mahdavi, Assistant Professor, Pennsylvania State University

### Paper track
For the paper track, we will assign 3 reviewers to each paper submission. Authors of each accepted paper will be invited to give a 10-minute presentation, introducing the work of their paper. The following domain experts have confirmed to serve as technical committee members.
* Dr. Mingchen Gao, Assistant Professor, Department of Computer Science and Engineering, University at Buffalo, SUNY;
* Dr. Minqing Chen, Staff Scientist, Google Brain;
* Dr. Yanqing Chen, Principal Scientist, JD Technology Silicon Valley R&D Lab;
* Dr. Yuncong Chen, Research Staff Member, NEC Labs America;
* Dr. Caiwen Ding, Assistant Professor, University of Connecticut;
* Mr. Wei Zhu, PhD Student, University of Rochester;
* Dr. Yao Zhou, Machine Learning Engineer, Instacart;
* Dr. Chenglin Miao, Assistant Professor, Department of Computer Science, University of Georgia;
* Dr. Jinghui Chen, Assistant Professor, College of Information Sciences and Technology, Pennsylvania State University.

###  Panel Discussion
At the end of the workshop there will be a 30-minute panel discussion between keynote speakers and workshop attendees. The workshop organizers will host the discussion.
## Organizers

* **Dr. Bo Liu** is a Senior Research Scientist in JD Technology Silicon Valley R&D Lab. He obtained his PhD degree from the Department of Computer Science at Rutgers University in 2018. Currently he focuses on federated learning and privacy-preserving computing research and product development. He has published over 50 conference and journal papers in machine learning and its applications, such as JMLR, ICML, AISTATS, AAAI, IJCAI, CIKM etc.. His group has recently released an open source privacy-preserving machine learning tool FedLearn-Algo <https://github.com/fedlearnAI/fedlearnalgo>.

<img src="https://scholar.googleusercontent.com/citations?view_op=view_photo&user=2Fe93n8AAAAJ&citpid=2" width = "500" height = "500" alt="Bo Liu" align=center />

* **Dr. Dongjin Song** is an assistant professor in the Department of Computer Science and Engineering at the University of Connecticut. Before that, he had been a research staff member at NEC Labs America and obtained his Ph.D. degree from the Department of Electrical and Computer Engineering at University of California,San Diego (UCSD) in 2016. His research interests include machine learning, data mining, federated learning, and related applications for time series data analysis as well as graph representation learning. He has published over 40 papers in top-tier data mining and artificial intelligence conferences, such as KDD, ICDM, SDM, ICML, ICLR, AAAI, IJCAI, ICCV, etc. He has served as Senior PC for AAAI, IJCAI,and CIKM. His personal website is: <https://songdj.github.io/>.


<img src="https://songdj.github.io/author/dongjin-song/avatar%202_huadb1ab2f651eaef92367682ab67b1646_2874891_270x270_fill_lanczos_center_2.png" width = "500" height = "500" alt="Dongjin Song" align=center />


* **Dr. Fenglong Ma** is currently an assistant professor in the College of Information Sciences and Technology at the Pennsylvania State University. He received his Ph.D. from the Department of Computer Science and Engineering, University at Buffalo (UB) in 2019. His research interests lie in data mining and machine learning, with an emphasis on mining health-related data. His research interests also include federated learning, natural language processing, social network mining and security. He has published over 70 papers in top conferences and journals such as KDD, WWW, WSDM, CIKM, ACL, AAAI, IJCAI, S&P, and TKDE. More information can be found at his website: <http://personal.psu.edu/ffm5105/>.


<img src="https://ist.psu.edu/sites/default/files/directory/Ma-Fenglong.jpg" width = "500" height = "500" alt="Fenglong Ma" align=center />

* **Dr. Heng Huang** is the John A. Jurenko Endowed Professor at the Department of Electrical and Computer Engineering, University of Pittsburgh. Dr. Huang has published more than 130 papers in top-tier conferences and many papers in premium journals such as NIPS, ICML, KDD, RECOMB, ISMB, IJCAI, AAAI, CVPR, ICCV, SIGIR, Bioinformatics, IEEE Trans. On Medical Imaging, Medical Image Analysis, IEEE TKDE, and others. As principal investigator, is leading a National Institutes of Health-funded R01 project on imaging genomics based complex brain disorder study, multiple NSF-funded projects on precision medicine, biomedical data science, big data mining, electronic medical record data mining and
privacy-preserving, computational biology, smart healthcare, cyber physical systems, and also industry-funded projects on computational sustainability, smart metering, and smart grids.

<img src="https://sites.pitt.edu/~heh45/heng.JPG" width = "500" height = "500" alt="Heng Huang" align=center />

## Previous academic events organizations
**Dr. Dongjin Song** has served as session chair in the following conferences:
* KDD 2021: Graphs and Networks
* SDM 2021: Time Series Analysis
* ICDM 2020: E-Learning and E-Commerce
* AAAI 2019: Transfer/Adaptation/Multitask Learning
* AAAI 2019: Vision and Video Analysis

**Dr. Fenglong Ma** gave tutorials in the following conferences:
* KDD 2021: Advances in Mining Heterogeneous Healthcare Data
* WSDM 2020: Learning with Small Data
* KDD 2019: Optimize the Wisdom of the Crowd: Inference, Learning, and Teaching

**Dr. Heng Huang** has served as the Program Co-Chair of ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD) 2020, General Co-Chair of International Workshop on Federated and Transfer Learning for Data Sparsity and Confidentiality in Conjunction with IJCAI 2021 (FTL-IJCAI’21),Senior Area Chair of International Joint Conference on Artificial Intelligence (IJCAI) 2018-2021, Senior Area Chair of AAAI Conference on Artificial Intelligence (AAAI) 2019-2021, Imaging Genomics Track Chair of Pacific Symposium on Biocomputing (PSB) 2018, Chair of Third International Workshop on Multimodal Brain Image Analysis 2013, Registration Chair of IEEE International Conference on Data Mining (ICDM) 2013, Program Chair of International Conference on Pervasive Technologies Related to Assistive Environments 2009, Co-Chairs of International Joint Conferences on Bioinformatics, Systems Biology and Intelligent Computing 2009, Organizing Chair of IEEE International Symposium on Bioinformatics & Bioengineering 2007.
