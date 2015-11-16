#Introduction（4页）
介绍问题来源，现有解决方案的不足。这篇论文提出的方案（概述），以seminar作为case study。论文结构等等
##Problem
##Case Study and Setting
##Disseration Structure


#Background（20页）
要解决以上提出的问题，有以下几个难点要克服，每个领域都有一定的解决方案，我们来介绍如下。
##Related Research
介绍相关研究领域
###Webpage Classification
其他网页分类的方法及其优劣，最后给出我们这个利用（ontology）的分类解决方案的优势，不需要谈细节，在methdology里面讲。
###Information Extraction
其他网页分类的方法及其优劣，最后给出我们这个利用（ontology）的提取解决方案的优势，不需要谈细节，在methdology里面讲。
###Webpage Annotation
其他人有人做Webpage Annotation，讲讲别人怎么做的，然后提下我们会用visualization来使得annotation更容易，更快的被人接受。
这块其实就是在提取的时候，网页上我们会标记处哪里是location，哪里是time，使得更直观，更能被终端用户接受。
##Background Knowledge(Knowledge Involved)


#Methodology（28页）
我们实现了一个系统，能使的一个经过短期培训就可以快速从大规模的网页中找到目标页面，然后进行信息提取。
##System Architecture（P2）
系统分为几个部分，每个部分都在干什么，画图
##Pipeline Design（P2）
以信息流为主线，从头到尾，一个网页经历了哪些过程。

##Communication Protocol（P4）
各个demon进程之间如何通过socket来通讯，具体的协议是什么。
##Webpage Crawler（P2）
##Judge(Webpage classification)（P6）
onto的结构。决策树。features的选取
##Extractor（P6）
onto的结构，rule的结构，例子

##Web Interface and Visualization Design（P4）
###Basic Elements
不同的颜色代表Single，Multiple，None
进度条的长短代表确信度

###Annotation Design
用Glyph(icon)来表现提取过程中的每一个属性

###Result Visualization
讲如何展现最终的结果

###Web Interface

#Experiment（14页）
##Classication Experiment
有实验数据

##Extract Experiment
需要构思，我在想可以编找了几个人做了实验，把准确率给出来


#Further study and Conclusion（2页）
需要构思