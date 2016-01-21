
These are some examples using Spark Graphx , written in Scala, to demonstrate How to get started with Spark Graphx on a MapR sandbox (requires Spark 1.3 )

There are  1 datafile  in this directory :
	rita2014jan.csv  
 
You will need to copy these files to your MapR sandbox, or wherever you have Spark installed.

You can run these examples in the spark shell by putting the code from the scala files in the spark shell after launching:
 
$spark-shell 

Or you can run the applications with these steps:

Step 1: First compile the project: Select project  -> Run As -> Maven Install

Step 2: Copy the sparkgraphx-1.0.jar to the sandbox 

To run the  standalone :

spark-submit --class solutions.FlightApp --master yarn sparkgraphx-1.0.jar


