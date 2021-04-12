# Udacity SF Crime Data
__________________________

1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
- The number of processedRowsPerSecond greatly increased when I added the 
  spark.sql.shuffle.partitions and spark.default.parallelism options.
  
2. What were the 2-3 most efficient SparkSession property key/value pairs? 
   Through testing multiple variations on values, how can you tell these were the most optimal?
- The two properties I've mentioned above were the most efficient. Combining 
  them I could achieve 214 processedRowsPerSecond. I've found those numbers 
  through trial and error, that's how I got the 10 and 80.
  

### Obs.: The screenshots can be found on the images folder.
