<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-dark.svg">
  <img alt="Alexis Johnson. I start at the interface and follow it all the way down the stack." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/hero-light.svg" width="100%">
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

I'm Alexis. For more than a decade I've built the layer people actually use, mostly in Angular and React, and I kept following the work past the browser into the APIs, queues, and data behind it. The interface is where I'm deepest, full-stack is the direction I'm growing, and AI is the tool I reach for most days.

I like being the newest person in the room on something. It's the fastest way I know to get good at it, and it keeps the work fun.

Almost everything below started the same way: something got in my way on an ordinary Tuesday, I went looking for the tool that would fix it, and the gap I found looked like a good excuse to build. So I did. I used it for a month, then spent considerably longer making it good enough to hand to a stranger.

> **That last part is the craft.** Getting something from *works for me* to *works for you* is the most satisfying stretch of any project.

<sub><b>01</b></sub>

## Working with AI

The most interesting problems in AI products sit around the model rather than inside it: how a person reviews the output, what still works with no network, where the data lives, and how someone stays in control of it. That's interface and architecture work, which is why I find it so absorbing.

> **AI made the work more interesting, not just faster.** Deciding what *should* happen is still the craft, and that's the part I enjoy most.

Here is how I assemble one. The same four layers apply whether it ends up in a phone, a browser tab, or a background job:

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-narrow-dark.svg">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-narrow-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-dark.svg">
  <img alt="Four layers: Interface (React, Angular, Jetpack Compose, Chrome MV3); Orchestration (scheduling, retries, run diagnostics, approval gates); Inference (cloud provider API, on-device via MediaPipe, compatible offline); Data (stays on the device unless you say otherwise)." src="https://raw.githubusercontent.com/atj393/atj393/main/assets/stack-light.svg" width="100%">
</picture>

<sub>Four layers, one feature, and I enjoy the work at every one of them.</sub>

What that looks like in the projects below:

**On-device and offline inference.** Automatist runs models locally through MediaPipe, so a scheduled task still completes with no connection and no account. Making that a real option rather than a degraded fallback is the entire point.

**Provider APIs, without holding your keys.** Re-Phraser routes a selection to the AI chat tab you already have open instead of to a backend I run. There's no API-key field because there's no server of mine to put a key in.

**Human-in-the-loop by default.** Nothing an AI produces in my tools replaces your text until you approve it. Trust is the feature, and it's earned by asking first.

