## 前言：

    工作上遇到了一筆 8,000 多維（X）對應 8,000多維(Y)的高維度資料，研究如何透過機器學習來讓資料產生價值時，發現了有一群人持
    續在研究多標籤的分類問題，並且穩定的產生相關Paper，相關文獻在此做分類並紀錄。


### 問題說明：

    多標籤分類問題（Multi-Label Classification）一直都有實際應用的需求，


* * * * *
### 第一類：一般資料維度（標籤數量約小於 < 1000）


    *


* * * * *
### 第二類：高資料維度（標籤數量 > 1000）：XML（Extreme Multi-Label Classification） 問題  

   #### Concept：
    * PPT :Extreme Multi-label Classification for Information Retrieval XMLC4IR Tutorial at ECIR 2018   
      [連結](http://www.cs.put.poznan.pl/kdembczynski/xmlc-tutorial-ecir-2018/xmlc4ir-2018.pdf) 
      
    * Dataset：
      The Extreme Classification Repository: Multi-label Datasets & Code  
      [連結]http://manikvarma.org/downloads/XC/XMLRepository.html  
      
    * Multi-label Classification using Deep Learning and Graph Embedding  
      [連結]http://xiaohan2012.github.io/2017/network-embedding-xml/

   #### Graphic：
    * Probabilistic Label Relation Graphs with Ising Models
    
   #### (Graphic) Embeding Method：
    * Deep Extreme Multi-label Learning
    

   #### Tree：
    * Label tree structure learning (PPT)  
      [PPT連結]http://www.cs.put.poznan.pl/kdembczynski/pdf/fastPLT-idss-2017.pdf  
    * Probabilistic Label Trees for Efficient Large Scale Image Classification  
      [文獻連結]https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Liu_Probabilistic_Label_Trees_2013_CVPR_paper.pdf
    * FastXML:A Fast, Accurate and Stable Tree-classifier for eXtreme Multi-label Learning  
      [Python coding] https://github.com/Refefer/fastxml  
      [C++ coding] http://manikvarma.org/code/FastXML/download.html  
    

 
   #### Other Deep Learning：
    * Deep Learning for Extreme Multi-label Text Classification  

    * Tenforflow 實作：
      https://blog.csdn.net/sinat_30665603/article/details/79888225  

    * Order-Free RNN with Visual Attention for Multi-Label Classification  
      https://arxiv.org/pdf/1707.05495.pdf  
      https://www.youtube.com/watch?v=dGfCWUN-oFs
     
    * Recurrently Exploring Class-wise Attention in A Hybrid Convolutional and Bidirectional LSTM Network for Multi-label 
      Aerial Image Classification  
      https://arxiv.org/pdf/1807.11245.pdf  

    * LEARNING TO DIAGNOSE FROM SCRATCH BY EXPLOITING DEPENDENCIES AMONG LABELS  
      https://arxiv.org/pdf/1710.10501.pdf  


#### 比較 Object Detecting
    * Object Detecting 是想辦法將畫面切分成多個物件區域後在進行分類預測，其最複雜的地方在於定位，與Multi-Lable 有本質上的不同
      
      參考文章: 關於影像辨識，所有你應該知道的深度學習模型
      [文章連結]https://medium.com/@syshen/%E7%89%A9%E9%AB%94%E5%81%B5%E6%B8%AC-object-detection-740096ec4540
