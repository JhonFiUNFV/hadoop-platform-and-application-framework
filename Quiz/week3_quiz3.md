1.Name the configuration file which holds HDFS tuning parameters

- hdfs-site.xml

2.Name the parameter that controls the replication factor in HDFS:

- dfs.replication

3.Check answers that apply when replication is lowered

- HDFS is less robust
- less likely make data local to more workers
- more space


4.Check answers that apply when NameNode fails to receive heartbeat from a DataNode

- DataNode is marked dead
- No new I/O is sent to particular DataNode that missed heartbeat check
- Blocks below replication factor are re-replicated on other DataNodes

5.How is data corruption mitigated in HDFS

- checksums are computed on file creation and stored in HDFS namespace for verification when data is retrieved.





        
        
          
1. Which of the following are valid access mechanisms for HDFS ❌          
- Accesed via Java API
- Accessed via HTTP
           
2. Which of the following is not a valid command to handle data in HDFS? ✅  
- cp -r /user/data /user/test
        
3. Which of the following commands will give information on the status of DataNodes ✅      
- hdfs dfsadmin –report
    
4. Which of the following is not a method in FSDataInputStream ✅
- hflush
   
5. You can only read data in HDFS via HTTP ✅
- False
        
6. What are some webhdfs REST API related parameters in HDFS ✅
- dfs.webhdfs.enabled   
- dfs.web.authentication.kerberos.keytab# Accessing HDFS
        
        
          










