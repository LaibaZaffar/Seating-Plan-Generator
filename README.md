# Project Description
This repository contains a Seating Plan Generator project coded in Python using AI techniques like K-means clustering. The project aims to automate the process of assigning rooms to students for exams across three shifts: morning, afternoon, and evening. It ensures efficient use of room capacity and faculty assignment based on domain expertise.

## Project Deliverables
The project delivers the following components:<br>
**K-means Clustering Algorithm:** Groups students based on their domains of study.<br>
**Optimized Seating Plan Algorithm:** Generates a seating plan considering batch distribution, room capacities, and student clusters.<br>
**Faculty Assignment Algorithm:** Assigns faculty members to each exam room based on their domain expertise.<br>
**User-friendly Interface:** Allows administrators to input student and faculty data and view the generated seating plan and faculty assignments. <br>

## Features
1. Accepts input for the total number of students, total faculty, and total rooms.<br>
2. Assigns rooms to students for three shifts: morning, afternoon, and evening.<br>
3. Informs about the unavailability of rooms if the number of students exceeds the capacity for the three timeslots.<br>
4. Clusters students based on batch distribution.<br>
5. Ensures students from the same domain are seated together.<br>
6. Optimizes room usage to its maximum capacity without exceeding limits.<br>
7. Assigns faculty based on their expertise in the corresponding domain of study.<br>

## Technologies Used
**Python**: Programming language used for the implementation. <br>
**NumPy**: For numerical operations.<br>
**Pandas**: For data manipulation and analysis.<br>
**Scikit-learn**: For K-means clustering and other machine learning tasks.<br>
and some others for data generation and code logic.

## Installation
To run the project, ensure you have Python installed and clone this repository:<br>
```bash
  git clone https://github.com/LaibaZaffar/Seating-Plan-Generator.git
  cd seating-plan-generator
```
## Install the required libraries
```bash
pip install numpy pandas scikit-learn
```
and others that are writen in the first cell.
