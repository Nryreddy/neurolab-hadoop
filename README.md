![image](https://upload.wikimedia.org/wikipedia/commons/0/0e/Hadoop_logo.svg)

# Open Terminal and execute the codes below

HDFS is the primary or major component of the Hadoop ecosystem which is responsible for storing large data sets of structured or unstructured data across various nodes and thereby maintaining the metadata in the form of log files.

### To check the Hadoop services are up and running use the following command:

```
jps
```

### General Shell Commands

- LOCAL FILE SYSTEM

```
ls
```

```
mkdir
```

```
cp
```

```
mv
```

```
rm

```

- LISTING ROOT DIRECTORY

```
hadoop fs -ls /
```

- LISTING DEFAULT TO HOME DIRECTORY

```
hadoop fs -ls
```

- CREATE A DIRECTORY IN HDFS

```
hadoop fs -mkdir /hadoop-user
```

- COPY FROM LOCAL FS TO HDFS

```
hadoop fs -copyFromLocal trees.csv /hadoop-user
```

- COPY TO HDFS TO LOCAL FS

```
hadoop fs -copyToLocal /hadoop-user/trees.csv .
```

```
hadoop fs -ls /hadoop-user
```

- COPY A FILE FROM ONE FOLDER TO ANOTHER

```
hadoop fs -cp /hadoop-user/trees.csv /hadoop-user2
```

## URL to view data in UI:

Name Node - <your_app_name>.ineuron.app:9870

Data Node - <your_app_name>.ineuron.app:9864

Hadoop Clutser - <your_app_name>.ineuron.app:8088/cluster
