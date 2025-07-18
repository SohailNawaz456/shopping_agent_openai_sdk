🛒 Shopping Agent CLI
A Python CLI tool that combines AI chat capabilities (using Gemini API) and real-time product search from a sample API.

✨ Features
✅ Ask product questions — Type your question and get an AI-generated answer.
✅ Fetch matching products — Searches a product API to list relevant products for your query.
✅ Built with Gemini API — Integrates with Google’s Gemini large language model via OpenAI-compatible SDK.

📸 Demo
$ python shopping_agent.py
🛒 Welcome to the Shopping Agent!
🔍 What product are you looking for? bluetooth headphones

📦 Matching Products:
- Bluetooth Headphones Pro | Rs 4999
- Wireless Bluetooth Earbuds | Rs 2499
- Bluetooth Sports Headphones | Rs 2999

🤖 Agent Answer:
Here are some Bluetooth headphones options that might fit your needs...

🔧 Installation
Clone the repository

git clone https://github.com/yourusername/shopping-agent-cli.git
cd shopping-agent-cli

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate      # On macOS/Linux
venv\Scripts\activate         # On Windows

Install dependencies
pip install -r requirements.txt



🗝️ Environment Variables
Create a .env file in the project root:


GEMINI_API_KEY=your_google_gemini_api_key_here

Note: Obtain your API key from Google AI Studio or Google Cloud console.

🚀 Usage
Run the script:

python shopping_agent.py

📝 Project Structure

shopping_agent.py
.env
requirements.txt
README.md

⚙️ Tech Stack
Python

Requests

Regular expressions

Google Gemini API

Rich for better console output

⚠️ Disclaimer
This tool uses a mock API hosted on https://hackathon-apis.vercel.app for demonstration purposes. For production, integrate a real e-commerce API.

📄 License
MIT License

💡 Author
SOHAIL NAWAZ
GitHub

🔗 Links
Gemini API Docs

Rich Documentation


✅ TODO
Add error handling for network failures

Support more APIs

Improve result formatting

Example requirements.txt
To accompany your README, here’s a requirements.txt that matches your script:

python-dotenv
requests
rich


→ How to use:

Save the above text as README.md in your repo root.

Update placeholders like yourusername or Your Name with your actual info.
