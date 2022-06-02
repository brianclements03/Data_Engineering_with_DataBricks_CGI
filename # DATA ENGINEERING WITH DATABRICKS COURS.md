# DATA ENGINEERING WITH DATABRICKS COURSE

# DBr Architecture: 
            #### Control Plane (DBr Cloud Acct) <--> Data Plane (Customer Cloud Acct)
    ## Control plane: 
        - Web Application
            - DBr Sql
            - Dbr ML
            - Dbr Workspace (DE and ML)
        - Repos/Notebooks
        - Job scheduling
        - Cluster Mgmt
            - One or more VM instances executed on w Spark jobs
            - All Purpose (up to 70 clusters up to 30 days): interactive notebooks 
            - vs 
            - Job (up to 30 clusters): Run automated jobs

# Interface: you can clone a repo straight from the DBr UI : )
