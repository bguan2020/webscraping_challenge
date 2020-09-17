# internship_challenge
### Sci Find Coding Challenge ###

This is a coding challenge that will test your creative and critical thinking, as well as your ability to learn skills quickly. 

![download](https://user-images.githubusercontent.com/43942774/82876787-32359980-9eee-11ea-8632-1e835a682014.png)


### Overview ###
Create a simple web-scraper that takes in a list of companies and extracts the abstracts from https://pubmed.ncbi.nlm.nih.gov/advanced/ using [BeautifulSoup](https://programminghistorian.org/en/lessons/intro-to-beautiful-soup) and/or [Selenium](https://www.geeksforgeeks.org/selenium-python-tutorial/). 

company_list:
1 Obatala Sciences <br>
2 23andMe <br>
3 Bellbrook Labs 

Basically, you need to input '"Obatala Sciences"[Affiliation]' into the query box, and search. That will bring you to list link: https://pubmed.ncbi.nlm.nih.gov/?term=%22obatala+sciences%22%5BAffiliation%5D&sort=. From there, click the first paper link and extract the abstract text from it. You only need the first one.

Once you've scraped the information, I'd like you to perform some data analysis of that abstract text. It can be anything, from simple EDA like mapping word counts to some kind of graph or word map to something more complicated like applying NLP and machine learning models to the set. This is an opportunity to be creative - ask yourself, what's an interesting way to look at this information, or what's some potentially useful information I can get from this data that maybe is not immediately obvious? If you are having trouble picking something, one thing we're interested in is finding similarity between texts. 


### How to Submit Project: ###
The project is due 3 days from the receipt of this email. Please email brian@scifind.net with the following information to submit your project:

  1. A URL link to your code (scraper + data analysis) on [Github](https://github.com/). Be sure to cite other code if you use it, I do not tolerate taking other people's code without credit. (*Note: Remember to make it publicly accessible so we can see your awesome work :) *)
