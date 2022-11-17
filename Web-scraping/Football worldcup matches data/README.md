## Scraping the match data using Beautiful Soup

The Fifa world cup is shortly ariving and this is best time to scrape some data and perform analysis to predict the winners of the worlcup.

### Installing the Libraries:
Here few commonly knwon scraping labraries are used to scrape the data.

+ We have used the bs4 to scrape the website.
+ 'lxml' to parse the HTML documents
+ 'requests' to send requests to target websit
+ 'pandas' to manage the data we have scraped.

Then the labraries are inported.

### Creating the Soup

+ To extract the data using Beautiful Soup we have to create the soup. This uses the lxml parser to parse the HTML content. To get the content froom HTML, a request has to be sent to the website and get the response.

### Extracting the data using few patterns:
+ Once the soup is created, we need to identify a pattern to scrape the data by inspecting the HTML page.
+ Use the identified patterns to extrat the data.
