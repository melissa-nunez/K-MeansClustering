# K-Means Clustering For Longitudinal Data

The Safe Passage Study, also known as PASS study, was a multicenter, prospective pregnancy cohort study that collected data from women living in the Northern Plains, US and Cape Town, South Africa. The goal of the study was to investigate the role of prenatal drinking and smoking on postnatal outcomes. 

Because the drinking and smoking habits of the women are dynamic and change per trimester, my goal was to define the exposure variable by using k-means clustering to group the women based on their drinking and smoking habits. I stratified by site and used R statistical software to explore the possible clusters for modeling the women’s drinking behavior only, their smoking behavior only, and their joint-trajectories for both drinking and smoking per trimester. Data is available for three trimesters, however not everyone had completed data for all three trimesters.

