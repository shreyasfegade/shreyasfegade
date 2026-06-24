<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Shreyas Fegade — turning raw signal into legible intelligence" src="assets/header-light.svg" width="100%">
</picture>

<br>

# Shreyas Fegade

**B.Tech CSE · Manipal University Jaipur · 2025–2029**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=2800&pause=900&color=5EEAD4&background=FFFFFF00&center=true&vCenter=true&width=620&height=40&lines=Raw+signal+in.+Legible+intelligence+out.;Every+chart+drawn+from+the+raw+data;Hand-built+visualization%2C+never+a+dropped-in+library;Gaussian+HMMs%2C+Shannon+entropy%2C+concept+graphs">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=2800&pause=900&color=0D9488&background=FFFFFF00&center=true&vCenter=true&width=620&height=40&lines=Raw+signal+in.+Legible+intelligence+out.;Every+chart+drawn+from+the+raw+data;Hand-built+visualization%2C+never+a+dropped-in+library;Gaussian+HMMs%2C+Shannon+entropy%2C+concept+graphs">
  <img alt="Raw signal in. Legible intelligence out." src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=2800&pause=900&color=0D9488&background=FFFFFF00&center=true&vCenter=true&width=620&height=40&lines=Raw+signal+in.+Legible+intelligence+out.">
</picture>

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-shreyas.info-0D9488?style=flat-square&logo=safari&logoColor=white)](https://shreyas.info)
[![GitHub](https://img.shields.io/badge/GitHub-shreyasfegade-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shreyasfegade)

</div>

---

<div align="center">

### I build tools that turn messy raw signal into legible intelligence —

#### each one rendered through custom visualization, not off-the-shelf chart libraries.

</div>

A trading tape, a desktop's worth of activity, a 30-page PDF, the bytes inside a file — all noisy, all illegible at a glance. Each project below takes one of those signals and resolves it into something you can *read*: a regime, a focus score, a concept map, a verdict. And in every one, the part that makes the signal legible — the candlesticks, the entropy ribbon, the force-directed graph — is built bespoke for that project and drawn straight from the data, rather than handed off to a charting package.

<div align="center"><img src="assets/divider.svg" width="100%" alt=""></div>

## ⬡ Cortex &nbsp;·&nbsp; <sub>flagship</sub>

> ### An AI-native developer workspace — terminal, browser, files, tasks, and a multi-provider AI assistant in one keyboard-driven window.
>
> A passive telemetry layer quietly records your workday to a **local SQLite (WAL) database**, then hands it back to the AI as *selectable context* — the assistant already knows what you ran, edited, and read. Five LLM providers (**OpenAI · Anthropic · Google · DeepSeek · local Ollama**) behind one streaming interface, with on-device token counting, live cost and context-window budgeting, and a one-click **Run** button on every shell block the model returns.
>
> Two-process Electron app: a Node main process owning PTY shells, the database, file watchers, and browser views, exposed through **120 typed IPC channels** to a React 19 + Zustand renderer with a custom D3 dashboard. Everything runs offline — nothing leaves your machine.

[![Electron](https://img.shields.io/badge/Electron_35-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)](https://github.com/shreyasfegade/cortex)
[![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://github.com/shreyasfegade/cortex)
[![TypeScript](https://img.shields.io/badge/TypeScript_5.7-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/shreyasfegade/cortex)
[![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://github.com/shreyasfegade/cortex)
[![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)](https://github.com/shreyasfegade/cortex)
&nbsp;&nbsp;**[→ shreyasfegade/cortex](https://github.com/shreyasfegade/cortex)**

---

## The rest of the portfolio

<table>
<tr>
<td width="50%" valign="top">

### [REGIME](https://github.com/shreyasfegade/regime)
Classifies any equity into one of four hidden market regimes with a **4-state Gaussian HMM**, then measures each regime's forward edge and stress-tests it with a **walk-forward, out-of-sample backtest**. India-first across NSE / BSE / indices, drawn through a zero-dependency HTML5 Canvas engine animated with GSAP.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-0D9488?style=flat-square)](https://regime-omega.vercel.app)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Canvas](https://img.shields.io/badge/-Canvas_API-E34F26?style=flat-square&logo=html5&logoColor=white)

</td>
<td width="50%" valign="top">

### [Chronicle](https://github.com/shreyasfegade/chronicle)
Passive focus intelligence for Windows. Samples the foreground window and turns attention into a single honest **Focus Score built from normalized Shannon entropy**, rendered as the *Focus Stream* — a day-long ribbon whose turbulence *is* the entropy. Custom D3, fully local, no telemetry leaves the machine.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Knowledge Mapper](https://github.com/shreyasfegade/knowledge-mapper)
Turns a dense PDF into an interactive **force-directed concept graph** — the prerequisite, causal, and dependency links inferred by an LLM through a three-stage pipeline with deterministic scaffolding around every model call. The renderer is a **custom canvas force simulation** with spatial-hash hit testing — no graph library, no embeddings, no clustering package.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-0D9488?style=flat-square)](https://knowledge-mapper-six.vercel.app)
![Next.js](https://img.shields.io/badge/-Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td width="50%" valign="top">

### [Forensics](https://github.com/shreyasfegade/forensics)
Drop any file to expose what it's hiding — EXIF/GPS leaks, true file type by magic bytes, byte-level **Shannon entropy**, embedded strings, and appended steganography — a full forensic report in ~200ms, entirely in the browser. Custom binary EXIF parser and a canvas-drawn map. **Zero uploads, zero dependencies.**

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-0D9488?style=flat-square)](https://forensics-bay.vercel.app)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Zero Deps](https://img.shields.io/badge/-Zero_Dependencies-30D158?style=flat-square)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [Unbored](https://github.com/shreyasfegade/unbored)
The decision-paralysis killer — for everyone the other five aren't for. Pick a mood and how long you've got; get **one confident thing to watch**, scored across taste, mood, runtime, and diversity and explained in one honest sentence. The "Why now?" line is provider-agnostic across Gemini / DeepSeek / OpenAI / OpenRouter, and every artless title gets **procedural poster art generated in the browser**. 302 passing tests.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-0D9488?style=flat-square)](https://unbored-five.vercel.app)
![React](https://img.shields.io/badge/-React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

</td>
</tr>
</table>

<div align="center"><img src="assets/divider.svg" width="100%" alt=""></div>

<div align="center">

### Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&logo=electron&logoColor=9FEAF9)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Canvas](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)

<br>

<sub>Custom visualization in every build — no charting libraries · Built with AI assistance · Portfolio at **[shreyas.info](https://shreyas.info)**</sub>

</div>
