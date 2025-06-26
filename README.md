# Keradon-Citadel
Citadel for the Keradon Software open for Open Source Contributions

## About

Keradon-Citadel is a comprehensive software platform that serves as the central hub for Keradon Software's ecosystem. This repository contains the main application and landing page components, designed to be open for community contributions and collaboration.

## 📁 Project Structure

This repository is organized as a monorepo with the following components:

- **`Keradon-App/`** - Main application (submodule)
- **`landing-page/`** - Landing page component (submodule)

## 🛠️ Tech Stack

### Frontend
- **Electron.js** - For Cross Native Desktop Development
- **Next.js** - React framework for production
- **TypeScript** - Type-safe JavaScript development
- **Tailwind CSS** - Utility-first CSS framework

### Backend
- **Supabase** - Supabase for database

## Auth
- **Next.Auth** -  For secure user Authentication

### Development Tools
- **Git** - Version control
- **Git Submodules** - Managing subprojects

### Deployment & Infrastructure
- **Vercel** - Frontend deployment

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Git

### Installation

1. **Clone the repository with submodules:**
   ```bash
   git clone --recursive https://github.com/vaishcodescape/Keradon-Citadel.git
   cd Keradon-Citadel
   ```

2. **If you already cloned without submodules:**
   ```bash
   git submodule update --init --recursive
   ```

3. **Set up the main application:**
   ```bash
   cd Keradon-App
   npm install
   ```

4. **Set up the landing page:**
   ```bash
   cd ../landing-page
   npm install
   ```

### Development

1. **Start the main application:**
   ```bash
   cd Keradon-App
   npm run dev
   ```

2. **Start the landing page:**
   ```bash
   cd landing-page
   npm run dev
   ```

## Contributing

We welcome contributions from the open source community! Here's how you can help:

### Contributing Guidelines

1. **Fork the repository**
2. **Create a feature branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
4. **Commit your changes:**
   ```bash
   git commit -m "feat: add your feature description"
   ```
5. **Push to your fork:**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request**

### Code Style

- Follow the existing code style and conventions
- Use TypeScript for type safety
- Write meaningful commit messages
- Include tests for new features
- Update documentation as needed

### Issue Reporting

- Use the GitHub issue tracker
- Provide detailed descriptions of bugs or feature requests
- Include steps to reproduce issues
- Add screenshots when relevant

## License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## Team

- **Maintainer:** [vaishcodescape](https://github.com/vaishcodescape)

## Support

- **Issues:** [GitHub Issues](https://github.com/vaishcodescape/Keradon-Citadel/issues)
- **Discussions:** [GitHub Discussions](https://github.com/vaishcodescape/Keradon-Citadel/discussions)

## Links

- **Main App Repository:** [Keradon-App](https://github.com/vaishcodescape/Keradon-App)
- **Landing Page Repository:** [Keradon-Landing-Page](https://github.com/vaishcodescape/Keradon-Landing-Page)

---

⭐ **Star this repository if you find it helpful!**
