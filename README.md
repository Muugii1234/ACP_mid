# ACP_mid
This project uses Scrapy to scrape GitHub repository details from a user’s profile. It extracts key information including the repository URL, description (About), last updated date, programming languages, and the number of commits. The scraper handles empty "About" sections by checking if the repository is empty; if not, it uses the repository name as the description. For non-empty repositories, it fetches the languages used and the number of commits. The extracted data is saved in a well-structured XML file. This project can be extended to scrape additional details or adapted to different GitHub profiles.
