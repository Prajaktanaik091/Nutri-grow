NutriGrow is a Java-based desktop application that reads data from an Excel sheet and provides a diagnosis of child malnutrition levels based on height (length) and weight inputs. The app also suggests appropriate diet plans depending on the severity of malnutrition.

Table of Contents
   Features
   Installation
   Usage
   Technologies Used

Features:
Input child's height and weight to diagnose malnutrition levels.
Diagnosis of severe, moderate, mild malnutrition, or normal.
Provides custom diet plans based on the child's age and malnutrition level.
Interactive GUI built using Java Swing.
Reads data from an Excel file using Apache POI for malnutrition level comparison.

Installation:
Prerequisites:
Ensure you have the following tools installed on your system:

Java 8 or later
Apache POI Library (for working with Excel files)
Swing (for GUI)

Usage:
Launch the application by running the ExcelSearchApp class.
Input the child's height (cm) and weight (kg).
The program will:
Search the Excel sheet for corresponding data.
Display a message indicating the malnutrition level.
Prompt for the child's age to recommend a suitable diet plan.
The app will provide a diet plan based on the child's malnutrition level and age.

Technologies Used:
  Java Swing: For building the graphical user interface (GUI).
  Apache POI: For reading Excel files in Java.
  Java: Core programming language.
