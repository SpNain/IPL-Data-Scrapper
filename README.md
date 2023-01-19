# IPL Data Scrapper

- The project scrapes data of all matches of Indian Premier League (IPL) that had been played till now and organizes the data into sub-groups for each IPL franchise.

- Each sub-group contains an object file of all matches runs of each player, providing a detailed breakdown of each player's performance across all seasons of the IPL.

- The scraped data can be used for statistical analysis, trending, and visualizing data, as well as to create leaderboards, rankings and more.

- The project uses npm packages `fs`, `cheerio`, and `request` to scrape data from the ESPN website.

- The `request` package is used to make HTTP requests to the ESPN website, while `cheerio` is used to parse and manipulate the HTML data that is returned.

- The `fs` package is used to write the scraped data to a file for storage or further processing.

## Working 📝

- We provide a link of a page of ESPN website that contains summary of all matches.
- This project identify each player franchise and make folder for that franchise if doesn't exists and push that player runs in a obj file.

## Tech Stack ⚒
**Javascript, Nodejs, FS Module, Request & Cheerio.**