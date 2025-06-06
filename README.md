# 🤖 AI QR Code Generator

An AI-powered QR Code Generator that combines traditional QR encoding with AI-generated visuals. Inspired by modern cyberpunk themes and stable diffusion magic, this project lets users generate personalized and aesthetic QR codes using natural language prompts.

---

## 🚀 Features

- Generate scannable QR codes from any text or URL
- Customize visuals using AI (Stable Diffusion via Replicate)
- Downloadable high-quality image output
- Futuristic and aesthetic design

---

## 🛠️ Tech Stack

- HTML / CSS / JavaScript (Frontend)
- Node.js (Backend API)
- Replicate API for image generation
- Vercel or local server for deployment

---

## 📦 Installation & Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/manali0899/AI-QR-Code-Generator.git
cd AI-QR-Code-Generator
2. Install Dependencies
Make sure Node.js is installed, then:

bash
Copy
Edit
npm install
3. Set Up Replicate API
Create an account at Replicate

Enable billing to access the Stable Diffusion model

Go to your Replicate billing page

Copy your API token and create a .env file:

env
Copy
Edit
REPLICATE_API_TOKEN=your_replicate_api_token_here
⚠️ Don’t commit your .env file publicly.

4. Run the Project
Start the development server:

bash
Copy
Edit
npm run dev
Open index.html in a browser or use a Live Server extension.

📱 How to Use
Enter your QR content (e.g., a link or text).

Enter a style prompt for the QR (e.g., "futuristic purple cyberpunk city").

Click the Generate button.

Wait for AI to create a styled, scannable QR code.

Click Download to save it.
