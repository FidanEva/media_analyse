# Media Analyse

> **⚠️ Private Project – Visuals Partially Redacted**  
> Due to confidentiality agreements, the source code and live access cannot be shared. The visuals presented have been intentionally blurred or redacted to protect sensitive information while still demonstrating the design and implementation quality.

## 📋 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Architecture](#project-architecture)

## 🎯 Overview

**Media Analyse** is a sophisticated Vue 3-based web application engineered for comprehensive media analysis and management. Built with modern development practices and cutting-edge technologies, it delivers a robust, scalable, and user-friendly solution for media monitoring and analytics.

The application combines powerful data visualization capabilities with intuitive user interfaces to provide actionable insights from media content analysis.

## ✨ Key Features

### 🔐 Authentication & Security
- **Multi-tier Authentication**: Secure user login and administrative root login functionality
- **Role-based Access Control**: Granular permissions system

### 📊 Project Management
- **Complete CRUD Operations**: Full create, read, update, and delete functionality for projects
- **Keyword Management**: Advanced keyword tracking and organization
- **Project Analytics**: Comprehensive project performance metrics

### 🔍 Media Analysis
- **Mentions Analysis**: Real-time fetching and display of media mentions
- **Advanced Filtering**: Sophisticated filtering mechanisms with pagination support
- **Content Classification**: Automated categorization of media content

### 📈 Data Visualization & Benchmarking
- **Interactive Charts**: Dynamic data visualization using professional charting libraries
- **Comparative Analysis**: Side-by-side benchmarking capabilities
- **Export Functionality**: Data export in multiple formats

### 🌐 User Experience
- **Internationalization**: Multi-language support with intelligent fallback mechanisms

### ⚡ Performance & Scalability
- **Centralized State Management**: Efficient global state handling
- **Optimized API Integration**: Smart caching and request optimization
- **Component Modularity**: Reusable component architecture

## 🛠 Technology Stack

### **Core Framework**
| Technology | Version | Purpose |
|------------|---------|---------|
| **Vue 3** | Latest | Primary frontend framework with Composition API |

### **State Management & Routing**
| Technology | Purpose |
|------------|---------|
| **Vuex** | Centralized state management with modules |
| **Vue Router** | Client-side routing with lazy loading |

### **API & Data Handling**
| Technology | Purpose |
|------------|---------|
| **Axios** | HTTP client with custom interceptors and error handling |

### **UI Components & Styling**
| Technology | Purpose |
|------------|---------|
| **Ant Design Vue** | Enterprise-class UI component library |
| **@vueform/multiselect** | Advanced dropdown and multi-select functionality |
| **TailwindCSS** | Utility-first CSS framework for rapid styling |

### **Data Visualization**
| Technology | Purpose |
|------------|---------|
| **Highcharts** | Interactive charts (pie, bar, line, etc.) |

### **Internationalization & Analytics**
| Technology | Purpose |
|------------|---------|
| **Vue I18n** | Multi-language support with dynamic locale switching |
| **Mixpanel** | User analytics and behavior tracking |

## 🏗 Project Architecture

The application follows a **modular architecture** designed for optimal scalability and maintainability:

```
src/
├── components/          # Reusable UI components
├── views/              # Page-level components
├── store/              # Vuex store modules
├── router/             # Route definitions
├── services/           # API service layers
├── utils/              # Utility functions
├── locales/            # Internationalization files
├── assets/             # Static assets
└── styles/             # Global styles and Tailwind config
```

### **Key Architectural Principles**
- **Separation of Concerns**: Clear distinction between business logic, presentation, and data layers
- **Component Reusability**: DRY principle implementation across UI components
- **Service Layer Pattern**: Abstracted API communication for better testability
- **Module Federation**: Scalable state management with Vuex modules
