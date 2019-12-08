# Market-data-extraction-sentimental-analysis
A Data science project in data extraction and sentimental analysis

In this project I used the python library Beautifulsoup to extract webpage contents with only <page> tags and whihc only contained these 3 sections namely:
  - Management's Discussions and Analysis
  - Quantitative and Qualitative Disclosures about Market Risks
  - Risk Factors
  
Then I used nltk library as well as the regex library to capture the essential words for sentimental analysis, I specifically calculated:
  - postivity, negativity, uncertainity, polarity, constraining score
  - fog-index, complex word count, average sentence length, word count
