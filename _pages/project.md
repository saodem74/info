---
permalink: /project/
title: "Project"
---

### Transfer Learning in IoT data discovery (2020 - 2022).
Vehicle arrival time prediction has been studied widely. With the emergence of IoT devices and deep learning tech- niques, estimated time of arrival (ETA) has become a critical com- ponent in intelligent transportation systems. Though many tools exist for ETA, ETA for special vehicles, such as ambulances, fire engines, etc., is still challenging due to the limited amount of traffic data for special vehicles. Existing works use one model for all types of vehi- cles, which can lead to low accuracy. To tackle this, as the first in the field, we propose a deep transfer learning framework TLETA for the driving time prediction. TLETA constructs cellular spatial-temporal knowledge grids for extracting driving patterns, combined with the road network structure embedding to build a deep neural network for ETA. TLETA contains transferable layers to support knowledge transfer between different categories of vehicles. Importantly, our transfer models only train the last layers to map the transferred knowledge, that reduces the training time significantly. The experi- mental studies show that our model predicts travel time with high accuracy and outperforms many state-of-the-art approaches.


### Summarization Techniques for Space Efficiency in IoT Data Discovery Network (2019 - 2020).
* [Github](https://github.com/saodem74/IoT-Data-Stream-Descriptions-Collection) 
* [Website](https://arxiv.org/pdf/2107.09558.pdf)

In this paper, we consider the IoT data discovery problem in very large and growing scale networks. Specifically, we investigate in depth the routing table summarization techniques to support effective and space-efficient IoT data discovery routing. Novel summarization algorithms, including alphabetical based, hash based, and meaning based summarization and their corresponding coding schemes are proposed. The issue of potentially misleading routing due to summarization is also investigated. Subsequently, we analyze the strategy of when to summarize in order to balance the tradeoff between the routing table compression rate and the chance of causing misleading routing. For experimental study, we have collected 100K IoT data streams from various IoT databases as the input dataset. Experimental results show that our summarization solution can reduce the routing table size by 20 to 30 folds with 2-5% increase in latency when compared with similar peer-to-peer discovery routing algorithms without summarization. Also, our approach outperforms DHT based approaches by 2 to 6 folds in terms of latency and traffic.


### Recovering Variable Names for Minified Code with Usage Contexts (2018 - 2019)
* [Github](https://github.com/saodem74/RecoverJSName-JSNeat)
* [Website](https://mrstarrynight.github.io/JSNeat/)

In modern Web technology, JavaScript (JS) code plays an important role. To avoid the exposure of original source code, the variable names in JS code deployed in the wild are often replaced by short, meaningless names, thus making the code extremely difficult to manually understand and analysis. This paper presents JSNeat, an information retrieval (IR)-based approach to recover the variable names in minified JS code. JSNeat follows a data-driven approach to recover names by searching for them in a large corpus of open-source JS code. We use three types of contexts to match a variable in given minified code against the corpus including the context of properties and roles of the variable, the context of that variable and relations with other variables under recovery, and the context of the task of the function to which the variable contributes. We performed several empirical experiments to evaluate JSNeat on the dataset of more than 322K JS files with 1M functions, and 3.5M variables with 176K unique variable names. We found that JSNeat achieves a high accuracy of 69.1%, which is the relative improvements of 66.1% and 43% over two state-of-the-art approaches JSNice and JSNaughty, respectively. The time to recover for a file or for a variable with JSNeat is twice as fast as with JSNice and 4x as fast as with JNaughty, respectively.


### Sentiment Analysis of Facebook comments (2016)

* [Github](https://github.com/saodem74/Sentiment-Analysis-facebook-comments)
* [Website](https://link.springer.com/chapter/10.1007/978-3-319-42345-6_24)


The most of the people have their account on social networks (e.g. Facebook, Vkontakte) where they express their attitude to different situations and events. Facebook provides only the positive mark as a like button and share. However, it is important to know the position of a certain user on posts even though the opinion is negative. Positive, negative and neutral attitude can be extracted from the comments of users. Overall information about positive, negative and neutral opinion can bring understanding how people react in a position. Moreover, it is important to know how attitude is changing during the time period. The contribution of the paper is a new method based on sentiment text analysis for detection and prediction negative and positive patterns for Facebook comments which combines (i) real-time sentiment text analysis for pattern discovery and (ii) batch data processing for creating opinion forecasting algorithm. To perform forecast we propose two-steps algorithm where: (i) patterns are clustered using unsupervised clustering techniques and (ii) trend prediction is performed based on finding the nearest pattern from the certain cluster. Case studies show the efficiency and accuracy (Avg. MAE = 0.008) of the proposed method and its practical applicability. Also, we discovered three types of users attitude patterns and described them.


### Blocks Supervised (2015)


* [Github](https://github.com/saodem74/Moodle-Plugins---Supervised)
* [Website](https://moodle.org/plugins/block_supervised)


This block allows teachers to plan and start supervised sessions in particular classroom, with particular group and of particular lesson type. This block is devoted to track supervised sessions, where students work on the site in classroom under teacher (or staff) supervision. The session can have it's type (lesson type), classroom and group of students. The classroom is defined via IP subnet, so students off class won't be recorded as participating in sessions. The block allows you to see logs on what is going in each particular session. More importantly, you can control students permissions, given them special abilities (like attempting exam quiz) only during supervised sessions. For now there is quiz access control rule, allowing you to restrict quiz access to supervised sessions. There will be more options later.
