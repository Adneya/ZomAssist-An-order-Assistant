🍽️ ZomAssist – AI Order Assistant
ZomAssist is an AI-powered food ordering assistant embedded via JotForm Agent. It provides an interactive interface for users to place food orders using conversational AI, enhancing the user experience with automation and simplicity.

🚀 Features
🤖 AI-powered conversational ordering assistant
🌐 Easy web integration using iframe
📱 Responsive design for all screen sizes
🎤 Supports microphone, camera, and geolocation permissions
⚡ Fast and lightweight embed (no heavy frontend setup required)

🛠️ Tech Stack
Frontend: HTML, JavaScript
Integration: JotForm Agent Embed
Hosting: Any static hosting (GitHub Pages, Netlify, Vercel)

📂 Project Structure
zomassist/
│── index.html       # Main file with embedded AI assistant
│── README.md        # Project documentation
🔧 Setup & Installation

Clone the repository:
git clone https://github.com/your-username/zomassist.git
cd zomassist
Open index.html in your browser
OR
Deploy using any static hosting platform

📌 Usage
Open the web page
Interact with the AI assistant
Place food orders through conversation
Allow permissions (if prompted) for better experience

💡 Code Explanation
📍 Iframe Integration
<iframe id="JotFormIFrame-0195524a17837e088fa5f9069d6f4218c4d0"
  title="ZomAssist: Order Assistant"
  src="https://agent.jotform.com/0195524a17837e088fa5f9069d6f4218c4d0?embedMode=iframe&background=1&shadow=1"
  allow="geolocation; microphone; camera; fullscreen"
  style="width:100%; height:688px; border:none;">
</iframe>
Embeds the AI agent interface
Uses JotForm's hosted AI agent system
Enables browser permissions for enhanced interaction

📍 Script Handler
<script src="https://cdn.jotfor.ms/s/umd/latest/for-form-embed-handler.js"></script>
<script>
  window.jotformEmbedHandler("iframe[id='JotFormIFrame-0195524a17837e088fa5f9069d6f4218c4d0']",
    "https://www.jotform.com")
</script>
Handles responsive behavior
Ensures proper iframe communication
Improves loading and resizing

🌍 Deployment Options
GitHub Pages
Netlify
Vercel

🔐 Permissions Used
Geolocation: To detect user location for nearby restaurants
Microphone: Voice-based ordering
Camera: Optional for advanced AI interactions

⚠️ Known Issues
Requires stable internet connection
Some browsers may restrict permissions
Dependent on JotForm service availability
🔮 Future Enhancements
🍕 Integration with Zomato/Swiggy APIs
📊 Order history tracking
💳 Payment gateway integration
🧠 Custom AI model instead of third-party embed
📦 Backend for order management

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.
📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
JotForm Agent for AI assistant embedding
OpenAI concepts for conversational AI inspiration

📬 Contact
Developer: Adneya Khatate
📧 Email: adneya.khatate24@vit.edu
🌐 GitHub: https://github.com/Adneya/
