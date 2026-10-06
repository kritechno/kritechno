<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Amir Buzubayev. I build and ship AI systems with guardrails, tests and real users." width="100%">
</picture>

<p align="center">
  <a href="https://amirbuzubayev.com"><img src="https://img.shields.io/badge/Portfolio-amirbuzubayev.com-1f6feb?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/amir-buzubayev"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://kritechno.github.io/clicko/"><img src="https://img.shields.io/badge/Try-Clicko-f0883e?style=for-the-badge" alt="Try Clicko"></a>
</p>

I study Artificial Intelligence at Johannes Kepler University Linz and build software that people use. My projects start from a real problem, usually one from the tour company I run, and end as something deployed, tested and maintained.

Most of my recent work is around language models in production: retrieval, document pipelines, evaluation, and the checks that stop a fluent answer from being a wrong one.

**Open to working-student and internship roles in AI or software engineering, in Vienna or remote, around 20 hours a week.**

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/kritechno/audardoc-showcase"><img src="assets/audardoc.png" alt="AudarDoc: a contract in Russian and its Kazakh translation with the same layout"></a>
      <h3><a href="https://github.com/kritechno/audardoc-showcase">AudarDoc</a></h3>
      <p>Document translation between Russian and Kazakh that keeps the original layout. A self-repairing LLM pipeline with validators for numbers, dates, negation and terminology, a custom PDF re-layout engine, and an isolated worker for untrusted files. More than 1,000 automated tests. Closed beta.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>OpenAI</code> <code>PyMuPDF</code> <code>OCR</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://kritechno.github.io/clicko/"><img src="assets/clicko.jpg" alt="Clicko typing trainer showing a warm-up line and an on-screen keyboard"></a>
      <h3><a href="https://github.com/kritechno/clicko">Clicko</a> · <a href="https://kritechno.github.io/clicko/">play</a></h3>
      <p>A calm, lofi typing trainer for English and Russian. Ten chapters per language, eight practice modes, weak-key tracking, and a room that fills up as you improve. Runs entirely in the browser with no account and no tracking.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Zustand</code> <code>Vite</code> <code>Vitest</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/kritechno/clockio"><img src="assets/clockio.jpg" alt="Clockio showing a large clock over an animated background"></a>
      <h3><a href="https://github.com/kritechno/clockio">Clockio</a></h3>
      <p>A native macOS clock and screensaver. Seven clock styles over animated backgrounds, automatic day and night from local sunrise and sunset, weather, and a built-in to-do list. Rewritten from an Electron prototype into SwiftUI and AppKit.</p>
      <p><code>Swift</code> <code>SwiftUI</code> <code>AppKit</code> <code>CoreLocation</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/kritechno/nicemaps"><img src="assets/nicemaps.jpg" alt="NiceMaps showing a composed route map"></a>
      <h3><a href="https://github.com/kritechno/nicemaps">NiceMaps</a></h3>
      <p>A map studio for composing polished, export-ready route maps for tour agencies and route planners. Build a route, group waypoints by day or region, and export a clean map for slides, print or the web.</p>
      <p><code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>Mapbox GL</code> <code>Tailwind</code></p>
    </td>
  </tr>
</table>

## Built for a real business

I run [SilkOffRoad Tours](https://silkoffroadtours.com), a motorcycle tour company in Central Asia, and I build its internal tools. The code is private because it holds customer data, and I am happy to walk through it in an interview.

- **SilkOffRoad AI Agent.** A local-first desktop assistant that drafts grounded, cited replies to client inquiries from the tour dataset. Two models split triage and drafting, two independent guardrail layers block any price or term that is not in the source, and a human approves every reply. In production. `Electron` `React` `SQLite` `OpenAI` `Gemini` `Ollama`
- **SilkCRM.** The CRM that runs daily operations: passport scans to structured client records through OCR, agreements generated from templates, rooming lists, expense imports with per-tour margins, and an audit trail. `Python` `FastAPI` `PostgreSQL` `Docker`

## Toolbox

**AI and ML** · LLM agents and pipelines, RAG, guardrails and evaluation, NLP and machine translation, OCR, PyTorch

**Backend** · Python, FastAPI, Node.js, PostgreSQL, SQLite, REST APIs, document processing

**Frontend and apps** · TypeScript, React, Next.js, Electron, React Native, Swift and SwiftUI

**Shipping** · Docker, GitHub Actions, pytest, Vitest, Railway, Cloudflare

## Get in touch

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/amir-buzubayev). More projects and case studies are at [amirbuzubayev.com](https://amirbuzubayev.com).
