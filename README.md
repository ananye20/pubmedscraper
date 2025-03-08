# pubmedscraper

Welcome to the PubMed Web Scraper repository! This tool is designed to streamline the process of extracting detailed information from the PubMed database based on user-specified search queries. Whether you're a researcher, student, or enthusiast looking to gather data for analysis, this scraper has you covered.

## How It Works
### User Input: 
The scraper first prompts the user to input their search term, specifying the details they want to extract from PubMed. This could include anything related to medical or pubmed data may it be journal names, author details, PubMed IDs, citations, or any combination or any medical term thereof.

### Data Retrieval: 
Once the search term is provided, the scraper initiates the process of data retrieval. It constructs the appropriate URL for the PubMed search query and proceeds to scrape the search results page using BeautifulSoup and requests libraries.

### Multithreading: 
To expedite the scraping process, the scraper utilizes multithreading, enabling concurrent execution of scraping tasks across multiple pages of search results.

### Comprehensive Data Collection: 
The scraper meticulously extracts relevant information from each search result page, including journal names, author details, citations, and PubMed IDs.

### Data Aggregation: 
As the scraping progresses, the retrieved data is aggregated into a structured format, ready for further analysis.

### Excel File Generation: 
Once the scraping is complete, the aggregated data is organized into an Excel spreadsheet format. This makes it easy for users to download and analyze the data using familiar tools.

## Usage
To start using the PubMed Web Scraper, simply clone this repository and follow the instructions provided in the documentation. You'll be up and running in no time, extracting valuable insights from the vast repository of biomedical literature available on PubMed.

## Performance Considerations
Please note that the scraping process may take some time, particularly if the search query returns a large volume of results. However, the scraper is optimized for efficiency, utilizing techniques such as multithreading to minimize processing time.

Please be aware that the provided code was executed within the Google Colab platform. If you intend to run it on a different platform, ensure that you install the necessary dependencies tailored to that platform.

## Dependencies
#### requests: 
For making HTTP requests to the PubMed website.
#### bs4 (Beautiful Soup): 
For parsing HTML content and extracting data from web pages.
#### pandas: 
For organizing and manipulating the scraped data into a structured format.

---

## V2 Update
- Now scrapes the Abstract of each article as well.
- Cleans Abstract text, removing unnecessary characters like \n, \t, etc.
- Sample output is saved in pubmed_data.csv.

## Contribution
We welcome contributions from the community to enhance and improve this tool further. Whether it's adding new features, optimizing performance, or fixing bugs, your contributions are highly appreciated. Please refer to the contribution guidelines in the repository for more information on how to get involved.

## Feedback
Your feedback is essential in helping us improve the PubMed Web Scraper. If you encounter any issues, have suggestions for new features, or simply want to share your experience using the tool, don't hesitate to reach out through the GitHub repository's issue tracker.



