🌙☀️ Next.js Context API Theme Toggle

This project is part of my **#100DaysOfCode MERN Stack Journey** (Day 29).  
It demonstrates how to implement a **Dark/Light Mode toggle** in a **Next.js App Router** project using the **React Context API** for global state management.  

---

## 🚀 Features
- 🌑 **Dark/Light mode toggle** with Context API  
- 🔄 **Global state management** without prop drilling  
- 💾 **Persistent theme** using `localStorage`  
- 🎨 **TailwindCSS dark mode classes** for seamless UI styling  
- 🖱️ Toggle button with custom Sun 🌞 / Moon 🌙 icons in the Header  

---

## 🛠️ Tech Stack
- [Next.js 13+ (App Router)](https://nextjs.org/)  
- [React Context API](https://react.dev/reference/react/useContext)  
- [TailwindCSS](https://tailwindcss.com/)  

---

## 📂 Project Structure
nextjs-contextapi-theme-toggle/
├── app/
│ ├── layout.js # Root layout wrapped in ThemeProvider
│ ├── page.js # Example Home page
├── components/
│ ├── Header.js # Navbar with theme toggle button
│ ├── SunIcon.js # Sun icon component
│ ├── MoonIcon.js # Moon icon component
├── context/
│ ├── ThemeContext.js # ThemeContext + Provider
├── styles/
│ ├── globals.css # TailwindCSS setup

yaml
Copy
Edit

---

## ▶️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/nextjs-contextapi-theme-toggle.git
cd nextjs-contextapi-theme-toggle
2️⃣ Install dependencies
bash
Copy
Edit
npm install
3️⃣ Run the development server
bash
Copy
Edit
npm run dev
Now open http://localhost:3000 🚀

📸 Preview

💡 Learnings
How Context API solves the prop drilling problem

How to integrate dark mode with TailwindCSS

How to persist state in localStorage for better UX

👩‍💻 Author
Sidra Akhtar
🔗 LinkedIn • Twitter

📜 License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

⚡ This README is **structured, professional, and recruiter-friendly**.  
Do you want me to also generate a **sample `package.json` and Next.js setup files** for this repo so you can dire
