# Week 4 AI Assignment

Name:Boniface Karanja  
Class: AI-Class SSN-10  
Date:09 March 2025

## Part 1: Data Foundations

### Question 1
**What is Data? Explain in your own words and give two Examples.**

Answer: 
Data is any piece of information that can be collected, stored, and used to learn something or make decisions. It can be numbers, text, pictures, or even sounds.

Examples:
1. Your phone number (a set of digits).
2. A photo you took with your phone.

### Question 2
**Explain the difference between Structured Data and Unstructured Data. Give two Examples of each.**

Answer:  
- Structured Data: Organized in rows and columns (like a table or spreadsheet). Easy for computers to search and analyze.  
  Examples:  
  1. Student marks in an Excel sheet (Name, Age, Score)  
  2. Bank transaction records in a database (Date, Amount, Account Number)

  -Unstructured Data: No fixed format.  
  Examples:  
  1. WhatsApp chat messages or emails  
  2. Videos or voice recordings

### Question 3
**What is a Schema? Explain using a simple example.**

Answer:  
A schema is like a blueprint or plan that shows how data should be organized.

Simple Example:    
 1: Student_ID 
 2:Banks receipt

## Part 2: Python Basics

### Question 4
**Write a Python program that prints the following message: Hello AI Students**

Answer (Python Code):
```python
print("Hello AI Students")

# Question 5 - Variables and printing
name = "Bonny"   
age = 20       
city = "Nairobi"

print("Name:", name)
print("Age:", age)
print("City:", city)
Name: Bonny
Age: 20
City: Nairobi

# Question 6 - List and accessing first item
programming_languages = ["Python", "Java", "C++", "JavaScript", "Go"]

print("First programming language:", programming_languages[0])
# or simply:
print(programming_languages[0])
First programming language: Python
Python

# Question 7 - Dictionary
student = {
    "Name": "Bonny",
    "Age": 20,
    "Course": "AI Foundations SSN-10"
}

print("Student Information:")
print("Name:", student["Name"])
print("Age:", student["age"])  
print("Course:", student["course"])    

print("\nFull dictionary:", student)
Student Information:
Name: Bonny
Age: 20
Course: AI Foundations SSN-10

Full dictionary: {'Name': 'Bonny', 'Age': 20, 'Course': 'AI Foundations SSN-10'}

Bonus Question (Optional)
Explain the difference between:
A list
A dictionary

List: An ordered collection of items (values only). Items are stored in sequence and accessed using numerical indexes (starting from 0).
Example: ["Alice", 20, "Biology"]
Dictionary: A collection of key-value pairs. Each value is associated with a unique key (not necessarily a number). You access values using the key, not position.
Example: {"name": "Alice", "age": 20, "course": "Biology"}
