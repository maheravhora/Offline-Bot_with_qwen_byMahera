⚡**Browser-Native Offline AI Chatbot**

Run powerful AI models like Llama 3 & Qwen 2.5 directly in your browser.

A fully client-side AI chat interface that runs Large Language Models (LLMs) directly inside your web browser using WebGPU. Once the model is cached, this application runs 100% offline with zero server latency and complete data privacy.

No Python. No Docker. No complex installations. Just load the page and chat.

🔗 Try the Live Demo Here

(👆 Click to launch the bot in your browser)

🚀 Key Features

🔒 100% Privacy :

Your chats and data never leave your device. The AI runs locally on your GPU.

📶 Offline Capable :

Download the model once (~2-4GB), and chat without internet forever.

⚡ WebGPU Powered :

Utilizes modern browser technology for hardware-accelerated inference.

🧠 Multi-Model :

Choose between Llama 3.2 3B (Speed) or Qwen 2.5 7B (Logic).

📦 Zero-Install :

Works instantly in Chrome, Edge, or Brave. No messy setups.

🛠️ How It Works :

This project uses WebLLM and WebGPU to load quantized Large Language Models directly into browser memory.

Initialization: The browser fetches the model weights from the CDN and caches them in the browser's Cache Storage.

Inference: When you type a message, the JavaScript engine sends the input to your GPU for processing.

Response: The GPU generates the response token-by-token, displaying it in real-time.

💻 System Requirements :

To run this bot smoothly, you need:

Browser: Latest Google Chrome, Microsoft Edge, or Brave (WebGPU support is required).

Hardware: * Apple M1/M2/M3 (MacBooks) - Recommended

NVIDIA/AMD Discrete GPU (Windows/Linux)

Storage: At least 5GB of free disk space for model caching.

Note: Not recommended for mobile phones due to VRAM limitations.

📖 Usage Guide :

Visit the Live Link.

Select your preferred model (Llama 3 for speed, Qwen for logic).

Click Download & Load Model.

⚠️ The first load downloads ~2.5GB. Please be patient.

Once the status turns Green, you can disconnect your Wi-Fi.

Chat away!

🗑️ Managing Storage

The AI model is stored in your browser's cache. To free up space:

Click the "Clear Model" (Trash Can 🗑️) icon in the top right corner of the app.

Or, manually go to: Developer Tools -> Application -> Clear Storage -> Clear Site Data.

🤝 Credits

Engine: Powered by WebLLM / MLC AI

Design: UI Styling by Tailwind CSS

Icons: Icons by FontAwesome

Created with ❤️ for the Open Source AI Community.
