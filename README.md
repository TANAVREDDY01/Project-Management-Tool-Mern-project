## Getting Started

Follow the steps below to run the project locally.

### 📦 Install Dependencies

In the **root project directory**, install server dependencies:

```bash
npm install
```

Go to the **frontend** folder and install the frontend dependencies:

```bash
cd frontend
npm install
```

### ⚙️ Build Frontend

Still inside the `frontend` folder, build the React app:

```bash
npm run build
```

### 🚀 Start the Server

Go back to the **project root folder** and run the server:

```bash
npm run devstart
```

Now, open your browser and visit:

```
http://127.0.0.1:8000/
```

---

### 🧪 Alternative: Run Client & Server Separately

You can also run the frontend and backend on separate ports for development.

From the **project root**, start the backend server:

```bash
npm run devstart
```

From the **frontend** folder, start the React app:

```bash
cd frontend
npm start
```

Visit the React frontend at:

```
http://localhost:3000
```

And the backend server will still be running on:

```
http://127.0.0.1:8000/
```
