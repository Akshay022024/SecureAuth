# SecureAuth


SecureAuth is a modern authentication system built with **React** (frontend) and **ASP.NET Core** (backend). It uses **JWT authentication with HTTP-only cookies** for secure login sessions.

## 🚀 Features
- 🔐 **JWT Authentication** (Stored in HTTP-only cookies)
- 📝 **User Registration & Login**
- 🔄 **Auto Login after Refresh**
- 🔑 **Secure Password Hashing**
- 🎨 **Modern UI with Responsive Design**

## 📸 Preview
![SecureAuth Screenshot](![Screenshot 2025-02-10 124752](https://github.com/user-attachments/assets/c1130408-a85a-469f-aa6f-779765079c4f)
)  

## 📂 Project Structure
```
SecureAuth/
├── AuthAPI/             # Backend (ASP.NET Core API)
│   ├── Controllers/     # API Controllers
│   ├── Models/         # Database Models
│   ├── Data/           # Database Context & Migrations
│   ├── appsettings.json # Configuration File (Add JWT Secret Here)
│
├── client/             # Frontend (React App)
│   ├── src/components/  # React Components
│   ├── src/pages/       # Page Components
│   ├── src/App.js       # Main React Component
│   ├── public/         # Static Files
│
└── README.md           # Project Documentation
```

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Akshay022024/SecureAuth.git
cd SecureAuth
```

### 2️⃣ Backend Setup (ASP.NET Core)
```sh
cd AuthAPI
# Install dependencies
dotnet restore
# Run migrations
dotnet ef database update
# Start the API
dotnet run
```

### 3️⃣ Frontend Setup (React)
```sh
cd client
# Install dependencies
npm install
# Start the React App
npm start
```

## 🔑 Environment Variables
Create a `.env` file in the `AuthAPI/` folder:
```env
JWT_SECRET=your_secret_key_here
JWT_ISSUER=your_issuer
JWT_AUDIENCE=your_audience
```

## 🚀 Deploying to Production
- **Backend**: Host ASP.NET Core API on **Azure, AWS, or any VPS**
- **Frontend**: Deploy React app on **Vercel, Netlify, or GitHub Pages**

## 📜 License
This project is licensed under the **MIT License**.

## 💡 Contributing
Contributions are welcome! Feel free to fork and submit a PR.

---

⭐ **Star this repo if you found it helpful!** ⭐

