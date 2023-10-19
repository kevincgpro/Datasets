### Here I offer Datasets created from Python pandas lib Dataframes. The values are random generated with logic in the back.
### Feel free to use them on your training.
----
 
### The organization structure is:
* #### Each folder is the model used for the Dataframe generation.
* #### The format of the file_name is:
    - ##### {**model version**}\_{**date**}\_{**serial number**}.csv
### Examples:
* ***Alpha/***
    - *v1-0_191023_86321277.csv*
* ***Beta/***
    - *v1-0_191023_56879412.csv*
 ----

 ### **Alpha** composition:
* #### [**COLUMNS** = 11], [**ROWS** = 10,000].
* #### Columns: ["Employee ID", "Rank level", "Seniority", "Salary", "Communication", "Teamwork", "Adaptability", "Leadership", "Empathy", "Satisfaction", "Productivity"].
* #### All columns are digit composed.
*generator_alpha function description:*

>* Company DataFrame.  
>* 10,000 employees.  
>* 5 rank levels.  
    |· rank 1: 60% of employees.  
    |· rank 2: 20% of employees.  
    |· rank 3: 12% of employees.  
    |· rank 4: 6% of employees.  
    |· rank 5: 2% of employees.  
>* Salary applying logic per rank level and seniority.  
>* 5 softskills (Communication, Teamwork, Adaptability, Leadership and Empathy).  
>* Satisfaction applying logic per rank level, salary, salary mean and softskills.  
>* Productivity applying logic per rank level, seniority and satisfaction.   
----