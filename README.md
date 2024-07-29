# Seating-Plan-Generator
This repository contains a Seating Plan Generator project coded in Python using AI techniques like K-means clustering. The project aims to automate the process of assigning rooms to students for exams across three shifts: morning, afternoon, and evening. It ensures efficient use of room capacity and faculty assignment based on domain expertise.

# Project Goals
The goal of the project is to develop an automated system that: <br>
*Uses K-means clustering to group students based on their domains of study, ensuring that students from the same domain are seated together.<br>
*Groups students based on batch distribution and room capacities, ensuring that each room is filled to its maximum capacity without exceeding the limit, and groups should be based on different exams in the same room.<br>
*Assigns faculty members to each exam room based on their expertise in the corresponding domain of study.<br>

# Project Deliverables
The project delivers the following components:<br>
*K-means Clustering Algorithm: Groups students based on their domains of study.<br>
*Optimized Seating Plan Algorithm: Generates a seating plan considering batch distribution, room capacities, and student clusters.<br>
*Faculty Assignment Algorithm: Assigns faculty members to each exam room based on their domain expertise.<br>
*User-friendly Interface: Allows administrators to input student and faculty data and view the generated seating plan and faculty assignments. <br>

# Features
*Accepts input for the total number of students, total faculty, and total rooms.<br>
*Assigns rooms to students for three shifts: morning, afternoon, and evening.<br>
*Informs about the unavailability of rooms if the number of students exceeds the capacity for the three timeslots.<br>
*Clusters students based on batch distribution.<br>
*Ensures students from the same domain are seated together.<br>
*Optimizes room usage to its maximum capacity without exceeding limits.<br>
*Assigns faculty based on their expertise in the corresponding domain of study.<br>

# Technologies Used
Python: Programming language used for the implementation. <br>
NumPy: For numerical operations.<br>
Pandas: For data manipulation and analysis.<br>
Scikit-learn: For K-means clustering and other machine learning tasks.<br>
and some others for data generation and code logic.

# Installation
To run the project, ensure you have Python installed and clone this repository:<br>
### git clone https://github.com/yourusername/seating-plan-generator.git <br>
### cd seating-plan-generator<br>

# Install the required libraries:
### pip install numpy pandas scikit-learn <br>
(and other that are writen in the first cell)
