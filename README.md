# Twitter_Bot_Detection
The main objective of this project is to build a Twitter bot detection model
which is capable of identifying malicious Twitter bots. These Twitter bots are always a
major concern for social media companies and pose a threat to security. Our aim is to
use various classifiers in order to determine which is the best-suited approach for solving
our problem statement.
Keywords — machine-learning, Data Analysis, Twitter bots, Pandas, Numpy, Feature
extraction, Decision Tree Classifier, Multinomial Naive Bayes, Random Forest
Classifier.
I. INTRODUCTION
Today, social media platforms like Twitter have many accounts that are
controlled by automated agents called bot or Sybil accounts. Mostly, people
aim to have more visitors to their websites, influence the community on a
specific topic, recruit people to their organizations that might be an illegal
organization, manipulate people for stock market actions, propagate fake news,
and blackmail people to spread their private information by the power of these
accounts. As a result, the social bot detection framework becomes very crucial
to keep people safe from Sybil's accounts.
When these bot accounts are analyzed, it can be seen that there are various
types; some of them are very primitive and some of them are very complex that
they are hard to diagnose even by humans. In order to avoid detection, they
mimic human accounts, develop strategies to a friend or follow human accounts
and support each other as a large network to gather trust. Additionally, a large
group or network of these accounts can act collaboratively to change trending
topics on Twitter for malicious purposes.
The sheer number of these bot accounts and their increasing complexity
bestows a challenge for the manual detection of these accounts.
Our aim through this Twitter Bot Detection Project is to find the classifier
which fits the best and has the greater accuracy in finding the solution to our
problem statement which is - detecting malicious Twitter bots.
II. LIBRARIES USED
1. Pandas - for data manipulations and analysis
2. Numpy - data analysis done through arrays
3. Matplotlib - plotting visualizations for various classifiers and while data
analysis
4. Seaborn - It is used for data visualization and exploratory data analysis.
Seaborn works easily with data frames and the Pandas library. The graphs
created can also be customized easily.
5. Warning - to display the warning messages
6. Decision Tree Classifier - The algorithm uses training data to create rules
that can be represented by a tree structure.
7. train_test_split - splits arrays or matrices into random subsets for train and
test data
8. sklearn.naive_bayes - naive bayes methods are a set of supervised learning
algorithms based on applying Bayes' theorem with the “naive” assumption
of conditional independence
9. sklearn.ensemble - includes two averaging algorithms based on randomized
decision trees: the RandomForest algorithm and the Extra-Trees method.
10.RandomForestClassifier - random forest is a meta estimator that fits a
number of decision tree classifiers on various sub-samples of the dataset
and uses averaging to improve the predictive accuracy and control
over-fitting.
III. DATASET USED
The dataset we are working on basically contains the important attributes of a Twitter
account that can be useful in determining whether a Twitter account is a bot or not. The
basic structure of the dataset attributes includes 3 boolean values attributes, 1 float valued
attribute, 6 integer type, and 10 object type attributes. These 20 attributes together form
the skeleton of our training datase
