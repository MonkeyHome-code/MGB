
# Bloxd.io Script Validator
# 🎮 Bloxd.io Script Validator
An AI-powered testing bot for validating Bloxd.io game scripts with automated error detection and gameplay simulation.
An AI-powered testing bot that automatically validates Bloxd.io game scripts with real-time error detection, gameplay simulation, and intelligent code assistance.
## Features
## ✨ Features
- **Script Validation**: Real-time syntax checking and API compatibility testing
- **AI Chat Assistant**: Get help writing and debugging scripts with OpenAI integration
- **Error Analysis**: Detailed performance analysis and security assessment
- **Mock Environment**: Safe testing environment with Bloxd.io API simulation
- **Dark/Light Mode**: Professional UI with theme switching
- **Mobile Responsive**: Works on all devices
### 🔍 **Script Validation Engine**
- Real-time syntax checking and error detection
- Bloxd.io API compatibility verification
- Performance analysis and optimization suggestions
- Security assessment for safe script execution
## Tech Stack
### 🤖 **AI Chat Assistant**
- Get instant help writing and debugging scripts
- Context-aware suggestions and code examples
- Powered by OpenAI GPT-4o for intelligent responses
- Conversation history and script context awareness
- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express
### 🛡️ **Safe Testing Environment**
- Secure VM2 sandbox for script execution
- Mock Bloxd.io API environment for testing
- No risk to actual game servers
- Detailed execution logs and simulation results
### 🎨 **Modern Interface**
- Clean, professional UI with dark/light mode
- Mobile-responsive design
- Real-time code editor with syntax highlighting
- Interactive error analysis and performance metrics
## 🚀 Live Demo
**[Visit Live Website](https://mgb-production.up.railway.app)**
Test your Bloxd.io scripts instantly with our free online validator!
## 🛠️ Tech Stack
- **Frontend**: React 18 + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express + VM2 sandbox
- **Database**: PostgreSQL with Drizzle ORM
- **AI**: OpenAI GPT-4o integration
- **Deployment**: Railway (free hosting)
- **UI Components**: Radix UI + shadcn/ui
## Live Demo
## 📦 Quick Start
🌐 **[Visit Live Website](https://your-app-name.up.railway.app)**
### Local Development
## Quick Start
```bash
# Clone the repository
git clone https://github.com/MonkeyHome-code/MGB.git
cd MGB
1. Clone the repository
2. Install dependencies: `npm install`
3. Set environment variables (see .env.example)
4. Run development server: `npm run dev`
# Install dependencies
npm install
## Deployment
# Set up environment variables
cp .env.example .env
# Add your DATABASE_URL and OPENAI_API_KEY
This project is configured for free deployment on Railway. See `COMPLETE_RAILWAY_DEPLOYMENT.md` for detailed instructions.
# Run development server
npm run dev
```
## Environment Variables
### Environment Variables
```
Create a `.env` file with:
```env
DATABASE_URL=postgresql://username:password@host/database?sslmode=require
OPENAI_API_KEY=your_openai_api_key_here
NODE_ENV=production
NODE_ENV=development
PORT=5000
```
## License
## 🌐 Free Deployment
MIT License
Deploy your own instance for free using Railway:
### Option 1: One-Click Deploy
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/your-template)
### Option 2: Manual Deployment
1. **Fork this repository**
2. **Get a free database**: Sign up at [neon.tech](https://neon.tech)
3. **Deploy on Railway**:
   - Go to [railway.app](https://railway.app)
   - Connect your GitHub repository
   - Add environment variables
   - Deploy automatically
4. **Environment Variables** (add in Railway dashboard):
   - `DATABASE_URL`: Your Neon database connection string
   - `OPENAI_API_KEY`: Your OpenAI API key
   - `NODE_ENV`: `production`
## 📖 Usage Guide
### Script Validation
1. Enter your Bloxd.io script in the code editor
2. Click "Validate Script" for instant analysis
3. Review syntax errors, API compatibility, and performance metrics
4. Get suggestions for improvements and optimizations
### AI Chat Assistant
1. Navigate to the "AI Chat" tab
2. Ask questions about Bloxd.io scripting
3. Get code examples, debugging help, and best practices
4. Chat history is automatically saved
### Supported Bloxd.io APIs
- Player management (`player.getPosition`, `player.setPosition`)
- World interaction (`world.getBlock`, `world.setBlock`)
- Game events (`events.onPlayerJoin`, `events.onBlockPlace`)
- Messaging (`game.broadcast`, `player.sendMessage`)
## 🤝 Contributing
We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.
### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes and test thoroughly
4. Submit a pull request
## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## 🙏 Acknowledgments
- Built for the Bloxd.io community
- Powered by OpenAI GPT-4o
- UI components by Radix UI and shadcn/ui
- Deployed on Railway's free tier
## 📞 Support
- 🐛 [Report Issues](https://github.com/MonkeyHome-code/MGB/issues)
- 💬 [Discussions](https://github.com/MonkeyHome-code/MGB/discussions)
- 📧 Contact: support@your-domain.com
---
**Made with ❤️ for the Bloxd.io community**
