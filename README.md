# Hadoop-WordCount
Operating System: Ubuntu 18.04
Commands:
1. export HADOOP_CLASSPATH=$(hadoop classpath)
2. echo $HADOOP_CLASSPATH
3. hadoop fs -mkdir /<Diractory Name>/
4. hadoop fs -mkdir /<Input folder Diractory>/
5. hadoop fs -put /<input file directory>/ /<Input folder directory>/
6. then, use cd  and go to the project folder.
7.javac -classpath ${HADOOP_CLASSPATH} -d /<classes folder directory>/ /<java files directory>/
8. jar -cvf <new jar file name> -C <class folder name>/ .
9.hadoop jar <jar file directory> <class name> <Input folder directory> <output folder directory>
10. hadoop dfs -cat /<output directory>/*
