<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/terminal-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/terminal-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/terminal-dark.svg">
  <img alt="An animated terminal session. whoami: alexis, senior full-stack engineer, twelve years, Berlin. ls shipped: automatist, easy-web-navigation, re-phraser, prompt-save-reuse, psalms-way, urban-ground. now: Streets and Signs, a browser driving game in public preview at streetsandsigns.com; at OPTIMAL SYSTEMS in Berlin, building an AI assistant over enterprise content; Automatist, on-device AI automation, live on Google Play." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/terminal-light.svg" width="100%">
</picture>

<p>
<a href="https://github.com/atj393"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-github.svg" height="34" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/atj393/"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-linkedin.svg" height="34" alt="LinkedIn"></a>
<a href="https://streetsandsigns.com/"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-streets-and-signs.svg" height="34" alt="Streets &amp; Signs"></a>
<a href="https://automatist.cloud/"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-automatist.svg" height="34" alt="Automatist"></a>
<a href="mailto:alexistoby393@gmail.com"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-email.svg" height="34" alt="Email"></a>
</p>

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-dark.svg">
  <img alt="Alexis Johnson. I build what I wish existed, and ship it with care. That's the bar." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-light.svg" width="100%">
</picture>

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-dark.svg">
  <img alt="Twelve years building. Three AI-powered products. Four Chrome extensions live. Two Android apps on Google Play. Five-time LinkedIn Top Voice." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-light.svg" width="100%">
</picture>

### Senior Full Stack Engineer

**Product-minded · Angular & React · Node.js · TypeScript · applied AI**

I'm Alexis Toby Johnson, a product-minded software engineer with around twelve years of experience, currently on enterprise content management at OPTIMAL SYSTEMS Group in Berlin. What has shaped my career is finding real problems, understanding the people and the constraints around them, and taking enough ownership across product and technology to turn those problems into something that actually works.

I started in startup environments, where I worked across different parts of a product and took on whatever role the week needed. Over time, frontend engineering and architecture became where I'm deepest, and I kept following the work into the layer where a product stops being a UI and starts being a system: state that survives a background job, a message contract across three processes that cannot share memory, an inference budget that has to hold before a native call. Frontend is the foundation of my career. It is no longer my engineering boundary.

There's a line from *Rework* I keep coming back to: scratch your own itch. Almost everything here started that way. I begin with a real problem, work out the best technical answer, learn whatever framework or AI capability it needs along the way, and if the result has wider value I turn it into a product and share it here. Getting each one from *works for me* to *works for you* is the part I stay for.

<sub><b>01 · NOW BUILDING</b></sub>

<a href="https://streetsandsigns.com/"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/streets-and-signs-horizontal-dark.svg">
  <img alt="Streets &amp; Signs. Every street. A new choice." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/streets-and-signs-horizontal-light.svg" width="360">
</picture></a>

