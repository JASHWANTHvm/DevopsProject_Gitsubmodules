# DevopsProject_Gitsubmodules

- This repository is a monorepo that organizes and manages both the frontend and backend of a full-stack application using **Git submodules**.

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
- Navigate into the submodule folder (e.g., frontend).
- Make and commit your changes there.
- Go back to the root repo and commit the updated submodule reference.

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
- This repo uses submodules to separate concerns between frontend and backend.
- Changes made in submodules need to be pushed to their own repos first.
- Submodule paths are defined in .gitmodules.
- 
# Demo picture the project runs

![Screenshot 2025-05-12 150525](https://github.com/user-attachments/assets/63ab203f-611a-4a29-9720-a6f0707fb093)

![Screenshot 2025-05-12 150531](https://github.com/user-attachments/assets/99262ffc-a562-41a7-bf5c-91193533a56d)

![Screenshot 2025-05-12 150417](https://github.com/user-attachments/assets/958d4b63-3079-4006-b62f-597334e442f9)

![Screenshot 2025-05-12 230444](https://github.com/user-attachments/assets/9ce1c553-b9f1-45f8-b68f-556bc2959576)

![Screenshot 2025-05-12 150430](https://github.com/user-attachments/assets/c189b60f-1584-4953-bd2e-abb6c4bafb9b)







# 👨‍💻 Author

- Jashwanth V M
- Mayilanandhan D

