# 📘 Task Manager (AJAX + JSON Server)

## 🎯 Purpose of This Project

This project helps you understand:

* How frontend (HTML + jQuery) communicates with backend
* How APIs work using:

  * GET
  * POST
  * PUT
  * DELETE
* How to run a local server using `json-server`

---

## 📂 Project Files

* `index.html` → Frontend (User Interface)
* `db.json` → Fake database (Backend)

---

## ⚙️ Requirements

Before starting, install:

* Node.js
* Git

Check installation:

```bash
node -v
git -v
```

---

## 🧱 Step 1: Create Workspace Folder (IMPORTANT)

You MUST create a folder called:

```bash
workspace
```

👉 Example location:

* Desktop/workspace

---

## 📥 Step 2: Clone This Project

Open terminal:

```bash
cd Desktop/workspace
git clone <YOUR_REPOSITORY_LINK>
```

Then:

```bash
cd <PROJECT_FOLDER_NAME>
```

---

## 📦 Step 3: Install JSON Server

Run this **once only**:

```bash
npm install -g json-server
```

---

## ▶️ Step 4: Start Backend Server (VERY IMPORTANT)

Inside the project folder:

```bash
json-server --watch db.json
```

✅ If successful, you will see:

```
http://localhost:3000/tasks
```

👉 This is your backend API.

⚠️ KEEP THIS TERMINAL OPEN

---

## 🌐 Step 5: Open the Frontend

Open:

```
index.html
```

In your browser.

---

## 🔁 How to Use the App

### Load Tasks

Click:

```
Load Tasks
```

👉 This sends a **GET request**

---

### Add Task

1. Write task name
2. Click:

```
Add Task
```

👉 This sends a **POST request**

---

### Delete Task

Click:

```
Delete
```

👉 This sends a **DELETE request**

---

### Update Task

1. Click:

```
Update
```

2. Enter new text
3. Click:

```
Confirm
```

👉 This sends a **PUT request**

---

## ⚠️ IMPORTANT NOTE

After:

* Adding
* Deleting
* Updating

👉 You must click **Load Tasks again** to refresh the list.

---

## 🧑‍💻 Your Assignment

Now YOU must create your own version.

---

### Step 1: Stay in workspace

```bash
cd Desktop/workspace
```

---

### Step 2: Create your project

```bash
mkdir my-project
cd my-project
```

---

### Step 3: Initialize Git

```bash
git init
```

---

### Step 4: Create Files

Create:

```
index.html
db.json
```

---

### Step 5: Run Your Project

```bash
json-server --watch db.json
```

Then open your `index.html`.

---

## 💡 Tips

* Always run server FIRST
* If nothing works → check terminal
* Make sure `db.json` exists
* Do NOT close the server terminal

---

## ❗ Common Mistakes

* Opening HTML before server
* Wrong folder in terminal
* Missing `db.json`
* Typing wrong command

---

## 🚀 Final Goal

You should understand how:

* Frontend sends requests
* Backend responds with data
* CRUD operations work in real apps

---

Good luck 👨‍💻
