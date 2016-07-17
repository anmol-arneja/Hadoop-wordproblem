The dataset for this problem is provided in wordcountproblem file.
The src file contains two map reduce programs:
1) WordCount.java -   This map reduce program calculates the number of times a given word has occurences in the text. The output for this program is stored in wordount_output file
2)WordSize_WordCount.java -  This map reduce program calculates the number a word of particular length has appeared in text. The output for this program is stored in wordsize_output file.


Instructions for running this program 
First create a jar file and the add the external jars given in lib folder
The input file wordcountproblem should be in hdfs and can be copied to hdfs using following commad:
hdfs dfs -copyFromLocal '[Local location where you have saved file wordcountproblem]'
Run the jar giving following commands

cd /[Location where your jar is stored]
hadoop jar [your created jar file] [input data in file stored in hdfs] [output file where output is to be stored]