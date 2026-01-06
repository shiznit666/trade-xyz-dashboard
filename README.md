# Trade XYZ Dashboard

A comprehensive trading dashboard application built with React and TypeScript, designed to provide real-time trading insights, analytics, and portfolio management.

## 🚀 Features

- **Real-time Trading Data**: Live market data and price updates
- **Portfolio Management**: Track and manage your trading portfolio
- **Advanced Analytics**: Detailed charts and analytics for informed decision-making
- **Responsive Design**: Mobile-friendly interface using Tailwind CSS
- **Type-Safe**: Built with TypeScript for robust code quality
- **State Management**: Efficient state management with Zustand
- **Modern Tooling**: Vite for fast development and optimized builds

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: v18.0.0 or higher
- **npm**: v9.0.0 or higher (or yarn/pnpm)
- **Git**: For version control

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shiznit666/trade-xyz-dashboard.git
   cd trade-xyz-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Edit `.env` with your specific configuration values.

4. **Start the development server**
   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:5173`

## 📦 Available Scripts

### Development
```bash
# Start development server with hot reload
npm run dev
```

### Build
```bash
# Build for production
npm run build

# Preview production build locally
npm run preview
```

### Code Quality
```bash
# Lint TypeScript files
npm run lint

# Fix linting issues automatically
npm run lint:fix

# Type check without emitting files
npm run type-check
```

### Testing
```bash
# Run tests
npm test

# Run tests with coverage report
npm test:coverage
```

## 🏗️ Project Structure

```
trade-xyz-dashboard/
├── src/
│   ├── components/        # Reusable React components
│   ├── pages/            # Page components
│   ├── hooks/            # Custom React hooks
│   ├── store/            # Zustand state management
│   ├── services/         # API services and external integrations
│   ├── types/            # TypeScript type definitions
│   ├── utils/            # Utility functions
│   ├── App.tsx           # Main App component
│   └── main.tsx          # Application entry point
├── public/               # Static assets
├── dist/                 # Production build output
├── package.json          # Project dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── vite.config.ts        # Vite configuration
├── .env.example          # Example environment variables
├── .gitignore            # Git ignore rules
├── .eslintrc.cjs         # ESLint configuration
└── README.md             # This file
```

## 🔧 Environment Variables

The application requires certain environment variables to function properly. Create a `.env` file based on `.env.example`:

```env
VITE_API_BASE_URL=https://api.tradingplatform.com
VITE_API_KEY=your_api_key_here
VITE_WEBSOCKET_URL=wss://ws.tradingplatform.com
VITE_APP_ENV=development
```

See `.env.example` for a complete list of available variables.

## 🚀 Deployment

### Vercel

This project is configured for easy deployment on Vercel.

1. **Connect your repository**
   - Go to [Vercel Dashboard](https://vercel.com)
   - Import your GitHub repository
   - Select this project

2. **Configure environment variables**
   - In Vercel project settings, add your environment variables
   - Reference `.env.example` for required variables

3. **Deploy**
   - Vercel will automatically deploy on push to main branch
   - Custom builds configured in `vercel.json`

### Manual Deployment

```bash
# Build the project
npm run build

# The dist/ folder contains your production-ready files
# Deploy the contents of dist/ to your hosting provider
```

## 📚 Technology Stack

- **Frontend Framework**: React 18.2+
- **Language**: TypeScript 5.3+
- **Build Tool**: Vite 5.0+
- **State Management**: Zustand 4.4+
- **UI Styling**: Tailwind CSS 3.4+
- **Charts & Visualization**: Recharts 2.10+
- **HTTP Client**: Axios 1.6+
- **Routing**: React Router DOM 6.20+
- **Date Handling**: date-fns 2.30+
- **Testing**: Vitest 1.0+
- **Linting**: ESLint 8.55+

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Code Standards

- Follow TypeScript strict mode rules
- Use ESLint and Prettier for code formatting
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed

## 🐛 Bug Reports

Found a bug? Please create an issue with:
- Clear description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Your environment details

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support and questions:
- Open an issue on GitHub
- Contact: shiznit666

## 🙏 Acknowledgments

- React community for excellent libraries and tools
- Vercel for seamless deployment platform
- All contributors and supporters of this project

---

**Last Updated**: January 6, 2026

**Status**: Active Development ✅