**AI-assisted engineering, made reusable.** My own code-cleanup workflow became a [Claude Code plugin](https://github.com/atj393/claude-plugin-code-cleanup) and the [marketplace](https://github.com/atj393/claude-plugins) that distributes it. A workflow is easier to trust once someone else can run it.

<sub><b>02</b></sub>

## On the desk

Two more threads, and they sit closer to the work above than they look.

**Accessibility you can see.** Reports tell you what's wrong; I wanted something that shows you. Drawing focus order, landmarks, and the tab path straight onto the page turns an abstract rule into something a developer can spot and fix in seconds, which is a much easier thing to care about.

**Local-first software.** Automation that fits in a pocket, data that stays on the device, and products that still open when the network doesn't.

<sub><b>03</b></sub>

## Evidence

<table>
  <tr>
    <td colspan="2" valign="top">
      <sub><b>CURRENT FOCUS &nbsp;·&nbsp; IN CLOSED TESTING</b></sub><br><br>
      <a href="https://github.com/atj393/automatist-android"><img src="https://raw.githubusercontent.com/atj393/automatist-android/main/docs/assets/readme/automatist-logo.png" width="44" height="44" alt=""></a><br>
      <b><a href="https://github.com/atj393/automatist-android">Automatist</a></b><br>
      <sub>MOBILE-FIRST AI WORKFLOW AUTOMATION</sub><br><br>
      Recurring AI tasks, scheduled and diagnosable from a phone, with a real choice between cloud, on-device, and compatible offline models. Free and open source: no ads, no subscription, nothing held behind a paywall.<br><br>
      <sub><code>Kotlin</code> <code>Jetpack Compose</code> <code>WorkManager</code> <code>Room</code> <code>MediaPipe</code></sub><br>
      <sub><a href="https://automatist.cloud/">Website</a> · <a href="https://github.com/atj393/automatist-android">Source &amp; docs</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/atj393/easy-web-navigation"><img src="https://raw.githubusercontent.com/atj393/easy-web-navigation/main/docs/assets/easy-web-navigation-icon.png" width="32" height="32" alt=""></a><br>
      <b><a href="https://github.com/atj393/easy-web-navigation">Easy Web Navigation</a></b><br>
      <sub>ACCESSIBILITY, MADE VISIBLE</sub><br><br>
      Focus, tab order, landmarks, and labels, drawn onto the page instead of filed as a report.<br><br>
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
      Reusable prompts across the popular AI chat products. MIT, and shaped by strangers' pull requests.<br><br>
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
      <b><a href="https://github.com/atj393/local-browser-automation-bridge">Local Browser Automation Bridge</a></b><br>
      <sub>WHERE I GO TO LEARN THE BACK HALF</sub><br><br>
      A React dashboard, an Express API, a SQLite queue, a WebSocket bridge, and a browser extension, all talking to each other locally. It ships with demo pages, explicit safety controls, and a README that calls it a proof of concept, because that is what it is.<br><br>
      <sub><code>TypeScript</code> <code>React</code> <code>Express</code> <code>SQLite</code> <code>WebSockets</code></sub><br>
      <sub><a href="https://github.com/atj393/local-browser-automation-bridge">Source &amp; architecture</a></sub>
    </td>
  </tr>
</table>

<sub><b>04</b></sub>

## Habits that stuck

**I write down what a thing can and cannot do.** The browser bridge carries "proof of concept" in its own README, because that is what it is. Being straight about the edges is what earns a tool its second use.

**Publishing the code is the beginning, not the end.** What makes a repository useful to a second person is the unglamorous half: architecture notes, tests, release assets, security guidance, stated limits. Five of the projects above are MIT or Apache-2.0, and I'd be delighted if someone picked one up and took it somewhere I hadn't thought of.

**Other people's pull requests made it better.** Prompt Save Reuse has been shaped by contributors I've never met. Merging someone else's work into a project you started is a different skill from writing it, and one I enjoy practicing in the open.

**I send fixes back upstream.** Including [repeat-visit caching](https://github.com/Octasol/octasol/pull/21) and [safer production logging](https://github.com/Octasol/octasol/pull/5) for Octasol. Open source gave me most of what I know, so sending improvements back is a part of the week I look forward to.

**I like being a beginner on purpose.** The browser bridge needed an Express API, a SQLite queue, and a WebSocket layer, so I learned them and built them. Backend isn't where I started, and that's what makes it fun. Understanding the system underneath makes every interface decision above it better.

> **AI is the best tool I've added to the bench.** It writes a good deal of my code now, which makes architecture, clear UX, testing, and review matter *more*, not less. Knowing whether the thing is right is still on me, and I like it that way.

<sub><b>05</b></sub>

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

<sub><b>06</b></sub>

## Signals

[Five-time LinkedIn Top Voice](https://www.linkedin.com/in/atj393/), and [verified credentials from Meta, Google, and IBM](https://www.credly.com/users/atj393).

I learn in public and keep studying deliberately. The certificates are a happy side effect of that habit, and the products above are what came out of it. I'm glad to talk about either.

<sub><b>07</b></sub>

## Let's compare notes

The best conversations about software start with a real problem rather than a job title. If you're building something around thoughtful interfaces, accessibility, open source, mobile, or applied AI, I'd genuinely love to hear from you. The same goes if you have a team where I'd get to learn a lot.

[GitHub](https://github.com/atj393) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/atj393/) &nbsp;·&nbsp; [automatist.cloud](https://automatist.cloud/) &nbsp;·&nbsp; [Credly](https://www.credly.com/users/atj393) &nbsp;·&nbsp; [alexistoby393@gmail.com](mailto:alexistoby393@gmail.com)
