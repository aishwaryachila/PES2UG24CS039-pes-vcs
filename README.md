
# PES Version Control System

## 📌 Overview
This project implements a mini Git-like Version Control System in C.  
It supports object storage, staging, commits, and log history.

---

## 🚀 Features
- Blob storage
- Tree structure
- Index (staging area)
- Commit system
- Log history

---

## 🛠️ How to Run

make pes  
./pes init  
./pes add <file>  
./pes commit -m "message"  
./pes log  

---

## 📸 Screenshots

### objects.png
![objects](screenshots/objects.png)

### tree.png
![tree](screenshots/tree.png)

### index.png
![index](screenshots/index.png)

### commit_file1.png
![commit1](screenshots/commit_file1.png)

### commit_file2.png
![commit2](screenshots/commit_file2.png)

### commit_file3.png
![commit3](screenshots/commit_file3.png)

### commit_file4.png
![commit4](screenshots/commit_file4.png)

### commit_file5.png
![commit5](screenshots/commit_file5.png)

---

## 📂 Project Structure

.
├── object.c  
├── tree.c  
├── index.c  
├── commit.c  
├── pes.c  
├── Makefile  
├── screenshots/  

---

## 🧠 Concepts Used
- File handling in C  
- SHA-256 hashing  
- Version control system basics  

---

## ✅ Conclusion
This project demonstrates the working of a Git-like version control system with staging, committing, and history tracking.

---