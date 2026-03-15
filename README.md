This project demonstrates how recommendation features used in social networks can be implemented using Python.

It includes implementations for:
* Mutual Friend Recommendation ("People You May Know")
* Page Recommendation ("Pages You May Like")

The system first loads and processes a **JSON dataset**, then applies different recommendation logics using the same data.

Technologies Used
* Python
* JSON data handling
* Jupyter Notebook
* Basic graph and similarity logic

Project Workflow
 1. JSON Data Handling
The dataset is stored in JSON format containing information about users, their friends, and pages they follow.
The notebook demonstrates how to:

* Load JSON data
* Convert it into Python dictionaries
* Access and manipulate social network data


2. Pages You May Like
This feature recommends pages to users based on **similar interests and page interactions**.

Approach:
* Analyze pages liked by a user’s friends
* Identify popular pages among similar users
* Recommend pages the user has not liked yet

This simulates the Pages You May Like feature used in social media platforms.

How to Run

1. Clone the repository
2. Open the Jupyter notebooks
3. Run the cells step by step to see:

   * JSON data loading
   * Page recommendation


* Implement recommendation ranking
* Convert the system into a web application
