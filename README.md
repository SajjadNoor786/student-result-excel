# 🎓 Student Result Excel Project

This project demonstrates how to calculate student **results and grades** using Excel formulas.

---

## 📌 Task Objective

Using marks in 3 subjects (`Sub1`, `Sub2`, `Sub3`) for each student, we:
- Calculated **Pass/Fail** using logical functions (`IF + AND`, `IF + OR`)
- Calculated **Percentage**
- Assigned **Grades** based on percentage using nested `IF` and `IFS` functions

---

## ✅ Features

- Logical Result:
  - `Result AND`: Pass only if all subjects have ≥ 35
  - `Result OR`: Pass if at least one subject has ≥ 35

- Grade Assignment:
  | Percentage Range | Grade |
  |------------------|--------|
  | 80 and above     | A      |
  | 70–79            | B      |
  | 60–69            | C      |
  | 50–59            | D      |
  | Below 50         | E      |

- Percentage:  
  ```excel
  =AVERAGE(Sub1, Sub2, Sub3)
