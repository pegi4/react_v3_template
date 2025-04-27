# Backend Server

This is the backend server for the React Vite Template project. It's built with Express.js and MongoDB.

## 🚀 Technologies Used

- [Express.js](https://expressjs.com/) - Web framework for Node.js
- [MongoDB](https://www.mongodb.com/) - NoSQL database
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling
- [Express Session](https://www.npmjs.com/package/express-session) - Session middleware
- [CORS](https://www.npmjs.com/package/cors) - Cross-Origin Resource Sharing
- [Multer](https://www.npmjs.com/package/multer) - File upload handling

## 📦 Installation

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The server will be available at `http://localhost:3000`

## 🛠️ Available Scripts

- `npm run dev` - Start the development server with nodemon (auto-reload)
- `npm start` - Start the production server

## 🔧 Environment Variables

Make sure to set up your environment variables in a `.env` file:

```env
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```

## 📚 API Documentation

The API endpoints are organized in the `routes` directory. Each route file corresponds to a specific resource or feature. 