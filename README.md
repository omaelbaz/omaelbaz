@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Inter:wght@300;400;500;600;700&display=swap'); \* { box-sizing: border-box; margin: 0; padding: 0 } :root { --teal: #64ffda; --navy: #0a192f; --dark: #050a0f; --card: #0d1117; --muted: #8892b0; --bright: #ccd6f6; --mono: 'JetBrains Mono', monospace; --sans: 'Inter', sans-serif; } body { background: var(--dark); color: var(--bright); font-family: var(--sans) } /\* HERO \*/ .hero { background: linear-gradient(160deg, #000 0%, #0a192f 50%, #000 100%); text-align: center; padding: 52px 24px 44px; position: relative; overflow: hidden; } .hero::before { content: ''; position: absolute; inset: 0; background: radial-gradient(ellipse 70% 60% at 50% 0%, rgba(100, 255, 218, 0.07) 0%, transparent 70%); } .hero-name { font-family: var(--mono); font-size: 60px; font-weight: 800; color: #fff; letter-spacing: -2px; line-height: 1; text-shadow: 0 0 60px rgba(100, 255, 218, 0.15); } .hero-name em { color: var(--teal); font-style: normal } .hero-line { width: 140px; height: 1px; background: linear-gradient(90deg, transparent, var(--teal), transparent); margin: 16px auto; } .hero-role { font-family: var(--mono); font-size: 11px; letter-spacing: 5px; color: var(--teal); text-transform: uppercase; opacity: .9; } .hero-sub { font-size: 13px; color: var(--muted); margin-top: 6px } /\* BADGES ROW \*/ .pill-row { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; padding: 20px 24px 0; } .pill { font-family: var(--mono); font-size: 10px; font-weight: 700; padding: 6px 14px; border-radius: 3px; letter-spacing: 1px; display: flex; align-items: center; gap: 6px; text-decoration: none; transition: all .2s; } .pill:hover { transform: translateY(-2px); filter: brightness(1.15) } .p-gh { background: #0d1117; color: #fff; border: 1px solid #30363d } .p-li { background: #0A66C2; color: #fff } .p-x { background: #111; color: #fff; border: 1px solid #333 } .p-em { background: #EA4335; color: #fff } .p-po { background: var(--teal); color: #000 } .p-status { background: #0d1117; color: var(--teal); border: 1px solid rgba(100, 255, 218, .3); font-size: 11px } /\* DIVIDER \*/ .div-line { height: 1px; margin: 28px 0; background: linear-gradient(90deg, transparent 0%, var(--teal) 20%, rgba(0, 191, 255, .8) 50%, var(--teal) 80%, transparent 100%); opacity: .5; } /\* SECTION TITLE \*/ .s-title { font-family: var(--mono); font-size: 11px; font-weight: 800; letter-spacing: 6px; color: var(--teal); text-align: center; text-transform: uppercase; margin-bottom: 24px; } /\* ABOUT GRID \*/ .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; padding: 0 20px } .terminal { background: #0d1117; border: 1px solid rgba(100, 255, 218, .15); border-radius: 8px; overflow: hidden; } .term-bar { background: #161b22; padding: 8px 14px; display: flex; align-items: center; gap: 7px; border-bottom: 1px solid rgba(100, 255, 218, .08); } .dot { width: 10px; height: 10px; border-radius: 50% } .d1 { background: #ff5f57 } .d2 { background: #ffbd2e } .d3 { background: #28c940 } .term-body { padding: 16px 18px; font-family: var(--mono); font-size: 11.5px; line-height: 2 } .cmd { color: var(--teal) } .resp { color: var(--muted) } .val { color: #fff } .diff-plus { color: var(--teal) } .diff-minus { color: #ff6b6b } .quote-box { background: #0d1117; border: 1px solid rgba(100, 255, 218, .12); border-left: 3px solid var(--teal); border-radius: 0 8px 8px 0; padding: 16px 18px; margin-top: 16px; font-size: 13px; color: var(--muted); line-height: 1.7; font-style: italic; } .quote-box cite { display: block; font-family: var(--mono); font-size: 10px; color: var(--teal); font-style: normal; margin-top: 6px; letter-spacing: 1px } .stat-col { display: flex; flex-direction: column; gap: 12px } .s-card { background: #0d1117; border: 1px solid rgba(100, 255, 218, .12); border-radius: 8px; padding: 14px 16px; } .s-card-top { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px } .s-label { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 2px; text-transform: uppercase } .s-val { font-family: var(--mono); font-size: 22px; font-weight: 800; color: var(--teal) } .s-sub { font-family: var(--mono); font-size: 10px; color: var(--teal) } .bar { height: 2px; background: rgba(100, 255, 218, .1); border-radius: 1px } .bar-fill { height: 2px; background: var(--teal); border-radius: 1px; transition: width .6s ease } /\* TECH \*/ .tech-wrap { padding: 0 20px; text-align: center } .tech-pills { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-top: 16px } .t-pill { background: #0d1117; border: 1px solid rgba(100, 255, 218, .15); border-radius: 4px; padding: 5px 12px; font-family: var(--mono); font-size: 10px; color: var(--muted); display: flex; align-items: center; gap: 7px; transition: all .2s; cursor: default; } .t-pill:hover { border-color: var(--teal); color: var(--teal); transform: translateY(-1px) } .t-dot { width: 6px; height: 6px; border-radius: 50%; flex-shrink: 0 } /\* PROJECTS \*/ .proj-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; padding: 0 20px } .p-card { background: #0d1117; border: 1px solid rgba(100, 255, 218, .1); border-radius: 10px; padding: 20px; position: relative; overflow: hidden; transition: all .25s; } .p-card:hover { border-color: rgba(100, 255, 218, .4); transform: translateY(-3px) } .p-card::after { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 1px; background: linear-gradient(90deg, transparent, var(--teal), transparent); opacity: 0; transition: opacity .25s; } .p-card:hover::after { opacity: 1 } .p-num { font-family: var(--mono); font-size: 9px; color: var(--teal); letter-spacing: 3px; margin-bottom: 8px; opacity: .7 } .p-title { font-size: 14px; font-weight: 700; color: #fff; margin-bottom: 8px } .p-desc { font-size: 11.5px; color: var(--muted); line-height: 1.65; margin-bottom: 14px } .p-desc strong { color: var(--bright) } .p-tags { display: flex; flex-wrap: wrap; gap: 5px } .p-tag { background: rgba(100, 255, 218, .07); border: 1px solid rgba(100, 255, 218, .18); border-radius: 3px; padding: 2px 8px; font-family: var(--mono); font-size: 9px; color: var(--teal) } /\* STATS GRID \*/ .metrics { display: grid; grid-template-columns: repeat(4, 1fr); gap: 12px; padding: 0 20px } .m-card { background: #0d1117; border: 1px solid rgba(100, 255, 218, .12); border-radius: 8px; padding: 16px; text-align: center } .m-val { font-family: var(--mono); font-size: 30px; font-weight: 800; color: var(--teal) } .m-lbl { font-family: var(--mono); font-size: 9px; color: var(--muted); letter-spacing: 2px; text-transform: uppercase; margin-top: 4px } /\* ACTIVITY \*/ .activity { padding: 0 20px } .act-bar-wrap { display: flex; align-items: flex-end; gap: 3px; height: 60px; margin-top: 12px; background: #0d1117; border: 1px solid rgba(100, 255, 218, .1); border-radius: 8px; padding: 12px 16px } .act-bar { background: rgba(100, 255, 218, .15); border-radius: 2px 2px 0 0; flex: 1; transition: height .4s; cursor: pointer } .act-bar:hover { background: var(--teal) } /\* CTA \*/ .cta-wrap { text-align: center; padding: 32px 24px 20px } .cta-ascii { font-family: var(--mono); font-size: 10px; color: rgba(100, 255, 218, .35); line-height: 1.9; margin-bottom: 20px; } .cta-btns { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin-bottom: 24px } .cta-btn { padding: 10px 22px; border-radius: 4px; font-family: var(--mono); font-size: 11px; font-weight: 700; text-decoration: none; letter-spacing: 1px; transition: all .2s; display: inline-flex; align-items: center; gap: 8px; } .cta-btn:hover { transform: translateY(-2px); filter: brightness(1.1) } .btn-e { background: #EA4335; color: #fff } .btn-l { background: #0A66C2; color: #fff } .btn-p { background: var(--teal); color: #000 } /\* FOOTER \*/ .footer { background: linear-gradient(180deg, #0a192f, #000); text-align: center; padding: 20px; font-family: var(--mono); font-size: 10px; color: rgba(100, 255, 218, .4); letter-spacing: 2px; border-top: 1px solid rgba(100, 255, 218, .06); } /\* TYPING CURSOR \*/ .cursor { animation: blink 1s infinite } @keyframes blink { 0%, 100% { opacity: 1 } 50% { opacity: 0 } } @media(max-width:580px) { .hero-name { font-size: 36px } .about-grid, .proj-grid, .metrics { grid-template-columns: 1fr } }

