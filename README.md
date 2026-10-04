<h1 align="center">Hey, I'm ashflamer 👋</h1><p align="center"> <em>I build developer tools — the small, sharp kind that fix one annoying thing properly.</em> </p><p align="center"> <a href="https://github.com/ashflamer?tab=repositories"> <img src="https://img.shields.io/badge/-Projects-0d1117?style=flat-square&logo=github&logoColor=white" alt="Projects"> </a> <!-- Add your links back by replacing the two placeholders and deleting these comment markers: <a href="https://linkedin.com/in/YOUR_LINKEDIN"> <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> <a href="mailto:YOUR_EMAIL"> <img src="https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"> </a> --> </p>
🔭 What I'm building\n
Project	What it does	Stack
pyvulncheck	Reachability-based CVE triage. Not "is a vulnerable version installed?" but "does a call path exist from my code to the vulnerable function?" PyPI advisories ship no symbol data, so it reconstructs it from each advisory's fix commit.	Python · zero dependencies
loglens	Drop in a log file, get answers. Auto-detects the format, collapses 4,000 lines into 12 patterns, flags the window where things broke.	FastAPI · React · TypeScript
resilient-fetch	Retries, timeouts, circuit breaking and request coalescing for fetch. 4.6 kB gzipped, zero dependencies.	TypeScript
gitpulse	Finds the risky parts of any git repo — bus factor, churn hotspots, knowledge silos — from git log alone.	Python
envguard	Catches .env drift and hardcoded secrets before they ship. CI-friendly exit codes.	Python
algoviz	Watch A*, Dijkstra and friends think. One HTML file, no build step. Live demo →	JavaScript · Canvas
🛠️ Tools I reach for
Python
TypeScript
React
FastAPI
Node.js
PostgreSQL
Docker
GitHub Actions
Linux

📊 Activity
<p align="center"> <img height="165" src="https://github-readme-stats.vercel.app/api?username=ashflamer&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&include_all_commits=true&count_private=true" alt="GitHub stats"> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashflamer&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&langs_count=8" alt="Top languages"> </p>
💭 How I work
Zero dependencies where it's reasonable. Five of the six projects above ship with none. Fewer moving parts, no supply-chain surprises, and you actually have to understand the problem.
Tests on the parts that break. Not coverage theatre — timestamp edge cases, invalid UTF-8, statistical corner cases, the 404-that-shouldn't-open-a-circuit.
Check the premise before building. pyvulncheck exists because I confirmed, against the
live OSV API, that PyPI advisories return an empty ecosystem_specific while Go's return a
full symbol list. There's a test asserting that gap; if it ever closes, the suite goes red.

<p align="center"> <em>Open to interesting problems — especially in developer tooling, infrastructure and backend systems.</em> </p>
