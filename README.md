# Create a professional, well-formatted README.md file for a Flask-based Free Fire Like API project hosted on Vercel. Use emojis, bold text, code blocks, tables, and clean markdown formatting throughout.

**Project Title:** 🔥 Free Fire Like API

**Badges to include:** Python 3.8+, Flask 2.x, MIT License

**Sections required (in this exact order):**

1. **📋 Features** — bullet list with ✅ checkmarks:
   - Send likes to any Free Fire player by UID
   - Multi-region support (IND, BR, US, SAC, NA, BD)
   - Daily limit tracking (200 likes/day)
   - API key authentication
   - Protobuf + AES encryption
   - Async request handling with aiohttp
   - Vercel deployment ready

2. **🗂️ Project Structure** — code block tree showing:
   app.py, wsgi.py, index.py, like_pb2.py, uid_generator_pb2.py, visit_count_pb2.py, token_ind.json, token_br.json, token_bd.json, requirements.txt, vercel.json

3. **⚙️ Setup & Installation** — numbered steps with commands:
   - Clone repo: `git clone https://github.com/mahendrakar/free-fire-like-api.git`
   - Install deps: `pip install -r requirements.txt` (show requirements.txt content in code block)
   - Create 3 token JSON files (token_ind.json, token_br.json, token_bd.json) with example format
   - Configure API key in app.py: `VALID_API_KEYS = {"BHUWAN"}`
   - Run locally: `python app.py` → http://0.0.0.0:8000
   - Deploy: `vercel --prod`

4. **🌐 API Endpoints** — two endpoints with full details:

   **1️⃣ GET /like** — Send Likes
   - URL: `/like?key=YOUR_API_KEY&uid=PLAYER_UID&region=REGION`
   - Query params table: key (required), uid (required), region (required)
   - Example request URL
   - Success response JSON (200):
     {
       "LikesGivenByAPI": 1,
       "LikesafterCommand": 1,
       "LikesbeforeCommand": 0,
       "PlayerNickname": ".ORIGIN..➝✩",
       "Level": 2,
       "Region": "IND",
       "UID": 17978854188,
       "status": 1,
       "daily_limit": 200,
       "used": 1,
       "remaining": 199
     }
   - Response fields table explaining each field (status: 1=Success, 2=Failed, 3=Invalid key)

   **2️⃣ GET /remain** — Check Remaining
   - URL: `/remain`
   - Response JSON: {"daily_limit": 200, "remaining": 199, "used": 1, "reset_info": "4:00 AM IST"}
   - Response fields table

5. **❌ Error Responses** — show JSON for:
   - 401 Invalid API Key: {"error": "Invalid or missing API key", "status": 3}
   - 400 Missing Params: {"error": "UID and region are required"}
   - 500 Server Error: {"error": "Error description here"}

6. **🧪 Usage Examples** — three code blocks:
   - cURL example
   - Python requests example
   - JavaScript fetch example

7. **📌 Supported Regions** — table mapping:
   IND → client.ind.freefiremobile.com
   BR/US/SAC/NA → client.us.freefiremobile.com
   BD/Others → clientbp.ppmainecoonghj.com

8. **⚠️ Disclaimer** — educational purposes only, not affiliated with Garena, author not responsible for misuse

9. **📄 License** — MIT License

10. **👤 Credits & Author** — 
    **MAHENDRA**
    - Role: Developer & Maintainer

11. **⭐ Support** — "If you like this project, please give it a ⭐ on GitHub!"

Make it visually appealing, easy to read, and ready to copy-paste directly into GitHub. Bold all section headers, endpoint names, and important keywords.
