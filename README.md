# Simple Task Manager

A **full-stack Simple Task Manager application** built using the **MERN stack**. It allows users to create, view, update, and delete tasks with a clean React UI and a RESTful Node.js + Express backend connected to MongoDB.

---

## Deployed Link

* UI/Frontend: [UI](https://simple-task-manager-ui-nine.vercel.app/)
* Backend: [Backend](https://task-manager-application-api-seven.vercel.app/)

## 🚀 Features

* Add new tasks
* View all tasks
* Update task status (complete / incomplete)
* Edit existing tasks
* Delete tasks
* Toast notifications for actions
* Clean and responsive UI

---

## 🛠️ Tech Stack

### Frontend

* React
* Bootstrap
* React Icons
* React Toastify

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

---

## 📁 Project Structure

```
Simple-Task-Manager/
│
├── backend/
│   ├── controllers/
│   │   └── taskController.js
│   ├── models/
│   │   ├── db.js            # Database connection
│   │   └── taskModel.js     # Task schema
│   ├── routes/
│   │   └── taskRoute.js
│   ├── .env
│   ├── index.js             # Main entry file
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md
```

---

## 🧩 API Endpoints

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| POST   | `/task`     | Create a new task |
| GET    | `/task`     | Get all tasks     |
| GET    | `/task/:id` | Get task by ID    |
| PUT    | `/task/:id` | Update task by ID |
| DELETE | `/task/:id` | Delete task by ID |

---

## 🧾 Task Schema

```js
{
  taskName: {
    type: String,
    required: true
  },
  isDone: {
    type: Boolean,
    required: true
  }
}
```

---

## ⚙️ Environment Variables

Create a `.env` file in the `backend` folder:

```env
PORT=8080
DB_URL=mongodb+srv://<username>:<password>@cluster.mongodb.net/<db-name>
```

---

## ▶️ How to Run the Project

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm start
```

---

## 📌 Notes

* Backend runs on **PORT 8080** by default
* Make sure MongoDB URL is correct
* Use `nodemon` for development (optional)

---

## ScreenShots
* UI
<img width="1600" height="761" alt="image" src="https://github.com/user-attachments/assets/3c341dde-821b-4f22-bd0f-898c09c707c7" />

* API
<img width="1600" height="815" alt="image" src="https://github.com/user-attachments/assets/0e5fa754-ac8e-4099-b16b-acb9be57bc3a" />


---

## 🔗 Repository

GitHub Repo: [Simple Task Manager](https://github.com/AryaGupta01/Simple-Task-Manager)

---

