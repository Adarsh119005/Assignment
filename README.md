# Assignment 

## Full-Stack Project

This is a full-stack web application built with **React (frontend)** and **Node.js with Express & Prisma (backend)**. It includes authentication using JWT tokens and session management with cookies.

## 📥 Download Project

I can't upload the project because it is too large.
You can download zip file of the project from the following Google Drive link:
[Download Full-Stack Project](https://drive.google.com/file/d/1L6RH0v7hADmBQJB1PRg60HsV69eojW3G/view?usp=drive_link)


## Project Video

Watch the video:-
[Watch Project Video](https://drive.google.com/file/d/1R5GbVSb8e4LhazP36267-0Kb2lEHgX07/view?usp=drive_link)


## 🛠 Requirements

### **Frontend Requirements:**

- Node.js (v20 or later)
- npm or yarn
- React.js
- React Router
- TypeScript
- js-cookie (for session management)
- Zod (for form validation)
- React Hook Form

### **Backend Requirements:**

- Node.js (v16 or later)
- npm or yarn
- Express.js
- Prisma (for database ORM)
- bcryptjs (for password hashing)
- jsonwebtoken (for authentication)
- cors (to handle CORS issues)
- dotenv (for environment variables)

## 🚀 Installation & Setup

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/your-repo/full-stack-project.git
cd full-stack-project
```

### **2️⃣ Setup Backend**

```sh
cd backend
npm install
```

#### **Create a ********************************************`.env`******************************************** file in the backend directory:**

```env
DATABASE_URL="your_database_connection_string"
JWT_SECRET="your_secret_key"
```

#### **Run Prisma Migrations:**

```sh
npx prisma migrate dev --name init
```

#### **Start Backend Server:**

```sh
npm run dev
```

\*Backend will run on \****[http://localhost:5000](http://localhost:5000)***

### **3️⃣ Setup Frontend**

```sh
cd ../frontend
npm install
```

#### **Start Frontend:**

```sh
npm start
```

\*Frontend will run on \****[http://localhost:3000](http://localhost:3000)***

## ⚡ Running the Project

1. **Start Backend**: Run `npm run dev` inside the backend folder.
2. **Start Frontend**: Run `npm start` inside the frontend folder.
3. **Login/Register**: Access `http://localhost:3000` in the browser.

## 🔑 Authentication Flow

- Users register/login via the frontend.
- Backend verifies credentials, generates a JWT token, and sets it in cookies.
- Frontend stores the session using **js-cookie**.
- Protected routes redirect to `/login` if the user is not authenticated.

## 📌 API Endpoints

### **Auth Routes** (`/api/login`, `/api/register`)

- `POST /api/login` → Logs in a user and returns a token.
- `POST /api/register` → Registers a new user.

## 💡 Features

✅ **User Authentication (JWT & Cookies)**\
✅ **Session Management**\
✅ **Secure Password Hashing (bcryptjs)**\
✅ **Form Validation (React Hook Form & Zod)**\
✅ **REST API with Express & Prisma ORM**\
✅ **Frontend Styling with CSS**

## 📄 License

This project is licensed under the MIT License.



