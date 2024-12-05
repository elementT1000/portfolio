---
title: "Data Driven Marketing: Pattern Recognition and Optimizing Campaigns with SQL and Stats"
summary: Using real-world telemarketing data to assess a campaign
date: 2024-10-25
#tags: ["PaperMod", "Docs"]
author: ["Ethan Trotter"]
draft: true
showtoc: true
slug: "data-driven-marketing" #Changes the URL
weight: 5
#This needs a lot of work. Include Matt's recommendations on dtats. Also, look at Christine Jiang's feedback on data portfolios. Suggestion to myself: Do something like "Three statistical models, informed by real world data." So, I can get rid of the shit data
---

## Introduction

Few activities in sales are as dreaded as cold calls. Sometimes the lowly sales reps, telemarketers, and other mosquito-like creatures (I can say that, I was one) will sit around as long as they can to delay that next call. So, what can you do get them going again? Easy. Give them a recipe for success. How do you do that? DATA!

You probably already know that, though. It's likely that your company pays for tons of services that have automated dashboards to give feedback on how you're doing. But, you probably have little control over the data points you get back, little understanding of how to get the most of the data by applying it to specific business question, and overwhelm at the sheer size and immediacy of the problem your team faces.

Here, I'll share some techniques to easily parse mountains of data with SQL. We will use some rudimentary tools on some real world data so that this actually means something to you.

In this analysis, SQL was utilized to extract insights from the Bank_Marketing_Dataset hosted on Kaggle. The platform CSVfiddle.io was the SQL platform used for this analysis. When necessary, Google Sheets was used for calculations and graphics. Canva was used to create graphics.

## Resulting Business Insights

This is a TLDR section where I briefly mention the main takeaways of this analysis. 

- The customer segment with the biggest Return on Investment in terms of calls per positive response to a campaign is the group that has been contacted by previous campaigns. Whether their response was positive or negative, they were between 40% to 51% more likely to respond positively to this telemarketing campaign.

- Based on the data, shifting calls from Monday to Tuesday, Wednesday, and Thursday could lead to 154 more positive responses to the telemarketing campaign while only adding 15 minutes of call time to each day. That's a 19% increase for spreading 45 minutes of calls to the rest of the week.  

- Every demographic variable has a statistically significant correlation with responses to the campaign. By prioritizing different target audiences the campaign could see a net improvement in positive response rate. 

Now, let's dig in!

## Exploration of Dataset

The Bank_Marketing_Dataset draws on real-world data gathered from a Portuguese retail bank that was conducting a telemarketing campaign for selling long-term bank deposits between May 2008 to June 2013. It has have 21 features and 39188 samples. 

Let's look at the features.
![alt text](images/SQL_Query1.png)

To be continued...