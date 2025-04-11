# 🧠 Kumar — My Personal AI OS

**Kumar** is not just an assistant. It's your second brain, digital twin, life manager, creative partner, and code companion — all in one.

Born from the vision of creating a true AI co-pilot, Kumar blends the power of large language models, voice interaction, memory, and agentic reasoning into a single, evolving personal AI system.

---

## 🚀 Features (in progress)

### Phase 1: Core Assistant
- 💬 Natural language interface (chat-based)
- 📅 Calendar integration (Google Calendar)
- 📝 Task/Note access (Notion/Obsidian support)
- 🧠 Personal memory: stores your routines, context, interests
- 🔧 Simple command execution (run local scripts)

### Phase 2: Voice + Personality
- 🎤 Voice input (Whisper)
- 🗣️ Voice output (TTS with ElevenLabs or Bark)
- 👤 Customizable personality (tweak Kumar’s vibe)
- 🪞 Terminal-based or minimal UI (optional GUI layer)

### Phase 3: Autonomous Agent Mode
- ⚙️ Task chaining and autonomous goal execution
- 🌐 Web search, API interaction, real-world tool use
- 📦 Plugins system (code, media, research tools, etc.)
- 📈 Feedback loop: learns from interactions over time

---

## 🧱 Built With

- LLMs: OpenAI GPT / Local (Mistral, LLaMA 3, etc.)
- LangChain / AutoGen (agent behavior)
- Whisper (speech-to-text)
- ElevenLabs / Bark (text-to-speech)
- Python + FastAPI (backend)
- ChromaDB / SQLite (memory)
- Optional: React / Electron (UI layer)

---

## 🛠️ Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/kumar.git
cd kumar

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Start the assistant
python main.py
