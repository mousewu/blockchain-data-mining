# Blockchain Intelligence

This repository lists some interesting reserach work on blockchian data mining and analysis.

## Papers

* ### Overview
  * Blockchain Data Analysis: A Review of Status, Trends and Challenges (Chinese)
    * [[paper]](http://crad.ict.ac.cn/CN/abstract/abstract3762.shtml)
    * This review begins by introducing the architecture and key techniques of blockchain technology and providing the main data types and their characteristics in blockchain with the corresponding analysis methods. Then, the current research progress in blockchain data analysis is summarized in seven research problems, which includes entity recognition, privacy disclosure risk analysis, network portrait, network visualization, market effect analysis, transaction pattern recognition, illegal behavior detection and analysis. Finaly, the directions, prospects and challenges for future research are explored based on the shortcomings of current research.
    
   * Zheng, Zibin, et al. “An overview on smart contracts: Challenges, advances and platforms.” Future Generation Computer Systems 105 (2020): 475-491
     * [[paper]](https://www.sciencedirect.com/science/article/pii/S0167739X19316280)
    
   * Xie, Shaoan, et al. “Blockchain for cloud exchange: A survey.” Computers & Electrical Engineering 81 (2020): 106526
       * [[paper]](https://www.sciencedirect.com/science/article/pii/S0045790618332750)
       
    * Zhou, Qiheng, et al. “Solutions to Scalability of Blockchain: A Survey.” IEEE Access 8 (2020): 16440-16455
       * [[paper]](https://ieeexplore.ieee.org/abstract/document/8962150/)
    
     * Dai, Hong-Ning, Zibin Zheng, and Yan Zhang. “Blockchain for internet of things: A survey.” IEEE Internet of Things Journal 6.5 (2019): 8076-8094
       * [[paper]](https://ieeexplore.ieee.org/abstract/document/8731639/)
       
     * Zheng, Zibin, et al. “Blockchain challenges and opportunities: A survey.” International Journal of Web and Grid Services 14.4 (2018): 352-375
       * [[paper]](https://www.researchgate.net/profile/Hong-Ning_Dai/publication/328271018_Blockchain_challenges_and_opportunities_a_survey/links/5bd2706f92851c6b278f31eb/Blockchain-challenges-and-opportunities-a-survey.pdf) 
       
     * Zheng, Zibin, et al. “An overview of blockchain technology: Architecture, consensus, and future trends.” 2017 IEEE international congress on big data (BigData congress). IEEE, 2017
       * [[paper]](https://ieeexplore.ieee.org/abstract/document/8029379/)
       
     * Huang, Huawei, et al. “When Blockchain Meets Distributed File Systems: An Overview, Challenges, and Open Issues.” IEEE Access 8 (2020): 50574-50586
       * [[paper]](https://ieeexplore.ieee.org/document/9031420)
       
     * Huang, Huawei, et al. “A Survey of State-of-the-Art on Blockchains: Theories, Modelings, and Tools.” 2020
       * [[paper]]( http://arxiv.org/abs/2007.03520)

* ### Network Embedding
  * T-EDGE: Temporal WEighted MultiDiGraph Embedding for Ethereum Transaction Network Analysis
    * [[paper]](https://arxiv.org/abs/1905.08038)  
    * This paper considers temporal characteristics and transfer values of Ethereum transaction network, which includes temporal & weight bias in random walk sampling.
    
* ### Graph Analysis
  * Market Manipulation of Bitcoin: Evidence from Mining the Mt. Gox Transaction Network
    * [[paper]](https://arxiv.org/abs/1902.01941)
    * This paper conducts a systematic study to analyze the leaked Mt. Gox transaction data through graph analysis. They divide the accounts into three categories, extreme high account (EHA), extreme low account (ELA), and normal account (NMA) and  construct three subgraphs based on these accounts and their transactions, respectively. In order to reveal the relationship between market manipulation behaviors and the Bitcoin price, the graphs are reconstructed into daily graph series and reshaped into matrices. Through adopting SVD to the matrices, 10 very important base networks are identiﬁed. By inspecting the base networks, they ﬁnd that the daily variation of the abnormal base networks closely related to the Bitcoin price and many market manipulation patterns.
  
* ### AML
  * Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics 
     * [[paper]](https://arxiv.org/abs/1908.02591)
     * This paper contributes the Elliptic Data Set, a time series graph of over 200K Bitcoin transactions (nodes), 234K directed payment flows (edges), and 166 node features and shares results from a binary classification task predicting illicit transactions using variations of Logistic Regression (LR), Random Forest (RF), Multilayer Perceptrons (MLP), and Graph Convolutional Networks (GCN), with GCN being of special interest as an emergent new method for capturing relational information. The results show the superiority of Random Forest (RF), but also invite algorithmic work to combine the respective powers of RF and graph methods.
   
   * An Inquiry into Money Laundering Tools in the Bitcoin Ecosystem 
     * [[paper]](https://maltemoeser.de/paper/money-laundering.pdf)
     * This paper investigates multiple bitcoin mixing services by sending and withdrawing bitcoins to/from these services and analyzing on-chain transaction graphs.

* ### Platform
  * BITSCOPE: Scaling Bitcoin Address De-anonymization using Multi-Resolution Clustering
    * [[paper]](https://izgzhen.github.io/bitscope-public/paper.pdf)
    * This paper proposes BITSCOPE, a de-anonymization system framework that uses a layered approach and exploits the domain-speciﬁc structures in Bitcoin transaction network.
