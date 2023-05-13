# pandas-challenge
School and scores analysis

[Input]
  This challenge has two sets of data. One consists of information about the schools in a district and the other has details about students, their grades and scores in each of the schools. The goal of the challenge is to make strategic decisions regarding future school budgets and priorities. 

[Output]
  Using Pandas in Jupyter notebook I created a report from the data available. First I created a summary for the whole district which includes the total number of schools, their budget, total students in the district and the average scores. Next I created another summary with all these information but for each school. Based on this information I could determine which school were highest performing and which were lowest performing. Next for each school grouped we grouped them again on grades and determine their average scores by grades.For the last step I sliced the data of interest and put them in separate bins so that we could analyse them based on school spending, size and type. 

[Observation]
  Based on the results of categorizing based on type it appears that charter schools perform significantly better than district schools. Another observation based on school population is that smaller(<1000) and medium(1000-2000) sized schools perform better than larger(2000-5000) sized schools. When scores are calculated based on school spending it cannot be concluded that the greater the spending the better the scores are. Scores appear to be increasing when spending increases upto a certain limit but after that it does not have the same increase.
