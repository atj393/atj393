<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-dark.svg">
  <img alt="Alexis Johnson — I start at the interface and follow it all the way down the stack." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-light.svg" width="100%">
</picture>

<p>
<a href="https://github.com/atj393"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-github.svg" height="34" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/atj393/"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-linkedin.svg" height="34" alt="LinkedIn"></a>
<a href="https://automatist.cloud/"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-automatist.svg" height="34" alt="Automatist"></a>
<a href="mailto:alexistoby393@gmail.com"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-email.svg" height="34" alt="Email"></a>
<a href="https://www.credly.com/users/atj393"><img src="https://raw.githubusercontent.com/atj393/atj393/main/assets/chip-credly.svg" height="34" alt="Credly"></a>
</p>

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-dark.svg">
  <img alt="More than ten years building. Three AI-powered products. Four Chrome extensions live. One Android app on Google Play. Five-time LinkedIn Top Voice." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/stats-light.svg" width="100%">
</picture>

<sub><b>01 &nbsp;—&nbsp; INTRODUCTION</b></sub>

## Who is writing this

I'm Alexis. For more than a decade I've built the layer people actually use — Angular and React by trade — and I kept following the work past the browser, into the APIs, queues, and data behind it. The interface is still where I'm deepest. Full-stack is the direction I'm traveling, and AI is what I'm building with while I get there.

Almost everything below started the same way. Something got in my way on an ordinary Tuesday. I went looking for the tool that fixed it. The tool didn't exist, or it existed and wanted my API key, or it existed and sent my text to somebody's server. So I built my own, used it for a month, and then spent considerably longer making it good enough to hand to a stranger.

> **That last part is the job.** Anyone can build the thing that works on their own machine.

<sub><b>02 &nbsp;—&nbsp; THE CENTER OF THE WORK</b></sub>

## Working with AI

The interesting problems in AI products are rarely the model. They're everything around it: what happens when it's wrong, who approves the output before it lands, what still works with no network, and whose data leaves the device.

> Those are interface and architecture questions. Which is why this became the center of my work rather than a side interest.

Here is how I actually assemble one — the same four layers whether it ends up in a phone, a browser tab, or a background job:

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-dark.svg">
  <img alt="Four layers: Interface (React, Angular, Jetpack Compose, Chrome MV3); Orchestration (scheduling, retries, run diagnostics, approval gates); Inference (cloud provider API, on-device via MediaPipe, compatible offline); Data (stays on the device unless you say otherwise)." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-light.svg" width="100%">
</picture>

<sub>The interesting engineering lives in layers 02 and 04. Layer 03 is the part everyone talks about.</sub>

Four things I've actually built with it:

**On-device and offline inference.** Automatist runs models locally through MediaPipe, so a scheduled task still completes with no connection and no account. Getting that path to real parity — rather than a degraded fallback — was most of the work.

**Provider APIs, without holding your keys.** Re-Phraser routes a selection to the AI chat tab you already have open instead of to a backend I run. There's no API-key field because there's no server of mine to put a key in.

**Human-in-the-loop by default.** Nothing an AI produces in my tools replaces your text until you approve it. An assistant that edits without asking isn't a feature, it's a liability.

