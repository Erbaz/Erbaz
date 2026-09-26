<div align="center" style="padding:20px;">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 420" width="100%" style="max-width:820px;margin:0 auto;border-radius:16px;overflow:hidden;border:1px solid #FFD700;box-shadow:0 0 20px rgba(255,215,0,0.15);">
  <defs>
    <!-- Background gradient: dark forest green to near-black -->
    <linearGradient id="bgGrad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0f2e1c"/>
      <stop offset="40%" stop-color="#0a1f12"/>
      <stop offset="100%" stop-color="#050c07"/>
    </linearGradient>
    <!-- Radial glow behind the title for a soft spotlight effect -->
    <radialGradient id="centerGlow" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="rgba(233, 194, 20, 0.1)"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>
    <!-- Gold gradient applied to the title text -->
    <linearGradient id="titleGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#FFE55C"/>
      <stop offset="50%" stop-color="#FFD700"/>
      <stop offset="100%" stop-color="#DAA520"/>
    </linearGradient>
    <!-- Fading horizontal bar separating the title from the subtitle -->
    <linearGradient id="barGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="transparent"/>
      <stop offset="50%" stop-color="rgba(255,215,0,0.8)"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <!-- Diagonal line pattern overlay for subtle texture -->
    <pattern id="diagPattern" width="25" height="25" patternUnits="userSpaceOnUse" patternTransform="rotate(60)">
      <line x1="0" y1="0" x2="0" y2="25" stroke="rgba(255, 217, 0, 0.25)" stroke-width="1"/>
    </pattern>
    <!-- Reverse diagonal line pattern overlay for texture -->
    <pattern id="diagPattern2" width="25" height="25" patternUnits="userSpaceOnUse" patternTransform="rotate(-60)">
      <line x1="0" y1="0" x2="0" y2="25" stroke="rgba(255, 217, 0, 0.25)" stroke-width="1"/>
    </pattern>
    <!-- Soft glow filter applied to the title text -->
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <!-- Base dark gradient fill -->
  <rect width="800" height="500" fill="url(#bgGrad)" rx="14"/>
  <!-- Soft radial spotlight behind the title -->
  <rect width="800" height="500" fill="url(#centerGlow)" opacity="0.8"/>
  <!-- Diagonal line texture overlay -->
  <rect width="800" height="500" fill="url(#diagPattern)" opacity="0.5"/>
  <!-- Reverse diagonal line texture overlay -->
  <rect width="800" height="500" fill="url(#diagPattern2)" opacity="0.5"/>
  <!-- Gold corner brackets -->
  <!-- Bottom-left bracket -->
  <line x1="8" y1="492" x2="32" y2="492" stroke="#FFD700" stroke-width="2"/>
  <line x1="8" y1="468" x2="8" y2="492" stroke="#FFD700" stroke-width="2"/>
  <!-- Bottom-right bracket -->
  <line x1="792" y1="492" x2="768" y2="492" stroke="#FFD700" stroke-width="2"/>
  <line x1="792" y1="468" x2="792" y2="492" stroke="#FFD700" stroke-width="2"/>
  <!-- Main title and text content -->
  <g>
    <!-- Main name title with gold gradient and glow filter -->
    <text x="400" y="120" text-anchor="middle" font-size="52" font-weight="900" letter-spacing="1" fill="url(#titleGrad)" filter="url(#textGlow)">Erbaz Kamran</text>
    <!-- Decorative gradient divider bar under the title -->
    <rect x="200" y="132" width="400" height="1.4" fill="url(#barGrad)"/>
    <!-- Professional title/subtitle text -->
    <text x="400" y="170" text-anchor="middle" font-size="20" font-weight="700" letter-spacing="0.5" fill="rgba(255,224,120,0.8)" font-family="Segoe UI,Helvetica,Arial,sans-serif" style="word-wrap:break-word;overflow-wrap:break-word;">Senior Software Engineer | Agentic-AI Engineer | Team Lead</text>
    <!-- Urdu dedication text -->
    <text x="400" y="200" text-anchor="middle" font-size="14" font-weight="400" letter-spacing="0.3" fill="rgba(255,224,120,0.6)" font-family="Segoe UI,Helvetica,Arial,sans-serif" style="word-wrap:break-word;overflow-wrap:break-word;">وہی جہاں ہے ترا جس کو تو کرے پیدایہ سنگ و خشت نہیں جو تیری نگاہ میں ہے</text>
    <!-- Allama Iqbal quote, wrapped into 2 lines using tspan -->
    <text x="400" y="230" text-anchor="middle" font-size="13" font-style="italic" fill="rgba(255,224,120,0.5)" font-family="Segoe UI,Helvetica,Arial,sans-serif" style="word-wrap:break-word;overflow-wrap:break-word;">
      <tspan x="400" dy="0">"Your world is - in fact - that which you birth through your thoughts,</tspan>
      <tspan x="400" dy="17">not the stones and bricks that you see." — Allama Iqbal</tspan>
    </text>
  </g>
  <!-- Tech stack icon row: 9 brand-colored icon boxes with logo images on top -->
  <g overflow="hidden">
    <!-- JavaScript logo: yellow (#F7DF1E) background -->
    <rect x="130" y="276" width="56" height="56" rx="8" fill="#F7DF1E" stroke="rgba(0,0,0,0.3)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/js-logo.png" x="133" y="278" width="50" height="50"/>
    <!-- TypeScript logo: blue (#007ACC) background -->
    <rect x="190" y="276" width="56" height="56" rx="8" fill="#007ACC" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/ts-logo.png" x="193" y="278" width="50" height="50"/>
    <!-- React logo: dark gray (#282c34) background -->
    <rect x="250" y="276" width="56" height="56" rx="8" fill="#282c34" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/react-logo.png" x="253" y="278" width="50" height="50"/>
    <!-- Express logo: white background -->
    <rect x="310" y="276" width="56" height="56" rx="8" fill="#FFFFFF" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/express-logo.png" x="313" y="278" width="50" height="50"/>
    <!-- Google Cloud logo: white background -->
    <rect x="370" y="276" width="56" height="56" rx="8" fill="#FFFFFF" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/google-cloud-logo.png" x="373" y="278" width="50" height="50"/>
    <!-- LangChain logo: black background -->
    <rect x="430" y="276" width="56" height="56" rx="8" fill="#000000" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/langchain-logo.png" x="433" y="278" width="50" height="50"/>
    <!-- Docker logo: ocean blue (#0266b8) background -->
    <rect x="490" y="276" width="56" height="56" rx="8" fill="#0266b8" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/docker-logo.png" x="493" y="278" width="50" height="50"/>
    <!-- LlamaIndex logo: black background -->
    <rect x="550" y="276" width="56" height="56" rx="8" fill="#000000" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/llama-index-logo.png" x="553" y="278" width="50" height="50"/>
    <!-- Redis logo: white background -->
    <rect x="610" y="276" width="56" height="56" rx="8" fill="#FFFFFF" stroke="rgba(255,215,0,0.25)" stroke-width="1.5"/>
    <image href="https://raw.githubusercontent.com/Erbaz/Erbaz/main/assets/redis-logo.png" x="613" y="278" width="50" height="50"/>
  </g>
</svg>
</div>

<h2 style="color:gold"> 🚀 What I Do </h2>

🏗️ **Lead** — led teams to deliver with a product engineering mindset. \
🤖 **AI-Driven Engineering** — I don't vibe-code. Rather I delve deep into technical design specs for each product feature, using coding agents to scale and speed up the development lifecycle, and improving on agent skills while maximizing context gathering efficiency. \
🌍 **Travel** — love hiking, treking, and discovering historical landmarks. \
📚 **Read and Philosophize** — fascinated by philosophy, logic, history, and high-fantasy novels.

---

<h2 style="color:gold">🏅 Certifications </h2>

[![Google Cloud Professional ML Engineer](https://img.shields.io/badge/Google%20Cloud-Professional%20ML%20Engineer-blue?style=for-the-badge&logo=googlecloud)](https://www.credly.com/badges/38be0abb-ff2b-4efb-8262-82fad0a0e5d2)
[![Datacamp Associate SQL Analyst](https://img.shields.io/badge/Datacamp-Associate%20SQL%20Analyst-009BDA?style=for-the-badge&logo=datacamp)](https://www.datacamp.com/completed/statement-of-accomplishment/track/1bae3fe0f0f5839af6a8d91ec5b36e564758e38f)

---

<h2 style="color:gold">📫 Let's Connect</h2>

<p align="left">
  <a style="padding-right:5px" href="https://github.com/erbazkamran" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a style="padding-right:5px" href="https://linkedin.com/in/erbaz" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a style="padding-right:5px" href="mailto:erbazkamran@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>
