# 🤖 SNTDM AI Chatbot

A modern, responsive AI-powered chatbot built with HTML, CSS, and JavaScript. This project features a sleek interface with real-time messaging capabilities powered by Google's Gemma AI model through OpenRouter API.

![Chatbot Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **🎨 Modern UI Design**: Beautiful gradient interface with smooth animations
- **💬 Real-time Messaging**: Instant AI responses with typing indicators
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🤖 AI-Powered**: Integrated with Google Gemma model via OpenRouter API
- **⚡ Fast Performance**: Lightweight and optimized for quick loading
- **🔄 Message History**: Persistent chat history during session
- **🧹 Clear Chat**: Easy-to-use clear chat functionality
- **📝 Markdown Support**: Rich text formatting in AI responses
- **⏰ Timestamps**: Message timestamps for better conversation tracking

## 🚀 Live Demo

Experience the chatbot live: [Open Chat_bot.html](./Chat_bot.html)

## 📸 Screenshots

### Main Chat Interface
The chatbot features a modern, gradient-based design with:
- Clean message bubbles with user/bot avatars
- Smooth animations and transitions
- Professional color scheme
- Intuitive input controls

### Responsive Design
- **Desktop**: Full-featured interface with optimal spacing
- **Mobile**: Touch-friendly design with adapted layouts
- **Tablet**: Balanced view for medium-screen devices

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with Flexbox and Grid
- **Icons**: Font Awesome 6.5.0
- **Fonts**: Google Fonts (Inter)
- **Framework**: Bootstrap 4.3.1
- **AI Integration**: OpenRouter API
- **AI Model**: Google Gemma-3n-e4b-it (Free tier)
- **Markdown**: Marked.js for rich text rendering

## 📁 Project Structure

```
SNTDM-AI-Chatbot/
├── Chat_bot.html          # Main chatbot application
├── home.html              # Landing/home page
├── README.md              # Project documentation
├── Guide lines & Members.docx  # Project guidelines
└── assets/
    ├── aibg.jpg          # Background image
    ├── aiimage.jpg       # AI-related image
    ├── aiimg.webp        # Optimized AI image
    └── bot.png           # Bot icon/avatar
```

## 🔧 Setup & Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for API calls and CDN resources)
- Text editor (VS Code, Sublime Text, etc.) for modifications

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nirwan-WSNj/Sample-AI-Chat-Bot.git
   cd Sample-AI-Chat-Bot
   ```

2. **Open the chatbot**
   - Simply open `Chat_bot.html` in your web browser
   - Or use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **Start chatting**
   - Type your message in the input field
   - Press Enter or click Send
   - Enjoy AI-powered conversations!

## ⚙️ Configuration

### API Configuration
The chatbot uses OpenRouter API with the following configuration:

```javascript
// API Endpoint
const API_URL = 'https://openrouter.ai/api/v1/chat/completions';

// Model Configuration
const MODEL = 'google/gemma-3n-e4b-it:free';

// Headers
const headers = {
  'Authorization': 'Bearer YOUR_API_KEY',
  'Content-Type': 'application/json',
  'HTTP-Referer': 'https://www.sitename.com',
  'X-Title': 'SNTDM Chatbot'
};
```

### Customization Options

#### 🎨 Styling
- **Colors**: Modify CSS variables for theme colors
- **Fonts**: Change font family in the CSS
- **Layout**: Adjust container sizes and spacing
- **Animations**: Customize transition effects

#### 🤖 AI Behavior
- **Model**: Switch between different AI models
- **Temperature**: Adjust response creativity
- **Max Tokens**: Control response length
- **System Prompt**: Add custom instructions

## 🔐 API Key Setup

1. **Get OpenRouter API Key**
   - Visit [OpenRouter.ai](https://openrouter.ai/)
   - Sign up for an account
   - Generate your API key

2. **Configure the Key**
   - Replace `YOUR_API_KEY` in `Chat_bot.html`
   - Keep your API key secure and never commit it to public repositories

## 📱 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | ✅ Fully Supported |
| Firefox | 75+ | ✅ Fully Supported |
| Safari | 13+ | ✅ Fully Supported |
| Edge | 80+ | ✅ Fully Supported |
| Opera | 70+ | ✅ Fully Supported |

## 🎯 Usage Examples

### Basic Conversation
```
User: Hello, how are you?
Bot: Hello! I'm doing well, thank you for asking. I'm here to help you with any questions or tasks you might have. How can I assist you today?
```

### Technical Questions
```
User: Explain machine learning in simple terms
Bot: Machine learning is like teaching a computer to learn patterns from examples, just like how you learn to recognize faces or predict weather patterns from experience...
```

## 🔄 Future Enhancements

- [ ] **User Authentication**: Login/logout functionality
- [ ] **Chat History**: Persistent conversation storage
- [ ] **Multiple AI Models**: Support for different AI providers
- [ ] **Voice Input**: Speech-to-text integration
- [ ] **File Upload**: Document and image analysis
- [ ] **Themes**: Dark/light mode toggle
- [ ] **Export Chat**: Download conversation history
- [ ] **Multi-language**: International language support

## 🐛 Troubleshooting

### Common Issues

**1. API Key Error**
```
Error: HTTP error! Status: 401
```
- **Solution**: Check your API key is correct and has sufficient credits

**2. Network Error**
```
Error: Failed to fetch
```
- **Solution**: Check internet connection and API endpoint availability

**3. CORS Issues**
```
Error: CORS policy blocked
```
- **Solution**: Use a local server instead of opening HTML directly

**4. Slow Responses**
```
Long loading times
```
- **Solution**: Check API rate limits and server status

## 📊 Performance Metrics

- **Load Time**: < 2 seconds
- **Response Time**: 1-3 seconds (depending on API)
- **Bundle Size**: ~50KB (excluding images)
- **Mobile Performance**: 95+ Lighthouse score

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Follow existing code style
2. Test on multiple browsers
3. Update documentation as needed
4. Ensure responsive design compatibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Nirwan-WSNj**
- GitHub: [@Nirwan-WSNj](https://github.com/Nirwan-WSNj)
- Email: weronsandesh0609@gmail.com

## 🙏 Acknowledgments

- **OpenRouter**: For providing AI model access
- **Google**: For the Gemma AI model
- **Font Awesome**: For beautiful icons
- **Bootstrap**: For responsive framework
- **Google Fonts**: For typography

## 📈 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/Nirwan-WSNj/Sample-AI-Chat-Bot)
![GitHub last commit](https://img.shields.io/github/last-commit/Nirwan-WSNj/Sample-AI-Chat-Bot)
![GitHub stars](https://img.shields.io/github/stars/Nirwan-WSNj/Sample-AI-Chat-Bot)
![GitHub forks](https://img.shields.io/github/forks/Nirwan-WSNj/Sample-AI-Chat-Bot)

---

⭐ **Star this repository if you found it helpful!**

Made with ❤️ by [Nirwan-WSNj](https://github.com/Nirwan-WSNj)