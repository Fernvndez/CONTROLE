# Full-Stack Task Manager

A modern, full-stack task management application built with React and Node.js. Features a beautiful, responsive UI and a robust REST API.

![Task Manager Screenshot](https://github.com/yourusername/task-manager/raw/main/screenshots/demo.png)

## ✨ Features

### Frontend
- Modern React application with hooks
- Beautiful UI with Tailwind CSS
- Real-time notifications with react-hot-toast
- Responsive design for all devices
- Interactive task management
- Optimistic updates for better UX

### Backend
- RESTful API with Express
- Clean architecture with services pattern
- Error handling middleware
- Input validation
- API documentation
- Testing with Jest

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/task-manager.git
cd task-manager
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=3000
```

4. Start the development servers:
```bash
npm run dev
```

This will start both the frontend (Vite) and backend (Node.js) servers concurrently.

## 🏗 Project Structure

```
├── server/                # Backend
│   ├── controllers/       # Request handlers
│   ├── middleware/        # Custom middleware
│   ├── routes/           # Route definitions
│   ├── services/         # Business logic
│   └── utils/            # Utility functions
├── src/                  # Frontend
│   ├── api/              # API integration
│   ├── components/       # React components
│   └── styles/           # CSS styles
├── tests/                # Test files
└── package.json          # Project configuration
```

## 🔄 API Endpoints

| Method | Endpoint         | Description      |
|--------|-----------------|------------------|
| GET    | /api/tasks      | Get all tasks    |
| GET    | /api/tasks/:id  | Get task by ID   |
| POST   | /api/tasks      | Create task      |
| PUT    | /api/tasks/:id  | Update task      |
| DELETE | /api/tasks/:id  | Delete task      |

## 💻 Available Scripts

- `npm run dev` - Start development servers
- `npm run dev:client` - Start frontend only
- `npm run dev:server` - Start backend only
- `npm test` - Run tests
- `npm run build` - Build for production

## 🧪 Testing

Run the test suite:
```bash
npm test
```

## 📦 Technologies Used

### Frontend
- React
- Vite
- Tailwind CSS
- React Icons
- Axios
- React Hot Toast

### Backend
- Node.js
- Express
- Morgan
- CORS
- UUID
- Jest
- Supertest

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.