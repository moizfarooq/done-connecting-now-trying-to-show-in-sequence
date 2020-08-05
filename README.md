Title : What prevents Finnish women from applying to software engineering roles? A preliminary analysis of survey data.

Authors : Annika Wolff, Antti Knutas, Paula Savolainen

Conference Name : ICCE-2020 program Software Engineering Education and Training - I14-SEET - Industry Relevant Teaching and Others at Goguryeo

INTRODUCTION AND MOTIVATION: 

If we talk about the satisfaction of users is only part of the success of a software
product, since a tough  competition can easily mislead users from a
software product/service. For this, they investigate a new dataset
provided by the alternativeto.net platform. Through our empirical study,
we observe that  the intention to change software is tightly asso-
ciated to the issues that are present in these software;  
are more likely to be associated with user churn. This study can
provide more insights on the prioritization of issues that need to
be fixed to efficiently and proactively minimize the chances of user churn.
This article revolves around software issues, users churn, software alternatives, deep learning.

Users satisfaction plays vital role for the success of software projects. No wonder about the budget management and leads of the project, if there is any sort of dissatisfaction then that might be the reason of failure.
Never the less it's not only the high talk of the success of software projects between developer and products, but between their strength and weakness of competitors.
So the main motive of this article is to resolve software issues, software alternative and deep learning.
 
 
 RESEARCH AND METHODOLOGY:

In this article they mainly focused on alternativeto.net1 website, beacuse it has some unique features which has alternatives for specific software product.
To seek user churn they investigate the reasons which are mentioned below:
• RQ0: What are the most significant users’ concerns for Browsers,
IDEs and Web Servers?
• RQ1: Can we find a correlation between potential user churn and
issue reports?
• RQ2: Can we use machine learning models to predict the rate of
potential churn?
• RQ3: What are the most important factors related to potential user
churn?
Their  goal of the alternativeto.net website is to provide users to find
software alternatives that can better address the users’ necessities.
Because if we talk about chrome, there are less languages in comparison to Firefox does. And there alternativeto.net work as cherry on the top because it has more alternatives voices option, opinions, ratings and much more relevant to perform task.

Their intelligent guess is that there may exist strong connections  between potential user churn and the issue reports that are submitted to software products (we perform this investigation in Research Q1.

To compile  the data for their study, they followed the process  Given our chosen studied projects, we collect
all the software alternatives tagged with the “Browser”, “IDE”, and
“Web Server” tags, which are the respective domains of the Eclipse,
Firefox, and Apache projects. In total, they collect 290 browser alter- natives, 296 IDE alternatives, and 134 web-server alternatives.

RESULTS:

Four questioned were discussed prior this article the following are the results, motivations and approach of the research:

RQ0: What are the most significant users concerns for Browsers, IDEs and Web Servers?
The motivation behind RQ0 is to  the main concerns within the competition scene of a specific software domain. This investigation is really important to highlight what are the main strengths and weaknesses within a particular domain (e.g., Browsers). This knowledge can be useful because, for example, an organization can study the main weaknesses within a domain and better assess whether its products/services fall within the same.
Their observations and research  suggest that the users concerns are
Highly related to issues (e.g., bugs or crashes) that are present in the respective software products.

RQ1: Can we find a correlation between potential user churn and issue reports?
Previously In RQ0, they highlighted  that software issues (e.g., bugs & crashes and memory issues) are common concerns that may
motivate users to churn. With such an observation, they gave an intelligent guess in RQ1 that the potential users’churn observed on alternativeto.net
may be correlated with the issue reports which developers address in their  projects. This analysis is important because if such a correlation exists, the potential user churn information can be possibly used to prioritize issue reports. Their research and its results suggest that there exists a significant cor-
relation between software issues and potential user churn.

RQ2: Can we use machine learning models to
predict the rate of potential user churn?
In the practice, most of the issue reports undergo human estimations of the priority and the severity, usually based
on internal business-oriented factors. Issues
might be prioritized by their recency, the affected platforms, the versions of the software where the issue is present. Looking after a machine learning model to identify the potential user churn that are
caused by issues may help automate the issue report prioritization process and ultimately save huge costs in software development.
They predict three different machines to identify low and high user issues rates by using information from issue report.
The first model they reported was FEED-FORWARD NEUTRAL 
NETWORKS with two hidden layers developed by using key framework. This is how they research on different models and then, their  results suggest that machine learning models, such as XGboost and Feed Forward Neural Networks, can predict the rate of user churn with relatively high accuracies (in terms of AUC).
Such predictions could help in the prioritization of issue reports.

RQ3: What are the most important factors
related to potential user churn?In RQ2, researchers  observe that machine learning models
can be used to predict the rate of potential userschurn. However, developers would hardly trust a machine learning model to help on their decisions (and they should not do so). Developers would mostly benefit from understanding the reasons behind the
predictions of our machine learning models, so that they could
possibly adapt (or not) their development process. Therefore, in
RQ3, they investigate the most important features in the predictions
of our machine learning model.
To find the most important features, we adopt a simple feature
extraction algorithm [61, 70]. Consider that our models are trained
on a feature set X = X1, X2, ..., XX (as explained in RQ2). The feature
extraction process consists of iteratively (i) removing each feature 
from our models and (ii) computing the AUC without each feature (by using the same leave-one-out validation process explained
in RQ2). The AUC values from the models without a feature  are
compared to the models containing all the features. The higher the drop in
the AUC value caused by removing a certain feature 
, the higher
the importance of such a feature  [4, 9, 10].
The number of Comments obtains a considerable ΔAUC in our three studied systems. The association between the Number of Comments and the rate of user churn may occur due to the multitude
number of users being affected by an churn. 
Their research and  results suggest that long lived issues can potentially lead to more potential users problems  and that the existing processes for prioritizing issues should be capture by highly interactive and long lived issues.

CONCLUSION:

In this research we came to know that, the data available on alternativeto.net to better understand the relationship between software issues and the potential user problems or churns  of users.
Thus, this study reveals the key issues that must be initially for the success of software programming projects
In overall, our study sug-
gests that the prioritization process of issues can be improved by
considering the potential user churn of users associated with such issues.
