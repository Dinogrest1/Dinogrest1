<!-- ════════════════════════════ HEADER ════════════════════════════ -->
<div align="center">

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/header.svg" width="100%" alt="Bogdan Tovstenko — AI Engineer, Automation Specialist, Generative AI" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=4A90D9&center=true&vCenter=true&width=780&height=42&lines=I+automate+what+shouldn't+be+done+by+hand;LLM+pipelines+%C2%B7+n8n+%C2%B7+agentic+systems;Ad+analytics+on+Gemini+%2B+Meta+Marketing+API;Self-hosted+generative+media+with+ComfyUI" alt="What I do" />

<br/>

<img src="https://img.shields.io/badge/Kyiv-Ukraine-0F2027?style=for-the-badge&logo=googlemaps&logoColor=7FD1FF&labelColor=0D1117" alt="Kyiv, Ukraine" />
<img src="https://img.shields.io/badge/MSc-AI_in_Biomedical_Systems_·_KPI-4A90D9?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=0D1117" alt="MSc at KPI" />

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/divider.svg" width="100%" alt="" />

</div>

<!-- ════════════════════════════ ABOUT ════════════════════════════ -->

## `$ whoami`

```yaml
name:      Bogdan Tovstenko
role:      AI Engineer & Automation Specialist @ Kyiv-Mohyla Business School
studying:  MSc — AI Technologies in Biomedical Systems, Igor Sikorsky KPI
focus:
  - turning manual business processes into unattended pipelines
  - LLM systems with structured output, validation and real guardrails
  - marketing automation: ad analytics in, generated creatives out
  - self-hosted generative media on open-weight models
languages: [Ukrainian (native), English (B2)]
```

I build **end-to-end automation** — the kind where nobody opens a dashboard anymore. Most of my work joins three things that usually live apart: **LLM APIs**, **external platforms** (ad networks, messengers, storage) and **internal CRM/SQL data**. Right now that means a closed marketing loop: a system that diagnoses ad performance, and a generative pipeline that produces the next batch of creatives from that diagnosis.

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/divider.svg" width="100%" alt="" />

<!-- ════════════════════════════ STACK ════════════════════════════ -->

## `$ ls ~/stack`

<table>
<tr>
<td valign="top" width="50%">

**Languages & Runtime**

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,nodejs,bash&theme=dark" alt="Python, TypeScript, JavaScript, Node.js, Bash" />

**Web & Data**

<img src="https://skillicons.dev/icons?i=react,nextjs,express,tailwind,postgres,prisma&theme=dark" alt="React, Next.js, Express, Tailwind, PostgreSQL, Prisma" />

**Tooling**

<img src="https://skillicons.dev/icons?i=docker,git,github,linux,vscode,vercel&theme=dark" alt="Docker, Git, GitHub, Linux, VS Code, Vercel" />

</td>
<td valign="top" width="50%">

**AI / LLM**

