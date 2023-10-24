# Spark_project
Big data-related project

![map reduce in google](https://github.com/warunasrinath/Spark_project/assets/56961480/6df79843-ede4-4d40-aabf-80e0e018086a)

Input->splitting->Mapping->shuffling->Reducing->Final output 

In Hadoop, we have major two concepts 

1. HDFS
Distributed the large amount of data parallel for different computers(stored in hard disk) 
   
 ![HDFS in hadoop](https://github.com/warunasrinath/Spark_project/assets/56961480/baa43a4c-e97a-4517-a1eb-aee1f8948ff6)

2. Map Reduce

This is the super smart way to process the stored data together. Like solving a puzzle which is splitting the tiny puzzle parts parallel and final adding them together 

![map reduce in github](https://github.com/warunasrinath/Spark_project/assets/56961480/b2c86446-9d19-4f18-9463-7c00778619a5)

cons(drawbacks)
*. Hadoop data is stored on the hard disk, it will read the data, process, and again store data on to the disk, this is too slow
*. It processes data only in batches, which means we have to wait for one process to complete before submitting any other job.

NOW we focus on why Apache spark

Now introduce RDD(Resilient Distributed Dataset), RDD is the backbone of Apache Spark. RDD allows data to be stored in memory(RAM), enabling data access and processing. Instead of reading and writing.

the Sparck is 100 times faster than Hadoop
![different components in spark](https://github.com/warunasrinath/Spark_project/assets/56961480/f60888a3-9ded-4355-947f-49a0223d77d1)

artitecture of Hadoop 
![structure](https://github.com/warunasrinath/Spark_project/assets/56961480/091eaec6-c2d7-4a18-b2c2-c63d5894a1c1)


