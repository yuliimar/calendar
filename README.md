# 📅 Calendar Layout

Responsive **Calendar layout** built with **HTML + SCSS** using **BEM methodology**.
No JavaScript was used – all rendering logic (days, numbers, modifiers) is implemented via **CSS pseudo-elements** and **Sass features** (`@for`, `@each`, variables).

---

## 🚀 DEMO

🔗 [Live Demo](https://yuliimar.github.io/calendar/)

---

## 📐 Features

- **31 calendar cells** (days) by default
- Each day:
  - Square **100px × 100px** with `1px` border
  - Number displayed with `::before` and `@for`
  - Centered **Arial, 30px** text
  - Default color: **grey `#eee`**
- Calendar width: **7 columns + paddings**
- Implemented fully with **flexbox**
- **Start-day modifier**:
  `.calendar--mon`, `.calendar--tue`, … `.calendar--sun`
  - Shifts first day with margin
  - Default start: **Sunday**
- **Month-length modifier**:
  `.calendar--28`, `.calendar--29`, `.calendar--30`, `.calendar--31`
  - Controls visibility of last days
  - Default: **31 days**
- **Hover effects**:
  - cursor → `pointer`
  - background → `#FFBFCB` (pink)
  - lifted effect: `transform: translateY(-20px)`
  - smooth animation (`0.5s`)

---

## 🛠️ Technologies

- **HTML5**
- **SCSS** (Parcel bundler compiles `.scss` directly)
- **BEM methodology**
- **Flexbox**

---

## 📦 Project Structure

---

## ▶️ Getting Started

Clone repository and run locally:

```bash
git clone https://github.com/<your_account>/<repo_name>.git
cd <repo_name>
npm install
npm start
```