Omar _Elbaz_

SaaS Architect  ·  Full Stack Engineer  ·  AI Solutions

Architecting Digital Empires  |  Morocco 🇲🇦

[⌁ GITHUB](https://github.com/omaelbaz) [in LINKEDIN](https://www.linkedin.com/in/omaelbaz/) [✕ X](https://x.com/omaelbaz) [✉ EMAIL](mailto:oelbaz010@gmail.com) [◈ PORTFOLIO](https://omarelbaz.vercel.app/)

✅ AVAILABLE FOR INNOVATION ⚡ 5+ YEARS 🚀 25+ PROJECTS

◈   A B O U T   ◈

~/omar-elbaz — bash

$ whoami

name       Omar Elbaz

role       SaaS Architect

stack      React · Next.js · TS

background Arch. Eng + CS

location   Morocco 🇲🇦

status     ✅ Available

  

$ git log --skills

\+ React & Next.js Specialist

\+ Scalable SaaS Architecture

\+ AI Integration / OpenAI API

\+ RTL Arabic-first UI Systems

\- Mediocre code (never committed)

"I don't just write code; I design systems." — OMAR ELBAZ

Years Experience5+

Projects Delivered25+

SpecialityReact / Next.js

AI SolutionsOpenAI · SaaS

BackendNode · Laravel · Postgres

DevOps / CloudDocker · AWS

◈   T E C H   S T A C K   ◈

React

Next.js

TypeScript

Tailwind CSS

Node.js

Laravel

PostgreSQL

Docker

AWS

Figma

OpenAI API

Framer Motion

Stripe

◈   S E L E C T E D   W O R K S   ◈

◈ CASE STUDY 01 · E-COMMERCE

🛍️ Intilaq E-Commerce

High-end Arabic-first e-commerce with **premium dark mode** and **native RTL support**. Built for luxury, engineered for scale.

Next.jsTailwind CSSRTL UIDark Mode

◈ CASE STUDY 02 · GENERATIVE AI

👟 Aura — AI Sneaker Studio

Futuristic platform with **built-in Generative AI**. Design sneakers via text prompts. Dark UI, Framer Motion, Stripe payments.

Next.js 14TypeScriptOpenAIStripeFramer

◈ CASE STUDY 03 · EDTECH

🎓 ArabAI Academy

The **leading Arabic AI education platform**. ML & Deep Learning courses, structured paths — empowering Arab youth.

Next.jsTypeScriptTailwindFramer Motion

◈ CASE STUDY 04 · HIGH TRAFFIC

📱 Alandroidnet — Alandroid العربي

**High-traffic** Arabic app reviews platform. Headless CMS powered, SEO optimised, serving the Arabic-speaking tech community.

Next.jsTailwindHeadless CMSSEO

◈   S T A T S   ◈

5+

Years

25+

Projects

13

Technologies

4

Case Studies

◈   C O N T R I B U T I O N   A C T I V I T Y   ◈

◈   L E T ' S   B U I L D   ◈

╔─────────────────────────────────────────────────────────╗  
│  Every great product starts with a conversation.      │  
│  Let's create something that stands the test of time. │  
╚─────────────────────────────────────────────────────────╝

[✉ EMAIL ME](mailto:oelbaz010@gmail.com) [🔗 LINKEDIN](https://www.linkedin.com/in/omaelbaz/) [◈ PORTFOLIO](https://omarelbaz.vercel.app/)

BUILT WITH NEXT.JS · TAILWIND · ❤️ · MOROCCO 🇲🇦  ·  © 2026 OMAR ELBAZ

// Random activity bars const bars = document.getElementById('bars'); const vals = \[15,28,42,55,38,62,70,45,80,55,38,90,65,48,72,55,38,85,60,42,75,50,88,63,45,70,55,40,95,68,50,82,58,42,76,60,45,88,65,48,72,56,38,80,62,44,78,58,42,85,65,50,90,70,52,88,68,48,76,60\]; vals.forEach(h => { const b = document.createElement('div'); b.className = 'act-bar'; b.style.height = h + '%'; b.style.minHeight = '3px'; bars.appendChild(b); });
