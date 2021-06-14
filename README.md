# matplotlib-challenge
Matplotlib Homework

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

**CODE:** Jupyter Notebook was used to create the code - Code is saved as anti_cancer_pymaceuticals.ipynb

**OBSERVATIONS:** A total of 4 observations were made and show at the beginning of the code in Jupyter Notebook.  
These observations are based on reviewing all figures that were generated.

**INSTRUCTIONS:**  Code was constructed based on the instructions given.  Following is a recap:

  - Any data based on mouse ID with duplicate time points was checked for
  - Any data associated with the mouse ID based on the above was removed
  - A Clean DataFrame was created eliminating any duplicate mouse IDs based on time points
  - A summary statistics table consisting of mean, median, variance, standard deviation and SEM was created based on the tumor volume for each drug regimen
  - A Pandas Bar plot and a Matplotlib Bar plot showing the total number of timepoints for all mice tested for each drug regimen were created
      - The above plots look identical

  - A Pandas Pie plot and a Matplotlib Pie Chart showing the distribution between female and male mice in the study were created
      - The above plots look identical

  - The final tumor volume of each mouse across the 4 most promising treatment regimens: Capomulin, Ramacine, Infubinol and Ceftamin were calculated
  - The quartiles and IQR were determined quantitatively to see if there were any potential outliers across these 4 regimens
  - Using Matplotlib, a box plot and whisker plot of the final tumor volume for the 4 treatment regimens was created (all within the same figure).

  - Mouse treated with Capomulin was selected and a line plot of tumor volume vs. timepoint was generated for that mouse (b128)
  - A Scatter plot of tumorvolume vs. mouse weight was created for the Capomulin treatment

  - Correlation and Linear Regression model was calculated between mouse weight and average tumor volume for the Capomulin treatment
  - The linear regression model was calculated on top of the previous scatter plot
