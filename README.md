🏛️ Kooshk Konkur Honar
Kooshk Konkur Honar is a Persian-first, AI-powered educational platform focused on the national entrance exam in the field of Art.
✨ What is Kooshk?
In Persian architecture, a "Kooshk" (کوشک) refers to a classical pavilion — an open, four-sided structure designed for connection with nature and light. Inspired by historic examples like the pavilions of Niavaran Palace, our project brings this concept into the digital age:
"A pavilion for learning art."
🧠 Meet Tadaa – The AI Consultant
Tadaa is a smart assistant trained and fine-tuned on up-to-date and official information about the Konkur-e-Honar.
Instead of browsing multiple long articles, you can now ask exactly what you need — and get a focused, trustworthy answer instantly.
📌 Version 1.0.0 Goals
This MVP is the foundation for a growing knowledge ecosystem. It offers:
Access to Tadaa without login
Free and fast answers for art exam questions
Full Persian language support and RTL layout
Kooshk is just beginning. We plan to grow it into a full academic hub — from podcasts and practice tests to a digital library and mobile app. Stay tuned.
🧠 Powered by AI SDK + RAG
This project is built using the AI SDK Preview Internal Knowledge Base template from Vercel Labs.
It leverages modern AI architecture with:
Retrieval-Augmented Generation (RAG) for accurate answers from our own content
OpenAI GPT models with custom embeddings
Streaming responses with useChat() hook
Data stored in PostgreSQL (Neon) with Drizzle ORM
This means Kooshk doesn’t just generate answers — it retrieves relevant, accurate, and up-to-date information and responds with precision in Persian.
In v1, the focus is on enabling the AI assistant (Tadaa) to serve as the user’s shortcut to knowledge.
🔧 Technical Summary
Framework: Next.js (React-based)
Language: Persian-first, RTL layout
AI Stack: Vercel AI SDK, OpenAI (gpt-3.5-turbo / gpt-4)
Database: Neon (PostgreSQL) + Blob (for longform)
Deployment: Vercel (frontend only)
Offline-first (PWA): Planned in future release
🤝 Contributing
We will open-source this project after version 1.0.0.
Stay tuned for CONTRIBUTING.md and DEVELOPER_GUIDE.md.
Project Installation Command
To install the project, simply enter the following command in your terminal
git clone https://github.com/your-repository/kooshk-konkur-honar.git
cd kooshk-konkur-honar
npm install
📜 License
This project is licensed under MIT.