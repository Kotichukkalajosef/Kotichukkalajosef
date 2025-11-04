<!-- README: Cybersecurity Portfolio (SOC / Pentest / Bug Bounty) -->
<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=Kotichukkalajosef.Kotichukkalajosef" />

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=700&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Josef+Kotichukkala+(ZeroTrace);" />
</h1>

<h3 align="center">Aspiring SOC Analyst · Junior Penetration Tester · Bug Bounty Hunter</h3>

<br />

<div align="center">
  🔭 Currently building: <b>SIEM Detection Lab & AD Attack/Defense Playbooks</b><br />
  🌱 Learning: <b>Splunk, Wazuh, Detection Engineering, eJPT</b><br /><br />
  💬 Ask me about <b>SIEM tuning, threat hunting, AD attacks, web app pentesting</b>
  <a href="https://github.com/Kotichukkalajosef/Kotichukkalajosef/issues"><b>here</b></a>
</div>

<br />

<div align="center">
  <a href="mailto:josefkotichukkala@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/kotichukkala-josef/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://github.com/Kotichukkalajosef" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" target="_blank" />
  </a>
  <a href="https://tryhackme.com/p/YourProfile" target="_blank">
    <img src="https://img.shields.io/badge/TryHackMe-00A8FF?style=for-the-badge&logo=tryhackme&logoColor=white" target="_blank" />
  </a>
</div>

<iframe src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=1874155" style='border:none;'></iframe>


<hr />

<h2 align="center">⚒️ Core Skills & Tools</h2>

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,windows,python,wireshark,nmap,docker,git" />
  <img src="https://skillicons.dev/icons?i=aws,sql,burp,metasploit,powershell" />
</div>

<br />
<hr />

<h2 align="center">📂 Verified Projects & Artifacts</h2>
<p align="center">Each project contains: lab steps, PoC artifacts (screenshots/logs), methodology, and a concise professional report.</p>

<ul>
  <li>
    <strong>SIEM Lab — Wazuh + ELK</strong><br />
    <em>What I did:</em> Collected Windows/Linux logs + network telemetry, wrote detection rules for brute-force, suspicious PowerShell, persistence, and validated detections with simulated attacks.<br />
    <em>Artifacts:</em> <code>/reports/siem-lab-report.md</code> · dashboards · detection-rules.yml
  </li>
  <br />
  <li>
    <strong>Vulnerability Assessment & Exploit Lab</strong><br />
    <em>What I did:</em> End-to-end pentest on isolated targets (DVWA, Metasploitable): recon → discovery → exploit → remediation report with CVEs and risk ratings.<br />
    <em>Artifacts:</em> <code>/reports/vuln-assessment-report.pdf</code> · nmap/gobuster outputs · screenshots
  </li>
  <br />
  <li>
    <strong>Active Directory Attack & Defense Lab</strong><br />
    <em>What I did:</em> Simulated Kerberoast, Pass-the-Hash, and lateral movement; implemented GPO hardening and logging improvements; created detection playbooks.<br />
    <em>Artifacts:</em> <code>/projects/ad-lab/playbook.md</code> · bloodhound-screenshots
  </li>
  <br />
  <li>
    <strong>Network IDS & Tuning (Suricata)</strong><br />
    <em>What I did:</em> Deployed Suricata, generated malicious traffic, tuned rules to reduce false positives and capture targeted alerts.<br />
    <em>Artifacts:</em> <code>/projects/ids-tuning/</code> · alerts-screenshots
  </li>
  <br />
  <li>
    <strong>Threat Hunting & Automation</strong><br />
    <em>What I did:</em> Python tools to parse logs, correlate IOCs, and produce alert summaries for triage.<br />
    <em>Artifacts:</em> <code>/tools/log-correlation/</code> · sample-output.csv
  </li>
  <br />
  <li>
    <strong>CTF Writeups & Bug Bounty</strong><br />
    <em>What I did:</em> Public CTF writeups (HTB/TryHackMe) and responsibly disclosed bounty reports (redacted).<br />
    <em>Artifacts:</em> <code>/ctf-writeups/</code> · <code>/bug-bounty/</code>
  </li>
</ul>

<hr />

<h2 align="center">🧾 How I Document a Test</h2>
<ol>
  <li>Scope & Rules of Engagement (explicit and written)</li>
  <li>Recon & Enumeration — commands + outputs</li>
  <li>Findings & Risk Rating (CVSS where applicable)</li>
  <li>PoC / Exploit Steps (reproducible)</li>
  <li>Remediation & Mitigation</li>
  <li>Appendix: logs / screenshots / scripts</li>
</ol>

<hr />

<h2 align="center">🎓 Certifications & Training</h2>
<p align="center">
  <strong>In progress / planned:</strong> CompTIA Security+ · Splunk Core User · Blue Team Level 1 · eJPT
</p>

<hr />

<h2 align="center">📫 Contact & Responsible Disclosure</h2>
<p align="center">
  <strong>Email (professional):</strong> josefkotichukkala@gmail.com<br />
  <strong>CTF / Bounty Alias:</strong> <code>ZeroTrace</code> (use this on HTB, TryHackMe, HackerOne)<br />
  <strong>Responsible Disclosure:</strong> I accept only engagements with explicit written permission. For bounty reports, follow the program policy and include PoC + remediation.
</p>

<hr />

<h2 align="center">🔧 Quick Setup — Reproduce My SIEM Lab</h2>
<pre>
1) Clone repo
2) Run: docker-compose up -d (Wazuh + ELK + Suricata)
3) Inject sample logs: scripts/generate-logs.sh
4) Validate detections: open dashboards and run detection testcases in /tests/detections/
</pre>

<hr />

<div align="center">
  <h3>Stats & Contributions</h3>
  <img width="390" src="https://github-readme-streak-stats-salesp07.vercel.app/?user=Kotichukkalajosef&count_private=true&theme=react&border_radius=10" alt="streak stats"/>
  <img width="390" src="https://github-readme-stats-salesp07.vercel.app/api?username=Kotichukkalajosef&count_private=true&show_icons=true&theme=react&border_radius=10" alt="readme stats"/>
</div>

<br />
<hr />

<p align="center">Replace <code>ZeroTrace</code> with your final alias and add links to your artifact files. Keep each project folder tidy and include one-page executive summaries for recruiters.</p>
