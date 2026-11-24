# Android Security Evaluation Using Forensics Techniques

A web tool that uses digital-forensics techniques and AI to evaluate how secure an Android device wipe really is: can deleted data be recovered, and are there threats left behind?

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Genkit](https://img.shields.io/badge/Genkit-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

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

## Author

**Ch Muhammad Samiullah**, AI Automation Engineer and Full-Stack Developer.
[GitHub](https://github.com/samiullah156-creator) · [Lexvaxa](https://lexvaxa.com)
