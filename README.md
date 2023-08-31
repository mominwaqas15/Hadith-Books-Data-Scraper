# Data Scraping Project

Welcome to the Data Scraping project! This repository contains the code and resources for scraping data from various sources. The project focuses on gathering information from websites and platforms to extract valuable data for analysis and other purposes.

## Project Overview

The goal of this project is to collect data from different sources using web scraping techniques. By scraping data from websites and platforms, we aim to extract relevant information that can be utilized for various purposes such as analysis, research, or building applications.

In this project, we have specifically targeted two websites: sunnah.com and 40hadithnawawi.com. We have scraped book titles, chapter information, and Forty Hadith related to a particular topic. The following steps were involved in this process:

1. **Identify the Targeted Websites**: We identified sunnah.com and 40hadithnawawi.com as the websites containing the desired data. They provide a comprehensive collection of hadith books and related information.

2. **Web Scraping**: We utilized web scraping techniques to extract the book titles, chapters, and Forty Hadith from sunnah.com and 40hadithnawawi.com. The code for scraping is provided in the `Scrape_Data.ipynb` Jupyter Notebook. We used the BeautifulSoup library in Python to parse the HTML structure of the web pages and extract the relevant data.

3. **Data Parsing and Cleaning**: Once the data was scraped, we performed parsing and cleaning operations to ensure the data's accuracy and consistency. This involved handling different text formats, removing unnecessary characters or tags, and standardizing the data structure.

4. **Data Integration and CSV File Creation**: We integrated the scraped data into CSV (Comma-Separated Values) files. This format allows easy storage and sharing of tabular data. The following CSV files were created:
   - `Scraped Data Books.csv`: Contains the scraped book titles and related information from sunnah.com.
   - `Book Name.csv`: Contains the scraped book titles from 40hadithnawawi.com.
   - `40 hadith.csv`: Contains the scraped Forty Hadith from 40hadithnawawi.com.

5. **Database Integration**: To further enhance the data management and querying capabilities, we have also provided a SQL Server database file named `Scraped_Data.bacpac`. This file can be imported into a SQL Server database using the appropriate tools provided by SQL Server management tools. It contains the scraped data in a structured format.

## Project Structure

The project has the following structure:

- `Scrape_Data.ipynb`: Jupyter Notebook file containing the code for web scraping book titles, chapters, and Forty Hadith from the targeted websites.
- `Scraped Data Books.csv`: CSV file that stores the scraped book titles and related information from sunnah.com.
- `Book Name.csv`: CSV file that stores the scraped book titles from 40hadithnawawi.com.
- `40 hadith.csv`: CSV file that stores the scraped Forty Hadith from 40hadithnawawi.com.
- `Scraped_Data.bacpac`: A data-tier application file in `.bacpac` format that contains the scraped data. Import this file into a SQL Server database.

## Getting Started

To get started with this project, follow these steps:

1. Install the required dependencies mentioned in the `dependencies.txt` file. Ensure that you have Python 3.11 installed on your system.

2. Open the `Scrape_Data.ipynb` Jupyter Notebook and execute the cells to scrape the book titles, chapters, and Forty Hadith from the targeted websites. Adjust the code as necessary to target different topics or websites.

3. The scraped data will be stored in the respective CSV files. Feel free to modify the code in the Jupyter Notebook to change the output file name or format.

4. If you want to use the SQL Server database, import the `Scraped_Data.bacpac` file into a SQL Server database using the appropriate tools provided by SQL Server management tools. Ensure that you have the necessary permissions and connection details to create the database and import the data.

5. Modify the code or scripts as per your requirements to extend the scraping functionality, integrate with other data sources, or perform additional data transformations.

## Additional Resources

- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/): Official documentation for BeautifulSoup, a Python library used for web scraping.
- [Jupyter Notebook](https://jupyter.org/): Official website for Jupyter Notebook, an open-source web application that allows creating and sharing documents containing live code, equations, visualizations, and narrative text.

## License

This project is licensed under the [MIT License](LICENSE).
