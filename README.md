<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=Android%20Security%20Evaluation%20Using%20Forensics%20Techniques&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Next.js%20%E2%80%A2%20TypeScript%20%E2%80%A2%20Genkit&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Android Security Evaluation Using Forensics Techniques" />

**A web tool that uses digital-forensics techniques and AI to evaluate how secure an Android device wipe really is: can deleted data be recovered, and are there threats left behind?**

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Genkit-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Genkit" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

<p>
  <a href="#features">Features</a> ·
  <a href="#tech-stack">Tech stack</a> ·
  <a href="#project-structure">Project structure</a> ·
  <a href="#getting-started">Getting started</a>
</p>

</div>

---

## Features

- Wipe accuracy assessment: checks how completely data was erased
- Recovery potential analysis and a simulated recovery flow
- Threat detection on uploaded evidence files
- Clear result cards for each analysis, with login and a sidebar dashboard

## Tech stack

- Next.js, React, TypeScript
- Google Genkit with Gemini for the analysis flows
- Tailwind CSS, shadcn/ui

## Project structure

```
src/ai/flows/     wipe-accuracy-assessment, recovery-potential-analysis, simulate-recovery-flow, threat-detection
src/components/   upload, result cards, layout
```

## Getting started

```bash
npm install
echo "GOOGLE_GENAI_API_KEY=your-key" > .env.local
npm run dev
```

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
