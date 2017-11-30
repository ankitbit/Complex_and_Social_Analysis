1. Prediction of link crossings in syntactic dependency trees (this project has also been submitted as Master Thesis proposal for MIRI-Data Science and therefore could be continued as master thesis) 

The syntactic structure of a sentence can be specified as a directed tree where vertices are words and arcs indicate syntactic dependencies. When arcs are drawn above the sentence, arcs tend to not cross in languages. This phenomenon is intimately related to the computational complexity of languages (the so-called mild-context sensitivity) but an explanation has been elusive. Recently, it has been hypothesized that the scarcity of these crossings could be a side-effect of cognitive pressure to reduce the length of arcs, namely the distance between linked words in the sentence, thus proposing a causal link between cognitive constraints and the computational complexity of languages. In this project, we aim to provide further support to this hypothesis proposing and evaluating new predictors of crossings that exploit minimal information about the length of arcs and the structure of the tree. The new predictors will be tested using a collection of dependency treebanks from 30 different languages. A dependency treebank is a collection of sentences of a given language where the syntactic dependency tree of each sentence has been specified. 
The supervisor has his own proposal of new predictors but he is totally open to proposals by the student.  
   
Recommended reading: Gómez-Rodríguez, C. & Ferrer-i-Cancho, R. (2017). Scarcity of crossing dependencies: A direct outcome of a specific constraint? Physical Review E, in press. https://arxiv.org/abs/1601.03210


2. Model selection of <k^2> in syntactic dependency trees. This project is an advanced version of lab 4 (Non-linear regression on dependency trees) on <k^2>  aimed at publishing results in a scientific journal (candidates: JQL, Physica A). 


3. Sentiment Analysis Using a Graph Based Representation. This is a computational project. The proposal is to implement the system described in 
E. Castillo et al (2015) UDLAP: Sentiment Analysis Using a Graph Based Representation
Proc. of 9th International Workshop on Semantic Evaluation (SemEval 2015)

The authors approach to tackling the sentiment analysis problem (to determine if a text reflects positive, negative or neutral sentiments) is based on the use of a co-occurrence graph to represent existing relationships among terms in a document with the aim of using centrality measures to extract
the most representative words that express the sentiment. These words are then used in a supervised learning algorithm as features to obtain the polarity of unknown documents. To do the text-mining one can use R package koRpus, so the real programming part will consist on building the co-ocurrence graph. Then we can try different centrality measures to determine importance of terms in a text and compare results. 


4. (immunization strategies)
This project will explore several strategies for immunization in real and synthetic networks. The problem is as follows: a disease spreads in a network according to the SIS model. We are allowed to vaccinate a limited nr of "nodes" -- what this means is that these vaccinated nodes will never contract the disease. A typical technique is to direct vaccination to those nodes of highest degree. This project will explore other immunization strategies such as directing vaccination to those nodes of highest pagerank or betweenness centrality. The result of this project should be an empirical study of what strategies are better suited for different network models, networks with different degree distribution, etc.



5. (immunization strategies and sampling)
In project #4, we propose to determine what kinds of nodes lead to better targets for immunization. However, knowledge of the full graph is required in order to determine centralization quantities that will determine the strategy. In more realistic scenarios we do not have full knowledge of the graph. This project will combine crawling techniques with immunization strategies. The idea is as follows: we will crawl part of the graph and determine which nodes to vaccinate during the crawl (using some reasonable heuristic). Then, we will see which crawling strategy leads to better results in terms of total fraction of infecteds after a finite amount of time.

In particular, I believe it is interesting to check whether the crawling strategy of "expansion sampling" [1] beats other strategies, such as a random walks.

[1] Maiya, A. S. and Berger-Wolf, T. Y. (2010). Sampling community structure. In Proceedings of the 19th International Conference on World Wide Web, WWW’10, pages 701–710, New York, NY, USA. ACM.


