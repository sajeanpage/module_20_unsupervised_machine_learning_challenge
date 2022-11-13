# Module 20 Unsupervised Machine Learning Challenge
## Summary

I am a member of the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. My supervisor has asked me to explore this possibility by using unsupervised learning. I was provided with raw data, so I processed it to fit the machine learning models. I used several clustering algorithms to explore whether the patients can be placed into distinct groups.

After analyzing the data I have determined the following:
- Using dimensionality reduction, I reduced the number of independent variables from 15 to 10  
- Addition TSNE reduction reduced the number of independent variables to 2 while accounting for .90 of the variability
- Plotting TSNE results at learning_rate=30, perplexity=30 revealed that patients may be able to be separated into 5 or 6 clusters
- Analyzing K means from 1 to 10 also revealed that 5 clusters may the the optimal number of groups for the data

# ![banner](https://github.com/sajeanpage/module_20_unsupervised_machine_learning_challenge/blob/291af7e97d4dc1d7e6c8325bc7889f68394064a1/Resources/clusters.JPG)
# ![banner](https://github.com/sajeanpage/module_20_unsupervised_machine_learning_challenge/blob/291af7e97d4dc1d7e6c8325bc7889f68394064a1/Resources/elbow.JPG)
