# Titanic Data Analysis

The two main problems that we will use are as follows:-
1) In this problem relation, we will find the average age of males and females who died in the Titanic tragedy.
2) Find the number of people who died or survived in each class with their genders and ages

The dataset is loaded on to the HDFS with the following command
# hadoop fs -put /home/diwakar/Desktop/Hadoop/Titanic/TitanicData.txt /Projects

The command used to run the MR code is as follows.
# hadoop jar /home/diwakar/Desktop/Hadoop/final-jarfiles/Titanic.jar Female_survived /Projects/TitanicData.txt /op7
