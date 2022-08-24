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

![image](https://user-images.githubusercontent.com/46407407/186335750-532e2278-8033-492a-bd38-78cea2d164f2.png)

## Code and Resources Used
**Python Version:  ** Python version: 3.8.5
**Packages:** pandas, numpy, senenium, webdriver_manager, sweetviz, graphvis, matplotlib
## EDA
![image](https://user-images.githubusercontent.com/46407407/186262898-f65eec68-fbef-4917-b550-f8e8e90cbd8f.png)

![image](https://user-images.githubusercontent.com/46407407/186265480-9c2b2590-7b69-4fce-b998-79a7f99c0498.png)

Data was scrubbed

## Summary
Some character associations can be viewed in the following chart:
![image](https://user-images.githubusercontent.com/46407407/186470482-7a149a9b-7d48-4bb8-95ab-1c59b4d7cac0.png)

Charting character associations allows us to visualize some association groupings:
![image](https://user-images.githubusercontent.com/46407407/186469850-125687cb-2b2c-4f99-a115-7f625a18ea67.png)


##  Limitations
  ** The character to character associations were made based on occurrence of a small window which may limit accuracy.  
  ** Associations are not categorized as positive and negative.

## Recommendations
Further analysis is required to determine more in-depth character associations. For example, the identified character associations may be either collaborative or adversarial in nature. 

## Sources
1. The Official Wticher 
https://www.youtube.com/watch?v=fAHkJ_Dhr50
2. 
https://witcher.fandom.com/wiki/Category:Characters_in_the_stories

3. https://selenium-python.readthedocs.io/locating-elements.html

4. https://selenium-python.readthedocs.io/locating-elements.html

5. dworschak / Witcher(2014). JonStryker and JonStryker text version of Witcher books
https://github.com/dworschak/Witcher/tree/master/RESSOURCES/_books/text
