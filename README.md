# DevopsProject_Gitsubmodules

This repository is a monorepo that organizes and manages both the frontend and backend of a full-stack application using **Git submodules**.

## 📁 Project Structure

```bash
DevopsProject_Gitsubmodules/
├── frontend/   # React/Vite frontend application (Git submodule)
└── backend/    # Node.js/TypeScript backend application (Git submodule)
```
# 🚀 Getting Started
📥 Clone This Repo With Submodules
```bash
git clone --recurse-submodules https://github.com/JASHWANTHvm/DevopsProject_Gitsubmodules.git
```
Already cloned?

```bash
git submodule update --init --recursive
```

# 🔧 Frontend Setup (React + Vite)
```bash
cd frontend
npm install
npm run dev
```
This will start the Vite dev server. Open http://localhost:5173 to view it in the browser.

# 🔧 Backend Setup (Node.js + TypeScript)
```bash
cd backend
npm install
npm start
```


# 🔁 Making Changes to Submodules
Navigate into the submodule folder (e.g., frontend).
Make and commit your changes there.
Go back to the root repo and commit the updated submodule reference.

```bash
# Inside submodule
cd frontend
git add .
git commit -m "Updated frontend"

# Push to frontend repo
git push origin main

# Back to root repo
cd ..
git add frontend
git commit -m "Updated frontend submodule pointer"
git push origin main
```
# 📌 Notes
This repo uses submodules to separate concerns between frontend and backend.
Changes made in submodules need to be pushed to their own repos first.
Submodule paths are defined in .gitmodules.

# 👨‍💻 Author
Jashwanth V M and Mayilanandhan D