![Gemini](https://img.shields.io/badge/Google_Gemini-1F3A63?style=flat-square&logo=googlegemini&logoColor=7FD1FF)
![OpenRouter](https://img.shields.io/badge/OpenRouter-4A90D9?style=flat-square&logo=openai&logoColor=white)
![Agentic](https://img.shields.io/badge/Agentic_Systems-0F2027?style=flat-square&logo=probot&logoColor=7FD1FF)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-1F3A63?style=flat-square&logo=openaigym&logoColor=white)
![Structured Output](https://img.shields.io/badge/Structured_Output_·_JSON_Schema-4A90D9?style=flat-square&logo=json&logoColor=white)
![RAG](https://img.shields.io/badge/Multimodal_Analysis-0F2027?style=flat-square&logo=googlebard&logoColor=7FD1FF)

**Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Meta](https://img.shields.io/badge/Meta_Marketing_API-0866FF?style=flat-square&logo=meta&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks_·_Cron-1F3A63?style=flat-square&logo=zapier&logoColor=white)
![SQL](https://img.shields.io/badge/SQL_·_CRM-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Generative Media**

![ComfyUI](https://img.shields.io/badge/ComfyUI-1F3A63?style=flat-square&logo=nodered&logoColor=7FD1FF)
![SDXL](https://img.shields.io/badge/SDXL_·_FLUX-4A90D9?style=flat-square&logo=stabilityai&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA_·_ControlNet_·_IPAdapter-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![GPU](https://img.shields.io/badge/Self--hosted_GPU-76B900?style=flat-square&logo=nvidia&logoColor=white)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/divider.svg" width="100%" alt="" />

<!-- ════════════════════════════ PROJECTS ════════════════════════════ -->

## `$ git log --oneline projects`

<table>
<tr>
<th width="20%" align="left">Project</th>
<th width="50%" align="left">What it does</th>
<th width="30%" align="left">Stack</th>
</tr>

<tr>
<td valign="top">

**[mediation_chat](https://github.com/Dinogrest1/mediation_chat)**

</td>
<td valign="top">

Production web app for **temporary, single-use AI chat sessions**. Admins define agents (system/developer prompts, model, temperature) and issue personal access links. Security is the whole point: only token *hashes* are stored, sessions bind to a device through signed httpOnly cookies plus a soft fingerprint, TTL is re-checked server-side on every message, and suspicious attempts are logged. Five link states — `active · used · expired · blocked · revoked` — with rate limiting on both validation and chat.

</td>
<td valign="top">

![TS](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Express](https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

</td>
</tr>

<tr>
<td valign="top">

**[profile_analyzer](https://github.com/Dinogrest1/profile_analyzer)**

</td>
<td valign="top">

**Documents in, report out.** Ingests PDF, DOCX, PPTX and XLSX through dedicated parsers — with **Tesseract OCR** as the fallback for scanned PDFs — routes the extracted content to an LLM via OpenRouter, then renders the result straight into a branded **Word document** from a `.docx` template. Ships with an admin panel: configurable custom fields, model selection, and per-request usage and cost logging.

</td>
<td valign="top">

![TS](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR-5C3EE8?style=flat-square&logo=tesseract&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
</tr>

<tr>
<td valign="top">

**Ad Analytics Loop**
<br/><sub>`internal · not public`</sub>

</td>
<td valign="top">

A closed daily loop over paid social. Scheduled n8n workflows pull Meta Insights at campaign/ad-set/ad level — handling pagination, backoff and token refresh — compute derived metrics and creative-fatigue signals, join leads against CRM outcomes in SQL, then hand a pre-triaged digest to Gemini for a structured verdict with reasoning. Every response is validated against a JSON schema and re-prompted on failure before anything reaches the team — and spend is measured against real enrolments, not platform-reported conversions.

</td>
<td valign="top">

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-1F3A63?style=flat-square&logo=googlegemini&logoColor=7FD1FF)
![Meta](https://img.shields.io/badge/Meta_Ads_API-0866FF?style=flat-square&logo=meta&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>

<tr>
<td valign="top">

**ComfyUI Creative Toolkit**
<br/><sub>`internal · not public`</sub>

</td>
<td valign="top">

Self-hosted creative production on open-weight models. Custom ComfyUI graphs for txt2img, img2img, inpaint/outpaint and upscaling; brand style locked in with LoRA adapters trained on in-house assets; ControlNet and IPAdapter for composition and reference control. Packaged as parameterised templates so non-technical marketers generate assets without touching a node editor — batched across every placement ratio and callable from n8n over the ComfyUI API.

</td>
<td valign="top">

![ComfyUI](https://img.shields.io/badge/ComfyUI-1F3A63?style=flat-square&logo=nodered&logoColor=7FD1FF)
![SDXL](https://img.shields.io/badge/SDXL_·_FLUX-4A90D9?style=flat-square&logo=stabilityai&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ControlNet](https://img.shields.io/badge/ControlNet_·_IPAdapter-0F2027?style=flat-square&logo=pytorch&logoColor=7FD1FF)
![GPU](https://img.shields.io/badge/Self--hosted_GPU-76B900?style=flat-square&logo=nvidia&logoColor=white)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/divider.svg" width="100%" alt="" />

<!-- ════════════════════════════ STATS ════════════════════════════ -->

## `$ gh repo list`

<div align="center">

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/stats.svg" width="100%" alt="Repository composition: 14 repositories, 10 with a primary language, led by TypeScript and HTML." />

<!--
  ┌─────────────────────────────────────────────────────────────────────┐
  │ SNAKE ANIMATION — розкоментуй ПІСЛЯ того, як додаси                 │
  │ .github/workflows/snake.yml і один раз запустиш його вручну         │
  │ (Actions → "Generate snake animation" → Run workflow).              │
  │ Воркфлоу створює гілку `output` з готовими SVG.                     │
  └─────────────────────────────────────────────────────────────────────┘

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/output/github-snake.svg" width="98%" alt="Snake eating the contribution graph" />
</picture>
-->

</div>

<img src="https://raw.githubusercontent.com/Dinogrest1/Dinogrest1/main/assets/divider.svg" width="100%" alt="" />

<!-- ════════════════════════════ CONTACT ════════════════════════════ -->

## `$ contact --me`

<div align="center">

<!-- TODO: підстав свої реальні посилання -->
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://t.me/YOUR-TELEGRAM"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
<a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-1F3A63?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>

<br/><br/>


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4A90D9,50:1F3A63,100:0F2027&height=110&section=footer" width="100%" alt="" />

</div>
