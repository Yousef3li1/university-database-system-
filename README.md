# 🎓 University Management System  

## 📌 Overview  
The **University Management System** is a **relational database-driven application** designed to streamline **university operations**, including **students, faculty, departments, courses, and employees**. It ensures **data integrity, efficiency, and structured relationships** between various university entities for effective academic management.  

---

## 🚀 Features  
✅ **Manage Universities** – Store details of multiple universities with unique addresses.  
✅ **Department Management** – Track different departments and their assigned majors.  
✅ **Course & Faculty Assignments** – Assign multiple professors to courses.  
✅ **Student Enrollment** – Maintain structured records of students and their professors.  
✅ **CRUD Operations** – Easily **Create, Read, Update, and Delete** data.  
✅ **Data Relationships** – Ensure **data integrity** through **foreign key constraints**.  

---

## 🛠️ Technologies Used  

| Category  | Technologies |
|-----------|-------------|
| **Database** | MySQL |
| **Query Language** | SQL (Structured Query Language) |
| **Operations** | CRUD (Create, Read, Update, Delete) |
| **Optimization** | Indexing, Foreign Keys |

---

## 📂 Database Structure  

| **Table Name**  | **Description** |
|----------------|----------------|
| `university`  | Stores university names and addresses. |
| `employee`    | Holds university staff details, linked to universities. |
| `department`  | Manages department names and their corresponding majors. |
| `course`      | Contains course details, linked to departments. |
| `doctor`      | Stores faculty member details (professors). |
| `cou_doc`     | Many-to-many relationship between **courses** and **faculty members**. |
| `student`     | Student records, linked to their assigned professor. |

---

