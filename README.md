# Opinionated-pandas
Use pandas in an opinionated way

## Content in the notebook 

Notebook walks through the important concepts in the pandas. My recommendation is to use subset of the library functions which are enough to do all of the data analysis that we usually do. 

Note - You will not find all the details for each conecept/method in the notebook. Notebook was prepared to just go through imporant functions. Please go through the reference link that are mentioned. 

You will find below concepts explanined in the notebook. 

1. Series_and Dataframe
2. Indexing and Selecting
3. Group by 
4. Pivot table
5. Stack and Unstack for Reshaping
6. Merge and Concat


## Setup

- Install Virtualenv if you do not have already

  virtualenv -p python3 venv

- Activate virtualenv

  source venv/bin/activate

- Install the requirements

  pip install -r requirements.txt

- Start jupyter notebook with command 

  jupyter notebook



## Recommendations

- Understand the pandas Series and Dataframe in the form of dictionary  


- Use .loc and .iloc for selecting data  


- Use reset_index and combine nested columns to convert mulit-index index/columns of dataframe to just columns  


- Use pivot_table and crosstab to compare the groups  


- Use Stack and Unstack for Reshaping the multi-index dataframe


- Use Merge and Concat to combine dataframes   



### References 

- https://pandas.pydata.org/   


- https://github.com/justmarkham 


- https://www.youtube.com/watch?v=S0RPvghGmlQ&list=PLgJhDSE2ZLxaENZWWF_VOUa5886KiUd15  


- https://school.geekwall.in/p/BkXnsC1VH/minimally-sufficient-pandas  


- https://medium.com/dunder-data/minimally-sufficient-pandas-a8e67f2a2428
