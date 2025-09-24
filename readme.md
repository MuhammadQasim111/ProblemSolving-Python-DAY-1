# 🧮 Algorithmic Problem Solutions

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat&logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

This repository contains clean and well-documented solutions to common **algorithmic problems** in Python.  
Each problem includes a **problem statement**, **constraints**, **approach explanation**, and **working code** with driver examples.

---

## 📌 Problems Implemented

### 1️⃣ Strobogrammatic Number

#### Problem Statement
Given a string `num` representing an integer, determine whether it is a **strobogrammatic number**.  
A number is *strobogrammatic* if it looks the same when rotated 180° (viewed upside down).

- Example:  
  - ✅ `"69"` → Strobogrammatic  
  - ✅ `"88"` → Strobogrammatic  
  - ❌ `"962"` → Not Strobogrammatic  

#### Constraints
- `1 <= num.length <= 50`
- `num` contains only digits.
- No leading zeros (except `"0"` itself).

#### Approach
- Use a **two-pointer technique** to compare digits from both ends.
- Maintain a mapping of valid strobogrammatic pairs:  