**[Streets & Signs](https://streetsandsigns.com/)** is a fictional browser driving game with simplified situations based on selected German traffic rules. Your screen becomes the driver's view and your phone becomes the controls: scan a QR code, then tilt or touch to steer, brake, accelerate and signal. Drive a fictional German neighbourhood, follow route directions in German, meet traffic that behaves, and finish with a round summary you can replay exactly or retry as a new variation. It started at home, watching how much a person has to hold in their head on a German road at once. Commercial simulators wanted a wheel and pedals. I wanted something that works with the laptop and phone already on the kitchen table. It is the biggest thing I've built, and the first with its own domain.

<sub>The phone carries input over a WebSocket relay and the laptop runs the simulation: fixed-step physics at 60 Hz, interpolated rendering, and Babylon.js owning the only render loop. Game points describe play within the game only and never claim to measure real driving; a wording check runs before every build and fails it if the product text drifts into claiming otherwise. Twenty situations across five topics come from five reusable templates with validated map and traffic bindings, so a new variation is a configuration, not a rewrite. More than 400 unit tests, three CI workflows, a decision register and a risk handbook. Qualified review of the rule content and physical-device validation are still open, and the docs say so.</sub>

<sub><code>Next.js</code> <code>React 19</code> <code>Babylon.js</code> <code>WebSockets</code> <code>Supabase</code> <code>Node 22</code> &nbsp;·&nbsp; <a href="https://streetsandsigns.com/">Play the preview</a> · English and German · version 0.3 alpha · private repository, for now</sub>

<sub><b>02 · SELECTED WORK</b></sub>

<table>
  <tr>
    <td colspan="2" valign="top">
      <a href="https://github.com/atj393/automatist-android"><img src="https://raw.githubusercontent.com/atj393/automatist-android/main/docs/assets/readme/automatist-logo.png" width="40" height="40" align="left" alt=""></a>
      &nbsp;<b><a href="https://github.com/atj393/automatist-android">Automatist</a></b> &nbsp;<sub>MOBILE-FIRST AI AUTOMATION · ON GOOGLE PLAY · APACHE-2.0</sub><br>
      &nbsp;<sub>A mobile-first alternative to OpenClaw. Recurring AI tasks, scheduled from a phone, with a real choice between cloud, on-device (MediaPipe, Gemini Nano), and offline models. No backend, your own keys encrypted at rest, and a preflight token budget because an oversized prompt aborts the native runtime rather than throwing. Sole engineer: 407 tests across 39 classes, with CI running on every push. Free and open source.</sub><br>
      &nbsp;<sub><code>Kotlin</code> <code>Jetpack Compose</code> <code>MediaPipe</code> <code>Room</code> <code>WorkManager</code> &nbsp;·&nbsp; <a href="https://play.google.com/store/apps/details?id=com.automatist.app">Google Play</a> · <a href="https://automatist.cloud/">Website</a> · <a href="https://github.com/atj393/automatist-android">Source</a></sub>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <b><a href="https://urban-ground-ten.vercel.app/">Urban Ground</a></b> &nbsp;<sub>REAL-WORLD-MAP STRATEGY PROTOTYPE · LIVE PREVIEW · PRIVATE REPOSITORY</sub><br>
      <sub>A browser strategy game played on real OpenStreetMap geography, driven by a deterministic economic model and pinned to a SHA-256-verified map snapshot, so every session is reproducible and gameplay never calls a source API. A design-token package is the single source of every visual decision, enforced by a test that fails the build if a component declares its own colour, and none of the nine map states is signalled by colour alone.</sub><br>
      <sub><code>React 19</code> <code>Vite</code> <code>MapLibre GL</code> <code>OpenStreetMap</code> <code>Vitest</code> <code>Playwright</code> &nbsp;·&nbsp; <a href="https://urban-ground-ten.vercel.app/">Play the preview</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/atj393/easy-web-navigation">Easy Web Navigation</a></b> &nbsp;<sub>CHROME WEB STORE · MIT</sub><br>
      <sub>A WCAG 2.2 keyboard-accessibility inspector: focus order, landmarks, and the tab path, drawn straight onto the page instead of filed as a report. A Shadow DOM overlay so the tool never joins the tab order it measures, zero host permissions, and 142 tests running across Chromium and Firefox in CI.</sub><br>
      <sub><code>TypeScript</code> <code>React</code> <code>MV3</code> &nbsp;·&nbsp; <a href="https://chromewebstore.google.com/detail/easy-web-navigation-keybo/jaffeipdpljhnfonacndcpjdkclgjiln">Chrome Web Store</a> · <a href="https://github.com/atj393/easy-web-navigation">Source</a></sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/atj393/local-browser-automation-bridge">Local Browser Automation Bridge</a></b> &nbsp;<sub>LOCAL PROTOTYPE · MIT</sub><br>
      <sub>Four processes that cannot share memory (dashboard, Node backend, MV3 service worker, content scripts) held together by typed contracts, a SQLite queue, and a request registry that gives a WebSocket the request/response semantics it does not have. An SSRF guard in front, and 56 tests in CI.</sub><br>
      <sub><code>TypeScript</code> <code>Node</code> <code>WebSocket</code> <code>SQLite</code> &nbsp;·&nbsp; <a href="https://github.com/atj393/local-browser-automation-bridge">Source</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/atj393/re-phraser">Re-Phraser</a></b> &nbsp;<sub>CHROME WEB STORE · MIT</sub><br>
      <sub>Your selection goes to the AI tab you already have open. No backend, no API-key box: their subscription, their account, nothing in the middle. 126 tests in CI, and the privacy claim is verifiable: there is no network call in the codebase.</sub><br>
      <sub><a href="https://chromewebstore.google.com/detail/re-phraser-ai-text-rewrit/ldocllepggdbadbedboopoeebadnpddi">Chrome Web Store</a> · <a href="https://github.com/atj393/re-phraser">Source</a></sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://play.google.com/store/apps/details?id=com.psalmswayapp">Psalms Way</a></b> &nbsp;<sub>GOOGLE PLAY · 500+ INSTALLS</sub><br>
      <sub>150 Psalms in 81 translations and 47 interface languages, entirely offline with no accounts or telemetry, which is why the bundler needs a static module map instead of a computed path. Chrome companion at 204 users, rated 4.3 of 5.</sub><br>
      <sub><a href="https://play.google.com/store/apps/details?id=com.psalmswayapp">Google Play</a> · <a href="https://github.com/atj393/psalms-way-app">Source</a> · <a href="https://chromewebstore.google.com/detail/psalms-way-biblical-begin/aplafmlmecdjlmcgbibmlbjnilcomcnl">Extension</a></sub>
    </td>
  </tr>
</table>

<sub><b>ENGINEERING LAB</b> · <a href="https://github.com/atj393/design-intelligence">design-intelligence</a>, a derived design-guidance layer synthesized from 74 brand analyses. &nbsp; <b>TOOLING</b> · my code-cleanup workflow as a <a href="https://github.com/atj393/claude-plugin-code-cleanup">Claude Code plugin</a>, a lead agent coordinating seven specialist workers, and its <a href="https://github.com/atj393/claude-plugins">marketplace</a>.</sub>

<sub><b>COMMUNITY</b> · <a href="https://chromewebstore.google.com/detail/prompt-save-reuse-chatgpt/fldaklkfolpnnlgoejcgcgjmklmheaim">Prompt Save Reuse</a>, a prompt manager across seven AI platforms on the Chrome Web Store and Edge Add-ons: 401 users, 15 forks, and five external pull requests reviewed and merged from four contributors. &nbsp; <b>PRIVATE</b> · a multi-tenant school operations platform, four deployables from one monorepo (NestJS, Prisma, PostgreSQL with row-level security, Next.js, Expo), with a transactional outbox and an append-only audit log the ORM cannot modify.</sub>

<sub><b>03 · THE DAY JOB</b></sub>

<sub><b>SHOP FLOOR FIRST</b> · My first role in Germany was building software for industrial shop-floor workers, at aucobo in Stuttgart. I owned much of the frontend and mobile side, but I also joined client visits and spent time on the floor watching the work happen. In manufacturing, saving a few seconds in a workflow that repeats all day saves hours across the whole process. That is still my test for whether a piece of software is useful.</sub>

<sub><b>FROM FRONTEND TO AUTOMATION</b> · At OPTIMAL SYSTEMS I joined on the frontend and kept looking for workflows we could automate. One early initiative was a Python-based email-classification service. It worked, and it pulled me steadily deeper into our AI work.</sub>

<sub><b>AN ASSISTANT THAT GREW UP</b> · Today I work on an enterprise AI assistant that we evolved from an Elasticsearch-based chatbot into a copilot, and now toward an agentic system with controlled tools and actions. A big part of the work is connecting the AI properly to the applications around it. A good answer is only half the job; what matters is what the user can safely do next with that answer. The model integration stays flexible, so we can move between providers without redesigning the product.</sub>

<sub><b>04 · THE STACK</b></sub>

`TypeScript` `Angular 6-22` `React / Next.js` `React Native` `Node.js / NestJS / Fastify` `Python` `PostgreSQL / Prisma / Redis` `Elasticsearch` `Kotlin / Jetpack Compose` `Babylon.js` `Browser Extensions / MV3` `Playwright / Vitest / Jest` `Docker / GitHub Actions` `Applied AI`

<sub><b>APPLIED AI</b> · agent tool-calling and capability governance · retrieval with source attribution and permission filtering · on-device inference (MediaPipe, Gemini Nano) · provider routing across OpenAI, Anthropic, and Gemini · Claude Code and Codex in daily development for the last year and a half, working from clear specifications and reusable rules, with skills, hooks and agents committed so the team inherits them</sub>

<sub>Running themes: human-in-the-loop correction · on-device and offline inference · WCAG 2.2 accessibility · local-first data · row-level security</sub>

<sub><b>WHAT I WORK ON</b> · frontend architecture for complex web applications · browser and platform integrations · applied-AI interfaces and workflows · local-first, privacy-conscious software · testing and developer experience</sub>

<sub><b>05 · SIGNALS</b></sub>

<sub><b>WHERE</b> · OPTIMAL SYSTEMS Group, Berlin, 2022 to now: wrote the concept for a commercial AI assistant over enterprise content and own it end to end, and introduced the testing foundation and CI pipelines used across seven repositories. Before that: aucobo, Stuttgart (2020 to 2022) and Robert Bosch Engineering, India (2017 to 2020).</sub>

Fixes sent upstream, like [repeat-visit caching](https://github.com/Octasol/octasol/pull/21) and [safer production logging](https://github.com/Octasol/octasol/pull/5) for Octasol · [Five-time LinkedIn Top Voice](https://www.linkedin.com/in/atj393/)

<sub><b>CREDENTIALS</b> · <a href="https://www.credly.com/users/atj393">verified certificates from Meta, Google, and IBM</a>: Meta Front-End and Back-End Developer, IBM Full Stack Software Developer</sub>

Based in Berlin, employed in Germany, no sponsorship required, and open to on-site, hybrid, or remote. I'd describe myself as a product-minded engineer who enjoys finding real problems, understanding the people and constraints around them, and taking enough ownership across product and technology to turn them into something that actually works. If you're building around thoughtful interfaces, local-first software, or applied AI, [say hello](mailto:alexistoby393@gmail.com).
