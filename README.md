# 🤖 Gemini Realtime Multimodal Chat

A real-time multimodal chat application powered by Google's Gemini AI. This project enables real-time communication with Gemini's advanced AI capabilities through WebSocket connections, supporting both text and multimodal interactions.

[View on GitHub](https://github.com/jadouse5/gemini-realtime-multimodal)

---

## ✨ Features

- 🎯 Real-time Gemini AI Integration
- 🖼️ Multimodal Support (Text + Images)
- 🔄 WebSocket-based Real-time Communication
- 🔐 Secure Environment Configuration
- ⚡ Async/Await Implementation
- 📱 Cross-platform Support

---

## 🛠️ Requirements

```python
google-genai==0.2.2
websockets
python-dotenv
```

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jadouse5/gemini-realtime-multimodal.git
   cd gemini-realtime-multimodal
   ```

2. **Set up virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment**:
   Create `.env` file:
   ```env
   GOOGLE_API_KEY=your_gemini_api_key_here
   ```

---

## 💻 Usage

1. **Start the server**:
   ```bash
   python main.py
   ```

2. **Connect to WebSocket**:
   ```bash
python -m http.server 8000
   # Connect using your preferred WebSocket client
   ```

---

## 🔧 Configuration Options

- `GOOGLE_API_KEY`: Your Gemini API key
- `PORT`: WebSocket server port (default: 8765)
- `HOST`: WebSocket server host (default: localhost)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Jad Tounsi**
- GitHub: [@jadouse5](https://github.com/jadouse5)

---

## 🙏 Acknowledgments

- Google Gemini AI team
- WebSocket protocol contributors
- Python async/await community

---

## 📚 Documentation

For detailed documentation on the Gemini API, visit:
- [Google Gemini API Documentation](https://ai.google.dev/docs)

---

Made with ❤️ and Python

This README has been updated to specifically match your repository at [jadouse5/gemini-realtime-multimodal](https://github.com/jadouse5/gemini-realtime-multimodal) and includes relevant sections for a multimodal AI chat application using Gemini.
