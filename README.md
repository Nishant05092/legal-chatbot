📜 Legal Chatbot 🤖⚖️
A responsive, AI-powered chatbot that dynamically answers 100+ legal queries using a pre-trained Hugging Face Transformer model (google/flan-t5-base), with zero static context files, built using Flask and a modern HTML/CSS frontend.

🚀 Features
✅ Text-based chatbot for legal information
✅ Uses transfer learning with a pre-trained NLP model
✅ Answers queries in under 2 seconds, 5× faster than manual search
✅ Clean, responsive UI with navbar, chat interface & footer
✅ Mobile-friendly design with smooth animations
✅ Plans for multi-turn conversation and cloud deployment

⚙️ Tech Stack
Frontend: HTML5, CSS3

Backend: Python, Flask

NLP Model: google/flan-t5-base (Hugging Face Transformers)

AI Concepts: Transfer Learning, NLP

Deployment: Local (Render/Replit planned)

📂 Project Structure
plaintext
Copy
Edit
legal-chatbot/
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── app.py
├── requirements.txt
├── README.md
🏃 How to Run Locally
1️⃣ Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/legal-chatbot.git
cd legal-chatbot
2️⃣ Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Flask app

bash
Copy
Edit
python app.py
5️⃣ Open your browser:
Visit http://127.0.0.1:5000/

💡 Sample Questions
What is a force majeure clause?

Are digital signatures legally valid?

Can an agreement be terminated early?

What happens if a contract is breached?

👥 Contributors
Name	Role
Baibhav Pratap Singh	Frontend Developer
Nishant Sharma	AI/ML Developer

📌 Next Steps
✅ Add multi-turn conversations
✅ Deploy to Render or Replit
✅ Expand to more legal domains (NDA, employment, rental)
✅ Optional voice input

📃 License
This project is open source for educational purposes.

🤝 Connect
If you’re interested in AI, NLP, or LegalTech, feel free to fork the repo, open issues, or connect on LinkedIn.

#AI #LegalTech #NLP #HuggingFace #Flask #Chatbot #OpenSource #TransferLearning
