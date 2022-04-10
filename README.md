# Credicxo

Scraping of data from the provided Paginated API "https://www.amazon.{country}/dp/{asin}" using bs4(BeautifulSoup) library of Python

Scraped the enlisted details:
1. Product Title
2. Product Image URL
3. Price of the Product
4. Product Details

### Steps involved in approaching the solution for the assignment are:

1. Setting up the Headers and Proxies to authenticate our requests to the targetted websites for scraping
2. Reading the URLs from the provided CSV document
3. Extracting out each URL for 100 countries with their unique ID and country code through iterating over each of them
4. Looping through each URL and extracting all the required details related to a product available on the website
5. Handling the exception for the not existing URLs i.e. 404 errors generated in response of few websites
6. Lastly, writing and saving the details of products in a JSON file 
7. Calculated and logged the execution time required for the whole scraping process

