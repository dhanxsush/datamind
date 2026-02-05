DataMind – AI-Powered Learning Platform

DataMind is an AI-driven web platform designed to enhance learning by intelligently extracting, cleaning, and improving content from PDF documents. It supports both structured and unstructured PDFs using OCR, NLP, and Machine Learning techniques, producing clean, grammatically correct, and study-ready material.

The platform is built for students, educators, and researchers who work with large volumes of academic or professional documents.

⸻

🚀 Key Features
	•	AI-Powered Learning
	•	Generates accurate and personalized study material from documents
	•	Advanced PDF Text Extraction
	•	Handles both structured and unstructured PDFs
	•	Supports scanned documents using OCR
	•	OCR Integration
	•	Extracts text from image-based PDFs
	•	NLP Processing
	•	Understands and cleans extracted text
	•	Improves readability and structure
	•	Automatic Grammar Correction
	•	Produces clean, polished, and professional-quality output
	•	Scalable Document Processing
	•	Designed to handle large document volumes efficiently
	•	User Authentication & Security
	•	Secure access and protected user data via Supabase

⸻

🧠 Tech Stack

Frontend
	•	React
	•	Vite
	•	TypeScript
	•	Tailwind CSS

Backend
	•	Python
	•	FastAPI
	•	Uvicorn

Database & Services
	•	Supabase (Auth + Database)

Deployment
	•	Backend: Render / Railway / Heroku
	•	Frontend: Vercel / Netlify / Render

⸻

📦 Prerequisites

Ensure the following are installed:
	•	Node.js (v18+ recommended)
	•	Python (3.8+)
	•	Git
	•	Supabase account

⸻

⚙️ Environment Configuration

Backend (project_final/backend/.env)

OPENAI_API_KEY=your_openai_api_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

Frontend (project_final/frontend/.env)

VITE_API_BASE_URL=http://localhost:9000

🔒 Security Note
Never commit .env files. Always include them in .gitignore.
Use .env.example to document required variables.

⸻

🛠️ Setup & Installation

Clone the Repository

git clone <repository_url>
cd datamind_final


⸻

Backend Setup

cd project_final/backend
python -m venv venv

Activate the virtual environment:
	•	Windows

.\venv\Scripts\activate

	•	macOS / Linux

source venv/bin/activate

Install dependencies and start the server:

pip install -r requirements.txt
uvicorn app:app --host 0.0.0.0 --port 9000 --reload

Backend runs at:
👉 http://localhost:9000

⸻

Frontend Setup

cd project_final/frontend
npm install
npm run dev

Frontend runs at:
👉 http://localhost:8000 (or the port shown in terminal)

⸻

🏗️ Production Build

Frontend

npm run build

The production-ready files will be generated in the dist/ folder.

Backend
	•	Deploy Remember to:
	•	Set environment variables on the hosting platform
	•	Use a production ASGI setup (Uvicorn / Gunicorn)

Refer to:
project_final/backend/README_DEPLOY.md

⸻

☁️ Deployment Options

Frontend
	•	Vercel
	•	Netlify
	•	Render
	•	AWS S3 + CloudFront

Backend
	•	Render
	•	Railway
	•	Heroku

⸻

📚 Code Citations

Any third-party code requiring attribution is documented in:

project_final/Code_Citations.md


⸻

🧩 Future Enhancements (Optional)
	•	Document summarization
	•	Topic-wise content breakdown
	•	Question generation from PDFs
	•	User-specific learning recommendations

