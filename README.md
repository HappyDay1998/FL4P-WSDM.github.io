## FL4P-WSDM

FL4P-WSDM, which stands for Federated Learning for Private Web Search and Data Mining

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Introduction

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

* **Applications in web search and data mining. **Federated learning was originally proposed in 2016. As a novel and generic solution to data insufficiency problem, there will
definitely be much broader use in web search and data mining. Therefore it deserves creating more channels so that the concept can be well introduced to domain practitioners.
The workshop we plan to organize is targeted on the above and other relevant issues, aiming to create a platform for people from academia and industry to communicate their insights and recent results.

## Topics

Specifically, the workshop will focus on the following topics:

* Novel distributed, collaborative and federated learning algorithms design and analysis;
* Novel multi-party secure computing algorithms;
* Social and legislation issues about privacy in web search and data mining;
* Privacy-preserving web search and data mining algorithms and applications;
* Federated learning algorithm applications in web search and data mining;
* Attacks on data privacy in web search and data mining;
* Datasets and open-source tools for federated and privacy preserving web search and data mining.

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HappyDay1998/FL4P-WSDM.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
