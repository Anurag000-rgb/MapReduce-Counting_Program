# MapReduce-Counting_Program
Anurag000-rgb/MapReduce-Repetation_Counting
MapReduce Code for Counting the numbers in JAVA Basically in this project But it good to write in Apache Spark using scala Rather In Apache MapReduce

## Both are Processing Framework on HADOOP and Implements Distributed Computation On Distributed Systems
## Apache MapReduce =>
* faster than Apache Spark
* But Not Effecient
* It Implement Batch Processing


## Apache Spark => 
* It Implements Batch Processing and Stream Processing
* It Works Effecient Than MapReduce

In Scala It Just One Line =>
# Just Import Scala Context By SC
```
scala: sc.textFile('YOUR HDFS FILE LOCATION').map(input => input.split(" ")).flatmap(input => input).countByValue;
```
