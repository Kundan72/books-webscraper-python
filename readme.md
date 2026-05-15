webscraping-books-project/
│
├── scraper.py
├── books.csv
├── requirements.txt
├── README.md
└── .gitignore



Objective
Scrape book data from Books To Scrape website.

Technologies Used
Python
BeautifulSoup
Requests
Pandas

Features
Extract titles
Extract prices
Extract ratings
Save CSV

Output Example
Add screenshot.



--WORKFLOW--

Website
   ↓
requests downloads HTML
   ↓
BeautifulSoup reads HTML
   ↓
find_all finds books
   ↓
for loop checks each book
   ↓
extract title/price/rating
   ↓
store in list
   ↓
pandas creates table
   ↓
save CSV