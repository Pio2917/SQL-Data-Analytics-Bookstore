# Bookstore Data Analysis with SQL

## Project Overview

This repository contains a series of SQL queries designed to extract valuable insights from an online bookstore database. As a data analyst, this project demonstrates my ability to manipulate and query relational databases to answer key business questions related to sales performance, customer behavior, and book popularity.

The analysis covers:
* Identifying top-selling books.
* Calculating revenue generated by authors.
* Understanding customer purchasing patterns.
* Extracting specific order details.
* Analyzing book review data.

## Database Schema

The bookstore database consists of the following tables:
* `authors`: Stores information about book authors.
* `books`: Contains details about each book, including title, author, and price.
* `customers`: Holds customer information.
* `order_items`: Links orders to books and specifies quantities.
* `orders`: Contains general order information, such as customer and order date.
* `reviews`: Stores customer reviews and ratings for books.

## Key Questions Answered

1.  **Top 5 Most Popular Books:** Retrieve a list of the top 5 most ordered books, ordered by author name in descending order.
2.  **Author Revenue Contribution:** Calculate the total revenue generated by each author from their book sales.
3.  **Top 5 Customers by Orders:** Identify the top 5 customers who have placed the most orders, ordered by customer name in descending order.
4.  **Orders Containing a Specific Book:** Find all orders that include a book with a specific `book_id` (e.g., `book_id = 1`).
5.  **Detailed Review Information for Least Rated Books:** Select detailed review information for the 5 least rated books, including book title, author name, review rating, and review text.

## Technologies Used

* **SQL (SQLite):** For querying and manipulating the database.
* **Python:** Used for running SQL queries within a Jupyter Notebook environment (via `ipython-sql` and `pandas`).
* **Jupyter Notebook:** For presenting the analysis and code.
* **Pandas:** For data manipulation and displaying query results.

## How to Run the Analysis (Local Setup)

To replicate this analysis locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Pio2917/SQL-Data-Analytics-Bookstore.git
    ```
2.  **Install Dependencies:**
    Make sure you have Python and `pip` installed. Then install the necessary libraries:
    ```bash
    pip install pandas ipython-sql SQLAlchemy
    ```
3.  **Open Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Run the Notebook:**
    Open `bookstore_data_analysis.ipynb` (or your chosen name) in your browser. Run all cells sequentially to execute the SQL queries and see the results. Ensure `q*.csv` files and `bookstore.sqlite` are in the same directory as the notebook.

## Contact

Feel free to connect with me for collaborations or discussions on data analysis projects!

* **LinkedIn:** https://linkedin.com/in/stephen-chinenye-anyalewechi-164741193]
* **Email:** anyalewechistephen@gmail.com
