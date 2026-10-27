# Hey, I'm Ammaar 👋

**I build and ship software: mobile apps, web platforms and tools that solve everyday problems.**

I'm a software developer with a computer systems engineering background, based in Auckland, New Zealand. From interfaces and cloud services to embedded devices, I enjoy turning ideas into working products. I use LLMs and generative AI in my development workflow to build faster, explore ideas and work through problems.

<p align="center">
<a href="#what-i-work-with"><img src="assets/pillars/software.svg" width="250" height="86" alt="Software: web, mobile and products" /></a> &nbsp;&nbsp;
<a href="#what-i-work-with"><img src="assets/pillars/systems.svg" width="250" height="86" alt="Firmware and systems: devices, data and control" /></a> &nbsp;&nbsp;
<a href="#what-i-work-with"><img src="assets/pillars/ai.svg" width="250" height="86" alt="AI: AI-assisted development" /></a>
</p>

[Selected work](#selected-work) · [Technology & experience](#what-i-work-with) · [Connect on LinkedIn](https://www.linkedin.com/in/ammaar-marzook-nz/)

## Core toolkit

<p>
<img src="assets/toolkit/typescript.svg" width="114" height="34" alt="TypeScript" />
<img src="assets/toolkit/javascript.svg" width="113" height="34" alt="JavaScript" />
<img src="assets/toolkit/python.svg" width="91" height="34" alt="Python" />
<img src="assets/toolkit/java.svg" width="77" height="34" alt="Java" />
<img src="assets/toolkit/dart.svg" width="74" height="34" alt="Dart" />
<img src="assets/toolkit/c.svg" width="58" height="34" alt="C" />
<img src="assets/toolkit/cplusplus.svg" width="74" height="34" alt="C++" />
<img src="assets/toolkit/html.svg" width="86" height="34" alt="HTML" />
<img src="assets/toolkit/css.svg" width="76" height="34" alt="CSS" />
<img src="assets/toolkit/react.svg" width="84" height="34" alt="React" />
<img src="assets/toolkit/react-native.svg" width="128" height="34" alt="React Native" />
<img src="assets/toolkit/flutter.svg" width="87" height="34" alt="Flutter" />
</p>

<p>
<img src="assets/toolkit/aws.svg" width="79" height="34" alt="AWS" />
<img src="assets/toolkit/firebase.svg" width="102" height="34" alt="Firebase" />
<img src="assets/toolkit/google-cloud.svg" width="133" height="34" alt="Google Cloud" />
<img src="assets/toolkit/postgresql.svg" width="124" height="34" alt="PostgreSQL" />
<img src="assets/toolkit/docker.svg" width="92" height="34" alt="Docker" />
<img src="assets/toolkit/linux.svg" width="81" height="34" alt="Linux" />
<img src="assets/toolkit/git.svg" width="65" height="34" alt="Git" />
<img src="assets/toolkit/raspberry-pi.svg" width="128" height="34" alt="Raspberry Pi" />
<img src="assets/toolkit/claude-code.svg" width="129" height="34" alt="Claude Code" />
<img src="assets/toolkit/codex.svg" width="88" height="34" alt="Codex" />
</p>

These are the main technologies I work with. [See the full toolkit and experience below ↓](#what-i-work-with)

## Selected work

A few things I've built. **Start with the lab**, or explore whichever catches your eye.

<table>
<tr>
<td width="50%" valign="top">
<h3>Remote Experiment<br />Control Lab</h3>
<a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/docs/WALKTHROUGH.md"><img src="assets/previews/lab.svg" width="420" alt="Lab monitor showing live measurement charts and recording status during a simulated experiment" /></a>
<p>Configure simulated experiments, watch measurements live and replay saved results.</p>
<p><sub>React · TypeScript · Python / FastAPI<br />C++ simulation engines · PostgreSQL</sub></p>
<p><a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab/blob/main/docs/WALKTHROUGH.md"><strong>Take a tour ↗</strong></a> · <a href="https://github.com/ammaar134/Remote-Expriment-Control-Lab">Source</a></p>
<sub>Simulator. Hosted access is operator-only.</sub>
</td>
<td width="50%" valign="top">
<h3>Fieldroom<br />Equipment lending</h3>
<a href="https://github.com/ammaar134/Live-Event-Operations/blob/main/docs/CASE-STUDY.md"><img src="assets/previews/fieldroom.svg" width="420" alt="Fieldroom equipment catalog with availability, categories and booking options" /></a>
<p>Help a club book, lend and maintain shared equipment without double bookings.</p>
<p><sub>React · TypeScript · C# / ASP.NET Core<br />Identity · EF Core · PostgreSQL</sub></p>
<p><a href="https://github.com/ammaar134/Live-Event-Operations/blob/main/docs/CASE-STUDY.md"><strong>Explore the app ↗</strong></a> · <a href="https://github.com/ammaar134/Live-Event-Operations">Source</a></p>
<sub>Portfolio application for a fictional club.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>EduFeed<br />A more focused YouTube</h3>
<a href="https://chromewebstore.google.com/detail/edufeed-%E2%80%93-productive-yout/cpppgdcmmigbddkhaaifjfmogcppoknd"><img src="assets/previews/edufeed.svg" width="420" alt="EduFeed extension on YouTube with educational mode selected and educational videos in the feed" /></a>
<p>Swap suggested videos for subscriptions or educational content to stay focused.</p>
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

### Languages & foundations

<p><img src="assets/icons/typescript.svg" width="34" height="34" alt="TypeScript" title="TypeScript" /> &nbsp; <img src="assets/icons/javascript.svg" width="34" height="34" alt="JavaScript" title="JavaScript" /> &nbsp; <img src="assets/icons/python.svg" width="34" height="34" alt="Python" title="Python" /> &nbsp; <img src="assets/icons/java.svg" width="34" height="34" alt="Java" title="Java" /> &nbsp; <img src="assets/icons/dart.svg" width="34" height="34" alt="Dart" title="Dart" /> &nbsp; <img src="assets/icons/c.svg" width="34" height="34" alt="C" title="C" /> &nbsp; <img src="assets/icons/cplusplus.svg" width="34" height="34" alt="C++" title="C++" /> &nbsp; <img src="assets/icons/csharp.svg" width="34" height="34" alt="C#" title="C#" /> &nbsp; <img src="assets/icons/html5.svg" width="34" height="34" alt="HTML" title="HTML" /> &nbsp; <img src="assets/icons/css3.svg" width="34" height="34" alt="CSS" title="CSS" /> &nbsp; <img src="assets/icons/php.svg" width="34" height="34" alt="PHP" title="PHP" /> &nbsp; </p>

TypeScript · JavaScript · Python · Java · Dart · C · C++ · C# · HTML · CSS · SQL · PHP · Solidity


### Web & mobile

<p><img src="assets/icons/react.svg" width="34" height="34" alt="React and React Native" title="React and React Native" /> &nbsp; <img src="assets/icons/flutter.svg" width="34" height="34" alt="Flutter" title="Flutter" /> &nbsp; <img src="assets/icons/fastapi.svg" width="34" height="34" alt="FastAPI" title="FastAPI" /> &nbsp; <img src="assets/icons/dotnetcore.svg" width="34" height="34" alt="ASP.NET Core" title="ASP.NET Core" /> &nbsp; <img src="assets/icons/vuejs.svg" width="34" height="34" alt="Vue" title="Vue" /> &nbsp; <img src="assets/icons/angular.svg" width="34" height="34" alt="Angular" title="Angular" /></p>

React · React Native · Flutter · FastAPI · ASP.NET Core / Identity · EF Core

Also used: Vue · Angular · Shopify integrations.


### Cloud, data & delivery

<p><img src="assets/icons/amazonwebservices.svg" width="34" height="34" alt="AWS" title="AWS" /> &nbsp; <img src="assets/icons/firebase.svg" width="34" height="34" alt="Firebase" title="Firebase" /> &nbsp; <img src="assets/icons/googlecloud.svg" width="34" height="34" alt="Google Cloud" title="Google Cloud" /> &nbsp; <img src="assets/icons/supabase.svg" width="34" height="34" alt="Supabase" title="Supabase" /> &nbsp; <img src="assets/icons/postgresql.svg" width="34" height="34" alt="PostgreSQL" title="PostgreSQL" /> &nbsp; <img src="assets/icons/docker.svg" width="34" height="34" alt="Docker" title="Docker" /> &nbsp; <img src="assets/icons/linux.svg" width="34" height="34" alt="Linux" title="Linux" /> &nbsp; <img src="assets/icons/githubactions.svg" width="34" height="34" alt="GitHub Actions" title="GitHub Actions" /></p>

AWS · Firebase / Firestore / Cloud Functions · Google Cloud · Supabase · PostgreSQL · Neon · Docker · Linux · GitHub Actions


### Engineering & design tools

<p><img src="assets/icons/git.svg" width="34" height="34" alt="Git" title="Git" /> &nbsp; <img src="assets/icons/playwright.svg" width="34" height="34" alt="Playwright" title="Playwright" /> &nbsp; <img src="assets/icons/vscode.svg" width="34" height="34" alt="VS Code" title="VS Code" /> &nbsp; <img src="assets/icons/androidstudio.svg" width="34" height="34" alt="Android Studio" title="Android Studio" /> &nbsp; <img src="assets/icons/figma.svg" width="34" height="34" alt="Figma" title="Figma" /> &nbsp; <img src="assets/icons/jira.svg" width="34" height="34" alt="Jira" title="Jira" /></p>

Git · Playwright · VS Code · Android Studio · Figma · Jira

Unit testing · API integration · debugging · CI workflows


### Firmware & systems

<p><img src="assets/icons/c.svg" width="34" height="34" alt="C" /> &nbsp; <img src="assets/icons/cplusplus.svg" width="34" height="34" alt="C++" /> &nbsp; <img src="assets/icons/python.svg" width="34" height="34" alt="Python" /> &nbsp; <img src="assets/icons/raspberrypi.svg" width="34" height="34" alt="Raspberry Pi" /></p>

C / C++ · Raspberry Pi Pico W · PSoC 5 / PSoC Creator · GPIO / ADC · sensors · UART / serial · Bluetooth · PCB work · LTspice

Hands-on experience through engineering coursework and device projects. The featured lab demonstrates simulation software.


### AI-assisted development

<p><img src="assets/icons/claudecode.svg" width="38" height="38" alt="Claude Code" title="Claude Code" /> &nbsp; <img src="assets/icons/codex.webp" width="38" height="38" alt="Codex" title="Codex" /> &nbsp; <img src="assets/icons/githubcopilot.svg" width="38" height="38" alt="GitHub Copilot" title="GitHub Copilot" /> &nbsp; <img src="assets/icons/openai.webp" width="38" height="38" alt="ChatGPT" title="ChatGPT" /> &nbsp; <img src="assets/icons/n8n.svg" width="38" height="38" alt="n8n" title="n8n" /></p>

Claude Code · Codex · GitHub Copilot · ChatGPT · Cursor · n8n

I work with LLMs and generative AI to accelerate development, from exploring an approach to writing and debugging code. AI-assisted development is part of how I work.


## Let's connect

For my broader experience, project history or a conversation: **[find me on LinkedIn ↗](https://www.linkedin.com/in/ammaar-marzook-nz/)**

> "Most people have dreams. Some turn them into plans. Some act on those plans. Very few stay consistent long enough to succeed."
