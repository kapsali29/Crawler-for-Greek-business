In this project we implemented crawlers in order to extract business data from their websites. In order to share the work load, we created 5 individual crawlers.

**First Crawler**

The first crawler gets as input the business website and extracts the following elements from the website, the *demo_first_crawler.ipynb* contains the first crawler:
1. Social network names
2. Social network urls
3. If the website provides multi language option (0 or 1)
4. If the website provides newsletter (0 or 1)
5. If the website provides search option (0 or 1)
6. If the website provides Blog (0 or 1)
7. If the website provides mobile application (0 or 1)
8. If the website has E-shop (0 or 1)

https://user-images.githubusercontent.com/29201775/31721822-1882895c-b423-11e7-9600-0a0708368a9c.PNG

**Second Crawler**

The second crawler gets as input the business website and extracts the following elements from business website, the *demo_second_crawler.ipynb* contains the second crawler:
1. Business phone contacts
2. Business email contacts
3. Business name
4. Business quality certifications
5. Countries in which the business operates
6. Business scope of activities

**Third Crawler**

The third crawler gets as input the business website and extracts the following elements from business website, the *demo_third_crawler.ipynb* contains the third crawler:
1. Business website last modified date (Source: Internet Archive)
2. Business website development quality (Source: Google Insights API)
3. Total visits/year (Source: StatsShow.com)
4. Unique visits/year (Source: StatsShow.com)

**Fourth Crawler**

The fourth crawler gets as input the business website and extracts:
1. Business street address
2. Business geographical coordinates
3. Business zip code
The file *demo_fourth_crawler.ipynb* contains the fourth crawler

**Fifth Crawler**

The fifth crawler, takes as input business website, checks if the following elements are referred on Business websites:
1. If "Corporate Social responsibility" is referred on business website (0 or 1)
2. If "exports" is referred on business website (0 or 1)
3. If "imports" is referred on business website (0 or 1)
4. If "customer support" is referred on business website (0 or 1)
5. If "representation" is referred on business website (0 or 1)
6. If "private facilities" is referred on business websites (0 or 1)
7. If "awards" is referred in business websites (0 or 1)
The file *demo_fifth_crawler.ipynb* contains the fifth crawler
