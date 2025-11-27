🍰 MERN-Cake — Online Cake Shop (Full-Stack MERN Project)

A modern and responsive full-stack Cake Shop Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).
Users can browse cakes, view details, and explore the shop through a clean UI.

🔗 Live Website: https://mern-cake.vercel.app/

📌 Features

🎂 View list of cake products

📝 Each product includes name, price, image & description

⚡ Fast & responsive React UI

🌐 REST API using Node.js + Express

🗄️ MongoDB integration

🚀 Modern deployment (frontend hosted on Vercel)

🔧 Easy to extend (Cart, Checkout, Admin Panel can be added)

🧰 Tech Stack
Frontend

React.js

CSS / Styled Components / Tailwind (depending on your setup)

Axios or Fetch API

Backend

Node.js

Express.js

MongoDB Atlas / Local MongoDB

Mongoose ODM

Tools

Git & GitHub

Vercel

Postman (for API testing)

🛠️ Installation & Setup (Local Machine)

Follow these steps to run the project locally:

1️⃣ Clone the Repository
git clone <your-repository-url>
cd mern-cake

📦 Backend Setup
cd backend
npm install

Create a .env file
MONGODB_URI=your_mongodb_connection_uri
PORT=5000

Start Backend
npm run dev


Backend runs on:
👉 http://localhost:5000

🎨 Frontend Setup
cd ../frontend
npm install

(Optional) Add .env in frontend
REACT_APP_API_URL=http://localhost:5000

Start Frontend
npm start


Frontend runs on:
👉 http://localhost:3000

📁 Project Structure (Example)
/mern-cake
   /backend
      ├── server.js
      ├── /models
      ├── /routes
      ├── /controllers
      ├── package.json
   /frontend
      ├── /src
      │    ├── App.js
      │    ├── components/
      │    ├── pages/
      │    ├── assets/
      ├── package.json
   README.md

🚀 Deployment Details

Frontend: Deployed on Vercel → https://mern-cake.vercel.app/

Backend: Can be deployed on Render / Railway / Cyclic / Vercel serverless

Database: MongoDB Atlas

If needed, I can create the deployment guide also.

🔮 Future Enhancements

User Login / Register

Add to Cart

Checkout + Payments

Order Tracking

Admin Dashboard (Add / Edit / Delete cakes)

Fully responsive animations & UI polish

🤝 Contributing

Contributions are welcome.

Fork the repo

Create your branch: git checkout -b feature/NewFeature

Commit: git commit -m "Add new feature"

Push: git push origin feature/NewFeature

Open a Pull Request
