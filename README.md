# Topic Modeling and Analysis of Misinformation Trends in India
### Thesis submitted in partial fulfillment of the requirements for the MA degree in the Master of Arts in Computational Social Science  
#### by Pritam Gajbhiye

This code repository organises and collects the data as well as analysis files for this project.

This research project aims to investigate the dynamics of misinformation in the Indian context, focusing on its patterns and themes during election periods, major events, and correlation among them. By leveraging computational methods and analyzing data from fact-checking websites and social media platforms, this study seeks to answer three key research questions:  
  
**RQ1.** What patterns emerge in the spread of misinformation before and after Indian elections, and how do these compare to misinformation trends observed in other countries?  
  
**RQ2.** Which topics are most susceptible to misinformation, and how do these align with existing social and political incidents like elections and protests?  
  
**RQ3.** How do social media users engage with fact-checking content, and does engagement vary across different themes of misinformation?  

## Data and Code Availability Statement
The data supporting the findings of this thesis were obtained from [BoomLive](https://www.boomlive.in/) and public Twitter (now X) posts by [Mohammed Zubair (@zoo_bear)](https://x.com/zoo_bear), co-founder of
[Alt News](https://www.altnews.in/). The BoomLive dataset consists of fact-check articles published be-
tween November 2018 and December 2024, while the Twitter dataset includes posts and
engagement metrics from January 2024 to December 2024.

All code used for data collection, preprocessing, topic modeling (BERTopic), and senti-
ment analysis is available in a public GitHub repository at [Misinformation India](https://github.com/Pritam0705/Misinformation_India).

## Repository Structure
- The Scripts folder contains the beautiful python scrapper script to scrape the articles from Boomlive.
- The Python Notebooks folder contains all the notebook files for data cleaning, exploration, Bertopic analysis,s and user engagement analysis.
