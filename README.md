from pathlib import Path

html = """<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pranav Ramakrishnan | Security Operations & AI Automation</title>
<style>
body{font-family:Arial,sans-serif;max-width:1100px;margin:auto;padding:20px;line-height:1.6;background:#f8fafc;color:#111}
header{text-align:center;padding:60px 20px}
h1{font-size:3rem;margin-bottom:10px}
.hero{color:#2563eb;font-weight:bold}
section{background:white;padding:25px;margin:20px 0;border-radius:12px;box-shadow:0 2px 8px rgba(0,0,0,.08)}
h2{color:#2563eb}
.tag{display:inline-block;background:#dbeafe;color:#1d4ed8;padding:6px 10px;border-radius:20px;margin:4px}
a{color:#2563eb;text-decoration:none}
</style>
</head>
<body>
<header>
<h1>Pranav Ramakrishnan</h1>
<p class="hero">Security Operations Engineer | Vulnerability Management | AI-Driven Security Automation</p>
<p>Cavan, Ireland | +353 89 270 6071 | Pranavsudha07@gmail.com</p>
<p>
<a href="https://github.com/Pranav25072001/Earthquake-magnitude-prediction">GitHub Project</a>
</p>
</header>

<section>
<h2>About Me</h2>
<p>I am a security-focused analyst with experience in vulnerability management, SIEM implementation, endpoint monitoring, security reporting, and data analytics. My goal is to combine AI and automation with Security Operations to improve detection, triage, and incident response workflows.</p>
</section>

<section>
<h2>Security Experience</h2>
<h3>RJ Tech Pvt Ltd (2025 - Present)</h3>
<ul>
<li>Conduct vulnerability assessments and prioritize remediation.</li>
<li>Track risk exposure and remediation timelines.</li>
<li>Create dashboards for security reporting and analytics.</li>
</ul>

<h3>CyArt Tech (2023 - 2024)</h3>
<ul>
<li>Built a centralized SIEM using Wazuh and MongoDB.</li>
<li>Managed endpoint monitoring and security event analysis.</li>
<li>Developed security monitoring and reporting workflows.</li>
</ul>
</section>

<section>
<h2>AI & Security Interests</h2>
<ul>
<li>AI-assisted vulnerability triage</li>
<li>Security alert summarization</li>
<li>Threat intelligence enrichment</li>
<li>Security chatbots and investigation copilots</li>
<li>LLM security and prompt injection defenses</li>
</ul>
</section>

<section>
<h2>Featured Projects</h2>
<h3>Security Data Correlation Dashboard</h3>
<p>Unified CrowdStrike and Tenable data for centralized visibility and reporting.</p>

<h3>Earthquake Magnitude Prediction</h3>
<p>Machine learning project focused on earthquake prediction and risk reduction.</p>
<p><a href="https://github.com/Pranav25072001/Earthquake-magnitude-prediction">View Project</a></p>
</section>

<section>
<h2>Skills</h2>
<span class="tag">Wazuh</span>
<span class="tag">CrowdStrike</span>
<span class="tag">Tenable</span>
<span class="tag">Python</span>
<span class="tag">SQL</span>
<span class="tag">MongoDB</span>
<span class="tag">Power BI</span>
<span class="tag">Machine Learning</span>
<span class="tag">Security Operations</span>
</section>

<section>
<h2>Education & Certifications</h2>
<p>MSc Data Analytics – National College of Ireland</p>
<p>BSc Computer Science – Sri Krishna College of Arts and Science</p>
<p>CompTIA Security+ | Red Hat System Administration</p>
</section>

</body>
</html>"""

path = "/mnt/data/Pranav_Security_Portfolio.html"
Path(path).write_text(html, encoding="utf-8")
print(path)
