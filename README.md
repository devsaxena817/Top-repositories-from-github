# Top Repositories from GitHub

This Python project scrapes the top repositories from GitHub based on specific topics, leveraging the GitHub API to gather repository details. It then stores the scraped data in CSV files for each topic.

## 🚀 Features

- Scrapes top repositories for each topic on GitHub.
- Stores repository data (name, stars, forks, issues) in CSV files.
- Utilizes **requests** and **BeautifulSoup** for web scraping.
- Uses **pandas** for data manipulation and saving to CSV.
- Can be customized to scrape additional details or handle different topics.

## 🗂️ Project Structure

Top-repositories-from-github/  
│  
├── .gitignore  
├── scrape-topics.py               # Scrapes all topics  
├── scrape-top-repos.py           # Scrapes top repositories from each topic  
├── get_topic_titles.py           # Helper function to get topic titles  
├── requirements.txt              # Python dependencies  
├── README.md                     # Project documentation  
└── data/                         # Folder where CSVs for each topic are stored

## 📝 How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/devsaxena817/Top-repositories-from-github.git
   cd Top-repositories-from-github
   Install dependencies:

Make sure you have Python 3.x installed, and then install the required packages from requirements.txt:

bash
Copy
Edit
pip install -r requirements.txt
Run the scripts:

To scrape the topics and save them to a CSV file:

bash
Copy
Edit
python scrape-topics.py
To scrape the top repositories for each topic and store them in CSV files:

bash
Copy
Edit
python scrape-top-repos.py
If you just want to get the list of topics:

bash
Copy
Edit
python get_topic_titles.py
Output:

After running the scripts, you will find a data/ folder containing CSV files. Each file corresponds to a GitHub topic and contains the top repositories for that topic.

🔧 Requirements
Python 3.x

requests: for making HTTP requests

BeautifulSoup4: for web scraping

pandas: for data manipulation and saving to CSV

Install the required dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
📂 Dependencies
This project uses the following Python libraries:

requests: HTTP library for making requests to the GitHub API

BeautifulSoup4: Web scraping library for parsing HTML and XML

pandas: Data analysis library for handling and saving data in CSV format

You can install these dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
🤖 Example Usage
Scrape top repositories from a topic:

After running the scrape-top-repos.py script, you'll have CSV files for each GitHub topic in the data/ folder. These CSV files contain the following details for each repository:

Repository name

Stars

Forks

Issues count

Customize the script:

You can modify the scrape-top-repos.py file to scrape additional information from the repositories or change the way repositories are filtered.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
📬 Contact
For questions, issues, or feedback, please open an issue or contact devsaxena817 on GitHub.
