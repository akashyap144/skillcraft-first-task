# SkillCraft Internship - Task 01  
## Population Distribution Bar Chart  

This project is part of my **SkillCraft Data Science Internship**.  
The task focuses on visualizing **India's population distribution by age group** using a simple bar chart in Python.

---

## 🔥 Key Features  
✅ Data visualization using Python  
✅ Bar chart representation of population distribution  
✅ Clean and simple representation for better understanding  

---

## 🛠 Technologies Used  
- Python  
- Matplotlib  

---

## 📂 Files in this Repository  
- `firsttask.py` → Python script to generate the population bar chart  
- `population_chart.png` → Bar chart image (generated after running the code)

---

## ✅ Code Snippet  

```python
import matplotlib.pyplot as plt

# Age groups and population data
age_groups = ['0-14', '15-24', '25-54', '55-64', '65+']
population = [350, 240, 480, 100, 80]  # population in millions

# Create the bar chart
plt.figure(figsize=(8, 5))
plt.bar(age_groups, population, color='skyblue', edgecolor='black')

# Add chart title and labels
plt.title("India's Population Distribution by Age")
plt.xlabel("Age Groups")
plt.ylabel("Population (in millions)")

# Add gridlines for better readability
plt.grid(axis='y', linestyle='--', alpha=0.7)

# Display the chart
plt.tight_layout()
plt.savefig("population_chart.png")  # Saves the chart as an image
plt.show()# skillcraft-first-task
This respiratory contains my first task of Skillcraft internship,including data cleaning and EDA


Author
Kumar Akash Deep
Skillcraft Data Science Intern
