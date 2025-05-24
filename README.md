# 🔢 Day 12: Inheritance | HackerRank 30 Days of Code

This repository contains the Python solution for Day 12 of the HackerRank 30 Days of Code challenge, which focuses on object-oriented programming using **class inheritance** and **method overriding**.

## 🚀 Challenge Summary

You are given two classes: `Person` and `Student`.

Your task is to extend the `Person` class by creating a `Student` class that includes a method to calculate the average grade and return a letter grade.

## 📝 Problem Statement

Complete the `Student` class by writing:

- A constructor that takes `firstName`, `lastName`, `id`, and `scores`.
  
- A method `calculate()` that computes the average score and returns the corresponding letter grade based on the grading scale.

### 📚 Grading Scale

      | Grade | Range          |
      |-------|----------------|
      | O     | 90 ≤ avg ≤ 100 |
      | E     | 80 ≤ avg < 90  |
      | A     | 70 ≤ avg < 80  |
      | P     | 55 ≤ avg < 70  |
      | D     | 40 ≤ avg < 55  |
      | T     | avg < 40       |

## ✅ Constraints

- `1 ≤ length of firstName, lastName ≤ 10`
  
- `idNumber` is a 7-digit integer
  
- `0 ≤ score ≤ 100`

## 🔢 Sample Input

        Heraldo Memelli 8135627
        
        2
        
        100 80

## ✅ Sample Output

        Name: Memelli, Heraldo
        
        ID: 8135627
        
        Grade: O

## 💡 Explanation

The student has two scores: 100 and 80.  

Average = (100 + 80) / 2 = 90  

According to the grading scale, an average of 90 returns grade `O`.

## 🧠 Concepts Practiced 

- Class Inheritance
  
- Constructors and Method Overriding
  
- Object-Oriented Programming (OOP)
  
- List operations and averages
  
- Conditional logic

## 🛠 How to Run

Option 1: With input file 

Create a file named `input.txt` with the required input and run:  

                   python3 inheritance.py < input.txt

Option 2: Manual input

Just run:

                   python3 inheritance.py

## 🔗 HackerRank Challenge Link

HackerRank – Day 12: Inheritance

🏆 Challenge Completed

✅ Problem Solved

🎯 Points Earned: 30

## 📅 Completed On:

24th May 2025

## 🔖 Tags

#Python #HackerRank #Inheritance #OOP #30DaysOfCode #ProblemSolving #Day12Challenge

## ✍ Author

          Harsha M
          
          GitHub: @Harshaharika7
          
          LinkedIn: Harsha M
