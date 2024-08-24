# Web Scraping and MySQL Integration Project for Entervi.com

This project is designed to scrape data from various websites and directly insert the scraped data into a MySQL database. The database is being created for the e-commerce website [entervi.com](https://entervi.com). The purpose of this project is to gather data about companies, their products, and other relevant information, which will be stored in a structured format within the MySQL database. This data will then be used to populate the product listings and other sections of the Entervi.com website.

## Explanation of the Project

The main goal of this project is to automate the process of collecting data from multiple sources and storing it directly in a MySQL database. This is particularly useful for Entervi.com, an e-commerce platform that requires a large and constantly updated database of products, suppliers, and their associated information.

The project uses Selenium to handle the web scraping, enabling the automated extraction of data from websites. The scraped data is immediately inserted into the MySQL database without intermediate steps, ensuring that the database is always up to date with the latest information.

By storing this data in a structured MySQL database, Entervi.com can efficiently display product listings, supplier information, and more, while also providing search and filtering functionality for users.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```

2. **Create a MySQL Database:**

   Ensure you have a MySQL database created to store the scraped data. Update the database connection details in `db/connection.py`.

3. **Install Dependencies:**

   Install the required Python packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

## Contributing

If you would like to contribute, feel free to fork the repository and submit a pull request. Contributions are welcome!

