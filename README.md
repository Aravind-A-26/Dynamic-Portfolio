# 🎯 Dynamic Portfolio

A personalized, responsive portfolio website showcasing skills, projects, and professional background. Built with React featuring a clean, light-themed design.

## ✅ Deployment Status

- **🌐 Live Website:** [View Deployed Portfolio](https://newportfolioupdated.netlify.app/)
- **Status:** ✅ Successfully Deployed on Netlify
- **Repository Type:** Production Build Only (Source code not included)

## ⚠️ Important Note

⚠️ **This repository contains ONLY the compiled production build**, not the source code. This means:
- ❌ Cannot be run in development mode locally
- ❌ No source files for editing (React components, CSS, etc.)
- ✅ Can be served as a static website
- ✅ Deployed and live on Netlify

## 🚀 Features

- **Light Theme:** Modern light background with dark text for better readability
- **Responsive Design:** Optimized for all devices
- **Hero Section:** Introduction with profile image
- **About Section:** Personal background and experience
- **Skills Section:** Technical skills in frontend, backend, and database
- **Contact Form:** Easy way to get in touch

## 🛠 Technologies Used

### Frontend
- React
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot

### Database
- SQL
- MongoDB

## 📁 Project Structure

```
portfolio/
├── build/                    # Production build (compiled React app)
│   ├── index.html           # Main HTML file
│   ├── static/              # Compiled JS, CSS, and assets
│   ├── favicon.ico
│   └── ...
├── netlify.toml             # Netlify deployment config
├── README.md
└── .gitignore
```

## 🏗 How to View Locally

### Option 1: View Deployed Version (Recommended)
Simply visit: **[https://newportfolioupdated.netlify.app/](https://newportfolioupdated.netlify.app/)**

### Option 2: Run Local Server
```bash
cd build
npx serve . -l 3000
# Open http://localhost:3000 in your browser
```

## 🧭 Website Sections

- **Home:** Hero section with greeting and profile photo
- **About:** Personal information and experience
- **Skills:** Categorized technical skills (Frontend, Backend, Database)
- **Contact:** Contact form and details

## 🚀 Deployment Info

This portfolio is deployed on **Netlify** with automatic continuous deployment:

```toml
# netlify.toml
[build]
  command = "echo 'Build already created - skipping build step'"
  publish = "build"
```

Every push to the GitHub repository automatically triggers a new deployment on Netlify.

## 📝 Deploy Your Own

1. Fork this repository
2. Sign up on [Netlify](https://netlify.com)
3. Connect your GitHub repo to Netlify
4. Set Publish directory to: `build`
5. Deploy!

## 📞 Contact

- **Email:** [Your email]
- **Phone:** (+91) 9865395474
- **LinkedIn:** [Your LinkedIn profile]
- **GitHub:** [https://github.com/Aravind-A-26](https://github.com/Aravind-A-26)

## 📌 Notes

- This repository contains the production build only
- Source code (React components, etc.) is stored separately
- For development/modifications, source code needs to be available
- Website is fully functional and deployed

---

Built with ❤️ by Aravind A | Deployed on Netlify ✨