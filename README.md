# Hey, I'm Ammaar 👋

**I build and ship software: mobile apps, web platforms and tools that solve everyday problems.**

I'm a software developer with a computer systems engineering background, based in Auckland, New Zealand. From interfaces and cloud services to embedded devices, I enjoy turning ideas into working products. I'm also exploring practical AI integrations and automation.

<p>
<a href="#what-i-work-with"><img src="assets/pillars/software.svg" width="250" height="86" alt="Software: web, mobile and products" /></a>
<a href="#what-i-work-with"><img src="assets/pillars/systems.svg" width="250" height="86" alt="Firmware and systems: devices, data and control" /></a>
<a href="#what-i-work-with"><img src="assets/pillars/ai.svg" width="250" height="86" alt="AI: integration and automation" /></a>
</p>

[Selected work](#selected-work) · [Technology & experience](#what-i-work-with) · [Connect on LinkedIn](https://www.linkedin.com/in/ammaar-marzook-nz/)

## Selected work

A few things I've built. **Start with the lab**, or explore whichever catches your eye.

<table>
<tr>
<td width="50%" valign="top">
<h3>Remote Experiment<br />Control Lab</h3>
<a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/docs/WALKTHROUGH.md"><img src="assets/lab-monitor.jpg" width="420" alt="Lab monitor showing live measurement charts and recording status during a simulated experiment" /></a>
<p>Configure simulated experiments, watch measurements live and replay saved results.</p>
<p><sub>React · TypeScript · Python / FastAPI<br />C++ simulation engines · PostgreSQL</sub></p>
<p><a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/docs/WALKTHROUGH.md"><strong>Take a tour ↗</strong></a> · <a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab">Source</a></p>
<sub>Simulator. Hosted access is operator-only.</sub>
</td>
<td width="50%" valign="top">
<h3>Fieldroom<br />Equipment lending</h3>
<a href="https://github.com/ammaar134/Live-Event-Operations/blob/main/docs/CASE-STUDY.md"><img src="assets/fieldroom-catalog.png" width="420" alt="Fieldroom equipment catalog with availability, categories and booking options" /></a>
<p>Help a club book, lend and maintain shared equipment without double bookings.</p>
<p><sub>React · TypeScript · C# / ASP.NET Core<br />Identity · EF Core · PostgreSQL</sub></p>
<p><a href="https://github.com/ammaar134/Live-Event-Operations/blob/main/docs/CASE-STUDY.md"><strong>Explore the app ↗</strong></a> · <a href="https://github.com/ammaar134/Live-Event-Operations">Source</a></p>
<sub>Portfolio application for a fictional club.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>EduFeed<br />A more focused YouTube</h3>
<a href="https://chromewebstore.google.com/detail/edufeed-%E2%80%93-productive-yout/cpppgdcmmigbddkhaaifjfmogcppoknd"><img src="assets/edufeed-focus.jpg" width="420" alt="EduFeed extension on YouTube with educational mode selected and educational videos in the feed" /></a>
<p>Replace recommendations with subscriptions or educational content, so viewers can stay focused.</p>
<p><sub>JavaScript · HTML / CSS · Manifest V3</sub></p>
<p><a href="https://chromewebstore.google.com/detail/edufeed-%E2%80%93-productive-yout/cpppgdcmmigbddkhaaifjfmogcppoknd"><strong>Install for Chrome ↗</strong></a> · <a href="https://github.com/ammaar134/edufeed">Source</a></p>
<sub><a href="https://github.com/ammaar134/edufeed#the-three-modes">Explore the focus modes</a></sub>
</td>
<td width="50%" valign="top">
<h3>More to come<br />Always building</h3>
<img src="assets/more-to-come.svg" width="420" alt="" />
<p>More ideas, experiments and useful things to share.</p>
<p><a href="https://github.com/ammaar134?tab=repositories"><strong>Browse my repositories ↗</strong></a></p>
</td>
</tr>
</table>

<details>
<summary><strong>Under the hood</strong> · architecture, tests & engineering decisions</summary>

### Remote Experiment Control Lab

**React UI → FastAPI → C++ engines** · PostgreSQL recording

Repeatable simulations, safe command retries and saved-data replay. Stop and fault handling zero the **simulated** output; recordings acknowledge samples after database commit.

[Architecture](https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/docs/ARCHITECTURE.md) · [Command path](https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/backend/lab/instrument.py) · [Engine tests](https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/instrument/tests/engine_test.cpp) · [CI](https://github.com/ammaar134/Remote-Expriment-Control-Lab/actions/workflows/ci.yml)

### Fieldroom

**React UI → ASP.NET Core + Identity → EF Core + PostgreSQL**

The database rejects overlapping reservations. Booking changes, audit history and retry outcomes commit together, with concurrent-booking tests against a real database.

[Architecture](https://github.com/ammaar134/Live-Event-Operations/blob/main/docs/ARCHITECTURE.md) · [Allocation service](https://github.com/ammaar134/Live-Event-Operations/blob/main/src/Api/Features/AllocationService.cs) · [Concurrency tests](https://github.com/ammaar134/Live-Event-Operations/blob/main/tests/Api.Tests/ConcurrencyTests.cs) · [CI](https://github.com/ammaar134/Live-Event-Operations/actions/workflows/verify.yml)

### EduFeed

**Extension controls → YouTube content scripts** · Local preferences

Focus modes and distraction filters adapt to YouTube's in-page navigation. Preferences stay in browser storage. YouTube layout changes can affect the extension.

[Feed replacement](https://github.com/ammaar134/edufeed/blob/main/src/content/feed-replacer.js) · [Manifest](https://github.com/ammaar134/edufeed/blob/main/manifest.json) · [Utility tests](https://github.com/ammaar134/edufeed/blob/main/test/utils.test.js)

<sub>The Chrome Web Store listing is live. The source README still has outdated release wording and missing demo/icon assets; the store package has not been matched to this source revision.</sub>

</details>

## What I work with

Across professional work, personal projects and engineering coursework. The projects above are a selection, not the full toolkit.

<details open>
<summary><strong>Languages & foundations</strong></summary>

<p><img src="assets/icons/typescript.svg" width="34" height="34" alt="TypeScript" title="TypeScript" /> &nbsp; <img src="assets/icons/javascript.svg" width="34" height="34" alt="JavaScript" title="JavaScript" /> &nbsp; <img src="assets/icons/python.svg" width="34" height="34" alt="Python" title="Python" /> &nbsp; <img src="assets/icons/java.svg" width="34" height="34" alt="Java" title="Java" /> &nbsp; <img src="assets/icons/dart.svg" width="34" height="34" alt="Dart" title="Dart" /> &nbsp; <img src="assets/icons/c.svg" width="34" height="34" alt="C" title="C" /> &nbsp; <img src="assets/icons/cplusplus.svg" width="34" height="34" alt="C++" title="C++" /> &nbsp; <img src="assets/icons/csharp.svg" width="34" height="34" alt="C#" title="C#" /> &nbsp; <img src="assets/icons/html5.svg" width="34" height="34" alt="HTML" title="HTML" /> &nbsp; <img src="assets/icons/css3.svg" width="34" height="34" alt="CSS" title="CSS" /> &nbsp; <img src="assets/icons/php.svg" width="34" height="34" alt="PHP" title="PHP" /> &nbsp; </p>

TypeScript · JavaScript · Python · Java · Dart · C · C++ · C# · HTML · CSS · SQL · PHP · Solidity

</details>

<details>
<summary><strong>Web & mobile</strong></summary>

<p><img src="assets/icons/react.svg" width="34" height="34" alt="React and React Native" title="React and React Native" /> &nbsp; <img src="assets/icons/flutter.svg" width="34" height="34" alt="Flutter" title="Flutter" /> &nbsp; <img src="assets/icons/fastapi.svg" width="34" height="34" alt="FastAPI" title="FastAPI" /> &nbsp; <img src="assets/icons/dotnetcore.svg" width="34" height="34" alt="ASP.NET Core" title="ASP.NET Core" /> &nbsp; <img src="assets/icons/vuejs.svg" width="34" height="34" alt="Vue" title="Vue" /> &nbsp; <img src="assets/icons/angular.svg" width="34" height="34" alt="Angular" title="Angular" /></p>

React · React Native · Flutter · FastAPI · ASP.NET Core / Identity · EF Core

Also used: Vue · Angular · Shopify integrations.

</details>

<details>
<summary><strong>Cloud, data & delivery</strong></summary>

<p><img src="assets/icons/amazonwebservices.svg" width="34" height="34" alt="AWS" title="AWS" /> &nbsp; <img src="assets/icons/firebase.svg" width="34" height="34" alt="Firebase" title="Firebase" /> &nbsp; <img src="assets/icons/googlecloud.svg" width="34" height="34" alt="Google Cloud" title="Google Cloud" /> &nbsp; <img src="assets/icons/supabase.svg" width="34" height="34" alt="Supabase" title="Supabase" /> &nbsp; <img src="assets/icons/postgresql.svg" width="34" height="34" alt="PostgreSQL" title="PostgreSQL" /> &nbsp; <img src="assets/icons/docker.svg" width="34" height="34" alt="Docker" title="Docker" /> &nbsp; <img src="assets/icons/linux.svg" width="34" height="34" alt="Linux" title="Linux" /> &nbsp; <img src="assets/icons/githubactions.svg" width="34" height="34" alt="GitHub Actions" title="GitHub Actions" /></p>

AWS · Firebase / Firestore / Cloud Functions · Google Cloud · Supabase · PostgreSQL · Neon · Docker · Linux · GitHub Actions

</details>

<details>
<summary><strong>Engineering & design tools</strong></summary>

<p><img src="assets/icons/git.svg" width="34" height="34" alt="Git" title="Git" /> &nbsp; <img src="assets/icons/playwright.svg" width="34" height="34" alt="Playwright" title="Playwright" /> &nbsp; <img src="assets/icons/vscode.svg" width="34" height="34" alt="VS Code" title="VS Code" /> &nbsp; <img src="assets/icons/androidstudio.svg" width="34" height="34" alt="Android Studio" title="Android Studio" /> &nbsp; <img src="assets/icons/figma.svg" width="34" height="34" alt="Figma" title="Figma" /> &nbsp; <img src="assets/icons/jira.svg" width="34" height="34" alt="Jira" title="Jira" /></p>

Git · Playwright · VS Code · Android Studio · Figma · Jira

Unit testing · API integration · debugging · CI workflows

</details>

<details>
<summary><strong>Firmware, systems & practical AI</strong></summary>

<p><img src="assets/icons/c.svg" width="34" height="34" alt="C" title="C" /> &nbsp; <img src="assets/icons/cplusplus.svg" width="34" height="34" alt="C++" title="C++" /> &nbsp; <img src="assets/icons/python.svg" width="34" height="34" alt="Python" title="Python" /> &nbsp; <img src="assets/icons/raspberrypi.svg" width="34" height="34" alt="Raspberry Pi" title="Raspberry Pi" /></p>

**Embedded:** C / C++ · Raspberry Pi Pico W · PSoC 5 / PSoC Creator · GPIO / ADC · sensors · serial / Bluetooth · PCB work · LTspice

**AI & automation:** LLM API integration · OpenAI API · n8n

**Development assistants:** Claude Code · Codex · GitHub Copilot · Cursor · ChatGPT

My embedded experience includes engineering coursework and device projects. The featured lab is a simulator. My AI work focuses on using models in applications and workflows; model training is an area to explore.

</details>

## Let's connect

For my broader experience, project history or a conversation: **[find me on LinkedIn ↗](https://www.linkedin.com/in/ammaar-marzook-nz/)**

<sub>Praise be to God.</sub>
