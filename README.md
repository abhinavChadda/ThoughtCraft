# ThoughtCraft - AI-Powered Note-Taking for macOS

![macOS](https://img.shields.io/badge/macOS-14.0%2B-blue)
![Swift](https://img.shields.io/badge/Swift-5.9-orange)
![SwiftUI](https://img.shields.io/badge/SwiftUI-5.0-purple)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Version](https://img.shields.io/badge/Version-2.2.0-green)

Transform the way you capture and organize thoughts with ThoughtCraft, an intelligent note-taking application that combines simplicity with the power of AI. Perfect for professionals, students, and researchers who want smart organization without compromising privacy.

## ✨ Key Features

### 🧠 AI-Powered Intelligence
- **Smart Action Item Extraction** - Automatically identifies and extracts tasks from your notes
- **Multi-Provider AI Support** - Choose from OpenAI, Anthropic, xAI, Apple Intelligence, or Local AI
- **Intelligent Organization** - Auto-categorization and smart project suggestions
- **Topic Chat** - Have conversations with your entire knowledge base
- **AI Apps** - Transform content with built-in AI applications

### 📝 Advanced Note-Taking
- **Quick Notes** - Instant capture for meetings and calls
- **Regular Notes** - Rich text editing with markdown support
- **Always-Editable Titles** - No more clicking edit buttons
- **Dynamic Navigation** - Context-aware navigation with icons
- **Universal Search** - Find anything across all your content

### 🔐 Privacy-First Design
- **100% Local Storage** - All data stays on your Mac
- **No Cloud Sync** - Complete offline functionality
- **Secure API Keys** - Stored in macOS Keychain with biometric protection
- **Time Machine Integration** - Automatic backup inclusion
- **Data Export** - Export your notes anytime, no vendor lock-in

### ⏰ Productivity Features
- **Time Blocking Planner** - Cal Newport-style deep work scheduling
- **Project Management** - Organize notes and tasks by projects
- **Dashboard View** - See your productivity at a glance
- **Calendar Integration** - Sync with your calendar events
- **Task Tracking** - Monitor action items and deadlines

## 🚀 Getting Started

### System Requirements
- macOS 14.0 (Sonoma) or later
- Apple Silicon or Intel Mac
- 4GB RAM minimum (8GB recommended)
- 500MB available storage

### Installation

#### TestFlight Beta
1. Join the beta program (coming soon)
2. Download TestFlight from the Mac App Store
3. Install ThoughtCraft through TestFlight

#### App Store
Coming soon to the Mac App Store!

## 🎯 Quick Start Guide

### 1. First Launch
- Open ThoughtCraft
- Complete the welcome tour
- Choose your preferred AI provider (optional)

### 2. Create Your First Note
- Click "New Note" or use Quick Note
- Start typing - ThoughtCraft handles the rest
- Watch as AI automatically extracts action items

### 3. Configure AI (Optional)
- Go to Settings → AI Settings
- Add your API key for enhanced features
- Or use Local AI for complete offline functionality

## 🛠 Configuration

### AI Providers

| Provider | Features | Requirements |
|----------|----------|--------------|
| Apple Intelligence | Basic AI features | macOS 15.0+ |
| OpenAI | GPT-4 powered analysis | API key required |
| Anthropic | Claude integration | API key required |
| xAI | Grok models | API key required |
| Local AI | Complete offline AI | Ollama installation |

### Setting Up Local AI
```bash
# Install Ollama
brew install ollama

# Pull a model
ollama pull llama2

# ThoughtCraft will automatically detect Ollama
```

## 📖 Documentation

- [Privacy Policy](PRIVACY.md)
- [Release Notes](SmartNotes/Documentation/RELEASE_NOTES_v2.2.0.md)
- [User Guide](docs/USER_GUIDE.md) (coming soon)
- [API Documentation](docs/API.md) (coming soon)

## 🔧 Development

### Tech Stack
- **Language**: Swift 5.9
- **UI Framework**: SwiftUI
- **Data Persistence**: SwiftData
- **AI Integration**: Multiple provider support
- **Security**: macOS Keychain Services

## 🤝 Contributing

While ThoughtCraft is currently proprietary software, we welcome feedback and bug reports:

1. **Report Bugs**: [Open an issue](https://github.com/abhinavchadda/thoughtcraft/issues)
2. **Feature Requests**: [Discussions](https://github.com/abhinavchadda/thoughtcraft/discussions)
3. **Security Issues**: Email security@thoughtcraft.app

## 🗺 Roadmap

### Version 2.3 (Coming Soon)
- [ ] iOS companion app
- [ ] CloudKit sync (optional)
- [ ] Collaborative notes
- [ ] Voice transcription

### Version 3.0 (Future)
- [ ] Plugin system
- [ ] Custom AI models
- [ ] Advanced markdown editor
- [ ] API for third-party integrations

## 📊 Version History

- **v2.2.0** - Navigation enhancements, UI polish, TestFlight release
- **v2.1.0** - Enhanced markdown, security improvements
- **v2.0.0** - Multi-provider AI, time blocking, database repair
- **v1.9.0** - AI infrastructure, biometric security
- [Full Release Notes](SmartNotes/Core/Services/ReleaseNotesService.swift)

## 📄 License

Copyright © 2025 Abhinav Chadda. All rights reserved.

ThoughtCraft is proprietary software. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited without the express written permission of the copyright holder.

## 🙏 Acknowledgments

- Built with Swift and SwiftUI
- AI providers: OpenAI, Anthropic, xAI
- Local AI powered by Ollama
- Icons and design inspiration from SF Symbols

## 📧 Contact

- **Support**: [GitHub Issues](https://github.com/yourusername/thoughtcraft/issues)
- **Email**: support@thoughtcraft.app
- **Website**: Coming soon

---

**Made with ❤️ for the Mac**

*ThoughtCraft - Where thoughts become action*
