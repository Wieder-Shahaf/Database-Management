<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Stock Management System</h1>
    <p>
        This project is a Django-based web application for managing stock trading data. It allows investors to view and purchase stocks, track transactions, and access analytics related to stock performance. This project builds upon a prior phase, expanding the functionality with a database-driven system.
    </p>
    <h2>Project Overview</h2>
    <p>
        The system is implemented through a single Django app named <strong>Stocks_App</strong>, using several data models that represent key entities in the stock trading domain. The models manage data for investors, companies, stocks, transactions, and stock purchases.
    </p>
    <h2>Database Models</h2>
    <ul>
        <li><strong>Investor</strong>: Stores details about each investor, including their ID, name, and available cash balance.</li>
        <li><strong>Company</strong>: Holds information about companies, such as symbol, sector, and founding details.</li>
        <li><strong>Stock</strong>: Tracks company stock prices on various dates.</li>
        <li><strong>Buying</strong>: Logs each stock purchase by an investor.</li>
        <li><strong>Transactions</strong>: Records monetary transactions made by investors.</li>
    </ul>
    <h2>Key Features</h2>
    <ul>
        <li><strong>Home Page</strong>: A welcoming page with navigation to all other sections of the site.</li>
        <li><strong>Query Results Display</strong>: Displays results from complex database queries on investor and stock data.</li>
        <li><strong>Transaction Entry</strong>: Allows investors to log fund transfers into their investment accounts.</li>
        <li><strong>Stock Purchase Entry</strong>: Enables investors to purchase stocks while validating available cash.</li>
    </ul>
    <h2>Challenges Addressed</h2>
    <p>
        The main challenges in this project include handling complex database relationships, validating user inputs, and optimizing SQL queries for efficient data retrieval. Additional care was taken to ensure data consistency, especially regarding transactions and stock purchases.
    </p>
    <h2>Getting Started</h2>
    <p>
        Ensure Django is set up and install any additional dependencies. Run the SQL script provided to create necessary tables before launching the app. Use the provided templates and static files for a complete web experience.
    </p>
    <h2>Summary</h2>
    <p>
        This project provides a robust platform for managing stock transactions and investor data. It leverages Django’s ORM and custom SQL views for a powerful, database-backed application.
    </p>
</body>
</html>
