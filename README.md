# 🔍 Inverted Search using Hash Table in C

A powerful text indexing tool that reads `.txt` files, analyzes word occurrences, and stores metadata efficiently using a **Hash Table**. Ideal for building fast search systems similar to real-world databases like Aadhaar or PAN systems.

---

## 📌 Overview

This C project implements an **Inverted Search Engine** using the **Hash Table** data structure to efficiently index and retrieve word-based data from multiple text files.

Each word is:
- Indexed into the hash table based on its initial character
- Tracked for:
  - **Number of occurrences in a file**
  - **Number of files the word appears in**

This project demonstrates how hashing helps **reduce time complexity** and is highly applicable to real-time data indexing systems.

---

## ⚙️ Features

- 🗂️ **Create Database**: Parses and indexes data from one or more `.txt` files into a hash table.
- 🔎 **Search Data**: Quickly search for a word and get details about its occurrences.
- 🧾 **Display Data**: View the full hash table with word details.
- 💾 **Save Data**: Store the hash table into a persistent `.txt` file.
- 🔁 **Update Database**: Add new files and update the existing hash table without data loss.

---

## 🛠 Technologies Used

- Language: **C**
- Data Structure: **Hash Table**
- File I/O for reading and saving database

---

## 🚀 How to Run

### 🧱 Compile

gcc inverted_search.c -o inverted_search

