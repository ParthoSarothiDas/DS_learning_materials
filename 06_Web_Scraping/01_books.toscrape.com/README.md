### Project Title: Books Data Scraper from Books to Scrape

**Objective:**  
To scrape and analyze detailed information about books, including their titles, ratings, prices, availability, and image URLs from the "Books to Scrape" website using Python and BeautifulSoup.

**Tools & Technologies Used:**  
- Python  
- Libraries: Pandas, NumPy, BeautifulSoup, Requests  
- Web Scraping  
- Data Cleaning & Processing  

---

#### Project Summary

This project aims to extract comprehensive information about books from **50 pages** of listings on the "Books to Scrape" website. Using Python and BeautifulSoup, the script scrapes book titles, ratings, prices in GBP, availability statuses, and image URLs. After collecting the data, it is consolidated into a Pandas DataFrame for further analysis or export.

Key steps include:  
- Sending HTTP requests to paginate through book listing pages  
- Parsing HTML content to locate relevant details like titles, ratings, and prices  
- Constructing full URLs for book details and image links  
- Structuring the scraped data into a well-organized DataFrame  
- Saving the final data to a CSV file  

---

#### Key Highlights  
- Scraped over **50 pages** of book listings from "Books to Scrape"  
- Collected data on titles, ratings, prices (GBP), availability, and image URLs  
- Implemented cooldowns between requests to avoid server overload  
- Compiled a clean DataFrame ready for analysis or export to CSV  

---

#### Sample Data Output

| Title                      | Rating    | Price (GBP) | Availability | Web Address                                | Image URL                                    |
|----------------------------|-----------|-------------|--------------|--------------------------------------------|---------------------------------------------|
| The Great Gatsby           | Five      | £9.99       | In stock     | https://books.toscrape.com/...             | https://books.toscrape.com/...              |
| To Kill a Mockingbird      | Four      | £7.99       | In stock     | https://books.toscrape.com/...             | https://books.toscrape.com/...              |

---

#### 🧑‍💼 About the Author  
**Partho Sarothi Das**  
Aspiring Data Scientist | Background Master's in Statistics  
Dhaka, Bangladesh  
🔗 [GitHub](https://github.com/ParthoSarothiDas) | 🔗 [LinkedIn](https://www.linkedin.com/in/partho-sarothi-das/)  

--- 
