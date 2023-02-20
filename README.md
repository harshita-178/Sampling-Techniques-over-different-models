# Sampling-Techniques-over-different-models
Sampling means selecting the group that you will actually collect data from in your research.

### Different Sampling Techniques used are:
1. **Simple random sampling**: Simple random sampling is a type of probability sampling in which the researcher randomly selects a subset of participants from a population. Each member of the population has an equal chance of being selected
2. **Stratified Random Sampling**: Stratified random sampling is a method of sampling that involves the division of a population into smaller subgroups known as strata. In stratified random sampling, or stratification, the strata are formed based on members' shared attributes or characteristics, such as income or educational attainment.
3. **Systematic Sampling**: Systematic sampling is a probability sampling method where researchers select members of the population at a regular interval – for example, by selecting every 15th person on a list of the population. If the population is in a random order, this can imitate the benefits of simple random sampling.
4. **Cluster Sampling**: Cluster sampling is a probability sampling method in which you divide a population into clusters, such as districts or schools, and then randomly select some of these clusters as your sample. The clusters should ideally each be mini-representations of the population as a whole.
5. **Multistage Sampling**: In statistics, multistage sampling is the taking of samples in stages using smaller and smaller sampling units at each stage. Multistage sampling can be a complex form of cluster sampling because it is a type of sampling which involves dividing the population into groups (or clusters).

### Different Models used are:
1. **Logistic Regression**: Logistic regression estimates the probability of an event occurring, such as voted or didn't vote, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1.
2. **Support Vector Machine (SVM)**: A support vector machine (SVM) is a supervised machine learning model that uses classification algorithms for two-group classification problems. After giving an SVM model sets of labeled training data for each category, they're able to categorize new text.
3. **K-Nearest Neighbours**: The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.
4. **Decision Tree Classifier**: It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node.
5. **Naive Bayes Classifier**: A Naive Bayes classifier is a probabilistic machine learning model that's used for classification task. The crux of the classifier is based on the Bayes theorem.

### Different accuracies over different sampling techniques and models are as follows:
|index|Models|Simple Random Sampling|Stratified Random Sampling|Sytematic Sampling|Cluster Sampling|Multistage Sampling|
|---|---|---|---|---|---|---|
|0|Logistic Regression|91\.01123595505618|91\.3265306122449|91\.62303664921467|91\.97080291970804|89\.80891719745223|
|1|Support Vector Machine|91\.38576779026218|92\.85714285714286|92\.67015706806284|93\.43065693430657|92\.35668789808918|
|2|K-Nearest Neighbours|97\.75280898876404|96\.93877551020408|92\.67015706806284|91\.97080291970804|92\.99363057324841|
|3|Decision Tree Classifier|99\.25093632958801|99\.74489795918367|98\.95287958115183|97\.08029197080292|100\.0|
|4|Naive Bayes Classifier|76\.02996254681648|78\.57142857142857|80\.10471204188482|65\.69343065693431|77\.07006369426752|
