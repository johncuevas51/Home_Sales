# Home_Sales
HW 22
Home Sales : 
Using SparkSQL to determine metrics about home sales data.
Use spark to create temporary views
Partition the data, cache, and uncache a temp table, then lastly verfity table has been uncached.

Packages imported : 
import findspark
from pyspark.sql import SparkSession
import time

Run times for the view queries :
Uncached  -- 0.17 seconds
Catched -- 0.11 seconds
Partitioned -- 0.20 seconds 

Below are all the queries :

![image](https://github.com/johncuevas51/Home_Sales/assets/119380122/fba9bbac-c295-45b1-8b35-edc358621c7b)







