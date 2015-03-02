# intellij_for_spark
|instruction of how to set intellij for spark developers

## Environment installation
### java
    | java 1.7.75
    | JAVA_HOME= jdk_root
### hadoop
    | hadoop 2.4.1
### Scala
    | Scala 2.10.4 
### Spark
    | Spark 2.1.0   
### Maven 
    | Maven 3.2.5
## install Intellij 14

## install plugins 
    1. Scala 
## Hello Wolrd
1. set up Scala Non-SBT project 
2. import spark-assembly-1.2.1-hadoop2.4.0 (in pre-built spark/ lib/)
3.  build and make artifacts 
4. insert code 
    [code] val conf = new SparkConf().setAppName("Spark Pi").setMaster("spark://TheOne:7077").setJars(List("out/artifacts/untitled2_jar/untitled2.jar"))

