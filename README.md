# SOSC314_MGao_Project
### This is the repository for Miles Gao’s Spring 2026 SOSC314 Project

## Guiding Research Question: How does increased online traffic and discourse about topics impact the editting of Wikipedia articles?

## Points of Interest
I started this project with the goal of looking at Twitter and the impact of the recent acquisition by Elon Musk on the content on the App. Unfortunately, the Twitter API is paywalled, and thus very expensive to use; still interested in online discourse, I shifted to look at Wikipedia edits; I wanted to see how increased traffic and discussion to a topic would change the edits on the page. At first, I was interested in specificically discourse happening on Twitter, but I have decided to broaden the project to look at any topics with increased traffic. To this end, Google Trends will be used to observe traffic. 


## Methods
MediaWiki will be used, and I am using a stripper called mwstripperfromhell to clean the data of formatting. 

Methods to try and answer the question will include finding which words are more likely to "survive" and which are more likely to be removed over time. I will try to categorize these words, and potentially, I will try to predict the survivablility. this is only a possible avenue, however, given that edits are rarely full thoughts, making it difficult to find sentimentality of singular edits. 

I will then try and compare this data to dips in traffic and analyze the impact of traffic on Wikipedia articles, their resistence to heightened activity, and if possible, potential biases in allowed changes.



## Original Research Question and Brief Background Information
Specifically, the project aims to examine the change in the activity level of specific topics, as well as the specific language used in the articles. The units of analysis will therefore be edit volume (edits/month), unique editors per period, revert rates, and word frequency. The purpose of the edit-based variables is to determine how active the site is, and the purpose of the word frequency is to detect possible shifts in acceptable language and rhetoric on the articles. 

To obtain the information, the intended method is the API MediaWiki, which contains important data, such as the text in each revision (including added and removed words) and the date of each revision (as well as the number of revisions in a given time period).

The articles must be carefully selected: articles should not be directly involved in the acquisition, as activity would increase due to coverage of new events (examples would include Elon Musk, who is directly involved, or Donald Trump, whose account was reinstated following the acquisition) which is irrelevant to the purpose of the project; such articles would bias the data in favor of X as an influential platform. From the preliminary exploration, the project will be focused on data from closely approaching October 2022 and around January - June of 2023. As the articles require individual research, the project seeks to examine around 10 topics, with 1-3 articles for each topic.

An example article with a shift around the target time period discusses transgender rights: https://en.wikipedia.org/w/index.php?title=Legal_status_of_transgender_people&action=history. The following figure contains data about editing volume.
<img width="747" height="595" alt="transgender_rights_preliminary_figure" src="https://github.com/user-attachments/assets/31508e91-043c-4b45-8bda-b7a3c2030ee3" />
https://xtools.wmcloud.org/articleinfo/en.wikipedia.org/Legal_status_of_transgender_people 
While the figure is a strong example, it does not inform decision making, as it is a small sample size, and the purpose of the initial exploration is to demonstrate feasibility in obtaining data and observing patterns. 
 
