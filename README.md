# Gym Management System (Flask + MongoDB)

A Gym Management System built with **Python Flask**, **MongoDB**, and basic **HTML/CSS**.  
It includes user management, reservations, services, trainers, and announcements.

Developed by **Kyriakos Papoutsis**

Bachelor of Science (BSc) in Digital Systems
*Specialization: Software and Data Systems*  
*Secondary Track: Information Systems*  
Department of Digital Systems, University of Piraeus

---

## 🏗️ Tech Stack

| Layer        | Technology              |
|--------------|--------------------------|
| Backend      | Python Flask             |
| Database     | MongoDB                  |
| Data Format  | JSON                     |
| Frontend     | HTML, CSS                |
| Dependencies | pymongo, requests, Flask |

---

## 🔧 Installation & Setup

Follow these steps to install **all required software** and run the project.

---

### **1️⃣ Install Required Software**

You MUST have the following installed on your system:

| Software | Download Link |
|----------|----------------|
| **Python (3.10+)** | https://www.python.org/downloads/ |
| **Git** | https://git-scm.com/downloads |
| **MongoDB Community Server** | https://www.mongodb.com/try/download/community |
| **MongoDB Compass** (GUI) | https://www.mongodb.com/try/download/compass |
| *(Optional)* MongoDB Database Tools | https://www.mongodb.com/try/download/database-tools |

✔ Ensure MongoDB is running on `localhost:27017`  
✔ When installing Python, check **"Add Python to PATH"**

---

### **2️⃣ Clone the Repository**

```bash
git clone https://github.com/KyriakosPapoutsis/Gym-Management-System-Flask-MongoDB.git
cd Gym-Management-System-Flask-MongoDB/my_files
```

---

### **3️⃣ (Optional) Create a Virtual Environment**

This step is optional but recommended to keep project dependencies isolated.

#### Windows:
```bash
python -m venv venv
venv\Scripts\activate
```
macOS / Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

If you skip this step, just make sure you have Python 3.10+ installed on your machine.

---

### **4️⃣ Install Python Dependencies**

If you created a virtual environment, ensure it is activated.

Install all required packages:
```bash
pip install -r ../requirements.txt
```

---

### **5️⃣ Load Initial MongoDB Data**
Using MongoDB Compass:

Open Compass

Connect to:
```bash
mongodb://localhost:27017
```
Create a database named: Gym
For each JSON file inside ../my_db/, create a collection with the same name and import the file.
Required collections:
- users
- trainers
- services
- announcements
- reservations

---

### **6️⃣ Run the Application**

From the my_files directory:
```bash
python app.py
```
Flask will start at:
```bash
http://localhost:5000/
```
Open the homepage:
```bash
http://localhost:5000/homeHTML
```

---

## 🖼️ Screenshot

<p align="center">
  <img src="static/home-image1.jpg" alt="Homepage Screenshot" width="70%">
</p>
