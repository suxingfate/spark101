Description
This is a project used to learn how to build a spark project with IDE.

Run
java -jar ./chinahadoop-1.0-SNAPSHOT.jar ./chinahadoop-1.0-SNAPSHOT.jar hdfs://server1:9000/lab/a.txt hdfs://server1:9000/lab/output/

Merge Result
hadoop fs -ls /lab/output/
hadoop fs -getmerge /lab/output/ result
head result #this is able to see the first group result
