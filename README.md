# HPV_AI_ChatBot_KZ
This website is designed to creatively propose an AI integrated solution to HPV Vacination problem in Kazakhstan. The AI Chat Bot that I propose is desighned specifically for parents for 11-13 year old girls and is grounded in official medical info-portal egu.kz.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>[Your project title]</title>
<style>
  :root {
    --ink: #1f2a2e; --muted: #5b6b70; --bg: #faf8f5; --card: #ffffff;
    --accent: #0f6e6a; --warn: #c2562f; --line: #e3ded6;
  }
  * { box-sizing: border-box; }
  body { margin: 0; font-family: Georgia, "Times New Roman", serif; color: var(--ink); background: var(--bg); line-height: 1.7; }
  nav { position: sticky; top: 0; background: var(--card); border-bottom: 1px solid var(--line); padding: 10px 20px; display: flex; gap: 18px; flex-wrap: wrap; font-family: Arial, sans-serif; font-size: 14px; z-index: 10; }
  nav a { color: var(--accent); text-decoration: none; }
  section { max-width: 760px; margin: 0 auto; padding: 60px 20px; border-bottom: 1px solid var(--line); }
  h1, h2 { line-height: 1.25; }
  h2 small { display: block; font-family: Arial, sans-serif; font-size: 13px; color: var(--muted); letter-spacing: 0.05em; text-transform: uppercase; }
  .todo { background: #fff4d6; padding: 2px 6px; border-radius: 4px; }

  /* Opening: phone mock-up */
  #opening { min-height: 100vh; display: flex; flex-direction: column; justify-content: center; }
  .phone { max-width: 360px; margin: 20px auto; background: #e9e4dc; border-radius: 28px; padding: 18px; border: 8px solid #222; font-family: Arial, sans-serif; font-size: 15px; }
  .phone .time { text-align: center; color: var(--muted); font-size: 12px; margin-bottom: 10px; }
  .msg { background: var(--card); border-radius: 12px; padding: 10px 12px; margin: 8px 0; max-width: 85%; }
  .msg .from { font-size: 12px; color: var(--accent); font-weight: bold; }
  .msg.form { border-left: 4px solid var(--accent); }
  .choices { display: flex; flex-direction: column; gap: 10px; max-width: 360px; margin: 10px auto; font-family: Arial, sans-serif; }
  .choices a { display: block; text-align: center; padding: 12px; border-radius: 10px; text-decoration: none; border: 2px solid var(--accent); color: var(--accent); }
  .choices a:hover { background: var(--accent); color: #fff; }
  .label { text-align: center; font-family: Arial, sans-serif; font-size: 12px; color: var(--muted); }

  figure { margin: 30px 0; background: var(--card); border: 1px solid var(--line); padding: 16px; border-radius: 8px; }
  figure img { max-width: 100%; }
  figcaption { font-family: Arial, sans-serif; font-size: 13px; color: var(--muted); margin-top: 8px; }
  .verdict { border: 3px solid var(--warn); padding: 20px; border-radius: 8px; background: var(--card); }
  footer { text-align: center; padding: 40px 20px; font-family: Arial, sans-serif; font-size: 13px; color: var(--muted); }
</style>
</head>
<body>

<nav>
  <a href="#opening">Start</a>
  <a href="#problem">1. Problem</a>
  <a href="#data">2. Data</a>
  <a href="#research">3. Research</a>
  <a href="#solution">4. Solution &amp; bill</a>
  <a href="#verdict">Verdict</a>
  <a href="#transparency">AI transparency</a>
</nav>

<!-- OPENING C: the visitor is the parent -->
<section id="opening">
  <h1>[Your project title]</h1>
  <p>You are the parent of an 11-year-old girl in [city]. It is late evening.</p>

  <div class="phone">
    <div class="time">21:47</div>
    <div class="msg form">
      <div class="from">School</div>
      [Message about the HPV vaccination consent form, in your words]
    </div>
    <div class="msg">
      <div class="from">Parents' group chat</div>
      [The rumour, based on a documented concern, e.g. the infertility fear]
    </div>
  </div>

  <p class="label">Illustrative scenario. The rumour reflects concerns documented in [source].</p>

  <div class="choices">
    <a href="#problem">[Choice 1, e.g. "Sign the form"]</a>
    <a href="#problem">[Choice 2, e.g. "Ask in the chat"]</a>
    <a href="#problem">[Choice 3, e.g. "Don't sign"]</a>
  </div>
</section>

<section id="problem">
  <h2><small>Section 1</small>The problem</h2>
  <p class="todo">[Who is affected, where, at what scale, how it is changing. At least 3 credible sources.]</p>
  <p class="todo">[The social-science question inside the issue.]</p>
</section>

<section id="data">
  <h2><small>Section 2</small>Background &amp; data</h2>
  <p class="todo">[What BNS, the Ministry, WHO and researchers measure, and what it shows.]</p>
  <figure>
    <!-- Upload your chart image to the repository and replace the file name below -->
    <img src="figure1.png" alt="[Describe your chart for screen readers]">
    <figcaption>[Figure 1. Title. Source: ...]</figcaption>
  </figure>
  <p class="todo">[Where the data is silent, who falls through the gaps, and how far the numbers can be trusted.]</p>
</section>

<section id="research">
  <h2><small>Section 3</small>Current state of research</h2>
  <h3>[Approach 1, e.g. why parents hesitate]</h3>
  <p class="todo">[...]</p>
  <h3>[Approach 2, e.g. health workers as messengers]</h3>
  <p class="todo">[...]</p>
  <h3>[Approach 3, e.g. what works: interventions and AI]</h3>
  <p class="todo">[...]</p>
  <p class="todo">[The gap your project speaks to.]</p>
</section>

<section id="solution">
  <h2><small>Section 4</small>The AI-assisted solution, and what it would cost</h2>
  <h3>The proposal</h3>
  <p class="todo">[What system, doing what, run by whom, reaching whom.]</p>
  <h3>Case studies</h3>
  <p class="todo">[At least 2 documented cases, with sources.]</p>
  <h3>What I tested</h3>
  <p class="todo">[Your chatbot test: results table and the mock conversation.]</p>
  <h3>The bill</h3>
  <p class="todo">[Environmental · Economic · Labour · Political &amp; governance · Data ethics]</p>
</section>

<section id="verdict">
  <h2><small>Verdict</small>Should Kazakhstan do this?</h2>
  <div class="verdict">
    <p class="todo">[Yes / No / Only under these conditions, argued from the bill. Return to the parent from the opening.]</p>
  </div>
</section>

<section id="transparency">
  <h2><small>Required</small>AI transparency statement</h2>
  <p class="todo">[What AI contributed to the project and to this site, what you accepted, what you rejected and why. Note: this page's HTML skeleton was drafted by Claude.]</p>
</section>

<section id="sources">
  <h2><small>References</small>Sources</h2>
  <ol>
    <li class="todo">[Reference]</li>
  </ol>
</section>

<footer>[Your name or pseudonym] · PLS 419, Nazarbayev University · Fall 2026</footer>

</body>
</html>
