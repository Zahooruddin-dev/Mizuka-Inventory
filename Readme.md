# 🎯 Mizuka Inventory System

<p align="center">
  <strong>A modern, intelligent inventory management solution for growing businesses</strong>
</p>

<p align="center">
  <a href="#features">Features</a> • <a href="#tech-stack">Tech Stack</a> • <a href="#getting-started">Getting Started</a> • <a href="#api-endpoints">API</a> • <a href="#project-structure">Structure</a>
</p>

---

## ✨ Features

**Mizuka** empowers businesses with intuitive inventory management:

- **🏷️ Product & Category Management** - Comprehensive CRUD operations with intelligent organization
- **📊 Real-time Stock Tracking** - Live inventory monitoring with instant updates and insights
- **🎨 Modern UI/UX** - Beautiful, responsive design with smooth animations and intuitive navigation
- **☁️ Cloud Image Hosting** - Secure product image storage powered by Cloudinary
- **⚡ Fast & Reliable** - Optimized performance with PostgreSQL for data integrity
- **🔒 Production-Ready** - Deployed on industry-standard platforms (Vercel & Render)

---

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern UI library with latest features
- **Vite** - Lightning-fast build tool and dev server
- **Tailwind CSS 4** - Utility-first styling framework
- **Framer Motion** - Smooth, professional animations
- **React Router DOM** - Client-side routing
- **Axios** - HTTP client for API communication

### Backend
- **Node.js + Express 5** - Scalable server framework
- **PostgreSQL (pg)** - Robust relational database
- **CORS** - Secure cross-origin requests
- **dotenv** - Environment configuration management

### Services & Deployment
- **NeonDB** - Managed PostgreSQL hosting
- **Cloudinary** - Image optimization and CDN
- **Vercel** - Frontend deployment
- **Render** - Backend deployment

---

## 📁 Project Structure

```
mizuka-inventory-system/
├── backend/
│   └── src/
│       ├── controller/      # Request handlers & business logic
│       ├── db/             # Database configuration & queries
│       ├── routes/         # API route definitions
│       ├── app.js          # Express server setup
│       └── server.js       # Application entry point
├── frontend/
│   └── src/
│       ├── components/     # Reusable UI components
│       │   ├── Forms       # Form components
│       │   ├── Layout      # Layout components
│       │   └── Modals      # Modal dialogs
│       ├── pages/          # Page-level components
│       ├── services/       # API service layer
│       └── App.jsx         # Main application component
├── ER-diagram.png          # Database schema visualization
└── README.md               # This file
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- PostgreSQL database (or NeonDB account)
- Cloudinary account for image hosting

### Backend Setup

```bash
cd backend
npm install

# Create .env file with the following variables:
# DATABASE_URL=your_neon_db_connection_string
# PORT=5000
# NODE_ENV=development

npm run dev
```

The backend server will start on `http://localhost:5000`

### Frontend Setup

```bash
cd frontend
npm install

# Create .env file with:
# VITE_API_URL=http://localhost:5000

npm run dev
```

The frontend will be available at `http://localhost:5173`

---

## 📡 API Endpoints

### Products
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/products` | Fetch all products with filters |
| `POST` | `/api/products` | Create a new product |
| `GET` | `/api/products/:id` | Get product details |
| `PUT` | `/api/products/:id` | Update product information |
| `DELETE` | `/api/products/:id` | Remove a product |

### Categories
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/categories` | Fetch all categories |
| `POST` | `/api/categories` | Create a new category |
| `GET` | `/api/categories/:id` | Get category details |
| `PUT` | `/api/categories/:id` | Update category |
| `DELETE` | `/api/categories/:id` | Delete category |

---

## 🎓 Key Learning Outcomes

Building Mizuka provided deep insights into full-stack development:

**Backend Development**
- Designing RESTful APIs with proper HTTP methods and status codes
- Implementing database transactions for data consistency
- Advanced error handling and validation strategies

**Frontend Architecture**
- Managing complex state with React hooks
- Implementing optimistic updates for better UX
- Building reusable component systems

**Database Design**
- PostgreSQL schema optimization with proper indexing
- Designing relationships between entities
- Writing efficient queries for performance

**Full-Stack Integration**
- Secure communication between frontend and backend
- Handling async operations and loading states
- Proper separation of concerns across layers

**DevOps & Deployment**
- Configuring CORS for production environments
- Deploying frontend to Vercel with CI/CD
- Setting up backend on Render with environment management
- Managing secrets and configuration

---

## 📸 Preview

The application features a sleek, modern interface with intuitive workflows for managing inventory efficiently.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements.

---

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

---

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub or reach out directly.

---

<p align="center">
  Made with ❤️ for inventory management
</p>