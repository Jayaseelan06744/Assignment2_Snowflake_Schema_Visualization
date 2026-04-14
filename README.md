# Assignment2_Snowflake_Schema_Visualization

## ▶️ Run This Project Online
Click below to open and run the notebook in Google Colab:
[(https://colab.research.google.com/github/Jayaseelan06744/Assignment2_Snowflake_Schema_Visualization/blob/main/Snowflake_Schema_Assignment.ipynb)]

# Snowflake Schema Visualization using Python

## 📖 Overview

This project presents a visual representation of the Snowflake Schema using Python. The schema is implemented and visualized using NetworkX and Matplotlib in a Jupyter Notebook environment.

The main objective is to understand how data warehouse schemas are structured and how Snowflake Schema differs from Star Schema.

---

## ⭐ Star Schema

* Contains a central fact table connected directly to dimension tables
* Simple structure
* Faster query performance
* Less normalization

---

## ❄️ Snowflake Schema

* Extension of Star Schema
* Dimension tables are normalized into multiple sub-tables
* Reduces redundancy
* More structured and scalable

---

## ⚙️ Technologies Used

* Python
* NetworkX
* Matplotlib
* Jupyter Notebook

---

## 🧠 How It Works

1. A graph is created using NetworkX
2. Nodes represent tables (fact, dimensions, sub-dimensions)
3. Edges represent relationships between tables
4. A custom layout is applied to organize schema levels
5. The graph is visualized using Matplotlib

---

## 📊 Example Use Case

This type of schema is widely used in:

* Data Warehousing
* Business Intelligence systems
* College analytics systems (student performance, attendance tracking)

---

## 🚀 Learning Outcome

* Understanding Star vs Snowflake Schema
* Data modeling basics
* Visualization of database relationships

---

## 📌 Conclusion

The Snowflake Schema provides a structured and normalized way of organizing data. This project helps visualize complex relationships in a simple and understandable way.
