# 3D AI Assistant with Autonomous Agents

An intelligent, visually immersive AI assistant that combines conversational capabilities with a 3D web interface. The assistant decomposes user inputs into subtasks, assigns them to specialised AI agents (like researcher, reviewer, coder), and visualises the flow using a .glb 3D model in real-time.

## Core Features

- **3D Visualisation:** Built with `Three.js` and `.glb` model support.
- **Conversational AI:** Integrates with Mistral API for natural language understanding.
- **Multi-Agent System:** Includes domain-specific agents (e.g., Researcher, Developer, Reviewer).
- **Backend Logic:** Powered by Python (Flask/FastAPI compatible) for managing agents and orchestration.


##  Getting Started

### 1. Clone the Repo
git clone https://github.com/abhay-0912/3d-ai-assistant.git
cd 3d-ai-assistant
2. Set Up Python Environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
3. Set Up Environment Variables
Create a .env file with:
MISTRAL_API_KEY=your_api_key_here
4. Run the Backend
python app.py
Note: Update app.py to use Flask or FastAPI as per your preference.

5. Open Frontend
Serve index.html from templates/ or run a local server. Make sure to enable Three.js support for .glb.

🔧 Technologies Used
Mistral AI – Natural language understanding.

Python – Backend logic and agent management.

Three.js – 3D interface rendering.

.glb / glTF – 3D model formats.

HTML/CSS/JS – Frontend structure.

Flask or FastAPI – Backend API server.

3D Model
Model: cute_home_robot.glb
Stored in: static/models/
Textures and GLTF alternative included.

License
This project is licensed under the MIT License. See LICENSE.txt.

Contributions
Pull requests are welcome!.
