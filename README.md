# 1.Team members name:Chuanjie Tang , Tong Wu
# 2.Project objective: Count the origins of each artwork to get the distributions of the artworks in the world;Count the production time of each artwork to get the distributions of these in the timeline；Combine these two distributions to compare the amounts of the artworks in the diffent regions at the same time.  

# The dataset has numeric and literal data such as object begin data and cultural background. There are many different types of metadata in this dataset such as artist end data,artist display bio, department title, culture, the details of its artist and so on. These two types of metadata were into our eyes first because we found that there were couple noisy data. For instance, under the artist display bio information, the first object is "American, Delaware County, Pennsylvania 1794–1869 Philadelphia, Pennsylvania", this is noisy because it has unnecessary duplication "Pennsylvania", the normal data should look like "American, East Cambridge, Massachusetts, 1818–1888". The other metadata is interesting because we found that there is an obviously wrong data. Under the artist end date information, there is an artist whose end date is 9999. The normal end date should not be later than 2019. There may be much more wrong data about artists' end date.

Steps and Outlines | Roughly Time Estimate
------------------ | ---------------------
Data Cleanup | two weeks 
transformation | one week
feature engineering | several days
statistical summary | one week
visualization | three weeks

#Final Project:
[Final project](https://mybinder.org/v2/gh/tcj1995/final-project/master?filepath=final.ipynb)
