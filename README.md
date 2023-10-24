# Pymaceuticals---Challenge-5
Repo for week 5 challenge

This assignment is broken down into the following tasks:
  Prepare the data.
  Generate summary statistics.
  Create bar charts and pie charts.
  Calculate quartiles, find outliers, and create a box plot.
  Create a line plot and a scatter plot.
  Calculate correlation and regression.
  Submit your final analysis.

I was able to successfully complete the first few sections of this challenge but then ran out of time to complete the last part.  Will revisit this challenge at a later date to resubmit.

Received help from AskBCS, tortiz, in regards to merging data into single dataframe
# Combine the data into a single DataFrame
study_data_complete = pd.merge(study_results, mouse_metadata, how="left", on="Mouse ID")

Received help from AskBCS, dchau, in regards to duplicate_mice code not running correctly.  Turns out I needed to rename the variable due to overriding it with the same variable name.
This is the code that needed to be renamed
# Optional: Get all the data for the duplicate mouse ID. 
duplicate_mice_data = study_data_complete.loc[study_data_complete["Mouse ID"] == "g989"]
duplicate_mice_data

Received help during tutoring session with Kourt Bailey on the section with Bar and Pie Charts.
