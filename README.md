<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Database Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            font-size: 2.5rem;
        }
        h2 {
            font-size: 2rem;
            margin-top: 20px;
        }
        h3 {
            font-size: 1.5rem;
            margin-top: 15px;
        }
        code {
            font-family: "Courier New", Courier, monospace;
            background-color: #eef;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            padding: 10px;
            overflow-x: auto;
            font-size: 0.9rem;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            list-style: disc;
            margin-left: 20px;
        }
        ol {
            list-style: decimal;
            margin-left: 20px;
        }
    </style>
</head>
<body>
    <h1>📚 Library Database Analysis Project</h1>
    <p>Welcome to the <b>Library Database Analysis Project</b>! This repository contains a Python program to analyze a library's collection of books, providing insights into genres, authors, publication years, and availability.</p>

    <h2>🚀 Features</h2>
    <ul>
        <li><b>Count Available Books</b>: Determine how many books are available for borrowing.</li>
        <li><b>Unique Genres</b>: Identify all genres in the library's collection.</li>
        <li><b>Search by Author</b>: Find all books written by a specific author.</li>
        <li><b>Books by Publication Year</b>: Get a count of books published each year.</li>
        <li><b>Oldest and Newest Books</b>: Identify the oldest and newest books in the library.</li>
        <li><b>Filter by Availability</b>: View books based on their availability status.</li>
        <li><b>Filter by Genre</b>: View books belonging to a specific genre.</li>
    </ul>

    <h2>🛠️ Technologies Used</h2>
    <ul>
        <li><b>Python</b>: Core logic of the application.</li>
        <li><b>Markdown</b>: For project documentation.</li>
        <li><b>HTML/CSS</b>: Styling for a GitHub-friendly view.</li>
    </ul>

    <h2>📂 Project Structure</h2>
    <pre>
├── library_analysis.py    # Python script containing the core logic.
├── README.md              # Project documentation (this file).
    </pre>

    <h2>📖 How to Run the Project</h2>
    <h3>Prerequisites</h3>
    <p>Ensure you have Python installed on your system. If not, download it from <a href="https://www.python.org/" target="_blank">Python's official site</a>.</p>

    <h3>Steps</h3>
    <ol>
        <li>Clone this repository:</li>
        <pre><code>git clone https://github.com/mairaperveen/library-database-analysis.git
cd library-database-analysis</code></pre>
        <li>Run the script:</li>
        <pre><code>python library_analysis.py</code></pre>
    </ol>

    <h2>🔍 Example Output</h2>
    <pre>
Library Database Analysis

Number of Available Books: 4

Unique Genres in Collection:
- Adventure
- Fiction
- Romance
- Dystopian

Books by George Orwell:
- 1984

Number of Books by Publication Year:
1813: 1
1851: 1
1925: 1
1949: 1
1951: 1
1960: 1

Oldest Book(s) in Collection:
- Pride and Prejudice

Newest Book(s) in Collection:
- To Kill a Mockingbird

Available Books:
- The Great Gatsby
- 1984
- The Catcher in the Rye
- Pride and Prejudice

Books in Genre 'Fiction':
- The Great Gatsby
- To Kill a Mockingbird
- The Catcher in the Rye
    </pre>

    <h2>🤝 Contributing</h2>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a feature branch:
        <pre><code>git checkout -b feature/AmazingFeature</code></pre></li>
        <li>Commit your changes:
        <pre><code>git commit -m "Add some AmazingFeature"</code></pre></li>
        <li>Push to the branch:
        <pre><code>git push origin feature/AmazingFeature</code></pre></li>
        <li>Open a pull request.</li>
    </ol>

    <h2>📄 License</h2>
    <p>This project is licensed under the MIT License. See <code>LICENSE</code> for more information.</p>

    <h2>👨‍💻 Maintainer</h2>
    <p><b>Maira Perveen</b><br>
    GitHub: <a href="https://github.com/mairaperveen" target="_blank">@mairaperveen</a><br>
    Email: maira.perveen25@gmail.com</p>

    <h2>🌟 Show Your Support</h2>
    <p>If you found this project helpful, give it a ⭐️ and consider sharing it with others!</p>
</body>
</html>
