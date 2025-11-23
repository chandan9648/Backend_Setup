# Backend Setup (Node.js + Express + MongoDB)

## 1. Clone the Project

```bash
git clone <repo-url>
cd backend
```

## 2. Install Dependencies

```bash
npm install
```

## 3. Create Environment File

Create a `.env` file in the project root:

```
PORT=3000
MONGO_URI=your_mongo_uri_here

```

## 4. Start MongoDB

Use local MongoDB or MongoDB Atlas:

* Local: `mongod`
* Atlas: use connection string in `.env`

## 5. Start the Server (Development)

```bash
npm run dev
```

## 6. Start the Server (Production)

```bash
npm start
```


Check:

```
 http://localhost:3000
```

## 8. Folder Structure (Basic)

```
src/app.js
   db=>db.j
  server.js
  .env
```

## 9. Required Packages

Installed automatically from `package.json`:

* express
* mongoose
* dotenv
* nodemon (dev)

---


