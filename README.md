# 📂 Consultant Rotation and Client Assignment Automation

Welcome to the Consultant Rotation and Client Assignment Automation Repository! 🚀

This repository streamlines the weekly client assignments among consultants, ensuring fair and balanced workload distribution through an automated rotation system. It involves an Excel data source, Python scripts, and a tracking mechanism to maintain state between runs.

I used this when I when automating the process of updating weekly clients with the team I led. I changed the names to "Client {number}" for privacy reasons instead of names and initialized my team consultants. Weekly it would run and change. It's very possible to randomly distribute as well.

### 📌 Project Overview

This system automates client assignment to consultants each week, rotating the assignments to evenly distribute workload. Perfect for managing consulting engagements, teaching assistant duties, or any role where consistent rotation is required.

### 📁 File Descriptions

1. 📃 Client_List.xlsx

Purpose: Contains the full list of clients who need to be assigned to consultants each week.

Format: Excel spreadsheet with client names listed in the first column.

Usage: Primary input file for generating weekly assignments.

2. 🔄 rotation_state.txt

Purpose: Stores the current rotation state (index) of consultants.

Format: Plain text file containing a single integer representing the rotation position.

Usage: Ensures continuity and fairness by tracking the consultant who should receive the next set of clients.

3. ⚙️ Python Automation Script (.ipynb)

Purpose: Reads the client list, manages rotation state, assigns clients evenly, and outputs the weekly assignments.

Format: Jupyter Notebook (.ipynb) containing Python scripts for automation.

Usage: Central script to perform the rotation logic and generate assignments each week.

4. 📊 Weekly_Consultant_Client_Assignments_.xlsx

Purpose: Outputs the weekly distribution of clients to consultants after running jupyter notebook.

Format: Formatted Excel spreadsheet with clear and readable assignments.

Usage: Generated by the automation script, this file serves as the weekly reference for consultant-client engagements.

### 🔗 File Relationships

Client_List.xlsx ➡️ Input file for the Python script.

rotation_state.txt 🔄 Tracks and updates rotation between script runs.

Python Script (.ipynb) 🛠️ Processes input, manages rotation logic, and generates the output assignment Excel file.

Weekly_Consultant_Client_Assignments_.xlsx 📈 Final product, ready for consultant distribution each week.

### 🚀 How to Use

Update 📃 Client_List.xlsx weekly with new or existing client names.

Run ⚙️ Python Automation Script (.ipynb) to distribute clients evenly.

Consult 📊 Weekly_Consultant_Client_Assignments_.xlsx for weekly assignments.

Enjoy automated fairness and save time managing your weekly rotations! 🌟✨

