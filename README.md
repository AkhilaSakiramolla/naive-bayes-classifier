# naive-bayes-from-scratch
Implementation of Naive Bayes classifier from scratch.

Problem statement:

When a foreigner comes to the States, sometimes they got very confused about baby’s names to tell it is
a boy’s name or a girl’s name, like Jack and Jane. For this question, you will implement a Naive Bayes
classifier to classify if a given test baby’s name is a boy’s name or a girl’s name. In the dataset, you can
find a boy’s name list, boy names.csv, which contains 1000 commonly used boy’s names. You can also find
a girl’s name list, girl names.csv, which contains 1000 commonly used girl’s names. In order to implement
a NB classifier, you need to:

• Compute P(X|Y )

• Compute P(Y ) but here we don’t need you to compute this as indicated in the hint

• Compute log probability log(P(Y =1|x)/P(Y =−1|x))
• decide the classification result

Questions:
• Implement a NB classifier for the name problem by using the two training files boy names.csv and
girl names.csv.

• Test your algorithm using the test dataset test names.csv. For now you can just output your classification result based on which class has higher probability based on your model. Export your result as
a .csv file, using “-1” to indicate a boy’s name and “+1” to indicate a girl’s name.