**AI-assisted engineering, made reusable.** My own workflow for reviewing AI-written code became a [Claude Code cleanup plugin](https://github.com/atj393/claude-plugin-code-cleanup) and the [marketplace](https://github.com/atj393/claude-plugins) that distributes it.

<sub><b>03 &nbsp;—&nbsp; CURRENT THREADS</b></sub>

## Where I am right now

Two other threads share the desk, and they're more related to the above than they look.

**Accessibility you can see.** Most accessibility tooling hands you a report. I'm more interested in tools that draw the problem directly onto the page — focus order, landmarks, the tab path — because a developer who *sees* the trap fixes it in a way a CI warning never achieves.

**Local-first software.** Automation that fits in a pocket, data that stays on the device, and products that still open when the network doesn't.

<sub><b>04 &nbsp;—&nbsp; SELECTED WORK</b></sub>

## The work

<table>
  <tr>
    <td colspan="2" valign="top">
      <sub><b>CURRENT FOCUS &nbsp;·&nbsp; IN CLOSED TESTING</b></sub><br><br>
      <a href="https://github.com/atj393/automatist-android"><img src="https://raw.githubusercontent.com/atj393/automatist-android/main/docs/assets/readme/automatist-logo.png" width="44" height="44" alt=""></a><br>
      <b><a href="https://github.com/atj393/automatist-android">Automatist</a></b> — mobile-first AI workflow automation<br><br>
      Scheduling, run diagnostics, and a real choice between cloud, on-device, and compatible offline models. Free and open source — no ads, no subscription, nothing held behind a paywall. That constraint is precisely why the offline path had to reach real parity instead of shipping as a fallback.<br><br>
      <sub><code>Kotlin</code> <code>Jetpack Compose</code> <code>WorkManager</code> <code>Room</code> <code>MediaPipe</code></sub><br>
      <sub><a href="https://automatist.cloud/">Website</a> · <a href="https://github.com/atj393/automatist-android">Source &amp; docs</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/atj393/easy-web-navigation"><img src="https://raw.githubusercontent.com/atj393/easy-web-navigation/main/docs/assets/easy-web-navigation-icon.png" width="32" height="32" alt=""></a><br>
      <b><a href="https://github.com/atj393/easy-web-navigation">Easy Web Navigation</a></b><br>
      <sub>ACCESSIBILITY, MADE VISIBLE</sub><br><br>
      Focus, tab order, landmarks, and labels — drawn onto the page, not filed as a report.<br><br>
      <sub><code>TypeScript</code> <code>React</code> <code>WXT</code></sub><br>
      <sub><a href="https://chromewebstore.google.com/detail/easy-web-navigation-keybo/jaffeipdpljhnfonacndcpjdkclgjiln">Chrome Web Store</a> · <a href="https://github.com/atj393/easy-web-navigation">Source</a> · <a href="https://github.com/atj393/easy-web-navigation/releases/latest">Release</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/atj393/re-phraser"><img src="https://raw.githubusercontent.com/atj393/re-phraser/main/docs/assets/re-phraser-icon-128.png" width="32" height="32" alt=""></a><br>
      <b><a href="https://github.com/atj393/re-phraser">Re-Phraser</a></b><br>
      <sub>WRITING HELP, IN PLACE</sub><br><br>
      Your selection goes to the AI tab you already have open. No backend, no API-key box.<br><br>
      <sub><code>TypeScript</code> <code>React</code> <code>Chrome MV3</code></sub><br>
      <sub><a href="https://chromewebstore.google.com/detail/re-phraser-ai-text-rewrit/ldocllepggdbadbedboopoeebadnpddi">Chrome Web Store</a> · <a href="https://github.com/atj393/re-phraser">Source</a> · <a href="https://github.com/atj393/re-phraser/releases">Releases</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/atj393/promt-save-reuse-chatgpt-and-gemini"><img src="https://raw.githubusercontent.com/atj393/promt-save-reuse-chatgpt-and-gemini/main/icons/icon128.png" width="32" height="32" alt=""></a><br>
      <b><a href="https://github.com/atj393/promt-save-reuse-chatgpt-and-gemini">Prompt Save Reuse</a></b><br>
      <sub>THE ONE THAT GREW A COMMUNITY</sub><br><br>
      Reusable prompts across the popular AI chat products. MIT — and shaped by strangers' pull requests.<br><br>
      <sub><code>JavaScript</code> <code>Chrome MV3</code> <code>MIT</code></sub><br>
      <sub><a href="https://chromewebstore.google.com/detail/prompt-save-reuse-chatgpt/fldaklkfolpnnlgoejcgcgjmklmheaim">Chrome Web Store</a> · <a href="https://github.com/atj393/promt-save-reuse-chatgpt-and-gemini">Source</a> · <a href="https://github.com/atj393/promt-save-reuse-chatgpt-and-gemini/releases">Releases</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://play.google.com/store/apps/details?id=com.psalmswayapp"><img src="https://raw.githubusercontent.com/atj393/psalms-way-browser-extension/main/icon128.png" width="32" height="32" alt=""></a><br>
      <b>Psalms Way</b><br>
      <sub>ONE IDEA, TWO SURFACES</sub><br><br>
      A localized React Native reader on Google Play, plus an offline Chrome companion.<br><br>
      <sub><code>React Native</code> <code>TypeScript</code> <code>i18n</code></sub><br>
      <sub><a href="https://play.google.com/store/apps/details?id=com.psalmswayapp">Google Play</a> · <a href="https://github.com/atj393/psalms-way-app">Mobile source</a> · <a href="https://chromewebstore.google.com/detail/psalms-way-biblical-begin/aplafmlmecdjlmcgbibmlbjnilcomcnl">Chrome Web Store</a> · <a href="https://github.com/atj393/psalms-way-browser-extension">Extension</a></sub>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <sub><b>THE LAB &nbsp;·&nbsp; DELIBERATE PROOF OF CONCEPT</b></sub><br><br>
      <a href="https://github.com/atj393/local-browser-automation-bridge"><img src="https://raw.githubusercontent.com/atj393/local-browser-automation-bridge/main/apps/extension/public/icon128.png" width="32" height="32" alt=""></a><br>
      <b><a href="https://github.com/atj393/local-browser-automation-bridge">Local Browser Automation Bridge</a></b> — where I go to learn the back half<br><br>
      A React dashboard, an Express API, a SQLite queue, a WebSocket bridge, and a browser extension, all talking to each other locally. It ships with demo pages, explicit safety controls, and a README that calls it a proof of concept — because that is exactly what it is.<br><br>
      <sub><code>TypeScript</code> <code>React</code> <code>Express</code> <code>SQLite</code> <code>WebSockets</code></sub><br>
      <sub><a href="https://github.com/atj393/local-browser-automation-bridge">Source &amp; architecture</a></sub>
    </td>
  </tr>
</table>

<sub><b>05 &nbsp;—&nbsp; PRINCIPLES</b></sub>

## How I actually work

**I write down what a thing cannot do.** Every project above carries its limits in the README. The browser bridge is labeled a proof of concept because that is what it is. Overselling a tool is the fastest way to lose the person using it, and the second-fastest way to lose their trust permanently.

**Publishing the code is the beginning, not the end.** What makes a repository useful to a second person is the unglamorous half — architecture notes, tests, release assets, security guidance, honest limits. Five of the projects above ship under MIT or Apache-2.0 for exactly that reason.

**Workflows become products too.** When my own engineering process needed a tool, it turned into a reusable [Claude Code cleanup plugin](https://github.com/atj393/claude-plugin-code-cleanup) and the [marketplace](https://github.com/atj393/claude-plugins) that distributes it.

**I send fixes back upstream.** Including [repeat-visit caching](https://github.com/Octasol/octasol/pull/21) and [safer production logging](https://github.com/Octasol/octasol/pull/5) for Octasol. Using open source without contributing to it always felt like a bill left unpaid.

**I follow the problem past my comfort zone.** The browser bridge needed an Express API, a SQLite queue, and a WebSocket layer, so I learned them and built them. Backend isn't where I started, but it's increasingly where the interesting constraints live — and you can't design an honest interface for a system you don't understand.

> **The tools change; the standard doesn't.** AI writes a good deal of code now, mine included. That makes architecture, clear UX, testing, and review *more* load-bearing, not less — someone still has to know whether the thing is right.

<sub><b>06 &nbsp;—&nbsp; TOOLKIT</b></sub>

## What I reach for

<sub><b>APPLIED AI</b></sub><br>
`Provider APIs` `On-device / offline inference` `MediaPipe` `Prompt tooling` `Human-in-the-loop UX` `AI-assisted engineering`

<sub><b>INTERFACES</b></sub><br>
`Angular` `React` `TypeScript` `JavaScript` `HTML` `CSS / SCSS` `RxJS` `NgRx`

<sub><b>BEHIND THE INTERFACE</b></sub><br>
`Node.js` `Express` `REST APIs` `WebSockets` `PostgreSQL` `MongoDB` `SQLite`

<sub><b>BEYOND THE PAGE</b></sub><br>
`Browser extensions` `Chrome / Edge MV3` `React Native` `Android` `Kotlin` `Jetpack Compose`

<sub><b>THE QUALITY LOOP</b></sub><br>
`Accessibility` `Vitest` `Jest` `Jasmine` `Playwright` `Cypress` `GitHub Actions`

<sub><b>07 &nbsp;—&nbsp; SIGNALS</b></sub>

## Beyond the repositories

[Five-time LinkedIn Top Voice](https://www.linkedin.com/in/atj393/), and [verified credentials from Meta, Google, and IBM](https://www.credly.com/users/atj393).

Useful context. But the software above is the real introduction, and it's the part I'd rather be asked about.

<sub><b>08 &nbsp;—&nbsp; SAY HELLO</b></sub>

## Let's compare notes

Good conversations about software tend to start with a real problem rather than a job title. If you care about thoughtful interfaces, accessibility, open source, mobile products, or AI that respects the person using it — say hello.

[GitHub](https://github.com/atj393) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/atj393/) &nbsp;·&nbsp; [automatist.cloud](https://automatist.cloud/) &nbsp;·&nbsp; [Credly](https://www.credly.com/users/atj393) &nbsp;·&nbsp; [alexistoby393@gmail.com](mailto:alexistoby393@gmail.com)
