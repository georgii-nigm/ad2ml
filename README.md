# Anomaly detection aided Active learning

Many modern machine learning methods require large amounts of data. Usually, it is not difficult to obtain feature data, while data labels can be difficult and expensive. In this regard, such an approach as "Active Learning" becomes relevant - it is aimed at simplifying the decision-making process about which instances should be marked up by the annotator in order to train the model faster and more efficiently. A popular approach is to evaluate the uncertainty of the model to the data.
But due to the peculiarities of the data collection process, the signs of some measurements may be anomalous – for example, in the smartwatch industry, anomalies may occur when measuring bioimpedance due to design features and variability of measurement conditions. Such anomalies can also be considered undefined by the model, but marking them up and including them in the training set will not improve the performance of the model.
Based on this, the objectives of the scientific work were formulated: "The first: Creation of a modified algorithm for active learning, providing for the detection of anomalies. And the second: The application of the proposed approach to solving the problem of planning experiments to create a regression model that estimates the ratio of extracellular water to total using smart watches."
