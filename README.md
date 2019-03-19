# K-Means Clustering For Longitudinal Data

Identifying the drinking/smoking patterns of women during pregnancy is important in order to better understand the risk of possible postnatal outcomes.

For this project, I analyzed data from a multi-center, prospective pregnancy cohort study that collected data from women living in Cape Town, South Africa. This population is at high risk for drinking and smoking during pregnancy. The goal of the study was to investigate how prenatal drinking, prenatal smoking, and emotional state during pregnancy may effect postnatal outcomes - specifically child heart rate during third trimester, gestational age in weeks, and baby weight at birth (in pounds). I conducted exploratory analysis to identify trends and associations.

Some participants did not have available data for all three trimesters. For this analysis, only those who did have all trimester data available were included.

Because the drinking and smoking habits of the women are dynamic and change per trimester, my goal was to define the exposure variable by using k-means clustering to group the women based on their drinking and smoking habits. I used R statistical software to explore the possible clusters for modeling the women’s drinking behavior only, their smoking behavior only, and their joint-trajectories for both drinking and smoking per trimester.
