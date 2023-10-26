### Here I offer Datasets created with Python "pandas" (library) through dataframes.  
#### The values are random-generated with logic in the back.  
<br>

>#### *Weekly uploads.*  
>#### ***Feel free to use them on your training.***
----
<br>

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
<br>

 ### **Alpha** composition:
* #### [**COLUMNS** = 11], [**ROWS** = 10,000].
* #### Columns: ["**Employee ID**", "**Rank level**", "**Seniority**", "**Salary**", "**Communication**", "**Teamwork**", "**Adaptability**", "**Leadership**", "**Empathy**", "**Satisfaction**", "**Productivity**"].
* #### All columns are digit composed.
<br>

*generator_alpha function description:*
>* Company DataFrame.  
>* 10,000 employees.  
>* 5 rank levels.  
    |· rank 1: 60% of total employees.  
    |· rank 2: 20% of total employees.  
    |· rank 3: 12% of total employees.  
    |· rank 4: 6% of total employees.  
    |· rank 5: 2% of total employees.  
>* **Salary** applying logic per **Rank level** and **Seniority**.  
>* 5 *softskills* (**Communication**, **Teamwork**, **Adaptability**, **Leadership** and **Empathy**).  
>* **Satisfaction** applying logic per **Rank level**, **Salary**, *salary mean* and *softskills*.  
>* **Productivity** applying logic per **Rank level**, **Seniority** and **Satisfaction**.   
----