# 📝 ToDo App

A simple To-Do List app built with **React** and **Vite**.  
This project is great for learning React basics like components, props, and state.

---

## 🚀 Features
- ➕ Add new tasks
- 🗑️ Delete tasks
- ⚡ Fast dev environment with Vite
- 🎨 Basic styling with CSS

---

## 📸 Screenshot

<img width="405" height="564" alt="Screenshot 2025-09-30 151338" src="https://github.com/user-attachments/assets/9f72fd14-7bbf-4abe-99e0-220ed9c15500" />

---

## 📂 Project Structure
```
public/
 └── styles.css         # App styles

src/
 ├── index.jsx          # Entry point (renders App)
 └── components/
     ├── App.jsx        # Main component (manages state)
     ├── InputArea.jsx  # Input + Add button
     └── ToDoItem.jsx   # List item with delete feature

index.html              # App HTML entry
package.json            # Dependencies
vite.config.js          # Vite config
```

---

## 🛠️ Requirements
- Node.js (v14 or higher)
- npm

---

## ▶️ Run the App

Install dependencies:
```sh
npm install
```

Start development server:
```sh
npm run dev
```
Open the app at the URL shown (http://localhost:5173).

Build for production:
```sh
npm run build
```

Preview production build:
```sh
npm run preview
```

---

## 💡 Notes
- For learning purposes, the app uses array index as React keys.  
  For real apps, use unique IDs.

---

## 🤝 Contributing
1. Fork this repo
2. Create a feature branch
3. Open a PR

---

## 📜 License
This project is open source. Do whatever you like with it! 🚀
