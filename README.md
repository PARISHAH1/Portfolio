# 🚀 Full Stack Developer Portfolio - MERN Stack

A stunning, modern portfolio website built with the MERN stack (MongoDB, Express.js, React.js, Node.js) featuring mind-blowing UI/UX design, smooth animations, and full-stack functionality.

![Portfolio Preview](https://via.placeholder.com/800x400/6366f1/ffffff?text=Portfolio+Preview)

## ✨ Features

### 🎨 Frontend (React.js)
- **Modern UI/UX Design** - Beautiful, responsive design with glass morphism effects
- **Smooth Animations** - Framer Motion animations and micro-interactions
- **Particle Background** - Interactive particle system in the hero section
- **Typed Text Animation** - Dynamic text typing effect
- **Responsive Design** - Mobile-first approach with perfect mobile experience
- **Dark Mode Support** - Automatic dark mode detection
- **Accessibility** - WCAG compliant with keyboard navigation
- **Performance Optimized** - Lazy loading and optimized animations

### 🔧 Backend (Node.js + Express)
- **RESTful API** - Clean, well-structured API endpoints
- **MongoDB Integration** - NoSQL database for dynamic content
- **Email Integration** - Contact form with email notifications
- **Security** - Helmet.js, CORS, input validation
- **File Upload** - Image upload for projects
- **Environment Configuration** - Secure environment variables

### 📱 Sections
- **Hero Section** - Animated introduction with particle effects
- **About Section** - Personal story with animated statistics
- **Skills Section** - Interactive skill cards with filtering
- **Projects Section** - Portfolio showcase with filtering
- **Contact Section** - Functional contact form with validation
- **Footer** - Social links and navigation

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI library
- **Framer Motion** - Animations
- **React Router** - Navigation
- **React Icons** - Icon library
- **React Hot Toast** - Notifications
- **React Scroll** - Smooth scrolling
- **React Particles** - Particle effects
- **React Typed** - Typing animations

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM
- **Nodemailer** - Email service
- **Multer** - File upload
- **Helmet** - Security
- **CORS** - Cross-origin requests

### Styling
- **CSS3** - Custom styling
- **CSS Variables** - Design system
- **Flexbox/Grid** - Layout
- **Media Queries** - Responsive design

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fullstack-portfolio.git
   cd fullstack-portfolio
   ```

2. **Install backend dependencies**
   ```bash
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd client
   npm install
   cd ..
   ```

4. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   NODE_ENV=development
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/portfolio
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-app-password
   ```

5. **Start the development servers**
   ```bash
   # Start both frontend and backend
   npm run dev
   
   # Or start them separately
   npm run server    # Backend only
   npm run client    # Frontend only
   ```

6. **Open your browser**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 📁 Project Structure

```
fullstack-portfolio/
├── client/                 # React frontend
│   ├── public/
│   │   ├── components/     # React components
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── models/                 # MongoDB models
├── routes/                 # API routes
├── server.js              # Express server
├── package.json
└── README.md
```

## 🎯 Customization

### Personal Information
1. Update personal details in `client/src/components/Hero.js`
2. Modify contact information in `client/src/components/Contact.js`
3. Update social links throughout the application

### Styling
1. Modify CSS variables in `client/src/index.css`
2. Update color scheme and gradients
3. Customize animations and transitions

### Content
1. Add your projects in `client/src/components/Projects.js`
2. Update skills in `client/src/components/Skills.js`
3. Modify about section content

### Backend
1. Configure MongoDB connection
2. Set up email service (Gmail, SendGrid, etc.)
3. Add authentication if needed

## 🌐 Deployment

### Frontend (Netlify/Vercel)
1. Build the React app: `npm run build`
2. Deploy the `client/build` folder

### Backend (Heroku/Railway)
1. Set environment variables
2. Deploy the backend code
3. Update frontend API endpoints

### Database (MongoDB Atlas)
1. Create a MongoDB Atlas cluster
2. Update connection string in environment variables

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- High contrast mode support
- Reduced motion preferences

## 🔧 API Endpoints

### Projects
- `GET /api/projects` - Get all projects
- `GET /api/projects/featured` - Get featured projects
- `POST /api/projects` - Create new project

### Skills
- `GET /api/skills` - Get all skills
- `GET /api/skills/featured` - Get featured skills

### Contact
- `POST /api/contact` - Send contact form

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Framer Motion](https://www.framer.com/motion/) for animations
- [React Icons](https://react-icons.github.io/react-icons/) for icons
- [Unsplash](https://unsplash.com/) for images
- [Google Fonts](https://fonts.google.com/) for typography

## 📞 Contact

- **Email**: hello@yourdomain.com
- **LinkedIn**: [Your LinkedIn](https://linkedin.com/in/yourusername)
- **GitHub**: [Your GitHub](https://github.com/yourusername)

---

⭐ **Star this repository if you found it helpful!** "# Portfolio" 
