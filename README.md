# Text_Analysis
💬 Analyzing the similarity of two text datasets using Python with pandas, numpy, and matplotlib

**The solution to the tasks set is located in the file Tropynina_LS_Twitter.**

**There are 2 datasets:** tweeter_dub1 and tweeter_dub2.
Each file contains data about "Forest Twitter" in the following format:\
post author;\
author type;\
post text;\
post date;

**Task:** Conduct sentiment analysis of the posts in the datasets and compare them based on the following criteria:
1. Determine which dataset, on average, has "kinder" posts.\
_*Initially, the sentiment of a post is considered neutral or equal to 0. Each positive word adds 1 point to the post sentiment, and each negative word subtracts. The evaluation should not depend on word form or case._
2. For the dataset that is on average less kind, determine the number of days when its posts are on average kinder;
3. Determine the kindest author type for each of the datasets and overall.

**Python used libraries:** numpy, pandas, matplotlib
