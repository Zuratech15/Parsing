This project represents a web scraping script designed to collect product data from a georgian  website https://www.domino.com.ge, Where a wide variety of tools are available for sale and save it into a CSV file(concretely products names and prices).

It requests the HTML content of the first five pages of the website's tools section, parses the content with BeautifulSoup and extracts product titles and prices. The extracted information is then written to the CSV file. To avoid server overload, the script pauses for a random interval between 5 to 10 seconds between requests.
