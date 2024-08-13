# Job Scraping and Data Cleaning Project

This project is a Python-based web scraping tool designed to extract job listings from [Wuzzuf](https://wuzzuf.net/), a popular job search website in Egypt. The script scrapes job titles, company names, locations, job times, and descriptions, cleans and organizes the data, and finally stores it in a CSV file for easy analysis.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data Cleaning Process](#data-cleaning-process)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The primary purpose of this project is to automate the collection of job listing data from Wuzzuf, enabling users to quickly gather and analyze job market trends. The data is processed and cleaned to ensure that it is suitable for further analysis or direct usage in other projects.

## Features

- **Automated Web Scraping**: Fetches job listing data from Wuzzuf based on a user-defined search query.
- **Data Storage**: Saves the extracted data into a CSV file for easy access and analysis.
- **Data Cleaning**: Processes and cleans the scraped data to remove unnecessary characters and format it properly.
- **Flexible Search**: Allows users to specify the search query and the number of pages to scrape.

## Technologies Used

- **Python**: The core language used for scripting and data manipulation.
- **Selenium**: A powerful web scraping tool used to interact with web pages and extract data.
- **Pandas**: Used for data manipulation and cleaning.
- **CSV**: The format used for saving the scraped data.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Keroles-Ramses/Job-Scraping-Project.git
    cd Job-Scraping-Project
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download and Install ChromeDriver**:
    - Ensure that the [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) version matches your Chrome browser version.
    - Add the ChromeDriver executable to your system's PATH.

## Usage

1. **Run the Script**:
    - Execute the script by running:
    ```bash
    python job_scraper.ipynb
    ```

2. **Enter the Search Query**:
    - You'll be prompted to enter the job title or keyword you want to search for.
  
3. **Enter the Number of Pages to Scrape**:
    - Specify the number of pages to scrape. Each page contains multiple job listings.

4. **View the Results**:
    - The scraped and cleaned data will be saved in a CSV file named after your search query.

## Data Cleaning Process

The script also includes a data cleaning process to organize and format the raw data into a more useful structure:
- Splits the job descriptions into separate columns.
- Cleans up and formats text fields, such as removing unwanted characters and extra spaces.
- Organizes the skills and experience details into separate, easy-to-read columns.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Open a pull request.



## Contact

If you have any questions, feel free to contact me:

- **Email**: keroles.ramses612@gmail.com
- **LinkedIn**: [Keroles Ramses](https://www.linkedin.com/in/keroles-ramses/)

---

Thank you for checking out this project! I hope you find it useful.
