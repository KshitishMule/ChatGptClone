ChatGPT Clone



A simple web-based ChatGPT clone built with Flask, HTML/CSS, and JavaScript. This project provides an interactive chat interface that connects to OpenAI's GPT models to generate AI-powered responses.

📌 Features
✅ Chat interface styled with Bootstrap

✅ Communicates with OpenAI's GPT models via API

✅ Flask backend server

✅ Clean, responsive, and easy to customize

✅ Fully open-source

📁 Project Structure
chatgpt-clone/
├── app.py                  # Flask server
├── requirements.txt        # Python dependencies
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
└── templates/
    └── index.html          # Main chat page


⚙️ Configuration
You can customize:

Model: Change "gpt-3.5-turbo" in app.py

System prompt: Modify the messages list in app.py

Frontend design: Edit templates/index.html, static/css/style.css, static/js/script.js



🧩 Dependencies
Listed in requirements.txt, e.g.:

nginx
Copy
Edit
Flask
openai
Install them with:

bash
Copy
Edit
pip install -r requirements.txt
✨ Example API Key setup
python
Copy
Edit
# app.py
openai.api_key = "sk-XXXXXXXXXXXXXXXXXXXX"

🙏 Acknowledgements
Flask
OpenAI API
⭐️ Support
If you find this project useful, please ⭐️ star the repository!

If you want, I can also give you:

✅ Shorter minimal version
✅ Even more advanced professional version with shields.io badges and deployment instructions (Heroku, Vercel, etc.)

Just let me know!
👤 Author
Kshitish Mule


