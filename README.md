# Slack Network Analysis 
<br/><br/>
## Find the Knowledge Hubs in Your Company using Social Network Analysis on Slack Data

## Project Intro
Imagine you are a newly hired manager at a big company which is scaling fast and you need answers to your questions. How would you know how to ask?
While teams are popping up like mushrooms everywhere with directions changing every odd week, you can't really rely on outdated organisational charts anymore. Your best bet will be to discover the internal networks and find the most valuable contributors by yourself.

That's where Social Network Analysis (SNA) can help.

## Notebooks
The notebooks in the code folder could be used to 
- clean & wrangle json data to extract features into a dataframe
- run network analysis
if you have your exported files at in hand.

If you don't know how to export, read up here> https://slack.com/intl/en-hu/help/articles/201658943-Export-your-workspace-data

The notebooks are fully annotated and include all the modules which needs to be imported to make the code work.

Read your json files after download:
In the EDA notebook, replace '../raw_data' with the folder you have your files in your repo where it's necessary.

## Methods used

- **Loading JSON files:**
  - creating a function to load each file into a dataframe<br/>
- **Data cleaning & wrangling in Python:**
  - function to extract real_name feature from json dictionary
  - function to clean:
   - drop columns which doesn't make sense
   - drop rows which doesn't make sense
   - filter down for 1to1 convos<br/>
- **Network Graphs**
  - undirected without real_names
  - function to 
  - directed with real_names, 
  - weighted,
  - highest betweenness nodes,
  - highest degree nodes,
  - degree frequency<br/>

## Medium article
If you wanna read through work I've done in a more consumble from, check out what I posted on Medium:
https://towardsdatascience.com/find-the-knowledge-hubs-in-your-company-38afb89d2eaa

**Thank you for reading!** <br/>
Any questions, hit me up at
lilla.szulyovszky@gmail.com<br/><br/>

