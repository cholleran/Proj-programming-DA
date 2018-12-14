# Proj-programming-DA
Project Programming for Data Analysis

Contents:

Section 1: Simulation with Binomial Distribution
  - Explains why binomial distribution was chosen
  - Example simulation of average incidence of cancer in general population
    
Section 2: Simulation of Cancer in Males
  - Simulation of cancer in males using numpy's binomial function across 5 year intervals from 0-45 years.
    Results of positive diagnoses in variable 'sum_of_male_cases'.

Section 3: Simulation of Cancer in Females
    - Simulation of cancer in females using numpy's binomial function across 5 year intervals from 0-45 years.
    Results of positive diagnoses in variable 'sum_of_female_cases'.

Section 4: Pandas Dataframe
    - Created Pandas dataframe to compare male simulation results against female simulation.
          -bar plot 
          -line plot

Section 5: Analysis of Simulated Results
     - Analysed simulation results.
     - Plotted male simulation with female simulation

Section 6: Simulated vs. Actual
     -  Analysed simulation results against the actual data from Cancer Research UK

Section 7: Percentage Difference - Simulated vs. Actual
    - Plotted the difference between simulated and actual no. of cases in male and female and calculated percentage difference between
      simulated and actual results for each interval.

Section 8: Simulation of Cancer Types (Males)
    - Used numpy.random.choice() to simulate the most common types of cancer 
      in males using probabilities estimated from Cancer Research UK. 
    - simulated dataset: type_inter_2_M

Section 9: Simulation of Cancer Types (Females)
    - Used numpy.random.choice() to simulate the most common types of cancer 
      in females using probabilities estimated from Cancer Research UK. 
    - simulated dataset: type_inter_2_F

Section 10: Analysis of Top 5 Cancers
    - Concatenated simulation of most common cancers in males and females into a single dataframe.

Section 11: Scatter Plot of Simulation Results - Most Common Cancer Types
   - Scatter plot of most common types of cancers comparing numbers and types for males and females.



Project Specifications:

​ Choose a real-world phenomenon that can be measured and for which you could
  collect at least one-hundred data points across at least four different variables.
  
  - The chosen phenomenon was the incidence of cancer in males and females from 0-49 years.
  - 100,000 data points were simulated for each of four main variables.
  
  
• Investigate the types of variables involved, their likely distributions, and their
relationships with each other.

- Cancer incidences per 100,000 were simulated using numpy's binomial function.
- The project compared the relationship between cancer incidence in male & female variables and age intervals from 0-49 years.
- It also examined the most common cancer types seen in these age intervals and compared cancer types in males and females.

• Synthesise/simulate a data set as closely matching their properties as possible.

- The datasets were simulated using estimated probabilities from real data provided by Cancer Research UK.

• Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.