
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  .profile-wrap { padding: 0 0 2rem; }
  .header { background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f64f59 100%); border-radius: var(--border-radius-lg); padding: 2.5rem 2rem 2rem; text-align: center; margin-bottom: 1.5rem; position: relative; overflow: hidden; }
  .header::before { content: ''; position: absolute; inset: 0; background: repeating-linear-gradient(45deg, transparent, transparent 30px, rgba(255,255,255,0.03) 30px, rgba(255,255,255,0.03) 60px); }
  .header h1 { font-size: 3rem; font-weight: 700; color: #fff; letter-spacing: -1px; margin-bottom: 0.25rem; font-family: var(--font-sans); position: relative; }
  .header p { color: rgba(255,255,255,0.8); font-size: 0.85rem; font-family: var(--font-mono); position: relative; }
  .socials { display: flex; justify-content: center; gap: 12px; margin-top: 1.25rem; position: relative; flex-wrap: wrap; }
  .social-btn { display: flex; align-items: center; gap: 7px; padding: 7px 16px; background: rgba(255,255,255,0.18); border: 1px solid rgba(255,255,255,0.35); border-radius: 20px; color: #fff; font-size: 13px; font-family: var(--font-sans); text-decoration: none; transition: background 0.2s; }
  .social-btn:hover { background: rgba(255,255,255,0.28); }
  .social-icon { width: 18px; height: 18px; object-fit: contain; }
  .li-icon { background: #0077b5; border-radius: 3px; width: 18px; height: 18px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .li-icon svg { width: 12px; height: 12px; fill: #fff; }
  .x-icon { background: #000; border-radius: 3px; width: 18px; height: 18px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .x-icon svg { width: 11px; height: 11px; fill: #fff; }
  .mail-icon { background: #ea4335; border-radius: 3px; width: 18px; height: 18px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .mail-icon svg { width: 12px; height: 12px; fill: #fff; }

  .card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); margin-bottom: 1rem; overflow: hidden; }
  .card-header { padding: 0.75rem 1.25rem; border-bottom: 0.5px solid var(--color-border-tertiary); display: flex; align-items: center; gap: 8px; }
  .dot { width: 8px; height: 8px; border-radius: 50%; }
  .card-header span { font-size: 11px; color: var(--color-text-secondary); font-family: var(--font-mono); }
  .card-body { padding: 1.25rem; }

  .code-block { font-family: var(--font-mono); font-size: 13px; line-height: 1.8; color: var(--color-text-primary); }
  .k { color: #a78bfa; }
  .s { color: #34d399; }
  .v { color: #60a5fa; }
  .p { color: var(--color-text-secondary); }
  .key { color: #f97316; }

  .section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); font-family: var(--font-sans); letter-spacing: 0.05em; text-transform: uppercase; margin-bottom: 1rem; }
  .divider { height: 1px; background: var(--color-border-tertiary); margin: 1.25rem 0; }

  .icon-grid { display: flex; flex-wrap: wrap; gap: 10px; }
  .icon-item { display: flex; flex-direction: column; align-items: center; gap: 6px; padding: 10px; background: var(--color-background-secondary); border-radius: var(--border-radius-md); width: 62px; transition: background 0.15s; }
  .icon-item:hover { background: var(--color-background-tertiary); }
  .icon-item img { width: 30px; height: 30px; object-fit: contain; }
  .icon-item span { font-size: 9px; color: var(--color-text-secondary); font-family: var(--font-sans); text-align: center; line-height: 1.2; }

  @media (prefers-color-scheme: dark) {
    .k { color: #c4b5fd; }
    .s { color: #6ee7b7; }
    .v { color: #93c5fd; }
    .key { color: #fb923c; }
    .x-icon { background: #fff; }
    .x-icon svg { fill: #000; }
  }
</style>

<div class="profile-wrap">
  <div class="header">
    <h1>Hello! 👋</h1>
    <p>Ali Rashid &nbsp;·&nbsp; Bangalore, India &nbsp;·&nbsp; B.Tech CSE</p>
    <div class="socials">
      <a class="social-btn" href="https://www.linkedin.com/in/ali-rashid-in">
        <div class="li-icon">
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        </div>
        LinkedIn
      </a>
      <a class="social-btn" href="https://x.com/Ali_Rashid_">
        <div class="x-icon">
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-4.714-6.231-5.401 6.231H2.742l7.73-8.835L1.254 2.25H8.08l4.253 5.622 5.892-5.622zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
        </div>
        Twitter / X
      </a>
      <a class="social-btn" href="mailto:alirashid.b37@gmail.com">
        <div class="mail-icon">
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M24 5.457v13.909c0 .904-.732 1.636-1.636 1.636h-3.819V11.73L12 16.64l-6.545-4.91v9.273H1.636A1.636 1.636 0 0 1 0 19.366V5.457c0-2.023 2.309-3.178 3.927-1.964L5.455 4.64 12 9.548l6.545-4.91 1.528-1.145C21.69 2.28 24 3.434 24 5.457z"/></svg>
        </div>
        Email
      </a>
    </div>
  </div>

  <div class="card">
    <div class="card-header">
      <div class="dot" style="background:#ef4444"></div>
      <div class="dot" style="background:#f59e0b"></div>
      <div class="dot" style="background:#22c55e"></div>
      <span>ali-rashid.ts</span>
    </div>
    <div class="card-body">
      <div class="code-block">
        <span class="k">const</span> <span class="v">aliRashid</span> <span class="p">= {</span><br>
        &nbsp;&nbsp;<span class="key">name</span><span class="p">:</span> <span class="s">"Ali Rashid"</span><span class="p">,</span><br>
        &nbsp;&nbsp;<span class="key">location</span><span class="p">:</span> <span class="s">"Bangalore, India"</span><span class="p">,</span><br>
        &nbsp;&nbsp;<span class="key">machineLearning</span><span class="p">: [</span><span class="s">"NLP"</span><span class="p">,</span> <span class="s">"Computer Vision"</span><span class="p">,</span> <span class="s">"Generative AI"</span><span class="p">],</span><br>
        &nbsp;&nbsp;<span class="key">backend</span><span class="p">: [</span><span class="s">"JavaScript"</span><span class="p">,</span> <span class="s">"TypeScript"</span><span class="p">,</span> <span class="s">"Golang"</span><span class="p">],</span><br>
        &nbsp;&nbsp;<span class="key">hobbies</span><span class="p">: [</span><span class="s">"Reading"</span><span class="p">,</span> <span class="s">"Cafe hopping"</span><span class="p">],</span><br>
        <span class="p">};</span>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-body">
      <div class="section-title">🔤 Languages</div>
      <div class="icon-grid">
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"/><span>Python</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg"/><span>C++</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg"/><span>Go</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg"/><span>TypeScript</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg"/><span>JavaScript</span></div>
      </div>

      <div class="divider"></div>

      <div class="section-title">🛠 Tools & Frameworks</div>
      <div class="icon-grid">
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg"/><span>TensorFlow</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg"/><span>PyTorch</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg"/><span>NumPy</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg"/><span>Pandas</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original-wordmark.svg"/><span>Matplotlib</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg"/><span>Node.js</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nestjs/nestjs-original.svg"/><span>NestJS</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/express/express-original.svg"/><span>Express</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg"/><span>React</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg"/><span>MongoDB</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongoose/mongoose-original.svg"/><span>Mongoose</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg"/><span>Git</span></div>
        <div class="icon-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg"/><span>GitHub</span></div>
      </div>
    </div>
  </div>
</div>
