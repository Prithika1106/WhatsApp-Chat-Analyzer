# 🧬 GroupDNA - WhatsApp Chat Analyzer

## 📌 Overview

GroupDNA is a Python-based WhatsApp chat analytics project that analyzes exported WhatsApp group conversations and generates meaningful insights about group behavior, activity patterns, and communication styles.

The project converts raw chat data into a structured analytical report.

---

## 🎯 Objective

The goal of this project is to understand:

- Who is the most active member?
- When is the group most active?
- What words define the group?
- Who is the night owl?
- Who stays silent?
- What personality does each member represent?

---

## 🚀 Features

### 1. WhatsApp Chat Parser
- Reads raw WhatsApp `.txt` export file
- Extracts:
  - Date
  - Time
  - Sender
  - Message

Handles:
- System messages
- Deleted messages
- Media messages
- Empty lines

---

### 2. Group Overview

Provides:

- Total messages
- Number of participants
- Active members ranking
- Contribution percentage

---

### 3. Activity Analysis

Analyzes:

- Most active day
- Most active hour
- Message patterns

---

### 4. Activity Heatmap

Created using NumPy.

Shows:
- User activity by hour
- Peak communication timings

---

### 5. Word Analysis

Finds:

- Most used words
- Group-specific vocabulary
- Common phrases

---

### 6. Response Analysis

Calculates:

- Average response time
- Silent streaks

---

### 7. Personality Archetypes

Assigns personalities based on behavior patterns:

Examples:

🌙 Night Owl  
🔥 Spammer  
👻 Ghost  
💬 Storyteller  
❤️ Caretaker


---

## 🛠 Technologies Used

- Python
- NumPy
- File Handling
- String Processing
- Data Cleaning
- Exploratory Data Analysis


---

## 📂 Project Structure
GroupDNA-WhatsApp-Chat-Analyzer/

│
├── Minor_project1.ipynb
├── hostel_bois.txt
├── README.md
└── requirements.txt
