# Email-Crawler
📬 Email Extractor from Chitkara University Website
This project is a simple Email Crawler built in Python. It crawls a webpage and extracts email addresses from its visible text content.

📌 What is an Email Crawler?
An Email Crawler is a tool or script that automatically scans web pages to collect email addresses. It's commonly used for tasks like:

Gathering contact information from websites

Automating directory building

Performing data collection for research or testing

Important: Crawling should always be done ethically and in compliance with site policies to avoid misuse or legal issues.

⚙️ How It Works
Request the Webpage
The crawler sends an HTTP GET request to the given URL using the requests library.

Parse HTML Content
It loads the page's HTML into BeautifulSoup to strip away tags and access raw text.

Extract Emails
The script uses a Regular Expression (regex) to search through the text and identify valid email patterns (like name@domain.com).

Display Unique Results
Duplicate emails are removed by converting to a Python set, and the final list is printed in sorted order.

🛠️ Technologies Used
Python 3

requests – to send HTTP requests

BeautifulSoup – for HTML parsing

re – for extracting emails using Regular Expressions

🧪 Example Output
nginx
Copy
Edit
Found emails:
admission.educarebd@gmail.com  
admissions@chitkara.edu.in  
ajay.dhiman@chitkarauniversity.edu.in  
coe@chitkarauniversity.edu.in  
info@chitkarauniversity.edu.in  
rajesh.nepal@chitkara.edu.in  
wangdi@chitkara.edu.in
⚠️ Disclaimer
This tool is for educational and ethical purposes only.

Respect a website’s robots.txt and privacy policy.

Do not use it for scraping sensitive data or spamming.

👤 Author
Developed by Maulik Kumar
🔗 GitHub Profile

