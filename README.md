# AutoVision - Auto Repair & Service Center 🔧

> A modern, professional auto repair and service website built with Next.js, designed to showcase automotive expertise and customer service excellence for Toyota SA graduate programme applications.

![AutoVision Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![Next.js](https://img.shields.io/badge/Next.js-14-black) ![TypeScript](https://img.shields.io/badge/TypeScript-5-blue) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38bdf8)

## 📋 Table of Contents

- [What does AutoVision do?](#-what-does-autovision-do)
- [Why is AutoVision useful?](#-why-is-autovision-useful)
- [How to get started](#-how-to-get-started)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Where to get help](#-where-to-get-help)
- [Who created AutoVision](#-who-created-autovision)
- [Deployment](#-deployment)

## 🚗 What does AutoVision do?

AutoVision is a comprehensive auto repair and service center website that provides:

### Core Functionality:
- **🔧 Service Booking System**: Complete multi-step booking process for automotive services with form validation, progress tracking, and confirmation
- **💰 Quote Generation**: Interactive quote request system for repair estimates with vehicle details and service type selection
- **📱 Responsive Web Experience**: Seamless experience across all devices (mobile, tablet, desktop) with touch-friendly interface
- **🎨 Professional Showcase**: Modern UI/UX with animations, image sliders, and interactive elements demonstrating automotive service expertise
- **⚡ Real-time Interactions**: Dynamic background image slider, hover effects, smooth transitions, and React.js animations

### Business Capabilities:
- **Service Management**: Showcase different automotive repair services (Engine, Brakes, Oil Change, Transmission) with transparent pricing
- **Customer Engagement**: Easy-to-use booking system with 3-step process and quote request forms
- **Professional Presentation**: Clean, modern design reflecting automotive industry standards and Toyota SA values
- **Emergency Support**: 24/7 contact information and emergency roadside assistance
- **Mobile Accessibility**: Full functionality optimized for smartphones and tablets

## 🎯 Why is AutoVision useful?

### For Toyota SA Graduate Programme Candidates:
- **✅ Demonstrates Technical Skills**: Modern React.js, Next.js, TypeScript development with hooks, animations, and responsive design
- **✅ Shows Industry Knowledge**: Deep understanding of automotive service business, repair processes, and customer needs
- **✅ Reflects Toyota Values**: Quality, innovation, customer focus, safety, continuous improvement, and respect for people
- **✅ Professional Portfolio**: Clean, modern design that showcases web development capabilities for automotive industry
- **✅ Functional Implementation**: Working booking system, quote generation, and interactive features

### For End Users:
- **🎯 Easy Service Booking**: Streamlined 3-step booking process with progress tracking and confirmation
- **💰 Transparent Pricing**: Clear pricing for all services (Engine Repair from R1,200, Brake Service from R800, etc.)
- **📞 24/7 Support**: Emergency roadside assistance and multiple contact channels
- **📱 Mobile-Friendly**: Optimized for use on any device, anywhere, anytime
- **🔍 Service Information**: Detailed information about automotive repair services and maintenance packages

### For Developers:
- **📚 Learning Resource**: Modern Next.js 14 with App Router, TypeScript, and Tailwind CSS implementation
- **🎨 Design Patterns**: Responsive design, component architecture, and animation techniques
- **🔧 Best Practices**: Clean code structure, proper TypeScript usage, and accessibility considerations

## 🚀 How to get started

### Prerequisites

Before you begin, ensure you have the following installed on your system:
- **Node.js** (version 18 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** package manager (comes with Node.js)
- **Git** for version control - [Download here](https://git-scm.com/)

### Quick Start Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/autovision.git
   cd autovision
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or if you prefer yarn
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:8000](http://localhost:8000) to see the application

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server on port 8000 |
| `npm run build` | Build the application for production |
| `npm run start` | Start the production server |
| `npm run lint` | Run ESLint for code quality checks |

### Project Setup Verification

After starting the development server, you should see:
- ✅ Homepage with dynamic background image slider
- ✅ Working "Book Service Now" and "Get Free Quote" buttons
- ✅ Responsive navigation menu
- ✅ Service cards with hover animations
- ✅ Contact form and emergency support section

## ✨ Features

### 🏠 **Interactive Homepage**
- **Dynamic Background**: Auto-rotating image slider with automotive photos from Unsplash
- **Smooth Animations**: Fade-in effects, scale animations, and pulse effects using React hooks
- **Working CTAs**: "Book Service Now" navigates to `/booking`, "Get Free Quote" goes to `/quote`
- **Real-time Stats**: 15K+ Cars Fixed, 98% Happy Customers, 24/7 Support

### 📋 **Functional Booking System** (`/booking`)
- **Step 1**: Personal Information (Name, Email, Phone)
- **Step 2**: Vehicle Details (Make, Model, Year, Mileage)
- **Step 3**: Service Selection & Scheduling (Service type, Date, Time, Notes)
- **Progress Tracking**: Visual progress bar showing current step
- **Form Validation**: Required field validation and proper input types
- **Confirmation**: Booking reference number and email confirmation

### 💬 **Quote Request System** (`/quote`)
- **Comprehensive Form**: Personal info, vehicle details, service type, problem description
- **Service Selection**: Dropdown with repair options (General Repair, Engine, Brakes, etc.)
- **Vehicle Information**: Make, model, year with validation
- **Success Confirmation**: Thank you message with 24-hour response promise

### 🔧 **Service Showcase**
- **Engine Repair** - From R1,200 (Same day service)
- **Brake Service** - From R800 (2-4 hours)
- **Oil Change** - From R350 (Quick service)
- **Transmission** - From R2,500 (1-2 days)
- **Interactive Cards**: Hover effects, image scaling, and pricing display
- **Emergency Contact**: Direct phone link for 24/7 support

### 📱 **Responsive Design**
- **Mobile-First**: Optimized for smartphones with touch-friendly interface
- **Tablet Support**: Two-column layouts and expanded navigation
- **Desktop Experience**: Multi-column layouts with full navigation
- **Cross-Browser**: Compatible with Chrome, Firefox, Safari, Edge

## 🛠️ Technology Stack

### Frontend Framework
- **[Next.js 14](https://nextjs.org/)** - React framework with App Router for server-side rendering and routing
- **[React 18](https://reactjs.org/)** - UI library with hooks (useState, useEffect) for state management
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript for better development experience

### Styling & Design
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for rapid UI development
- **[Google Fonts](https://fonts.google.com/)** - Inter and Poppins fonts for professional typography
- **Custom Animations** - CSS transitions and transforms for smooth user interactions

### Development Tools
- **ESLint** - Code linting for consistent code quality
- **PostCSS** - CSS processing and optimization
- **Autoprefixer** - Automatic vendor prefixing for CSS

### External Resources
- **[Unsplash](https://unsplash.com/)** - High-quality automotive photography for backgrounds and service images

## 📁 Project Structure

```
autovision/
├── 📁 src/
│   ├── 📁 app/                    # Next.js App Router
│   │   ├── 📄 globals.css         # Global styles and Tailwind imports
│   │   ├── 📄 layout.tsx          # Root layout with navigation and footer
│   │   ├── 📄 page.tsx            # Homepage (simplified with 3 sections)
│   │   ├── 📁 booking/            # Booking system
│   │   │   └── 📄 page.tsx        # Multi-step booking form
│   │   └── 📁 quote/              # Quote system
│   │       └── 📄 page.tsx        # Quote request form
│   ├── 📁 components/             # React components
│   │   ├── 📄 HeroSection.tsx     # Hero with image slider and animations
│   │   ├── 📄 ServicesSection.tsx # Service showcase with photos and pricing
│   │   ├── 📄 ContactSection.tsx  # Contact form and information
│   │   ├── 📄 NavigationBar.tsx   # Responsive navigation menu
│   │   └── 📄 Footer.tsx          # Site footer with links
│   └── 📁 data/                   # Data files
│       └── 📄 vehicles.ts         # Vehicle data (legacy, can be removed)
├── 📁 public/                     # Static assets
├── 📄 package.json                # Dependencies and scripts
├── 📄 tailwind.config.js          # Tailwind CSS configuration
├── 📄 tsconfig.json               # TypeScript configuration
├── 📄 next.config.js              # Next.js configuration
└── 📄 README.md                   # This documentation
```

## 🆘 Where to get help

### Getting Support

If you need help with AutoVision, here are your options:

#### 📖 **Documentation & Resources**
- **This README**: Comprehensive guide covering setup, features, and usage
- **Inline Comments**: Code comments explaining complex logic and React patterns
- **Next.js Docs**: [https://nextjs.org/docs](https://nextjs.org/docs)
- **Tailwind CSS Docs**: [https://tailwindcss.com/docs](https://tailwindcss.com/docs)

#### 🐛 **Issues & Questions**
- **GitHub Issues**: [Create an issue](https://github.com/your-username/autovision/issues) for bugs or questions
- **Stack Overflow**: Tag questions with `nextjs`, `react`, `tailwindcss`

#### 📧 **Direct Contact**
- **Email**: [your.email@example.com](mailto:your.email@example.com)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- **Response Time**: Usually within 24-48 hours

### Common Issues & Solutions

#### Development Server Won't Start
```bash
# Clear cache and reinstall dependencies
rm -rf node_modules package-lock.json
npm install
npm run dev
```

#### Build Errors
```bash
# Check TypeScript errors
npx tsc --noEmit

# Check linting issues
npm run lint
```

#### Styling Issues
```bash
# Rebuild Tailwind CSS
npm run build
```

### FAQ

**Q: Can I use this code for my own projects?**
A: This is a personal portfolio project created for educational purposes. Feel free to use it as inspiration for your own learning.

**Q: How do I customize the services and pricing?**
A: Edit the `services` array in `src/components/ServicesSection.tsx` to add/modify services and pricing.

**Q: Can I deploy this to production?**
A: Yes! The recommended deployment platform is Vercel. See deployment section for details.

## 👥 Who created AutoVision

### Project Creator

**[Your Name]** - University Student
- **Program**: [Your Degree/Program]
- **University**: [Your University]
- **Email**: [your.email@example.com](mailto:your.email@example.com)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- **GitHub**: [@your-username](https://github.com/your-username)
- **Location**: South Africa

### Technical Skills Demonstrated
- **Frontend Development**: React.js, Next.js 14, TypeScript, Tailwind CSS
- **UI/UX Design**: Responsive design, animations, user experience optimization
- **State Management**: React hooks (useState, useEffect), form handling
- **Modern Web Development**: Component architecture, routing, API integration concepts
- **Industry Application**: Understanding of automotive service business requirements

### Project Purpose
This project was created as a **personal portfolio piece** to demonstrate:
- **Technical Proficiency**: Modern web development skills using industry-standard tools
- **Problem-Solving**: Building a complete web application from concept to implementation
- **Industry Understanding**: Knowledge of automotive service business and customer needs
- **Professional Development**: Preparation for Toyota SA graduate programme application
- **Academic Excellence**: Application of university learning to real-world scenarios

### Project Stats
- **Created**: 2024
- **Development Time**: 40+ hours
- **Lines of Code**: 2,000+
- **Components Created**: 10+
- **Pages Implemented**: 3 (Home, Booking, Quote)
- **Technologies Used**: 8+ (Next.js, React, TypeScript, Tailwind, etc.)

## 🚀 Deployment

### Vercel (Recommended)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/autovision)

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Deploy automatically on every push to main branch

### Manual Deployment
```bash
# Build the application
npm run build

# Start production server
npm run start
```

---

<div align="center">

## 🎯 Toyota SA Graduate Programme

*This project demonstrates key competencies valued by Toyota SA:*

| Toyota Value | Implementation |
|--------------|----------------|
| **Quality** | Clean code, thorough testing, professional design |
| **Innovation** | Modern web technologies, creative solutions |
| **Customer Focus** | User-friendly interface, accessible design |
| **Continuous Improvement** | Regular updates, performance optimization |
| **Respect for People** | Inclusive design, accessible development |

---

**AutoVision** - Expert Auto Repair & Service 🔧✨

*Built with ❤️ for Toyota SA Graduate Programme*

*Personal Portfolio Project by [Your Name]*

[🌐 Live Demo](https://autovision-demo.vercel.app) | [📧 Contact](mailto:your.email@example.com) | [💼 LinkedIn](https://linkedin.com/in/your-profile)

</div>
