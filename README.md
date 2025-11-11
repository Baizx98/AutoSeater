# 🎯 AutoSeater

A fully offline, interactive seating arrangement and personnel assignment system.  
Designed for classrooms, exam rooms, conferences, auditoriums, and event seating layouts.

Supports customizable seat states, batch editing, Excel-based people import, unique seat assignment management, intelligent highlight & locate features, and precise Ctrl+Scroll zooming.

---

## ✨ Features

| Capability                       | Description                                                      |
| -------------------------------- | ---------------------------------------------------------------- |
| 🪑 **Interactive Seat Layout**    | Click, multi-select, or drag to swap seats between people        |
| 🎨 **Seat States & Colors**       | Custom seat categories (Leader, Teacher, Office, Reserved, etc.) |
| 🗂️ **Excel Import & Export**      | Import personnel list and export final seating arrangement       |
| 🔍 **Locate Assigned Person**     | Click a person to center and highlight their seat                |
| 🟦 **Accurate Marquee Selection** | Selection box remains correct even after zoom & pan              |
| 🔒 **Unique Seat Assignment**     | A person can only occupy one seat at a time                      |
| 🖼️ **PNG Seating Chart Export**   | Quickly generate printable seating maps                          |
| 🧭 **Ctrl + Scroll Zooming**      | Smooth scalable canvas without accidental zooming                |
| 🧰 **Fully Offline**              | No server required — open `index.html` and start using           |

---

## 🚀 Getting Started

### 1. Clone or Download Repository
` git clone https://github.com/yourname/your-repo.git `

### 2. Open the Application
Simply **double-click**:

` index.html `

No server, no dependencies, no install.  
Works on Windows / macOS / Linux.  
### 3. Try Online
<https://site.baizx.cool>  
---

## 🧩 File Structure

.  
├── index.html # Main application  
├── README.md # Documentation  
├── docs/ # (Optional) screenshots, diagrams  
└── data/ # (Optional) sample Excel files  

---

## 📁 Recommended Excel Format

| name  | state (optional) |
| ----- | ---------------- |
| Alice | Teacher          |
| Bob   | Leader           |
| Carol | (empty)          |

State is optional and can be used for filtering before assignment.

---

## 🎨 Customizing Seat Layout

Modify layout in the **Layout (JSON)** section inside the application:
```
{
"rows": 16,
"cols": 25,
"seat": { "w": 46, "h": 30, "gap": 10 },
"labels": { "stage": "主席台", "booth": "放映室" }
}
```
Add aisles using tokens like:
` r5,c6,c19 `

---

## 📦 Exporting Results

| Export Type              | Button         |
| ------------------------ | -------------- |
| Seating Chart (PNG)      | `Export PNG`   |
| Assignment Sheet (Excel) | `Export Excel` |

---

## ⭐ Support & Feedback

If you find this useful, please consider **starring ⭐ the repository** — it helps very much!

Feel free to open:
- Issue → bug reports or feature requests
- Discussion → idea sharing or use cases

---

## 🤝 Contributions

Contributions are welcome.  
Fork → Improve → Pull Request.

---

### ❤️ Enjoy your organized seating workflow!
