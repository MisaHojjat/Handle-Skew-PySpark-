# Handle-Skew-PySpark

This statement is based on my experience and background and research on optimal way to handle skew  

## what is skew:
Unbalanced distribution of data across partitions or nodes.   
1- This will cause slowing down the jobs  
2- overwhelms memory   
3- costs and runtime   
4- biased insights   

## How to handle Data skew:   
1- use repartition() with salting to balance skew   
2- clean critical fields   
3- write partitined data to Delta      
4- Add processing date (Makes incremental processing and queries more efficient)




<img width="950" height="282" alt="image" src="https://github.com/user-attachments/assets/923b9234-a417-482b-9d84-db9e0c9d2a5f" />



