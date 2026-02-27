# Smart Expense Tracker

1. A full-stack web application that allows users to manage and track their daily expenses effieciently.
2. It gives you a month-wise total of your expenses and helps you compare your monthly expenses.
3. The application provides a simple user- friendly interface to record, monitor, and visualize spending patterns.

_ _ _

## Features

1. User Registration & Login Authentication.
2. Add New Expenses.
3. Delete Expenses.
4. View Expense History.
5. Expense Visualization with Charts
6. Category-wise Expense Tracking

_ _ _

## Tech Stack

**Frontend**
1. HTML
2. CSS
3. JavaScript

**Backend**
1.Python
2.Flask

**Database**
1.MySQL


## Requirements

```
A version of python
pip package manager installed
Local instance of MySQL running on localhost as user root
Set MySQL password as an environment variable as 'MYSQL_PWD'
Run queries.sql
```

```bash
pip install flask
pip install mysqlclient
pip install flask-mysqldb
pip install flask-WTF
pip install passlib

```


## Quick Start

```bash
# Clone the repository
git clone https://github.com/kavishamishra/Smart-Expense-Tracker.git
```

## Go to the directory where you cloned the repository

> Run

```bash
python app.y
```

Runs the app in the development mode.<br />
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

# Info

1. In this website,a user can signup and feed in his daily expenses and keep a track of it.The user can see the history of his expenses and filter them on the basis of month and year.The user can also visualise the data using the graphs provided.If the user,forgets the password,he can also change his password based on his email.A mail will be sent to the users address and the user can change the password by clicking on the link provided in the mail.

2. Mobile Responsive


# Overview Of The Website

<p align="center">Sign Up Page</p>
<p align="center">
 <img src="./static/signup.png">
</p>

<p align="center">Login Page</p>
<p align="center">
 <img src="./static/login.png">
</p>

<p align="center">Add Transaction Page</p>
<p align="center">
 <img src="./static/add.png">
</p>

<p align="center">Transaction History Page</p>
<p align="center">
 <img src="./static/history.png">
</p>

<p align="center">Category Wise Pie Chart For Current Year</p>
<p align="center">
 <img src="./static/pie.png">
</p>

<p align="center">Comparison Between Current Year And Previous Year Transactions</p>
<p align="center">
 <img src="./static/comparison.png">
</p>

<p align="center">Daily Line Chart for Current Month</p>
<p align="center">
 <img src="./static/line.png">
</p>

## Learning Outcomes

1. Implemented user Authentication 
2. Performed CRUD operations using Flask
3. Connected MySQL database with Python
4. Built data visualisation using charts

## Future Improvements

1. Improve UI responsiveness
2. Add monthly budget alerts


## Author

- [Kavisha Mishra]("https://github.com/kavishamishra")

