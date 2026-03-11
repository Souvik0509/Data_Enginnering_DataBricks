# Data_Enginnering_DataBricks

1. We are creating an end to end databricks project with medialian architecture for FMCG Domain 
   """ 
   Main buisness purpose of doing this project is -- - 

   """ 
2. we are using different S3 bucket for storage for dimentional and fact files to come and sit 
3. we have established connection between databricks and S3 bucket to fetch the files through code and do some processing and then put it in the bronze table 
4. For silver processing we are going with each entity wise silver transformations following a proper interface 
5. we have already pushed the files (dim,fact) to the bronze table ,where two different databricks pipeline would run as part of databricks job ,dim one would run twice a week 
and fact one would run daily at particular time 
