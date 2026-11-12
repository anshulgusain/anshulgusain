<h1 align="center">Anshul Gusain</h1>
<h3 align="center">Generative AI Full Stack Developer · I build AI agents and the full-stack products around them</h3>

<p align="center">
  <a href="https://anshulgusain.github.io/"><img src="https://img.shields.io/badge/Portfolio-anshulgusain.github.io-2dd4bf?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://anshulgusain.github.io/assets/resume/anshul-gusain-resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-111111?style=for-the-badge" alt="Resume"></a>
  <a href="https://linkedin.com/in/anshul-gusain-76573a224"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:anshulgusain99@gmail.com"><img src="https://img.shields.io/badge/Email-anshulgusain99%40gmail.com-555555?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Full stack developer with 1.5+ years of shipping production web apps in **React, Next.js, Node.js and TypeScript**. Lately I build generative AI products: agents that use tools and real browsers, conversational AI on WhatsApp and Instagram, and developer tools that write code in your project's style.

**Open to AI Engineer, Full Stack and Backend roles.** Based in Dehradun, India.

## Featured work

### [AnyTask](https://github.com/anshulgusain/AnyTask.Ai): an AI agent that QA-tests web apps · [Live demo](https://any-task-ai.vercel.app)

Paste a URL and describe the app. The agent opens it in a real browser, signs up with a throwaway account, fills in forms, clicks through the main flows and reports what works and what's broken, with screenshots and steps to reproduce.

- Observe-decide-act loop with **OpenAI tool calling**; **Playwright** drives the browser
- Acts on a numbered element map of each page instead of guessed CSS selectors
- Human-in-the-loop: asks for OTPs and credentials, takes mid-run notes, needs approval before payments or deletes
- Pass / Fail / Blocked / Inconclusive verdicts, so the agent's own mistakes are never reported as site bugs
- SSRF protection, API-key auth, a job queue and live progress over Server-Sent Events; Docker on Render + Vercel

`TypeScript` `Node.js` `Playwright` `OpenAI API` `Next.js` `PostgreSQL` `Prisma` `Docker`

### [AutoStack AI](https://github.com/anshulgusain/AutoStack-Ai): backend scaffolding CLI with AI code generation · [npm](https://www.npmjs.com/package/autostack-ai)

`npx autostack-ai` scaffolds a production-ready Express backend (JWT, Google OAuth, Socket.IO, Helmet, rate limiting, Vitest/Supertest, Docker, GitHub Actions). An AI command reads your codebase conventions and uses the Gemini API to generate matching routes.

### [WhatsApp & Instagram AI Chat Agent](https://github.com/anshulgusain/WhatsApp-Business-Agent)

LLM-powered agent on the WhatsApp Business and Instagram Messaging APIs that handles FAQs, lead capture and order-status lookups, with MongoDB conversation history for multi-turn context.

### Safe Safar: safety-first carpooling platform · [Live](https://www.safe-safar.com/)

Backend with AI-powered KYC (DigiLocker, selfie liveness, face match), OCR-verified vehicle documents, real-time ride tracking with SOS, and Cashfree payments with refunds, an idempotent driver wallet and bank/UPI payouts, covered by 290+ Vitest tests.

## Tech stack

**AI:** OpenAI API · Gemini API · LLM agents · tool calling · prompt engineering · Playwright<br>
**Frontend:** React · Next.js · TypeScript · Tailwind CSS<br>
**Backend:** Node.js · Express · REST · WebSockets / Socket.IO · Server-Sent Events · webhooks<br>
**Data:** PostgreSQL · MongoDB · Prisma · Redis · MySQL<br>
**DevOps:** Docker · GitHub Actions · Render · Vercel · Cloudinary
