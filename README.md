# The_Witcher
**Analysis of character to character associations**

## Overview
User information was scraped from Witcher Wiki. Created a Natural Language Processing (N.L.P.) tool that analyzes character to character associations. 

## Research Question
Can character to character associations be identified through N.L.P.?

## Stakeholder Benefit
Some understanding of the character to character associations may be bennificial while making predictions. 

## Data
The list of characters was acquired by scraping the the Witcher Wiki website.  And the character's association were identified using using the book text for eight of the books (dworschak.2014).

##  B3. Justification:

The book text was parsed in blocks of 5 sentences.  Two characters are considered to be associated if both names are referenced in a block.  These character to character associations were summed.  Refer to the table below:
![image](https://user-images.githubusercontent.com/46407407/186470482-7a149a9b-7d48-4bb8-95ab-1c59b4d7cac0.png)

## Code and Resources Used
**Python Version:  ** Python version: 3.8.5
**Packages:** pandas, numpy, senenium, webdriver_manager, spacy, sweetviz, graphvis, matplotlib
## EDA
![image](https://user-images.githubusercontent.com/46407407/186262898-f65eec68-fbef-4917-b550-f8e8e90cbd8f.png)

![image](https://user-images.githubusercontent.com/46407407/186265480-9c2b2590-7b69-4fce-b998-79a7f99c0498.png)

## Summary
The Selenium package was used to scrape a list of characters from the the Wiki Witcher website.
Scrapy was used used to identify the associations in book text. 
Some character associations can be viewed in the following table:
![image](https://user-images.githubusercontent.com/46407407/186470482-7a149a9b-7d48-4bb8-95ab-1c59b4d7cac0.png)

Charting character associations allows us to visualize some association groupings:
![image](https://user-images.githubusercontent.com/46407407/186469850-125687cb-2b2c-4f99-a115-7f625a18ea67.png)


##  Limitations
  * The character to character associations were made based on occurrence of a small window which may limit accuracy.  
  * Associations are not categorized as positive and negative.

## Recommendations
Further analysis is required to determine more in-depth character associations. For example, the identified character associations may be either collaborative or adversarial in nature. 

## Sources
1. The Official Wticher 
https://www.youtube.com/watch?v=fAHkJ_Dhr50


2. Witcher Fandom
https://witcher.fandom.com/wiki/Category:Characters_in_the_stories

3. Baiju Muthukadan (2018). Selenium documentation.
https://selenium-python.readthedocs.io/locating-elements.html

4. Dworschak / Witcher(2014). JonStryker and JonStryker text version of Witcher books
https://github.com/dworschak/Witcher/tree/master/RESSOURCES/_books/text
