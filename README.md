# RegressionAnalysis
Regression analysis is a statistical procedure for estimating the relationship between a target variable and a set of potentially relevant variables. In this project, we explore basic regression models on a given dataset, along with basic techniques to handle over- fitting; namely cross-validation, and regularization. With cross-validation, we test for over-fitting, while with regularization we penalize overly complex models.
## Dataset
We use a Network backup Dataset, which is comprised of simulated traffic data on a backup system over a network. The system monitors the files residing in a destination machine and copies their changes in four hour cycles. At the end of each backup process, the size of the data moved to the destination as well as the duration it took are logged, to be used for developing prediction models. We define a workflow as a task that backs up data from a group of files, which have similar patterns of change in terms of size over time. The dataset has around 18000 data points with the following columns/variables:
• Week index
• Day of the week at which the file back up has started
• Backup start time: Hour of the day
• Workflow ID
• File name
• Backup size: the size of the file that is backed up in that cycle in GB • Backup time: the duration of the backup procedure in hour

