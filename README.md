# Death-Row-NLP-analysis
This is a student project for Tomsk Polytechnic University.

The goal is to see similarities in last statements of Texas Prisoners.

https://www.tdcj.texas.gov/death_row/dr_executed_offenders.html

Contains parcing module to gather info from site. 
As this site blocked in Russia, I used https://www.zyte.com/ proxy solution.
It's 14-days free proxy service to make requests from sites without being blocked.
They provided proxy certificate that should be used when making requests.

![image](https://user-images.githubusercontent.com/91039005/155667799-e620d640-99f1-4510-aecf-35c9a482984b.png)

The field I was interested in is 'laststatement'
![image](https://user-images.githubusercontent.com/91039005/155668007-22505222-00d5-4675-82d5-8f0a736aa507.png)

I made some processing of text:
- clear of punctuation
- remove stopwords
- tokenize words
- normalize words

![image](https://user-images.githubusercontent.com/91039005/155668221-005de282-ec2c-4c82-9d44-c7d22d1787ad.png)

Made a correlation matrix filled with Jaccard index. comparing each two text to each other.
![image](https://user-images.githubusercontent.com/91039005/155668701-96ac7b82-a028-4b8e-8cd8-388a322e4d3c.png)
