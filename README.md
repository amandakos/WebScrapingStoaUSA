# WebScrapingStoaUSA
Webpage is scraped to look at the top 20 most frequently used words.
Stoausa.org webpage is scraped to look at the 20 most frequenstly used words.
First, packages are loaded.
requests, bs4's BeautifulSoup, nltk, RegexpTokenizer, matplotlib, & seaborn are used.
Next, the webpage's information is imported into Python.
Then the text on the webpage is parsed into individual words then each word is assigned a token.
From there, uniformity is formatted by removing capital letters.
Stopwords are then removed to clean up frequency counts.
Next, using a for loop a list is made of words that are not in the stopwords list.
Finally, seaborn is used to get word frequencty counts.
The top 20 results are then graphed.
