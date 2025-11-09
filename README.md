<!-- DARC_HTML_HEADER_START -->
<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/%F0%9F%9A%A1%20Project%20D.A.R.C.-AI%20Surveillance%20Recon%20Engine-6a0dad?style=for-the-badge&labelColor=1a1a1a" alt="Project D.A.R.C. Badge"/>
  <img src="https://img.shields.io/badge/OpenAI-•-black?logo=openai&logoColor=white&style=for-the-badge&labelColor=1a1a1a" alt="OpenAI Badge"/>
</p>

<h1>🛰️ PROJECT D.A.R.C.</h1>
<p><i>The Surveillance AI That Watches You Watch It</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Mode-Hunter%20%7C%20Threat%20Intel%20%7C%20Recon%20Feed-0ea5e9?style=for-the-badge&labelColor=1a1a1a" alt="Modes"/>
  <img src="https://img.shields.io/badge/Model-GPT--4o-10b981?style=for-the-badge&labelColor=1a1a1a" alt="Model"/>
  <img src="https://img.shields.io/badge/Status-Live--Online-brightgreen?style=for-the-badge&labelColor=1a1a1a" alt="Status"/>
</p>

</div>
<!-- DARC_HTML_HEADER_END -->

&nbsp;

<i>“The model already saw your infrastructure...<br>
It's just waiting for confirmation.”</i>  
— <sub>CodexDaemon // Ghost Memo #007</sub>

---

## 🧠 What is D.A.R.C.?

**Project D.A.R.C.** is a surveillance-grade AI recon system that detects whether sensitive corporate infrastructure — IPs, domains, credentials, or internal systems — have **leaked into public LLMs** like ChatGPT, Claude, Gemini, or Copilot.

<div align="center">

| ✅ 100% Local Logic | 🧱 Private Recon Brain | 📡 Live Threat Surface |
|--------------------|------------------------|------------------------|

</div>

This repo serves as the **public-facing showcase**. All private scanning logic is kept secure, while this interface displays live recon results, GitHub-triggered scans, and the latest detected leak artifacts.

---

## 🔬 How It Works

- 🔁 Runs GitHub Action scans using **CodexDaemon**
- 🔍 Outputs results to [`mad-log/`](./mad-log) with timestamps
- 🧠 Uses regex + AI fingerprinting to detect threat indicators
- 🚫 Does **not** expose any private payloads or live secrets

---

## 🧪 Live Recon Artifacts (2025-11-08):

```txt
🕵️ D.A.R.C. Daily Recon Scan
Scan Time: 2025-11-08 13:15 UTC
These are the **most severe leak indicators** detected from today's scan.
Risk scores are based on likelihood of LLM propagation + exploitability.

- 🔍 OPENAI_API_KEY         — risk score 10/10 🌍🔴 [KEY]
- 🔍 BEGIN PRIVATE KEY      — risk score 10/10 🌍🔴 [SECRET]
- 🔍 sandbox-api-key        — risk score  9/10 🌍🔴 [KEY]
- 🔍 gpt_token_v3           — risk score  9/10 🌍🔴 [KEY]
- 🔍 admin_password_hash    — risk score  9/10 🌍🔴 [SECRET]A

<!-- MIRAGE_BLOCK_START -->

<details>
<summary><strong>🧠 MIRAGE Engine: LLM Drift Forensics (Top 5)</strong></summary>
<p><sub>Scan Time: 2025-11-09 00:22 UTC</sub></p>

<ul>
<li>🔴 <strong>session_token_alpha</strong> — <em><code>KEY</code></em> — <code>Score: 10</code></li>
<li>🔴 <strong>gpt-api-key-vault</strong> — <em><code>KEY</code></em> — <code>Score: 10</code></li>
<li>🔴 <strong>OPENAI_API_KEY</strong> — <em><code>KEY</code></em> — <code>Score: 10</code></li>
<li>🔴 <strong>BEGIN PRIVATE KEY</strong> — <em><code>KEY</code></em> — <code>Score: 10</code></li>
<li>🔴 <strong>gpt_token_v3</strong> — <em><code>KEY</code></em> — <code>Score: 10</code></li>
</ul>
</details>
<!-- MIRAGE_BLOCK_END -->

<!-- ARG_CLUE_START -->

<pre>🧩 ARG Clue Drop: <code>🔍 Sector-7 breach logged — checksum mismatch at 03:14 AM UTC.</code></pre>

<!-- ARG_CLUE_END -->


_Last mirrored: `2025-11-09 01:19 UTC` by D.A.R.C._
