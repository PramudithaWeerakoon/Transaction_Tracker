<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
</head>
<body>

<h1>Transaction Tracker</h1>

<h2>Overview</h2>
<p>
    Welcome to the Transaction Tracker repository! This project is designed to track and categorize financial transactions, such as salary, food, and other expenses. It is a simple yet effective system that allows users to log and retrieve their transaction history efficiently.
</p>

<h2>Features</h2>
<ul>
    <li><strong>Transaction Logging:</strong> Log transactions under various categories like salary, home, food, etc.</li>
    <li><strong>JSON Data Structure:</strong> The system outputs transaction data in an easy-to-read JSON format.</li>
    <li><strong>Category-based Organization:</strong> Transactions are categorized for easy retrieval and management.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Python</strong> (or relevant language/library)</li>
    <li><strong>JSON</strong> for data storage and retrieval</li>
</ul>

<h2>Sample Output</h2>
<pre>
<code>
{
  "hi": [
    {"date": "2023/12/1", "amount": 1000.0},
    {"date": "2023/12/1", "amount": 1000.0}
  ],
  "home": [
    {"date": "2023/12/1", "amount": 2000.0},
    {"date": "2023/12/12", "amount": 2000.0}
  ],
  "shakya": [
    {"id": "10", "date": "28/04/2024", "amount": 12000.0}
  ],
  "salary": [
    {"id": "15", "date": "2022-11-12", "amount": 25000.0, "type": "salary"}
  ],
  "food": [
    {"id": "16", "date": "2022-12-16", "amount": 400000.0}
  ]
}
</code>
</pre>

<h2>Getting Started</h2>
<ol>
    <li><strong>Clone the Repository:</strong>
        <pre><code>git clone https://github.com/PramudithaWeerakoon/Transaction_Tracker.git</code></pre>
    </li>
    <li><strong>Navigate to the Project Directory:</strong>
        <pre><code>cd Transaction_Tracker</code></pre>
    </li>
    <li><strong>Install Dependencies:</strong>
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li><strong>Run the Application:</strong>
        <pre><code>python main.py</code></pre>
    </li>
</ol>

<h2>Contributing</h2>
<p>
    We welcome contributions from the community to enhance the features and functionalities of the Transaction Tracker. If you have ideas for improvements, feel free to open issues or submit pull requests.
</p>

<h2>License</h2>
<p>
    This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
</p>

<h2>Contact</h2>
<p>
    For inquiries or feedback, please contact the project maintainer:
</p>
<ul>
    <li><a href="mailto:pramudithapaypal@gmail.com">Pramuditha Weerakoon</a></li>
</ul>

<p>Thank you for your interest in the Transaction Tracker!</p>

</body>
</html>
