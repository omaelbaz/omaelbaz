<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Omar Elbaz — GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Sora:wght@300;400;600;700&display=swap" rel="stylesheet"/>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--t:#64ffda;--navy:#0a192f;--dark:#07101a;--card:#0d1a27;--muted:#637087;--bright:#ccd6f6;--dim:#3d5166;--mono:'JetBrains Mono',monospace;--sans:'Sora',sans-serif;--r:8px}
html,body{background:var(--dark);color:var(--bright);font-family:var(--sans);font-size:13px;min-height:100vh}
.hero{background:var(--dark);padding:56px 36px 48px;text-align:center;border-bottom:1px solid rgba(100,255,218,.07);position:relative;overflow:hidden}
.hero-grid{position:absolute;inset:0;background-image:linear-gradient(rgba(100,255,218,.03) 1px,transparent 1px),linear-gradient(90deg,rgba(100,255,218,.03) 1px,transparent 1px);background-size:40px 40px}
.hero-glow{position:absolute;top:-80px;left:50%;transform:translateX(-50%);width:600px;height:320px;background:radial-gradient(ellipse,rgba(100,255,218,.07) 0%,transparent 70%)}
.hero-name{font-family:var(--mono);font-size:64px;font-weight:800;color:#fff;letter-spacing:-2px;line-height:1;position:relative}
.hero-name span{color:var(--t)}
.hero-rule{width:120px;height:1px;background:linear-gradient(90deg,transparent,var(--t),transparent);margin:16px auto}
.hero-role{font-family:var(--mono);font-size:11px;letter-spacing:5px;color:var(--t);opacity:.85;position:relative;text-transform:uppercase}
.hero-sub{font-size:12px;color:var(--muted);margin-top:6px;position:relative}
.pills{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;padding:22px 24px 8px}
.pill{display:inline-flex;align-items:center;gap:7px;padding:7px 16px;border-radius:4px;font-family:var(--mono);font-size:10px;font-weight:700;letter-spacing:.5px;text-decoration:none;transition:transform .15s,filter .15s;border:1px solid transparent}
.pill:hover{transform:translateY(-2px);filter:brightness(1.15)}
.p-gh{background:#0d1117;color:#e2e8f0;border-color:#21262d}
.p-li{background:#0a4fa6;color:#e2e8f0}
.p-x{background:#111;color:#e2e8f0;border-color:#333}
.p-em{background:#b91c1c;color:#fef2f2}
.p-po{background:var(--t);color:#021714;font-weight:800}
.status-row{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;padding:6px 24px 0}
.s-pill{font-family:var(--mono);font-size:10px;padding:4px 12px;border-radius:3px;background:rgba(100,255,218,.06);color:var(--t);border:1px solid rgba(100,255,218,.2)}
.div{height:1px;background:linear-gradient(90deg,transparent,rgba(100,255,218,.3),rgba(0,191,255,.4),rgba(100,255,218,.3),transparent);margin:28px 0;opacity:.6}
.section{padding:0 32px 32px}
.sec-label{font-family:var(--mono);font-size:9px;letter-spacing:5px;color:var(--t);text-align:center;margin-bottom:24px;opacity:.8;text-transform:uppercase}
.term{background:#060f17;border:1px solid rgba(100,255,218,.12);border-radius:var(--r);overflow:hidden}
.term-bar{background:#0a1520;padding:9px 16px;display:flex;align-items:center;gap:6px;border-bottom:1px solid rgba(100,255,218,.06)}
.td{width:9px;height:9px;border-radius:50%}
.term-title{font-family:var(--mono);font-size:10px;color:var(--muted);margin-left:8px}
.term-body{padding:18px 20px;font-family:var(--mono);font-size:12px;line-height:2.1}
.tc{color:var(--t)}.tm{color:var(--muted)}.tv{color:#e2e8f0}.tp{color:var(--t)}.tn{color:#ff6b6b}
.quote{border-left:2px solid var(--t);padding:14px 18px;margin-top:14px;background:rgba(100,255,218,.03);border-radius:0 var(--r) var(--r) 0}
.quote p{font-size:13px;color:var(--muted);font-style:italic;line-height:1.6}
.quote cite{font-family:var(--mono);font-size:9px;color:var(--t);letter-spacing:2px;margin-top:6px;display:block;font-style:normal}
.skill{margin-bottom:13px}
.skill-top{display:flex;justify-content:space-between;margin-bottom:5px}
.skill-name{font-family:var(--mono);font-size:10px;color:var(--bright)}
.skill-pct{font-family:var(--mono);font-size:10px;color:var(--t)}
.skill-bg{height:3px;background:rgba(100,255,218,.08);border-radius:2px}
.skill-fill{height:3px;border-radius:2px;background:linear-gradient(90deg,var(--t),#00bfff)}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:12px}
.tech-grid{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
.tech-item{display:flex;align-items:center;gap:8px;background:rgba(100,255,218,.04);border:1px solid rgba(100,255,218,.1);border-radius:6px;padding:8px 14px;font-family:var(--mono);font-size:11px;color:var(--muted);transition:all .2s;cursor:default}
.tech-item:hover{border-color:var(--t);color:var(--t);transform:translateY(-2px)}
.p-card{background:var(--card);border:1px solid rgba(100,255,218,.08);border-radius:10px;padding:22px;position:relative;overflow:hidden;transition:border-color .2s,transform .2s}
.p-card:hover{border-color:rgba(100,255,218,.35);transform:translateY(-3px)}
.p-card::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--t),transparent);opacity:0;transition:opacity .2s}
.p-card:hover::before{opacity:1}
.p-num{font-family:var(--mono);font-size:9px;color:var(--t);letter-spacing:3px;opacity:.6;margin-bottom:8px}
.p-title{font-size:14px;font-weight:700;color:#fff;margin-bottom:8px}
.p-desc{font-size:12px;color:var(--muted);line-height:1.7;margin-bottom:14px}
.p-desc strong{color:var(--bright)}
.p-tags{display:flex;flex-wrap:wrap;gap:5px}
.p-tag{background:rgba(100,255,218,.06);border:1px solid rgba(100,255,218,.16);border-radius:3px;padding:2px 9px;font-family:var(--mono);font-size:9px;color:var(--t)}
.m-card{background:var(--card);border:1px solid rgba(100,255,218,.08);border-radius:var(--r);padding:18px;text-align:center}
.m-val{font-family:var(--mono);font-size:30px;font-weight:800;color:var(--t)}
.m-lbl{font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:2px;text-transform:uppercase;margin-top:4px}
.act-wrap{background:var(--card);border:1px solid rgba(100,255,218,.08);border-radius:var(--r);padding:18px}
.act-bars{display:flex;align-items:flex-end;gap:3px;height:60px}
.act-bar{flex:1;border-radius:2px 2px 0 0;background:rgba(100,255,218,.15);transition:background .2s}
.act-bar:hover{background:var(--t)}
.cta{text-align:center;padding:36px 32px 32px}
.cta-box{font-family:var(--mono);font-size:10px;color:rgba(100,255,218,.3);line-height:2;margin-bottom:22px}
.cta-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
.cta-btn{padding:11px 24px;border-radius:4px;font-family:var(--mono);font-size:11px;font-weight:700;text-decoration:none;letter-spacing:1px;transition:all .2s;display:inline-flex;align-items:center;gap:8px}
.cta-btn:hover{transform:translateY(-2px);filter:brightness(1.1)}
.be{background:#b91c1c;color:#fef2f2}.bl{background:#0a4fa6;color:#e2e8f0}.bp{background:var(--t);color:#021714}
.footer{background:linear-gradient(180deg,var(--navy),var(--dark));text-align:center;padding:24px;font-family:var(--mono);font-size:9px;color:rgba(100,255,218,.3);letter-spacing:3px;border-top:1px solid rgba(100,255,218,.05)}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.cur{animation:blink 1s infinite}
@media(max-width:600px){.g2,.g4{grid-template-columns:1fr}.hero-name{font-size:40px}}
</style>
</head>
<body>

<div class="hero">
  <div class="hero-grid"></div>
  <div class="hero-glow"></div>
  <div class="hero-name">Omar <span>Elbaz</span></div>
  <div class="hero-rule"></div>
  <div class="hero-role">SaaS Architect &nbsp;·&nbsp; Full Stack Engineer &nbsp;·&nbsp; AI Solutions</div>
  <div class="hero-sub">Architecting Digital Empires &nbsp;|&nbsp; Morocco &#127474;&#127462;</div>
</div>

<div class="pills">
  <a href="https://github.com/omaelbaz" class="pill p-gh">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.008-.866-.013-1.7-2.782.603-3.369-1.342-3.369-1.342-.454-1.155-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.268 2.75 1.026A9.578 9.578 0 0112 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.026 2.747-1.026.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.741 0 .267.18.578.688.48C19.138 20.163 22 16.418 22 12c0-5.523-4.477-10-10-10z"/></svg>
    GITHUB
  </a>
  <a href="https://www.linkedin.com/in/omaelbaz/" class="pill p-li">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
    LINKEDIN
  </a>
  <a href="https://x.com/omaelbaz" class="pill p-x">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-4.714-6.231-5.401 6.231H2.744l7.73-8.835L1.254 2.25H8.08l4.253 5.622 5.912-5.622zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
    X / TWITTER
  </a>
  <a href="mailto:oelbaz010@gmail.com" class="pill p-em">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
    EMAIL
  </a>
  <a href="https://omarelbaz.vercel.app/" class="pill p-po">
    <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 19.778h20L12 2z"/></svg>
    PORTFOLIO
  </a>
</div>
<div class="status-row" style="margin-bottom:6px">
  <span class="s-pill">&#10003; AVAILABLE FOR INNOVATION</span>
  <span class="s-pill">&#9889; 5+ YEARS</span>
  <span class="s-pill">&#128640; 25+ PROJECTS</span>
</div>

<div style="padding:0 32px"><div class="div"></div></div>

<div class="section">
  <div class="sec-label">&#9674; &nbsp; A B O U T &nbsp; M E &nbsp; &#9674;</div>
  <div class="g2">
    <div>
      <div class="term">
        <div class="term-bar">
          <div class="td" style="background:#ff5f57"></div>
          <div class="td" style="background:#ffbd2e"></div>
          <div class="td" style="background:#28c940"></div>
          <span class="term-title">~/omar-elbaz — bash</span>
        </div>
        <div class="term-body">
          <div><span class="tc">$</span> <span class="tv">whoami</span></div>
          <div style="padding-left:14px;margin-top:2px">
            <div><span class="tm">name &nbsp;&nbsp;&nbsp;&nbsp;</span><span class="tv"> Omar Elbaz</span></div>
            <div><span class="tm">role &nbsp;&nbsp;&nbsp;&nbsp;</span><span class="tv"> SaaS Architect</span></div>
            <div><span class="tm">stack &nbsp;&nbsp;&nbsp;</span><span class="tv"> React · Next.js · TS</span></div>
            <div><span class="tm">bg &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="tv"> Arch.Eng + CS</span></div>
            <div><span class="tm">location </span><span class="tv"> Morocco &#127474;&#127462;</span></div>
            <div><span class="tm">status &nbsp;&nbsp;</span><span class="tv"> &#10003; Open to Work</span></div>
          </div>
          <br/>
          <div><span class="tc">$</span> <span class="tv">git log --skills</span></div>
          <div style="padding-left:14px;margin-top:2px">
            <div class="tp">+ React &amp; Next.js Specialist</div>
            <div class="tp">+ Scalable SaaS Architecture</div>
            <div class="tp">+ AI Integration / OpenAI API</div>
            <div class="tp">+ RTL Arabic-first UI Systems</div>
            <div class="tn">- Mediocre code (never committed)</div>
          </div>
          <div style="margin-top:10px"><span class="tc">$</span> <span class="cur">&#9646;</span></div>
        </div>
      </div>
      <div class="quote">
        <p>"I don't just write code; I design systems."</p>
        <cite>— OMAR ELBAZ</cite>
      </div>
    </div>
    <div>
      <div style="margin-bottom:18px">
        <div class="skill"><div class="skill-top"><span class="skill-name">React / Next.js</span><span class="skill-pct">95%</span></div><div class="skill-bg"><div class="skill-fill" style="width:95%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">TypeScript</span><span class="skill-pct">88%</span></div><div class="skill-bg"><div class="skill-fill" style="width:88%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">SaaS Architecture</span><span class="skill-pct">82%</span></div><div class="skill-bg"><div class="skill-fill" style="width:82%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">AI / OpenAI API</span><span class="skill-pct">75%</span></div><div class="skill-bg"><div class="skill-fill" style="width:75%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">Node · Laravel · Postgres</span><span class="skill-pct">80%</span></div><div class="skill-bg"><div class="skill-fill" style="width:80%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">Docker · AWS</span><span class="skill-pct">65%</span></div><div class="skill-bg"><div class="skill-fill" style="width:65%"></div></div></div>
        <div class="skill"><div class="skill-top"><span class="skill-name">Figma / UI Design</span><span class="skill-pct">78%</span></div><div class="skill-bg"><div class="skill-fill" style="width:78%"></div></div></div>
      </div>
      <div class="g4" style="grid-template-columns:1fr 1fr">
        <div class="m-card"><div class="m-val">5+</div><div class="m-lbl">Years</div></div>
        <div class="m-card"><div class="m-val">25+</div><div class="m-lbl">Projects</div></div>
        <div class="m-card"><div class="m-val">13</div><div class="m-lbl">Tech</div></div>
        <div class="m-card"><div class="m-val">4</div><div class="m-lbl">Studies</div></div>
      </div>
    </div>
  </div>
</div>

<div style="padding:0 32px"><div class="div"></div></div>

<div class="section">
  <div class="sec-label">&#9674; &nbsp; T E C H &nbsp; S T A C K &nbsp; &#9674;</div>
  <div class="tech-grid">
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><circle cx="12" cy="12" r="2.5" fill="#61DAFB"/><ellipse cx="12" cy="12" rx="10" ry="4" fill="none" stroke="#61DAFB" stroke-width="1.5"/><ellipse cx="12" cy="12" rx="10" ry="4" fill="none" stroke="#61DAFB" stroke-width="1.5" transform="rotate(60 12 12)"/><ellipse cx="12" cy="12" rx="10" ry="4" fill="none" stroke="#61DAFB" stroke-width="1.5" transform="rotate(120 12 12)"/></svg>React</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#ffffff"><path d="M11.572 0c-.176 0-.31.001-.358.007a19.76 19.76 0 01-.364.033C7.443.346 4.25 2.185 2.228 5.012a11.875 11.875 0 00-2.119 5.243c-.096.659-.108.854-.108 1.747s.012 1.089.108 1.748c.652 4.506 3.86 8.292 8.209 9.695.779.25 1.6.422 2.534.525.363.04 1.935.04 2.299 0 1.611-.178 2.977-.577 4.323-1.264.207-.106.247-.134.219-.158-.02-.013-.9-1.193-1.955-2.62l-1.919-2.592-2.404-3.558a338.739 338.739 0 00-2.422-3.556c-.009-.002-.018 1.579-.023 3.51-.007 3.38-.01 3.515-.052 3.595a.426.426 0 01-.206.214c-.075.037-.14.044-.495.044H7.81l-.108-.068a.438.438 0 01-.157-.171l-.049-.106.005-4.703.007-4.705.073-.091a.637.637 0 01.174-.143c.096-.047.134-.051.54-.051.478 0 .558.018.682.154.035.038 1.337 1.999 2.895 4.361a10760.433 10760.433 0 004.735 7.17l1.9 2.879.096-.063a12.317 12.317 0 002.466-2.163 11.944 11.944 0 002.824-6.134c.096-.66.108-.854.108-1.748 0-.893-.012-1.088-.108-1.747-.652-4.506-3.859-8.292-8.208-9.695a12.597 12.597 0 00-2.499-.523A33.119 33.119 0 0011.573 0z"/></svg>Next.js</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><rect x="2" y="2" width="20" height="20" rx="2" fill="#3178C6"/><path d="M14.4 13.5v1.4c.3.2.7.3 1.1.4.4.1.9.1 1.3.1.4 0 .8 0 1.2-.1.4-.1.7-.2 1-.4.3-.2.5-.4.6-.7.2-.3.2-.6.2-1 0-.3 0-.5-.1-.7-.1-.2-.2-.4-.4-.5-.2-.2-.4-.3-.6-.4-.2-.1-.5-.2-.8-.3-.2-.1-.4-.2-.6-.2-.2-.1-.3-.2-.4-.3-.1-.1-.2-.2-.2-.3 0-.1-.1-.2-.1-.3 0-.1 0-.2.1-.3.1-.1.1-.2.2-.2.1-.1.2-.1.4-.2.2 0 .3-.1.5-.1.1 0 .3 0 .4.1.2 0 .3.1.4.1.1.1.2.1.3.2.1.1.2.1.2.2v-1.4c-.2-.1-.5-.2-.8-.2-.3-.1-.6-.1-1-.1-.4 0-.8 0-1.1.1-.3.1-.6.2-.9.4-.3.2-.5.4-.6.7-.1.3-.2.6-.2.9 0 .5.1.9.4 1.2.3.3.7.6 1.2.8.2.1.4.2.6.2.2.1.3.2.5.3.1.1.2.2.3.3.1.1.1.2.1.4 0 .1 0 .2-.1.3-.1.1-.1.2-.2.3-.1.1-.2.1-.4.2-.2 0-.3.1-.5.1-.4 0-.7-.1-1-.2-.4-.2-.7-.4-1-.7zM9.3 9.1H6.7V19h1.7v-3.8h.8c.6 0 1.1-.1 1.5-.2.5-.1.8-.3 1.1-.6.3-.2.5-.5.7-.9.1-.4.2-.7.2-1.2 0-.4-.1-.8-.2-1.1-.2-.3-.4-.6-.7-.8-.3-.2-.6-.4-1-.5-.3-.1-.8-.2-1.5-.2zm0 4.3c-.1.1-.4.2-.8.2H8.4v-3.1h.1c.2 0 .4 0 .6.1.2.1.4.1.5.2.1.1.2.3.3.5.1.2.1.4.1.6 0 .2 0 .4-.1.6-.1.2-.1.3-.2.4-.1.2-.2.3-.4.5z" fill="white"/></svg>TypeScript</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><path d="M12 6C8.21 6 5.93 7.88 5 11.64c1.25-1.64 2.71-2.26 4.38-1.84.95.24 1.63.93 2.38 1.69C13.05 12.8 14.5 14 17 14c3.79 0 6.07-1.88 7-5.64-1.25 1.64-2.71 2.26-4.38 1.84-.95-.24-1.63-.93-2.38-1.69C15.95 7.2 14.5 6 12 6zM7 14c-3.79 0-6.07 1.88-7 5.64 1.25-1.64 2.71-2.26 4.38-1.84.95.24 1.63.93 2.38 1.69C8.05 20.8 9.5 22 12 22c3.79 0 6.07-1.88 7-5.64-1.25 1.64-2.71 2.26-4.38 1.84-.95-.24-1.63-.93-2.38-1.69C14.95 14.2 13.5 13 11 13" fill="#38BDF8"/></svg>Tailwind CSS</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><path d="M12 1.85c-.27 0-.55.07-.78.2l-7.44 4.3c-.48.28-.78.8-.78 1.36v8.58c0 .56.3 1.08.78 1.36l7.44 4.3c.46.26 1.05.26 1.56 0l7.44-4.3c.48-.28.78-.8.78-1.36V7.71c0-.56-.3-1.08-.78-1.36l-7.44-4.3c-.23-.13-.51-.2-.78-.2zM12 4l5.5 3.18v6.36L12 16.54 6.5 13.54V7.18L12 4zm0 2.18L8 8.5v5l4 2.32 4-2.32v-5L12 6.18z" fill="#6DA55F"/></svg>Node.js</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#FF2D20"><path d="M23.642 5.43a.364.364 0 01.014.1v5.149c0 .135-.073.26-.189.326l-4.323 2.49v4.934a.378.378 0 01-.188.326L9.93 23.949a.316.316 0 01-.066.027.26.26 0 01-.057.017.286.286 0 01-.203-.017L.718 18.755a.376.376 0 01-.189-.326V4.947a.36.36 0 01.014-.1.233.233 0 01.024-.055l.028-.045a.327.327 0 01.05-.056c.007-.006.014-.015.022-.02L4.83 2.418a.38.38 0 01.378 0l4.164 2.253a.382.382 0 01.189.327v4.863l3.945-2.28V2.717a.382.382 0 01.189-.327l4.164-2.253a.38.38 0 01.378 0l4.162 2.253a.376.376 0 01.143.14zM9.217 18.102l-4.67-2.698V10.44l4.67 2.698v4.964zm8.68-5.001l-4.667-2.698 4.667-2.698 4.667 2.698-4.667 2.698zm-.378 4.966v-4.964l4.67-2.698v4.964l-4.67 2.698z"/></svg>Laravel</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#4169E1"><path d="M17.128 0a10.134 10.134 0 00-2.755.403 5.834 5.834 0 00-.32.09C13.5.705 12.5 1.856 12 3.36c-.286-.41-.633-.8-1.05-1.152C9.887 1.246 8.58.807 7.28.73A8.97 8.97 0 005.842.8C3.155 1.175 1.078 3.27.802 5.9c-.023.224-.034.448-.034.67v6.41L0 13h1.984v2h1.98v2h1.992v2H7.95v2h2.012v-2h2.012v2h1.997v-2h1.985v-2h1.985v-2H19.95v-2h1.985v-2H24V6.57C24 2.943 21.077.102 17.128 0z"/></svg>PostgreSQL</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#2496ED"><path d="M13.983 11.078h2.119a.186.186 0 00.186-.185V9.006a.186.186 0 00-.186-.186h-2.119a.185.185 0 00-.185.185v1.888c0 .102.083.185.185.185m-2.954-5.43h2.118a.186.186 0 00.186-.186V3.574a.186.186 0 00-.186-.185h-2.118a.185.185 0 00-.185.185v1.888c0 .102.082.185.185.185m0 2.716h2.118a.187.187 0 00.186-.186V6.29a.186.186 0 00-.186-.185h-2.118a.185.185 0 00-.185.185v1.887c0 .102.082.185.185.186m-2.93 5.733h2.12a.186.186 0 00.184-.186v-1.88a.185.185 0 00-.185-.185H8.1a.185.185 0 00-.185.185v1.88c0 .102.083.186.185.186m-2.964-4.627h2.12a.186.186 0 00.185-.185V7.581a.186.186 0 00-.185-.185H5.135a.185.185 0 00-.185.185v1.888c0 .102.082.185.185.185M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm0 18c-4.418 0-8-3.582-8-8s3.582-8 8-8 8 3.582 8 8-3.582 8-8 8z"/></svg>Docker</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><path d="M18.75 9.18L12 2.44 5.25 9.18A9.1 9.1 0 002.44 16c0 5.08 4.27 9.14 9.56 9.14S21.56 21.08 21.56 16a9.1 9.1 0 00-2.81-6.82z" fill="none" stroke="#FF9900" stroke-width="1.5"/><path d="M12 7.56l4.5 4.56A6.39 6.39 0 0118.5 16c0 3.63-2.91 6.56-6.5 6.56S5.5 19.63 5.5 16a6.39 6.39 0 012-4.88L12 7.56z" fill="#FF9900" opacity=".4"/></svg>AWS</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24"><path d="M15.852 8.981h-4.588V0h4.588c2.476 0 4.49 2.014 4.49 4.49s-2.014 4.491-4.49 4.491zM12.735 7.51h3.117c1.665 0 3.019-1.355 3.019-3.019s-1.354-3.019-3.019-3.019h-3.117V7.51zm0 1.471H8.148c-2.476 0-4.49-2.014-4.49-4.49S5.672 0 8.148 0h4.588v8.981zm-4.587-7.51c-1.665 0-3.019 1.355-3.019 3.019s1.354 3.019 3.019 3.019h3.117V1.471H8.148zm4.587 15.019H8.148c-2.476 0-4.49-2.014-4.49-4.49s2.014-4.49 4.49-4.49h4.588v8.98zM8.148 11.981c-1.665 0-3.019 1.354-3.019 3.019s1.354 3.019 3.019 3.019h3.117v-6.038H8.148z" fill="#F24E1E"/></svg>Figma</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#412991"><path d="M22.282 9.821a5.985 5.985 0 00-.516-4.91 6.046 6.046 0 00-6.51-2.9A6.065 6.065 0 0011.25 1a5.984 5.984 0 00-5.722 4.124 6.049 6.049 0 00-3.985 2.905 6.046 6.046 0 00.023 6.073A5.985 5.985 0 002.084 19a6.046 6.046 0 006.51 2.9 6.065 6.065 0 004.007 1.311 5.984 5.984 0 005.723-4.124 6.049 6.049 0 003.984-2.905 6.046 6.046 0 00-.026-6.061zm-9.023 12.66a4.507 4.507 0 01-2.89-1.044l.142-.081 4.803-2.773a.795.795 0 00.4-.69v-6.775l2.03 1.173a.073.073 0 01.04.055v5.614a4.507 4.507 0 01-4.525 4.521zm-9.74-4.132a4.505 4.505 0 01-.535-3.014l.142.085 4.803 2.774a.768.768 0 00.8 0l5.864-3.386v2.346a.073.073 0 01-.029.062L9.651 21.95a4.501 4.501 0 01-6.13-3.6z"/></svg>OpenAI</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#EF008F"><path d="M15 2H9L2 12l5 10h10l5-10-7-10z" opacity=".5"/><path d="M15 2L9 12l3 10h3l5-10-5-10z"/></svg>Framer Motion</div>
    <div class="tech-item"><svg width="16" height="16" viewBox="0 0 24 24" fill="#635BFF"><path d="M13.976 9.15c-2.172-.806-3.356-1.426-3.356-2.409 0-.831.683-1.305 1.901-1.305 2.227 0 4.515.858 6.09 1.631l.89-5.494C18.252.975 15.697 0 12.165 0 9.667 0 7.589.654 6.104 1.872 4.56 3.147 3.757 4.992 3.757 7.218c0 4.039 2.467 5.76 6.476 7.219 2.585.92 3.445 1.574 3.445 2.583 0 .98-.84 1.545-2.354 1.545-1.875 0-4.965-.921-6.99-2.109l-.9 5.555C5.175 22.99 8.385 24 11.714 24c2.641 0 4.843-.624 6.328-1.813 1.664-1.305 2.525-3.236 2.525-5.732 0-4.128-2.524-5.851-6.594-7.305h.003z"/></svg>Stripe</div>
  </div>
</div>

<div style="padding:0 32px"><div class="div"></div></div>

<div class="section">
  <div class="sec-label">&#9674; &nbsp; S E L E C T E D &nbsp; W O R K S &nbsp; &#9674;</div>
  <div class="g2">
    <div class="p-card">
      <div class="p-num">&#9674; CASE STUDY 01 · E-COMMERCE</div>
      <div class="p-title">Intilaq E-Commerce</div>
      <div class="p-desc">High-end Arabic-first e-commerce with <strong>premium dark mode</strong> and <strong>native RTL support</strong>. Built for luxury, engineered for scale.</div>
      <div class="p-tags"><span class="p-tag">Next.js</span><span class="p-tag">Tailwind CSS</span><span class="p-tag">RTL UI</span><span class="p-tag">Dark Mode</span></div>
    </div>
    <div class="p-card">
      <div class="p-num">&#9674; CASE STUDY 02 · GENERATIVE AI</div>
      <div class="p-title">Aura — AI Sneaker Studio</div>
      <div class="p-desc">Futuristic platform with <strong>built-in Generative AI</strong>. Design sneakers via text prompts. Dark UI, Framer Motion transitions, Stripe payments.</div>
      <div class="p-tags"><span class="p-tag">Next.js 14</span><span class="p-tag">TypeScript</span><span class="p-tag">OpenAI API</span><span class="p-tag">Stripe</span><span class="p-tag">Framer</span></div>
    </div>
    <div class="p-card">
      <div class="p-num">&#9674; CASE STUDY 03 · EDTECH</div>
      <div class="p-title">ArabAI Academy</div>
      <div class="p-desc">The <strong>leading Arabic AI education platform</strong> — ML &amp; Deep Learning courses, structured paths, empowering Arab youth with future-ready skills.</div>
      <div class="p-tags"><span class="p-tag">Next.js</span><span class="p-tag">TypeScript</span><span class="p-tag">Tailwind</span><span class="p-tag">Framer Motion</span></div>
    </div>
    <div class="p-card">
      <div class="p-num">&#9674; CASE STUDY 04 · HIGH TRAFFIC</div>
      <div class="p-title">Alandroidnet — Alandroid العربي</div>
      <div class="p-desc"><strong>High-traffic</strong> Arabic app reviews &amp; downloads platform. Headless CMS powered, SEO optimised, serving the Arabic-speaking tech community.</div>
      <div class="p-tags"><span class="p-tag">Next.js</span><span class="p-tag">Tailwind</span><span class="p-tag">Headless CMS</span><span class="p-tag">SEO</span></div>
    </div>
  </div>
</div>

<div style="padding:0 32px"><div class="div"></div></div>

<div class="section">
  <div class="sec-label">&#9674; &nbsp; S T A T S &nbsp; &#9674;</div>
  <div class="g4" style="margin-bottom:16px">
    <div class="m-card"><div class="m-val">5+</div><div class="m-lbl">Years Exp.</div></div>
    <div class="m-card"><div class="m-val">25+</div><div class="m-lbl">Projects</div></div>
    <div class="m-card"><div class="m-val">13</div><div class="m-lbl">Technologies</div></div>
    <div class="m-card"><div class="m-val">4</div><div class="m-lbl">Case Studies</div></div>
  </div>
  <div class="act-wrap">
    <div style="font-family:var(--mono);font-size:9px;color:var(--muted);letter-spacing:3px;margin-bottom:12px">CONTRIBUTION ACTIVITY</div>
    <div class="act-bars" id="bars"></div>
  </div>
</div>

<div style="padding:0 32px"><div class="div"></div></div>

<div class="cta">
  <div style="font-family:var(--mono);font-size:9px;letter-spacing:5px;color:var(--t);margin-bottom:18px;opacity:.8">&#9674; &nbsp; L E T ' S &nbsp; B U I L D &nbsp; &#9674;</div>
  <div class="cta-box">
    &#9556;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9557;<br/>
    &#9553; &nbsp;Every great product starts with a conversation &nbsp;&#9553;<br/>
    &#9553; &nbsp;Let's build something that stands the test of time &#9553;<br/>
    &#9562;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9552;&#9565;
  </div>
  <div class="cta-btns">
    <a href="mailto:oelbaz010@gmail.com" class="cta-btn be">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
      EMAIL ME
    </a>
    <a href="https://www.linkedin.com/in/omaelbaz/" class="cta-btn bl">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452z"/></svg>
      LINKEDIN
    </a>
    <a href="https://omarelbaz.vercel.app/" class="cta-btn bp">
      <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 19.778h20L12 2z"/></svg>
      PORTFOLIO
    </a>
  </div>
</div>

<div class="footer">BUILT WITH NEXT.JS &nbsp;·&nbsp; TAILWIND &nbsp;·&nbsp; MOROCCO &#127474;&#127462; &nbsp;·&nbsp; &copy; 2026 OMAR ELBAZ</div>

<script>
const b=document.getElementById('bars');
[15,28,42,55,38,62,70,45,80,55,38,90,65,48,72,55,38,85,60,42,75,50,88,63,45,70,55,40,95,68,50,82,58,42,76,60,45,88,65,48,72,56,38,80,62,44,78,58,42,85,65,50,90,70,52,88,68,48,76,60].forEach(h=>{
  const d=document.createElement('div');
  d.className='act-bar';
  d.style.height=h+'%';
  b.appendChild(d);
});
</script>
</body>
</html>
