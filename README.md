<div align="center">

<img src="banner.svg" alt="Venkata Naga Kusal. Software that keeps your data on your device." width="100%">

<br>

<a href="https://linkedin.com/in/venkata-naga-kusal-kotte-314268240">LinkedIn</a> &nbsp;·&nbsp;
<a href="https://kaggle.com/venkatanagakusal">Kaggle</a> &nbsp;·&nbsp;
<a href="mailto:kottekvnkusal@gmail.com">Email</a>

<br>

<a href="#selected-work">Work</a> &nbsp;·&nbsp;
<a href="#how-rethink-root-works">How Rethink Root works</a> &nbsp;·&nbsp;
<a href="#privacy">Privacy</a> &nbsp;·&nbsp;
<a href="#skills">Skills</a> &nbsp;·&nbsp;
<a href="#background">Background</a> &nbsp;·&nbsp;
<a href="#earlier-projects">Earlier projects</a>

</div>

<br>

I'm Venkata Naga Kusal, an AI and Data Science undergraduate at Shiv Nadar University Chennai, class of 2028.

I build open source software for the parts of computing most people never question: where your time data goes, who holds your files, and what sits between your phone and the network. Five of those projects are below. Three are finished, one is underway, and one is going slower than I'd like.

<br>

## Selected work

<table width="100%">
<tr>
<td width="50%" valign="top">
<p><img src="icon-soul-track.svg" width="44" height="44" alt=""><br>
<b><a href="https://github.com/kusal630/TIme-tracker">Soul Track</a></b><br>
<sub>Kotlin &nbsp;·&nbsp; Completed</sub></p>
<p>A private time tracker that accounts for every second of your day and keeps all of it on the device. It produces a growth score and a breakdown of where your time went, and includes a to-do list with a Pomodoro timer.</p>
<p>It also notices when you've been in your comfort zone for too long and says so.</p>
</td>
<td width="50%" valign="top">
<p><img src="icon-localvault.svg" width="44" height="44" alt=""><br>
<b><a href="https://github.com/kusal630/local-cloud-storage">LocalVault</a></b><br>
<sub>Dart &nbsp;·&nbsp; Completed</sub></p>
<p>Turns the SSD or phone storage you already own into a personal cloud you can reach from anywhere. No subscription, and no company holding your files.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><img src="icon-rethink-root-android.svg" width="44" height="44" alt=""><br>
<b><a href="https://github.com/kusal630/rethink-root-level-android">Rethink Root for Android</a></b><br>
<sub>Kotlin &nbsp;·&nbsp; Completed</sub></p>
<p>A fork of RethinkDNS, the Mozilla Builders Android app. The original filters traffic through a VPN tunnel. This version runs at kernel level with root privileges instead, offloads the firewall to the root level, and adds a power profile focused on battery life.</p>
</td>
<td width="50%" valign="top">
<p><img src="icon-rethink-root-linux.svg" width="44" height="44" alt=""><br>
<b><a href="https://github.com/kusal630/rethink-root-linux">Rethink Root for Linux</a></b><br>
<sub>Python &nbsp;·&nbsp; In progress</sub></p>
<p>The same approach on the desktop: a system-wide DNS firewall with per-app blocking and a proxy, running with sudo or root on any Linux machine.</p>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<p><img src="icon-purepad.svg" width="44" height="44" alt=""><br>
<b><a href="https://github.com/kusal630/purepad">PurePad</a></b><br>
<sub>Python &nbsp;·&nbsp; In development</sub></p>
<p>A LineageOS-based build for the Realme Pad 1, with the goal of running Android 16 on a low-end tablet the manufacturer has moved on from. Not shipped yet, and it will be late.</p>
</td>
</tr>
</table>

<br>

## How Rethink Root works

Stock RethinkDNS needs a VPN tunnel to see your traffic. Root mode removes the tunnel and moves enforcement into the kernel.

```text
Stock RethinkDNS
  Apps  →  VPN tunnel  →  Filtering in the app  →  Network

Rethink Root
  Apps  →  Kernel-level rules (root)  →  Network
```

<br>

## Privacy

I understand how companies collect personal data, from apps, operating systems and online services, and how to cut that collection down, including on stock Android where much of it happens by default. That knowledge shapes what I build.

Soul Track keeps your time data on the device. LocalVault replaces hosted cloud storage with storage you own. Rethink Root blocks unwanted connections at the network layer, for the whole system or per app.

<br>

## Skills

| | |
|---|---|
| **Full-stack** | React, Node.js, Express, Python backends, REST APIs, PostgreSQL, Supabase, webhooks, database and schema design |
| **Mobile and systems** | Android (Kotlin), Flutter and Dart, Linux, root-level networking and firewalls |
| **Machine learning** | Gradient-boosted models (XGBoost, CatBoost, LightGBM), feature engineering, validation, ML pipelines |
| **Deep learning** | Training and experimenting with neural networks on Kaggle GPUs |
| **Applied AI** | LLM agents, prompt and context management, OpenAI API, Gradio, n8n automation. Currently learning RAG pipelines |
| **Privacy** | How data is collected by apps and platforms, and how to limit it: permissions, network filtering, on-device storage, self-hosting |

<br>

## Background

| | |
|---|---|
| **Shell.ai Hackathon** | Top 100 globally. Predicted fuel properties from raw data with XGBoost, CatBoost and LightGBM. |
| **IIT Jammu Winter School** | Built a study assistant agent at the Gen AI and AI Agents program, December 2025 to March 2026. |
| **Education** | AI and Data Science, Shiv Nadar University Chennai, 2028. |

<br>

## Earlier projects

<details>
<summary>Open the list</summary>

<br>

| Project | What happened | Stack |
|---|---|---|
| **FuelPropertiesPredictor** | The Shell.ai entry. The leaderboard climb came from feature engineering and careful validation, not a fancier model. | XGBoost, CatBoost, LightGBM |
| **Predictive Maintenance Scheduling System** | Began as a DBMS assignment and grew into a full-stack app with a 21-table Postgres schema and an ML pipeline for equipment failure. Most of the effort went into making the SRS, ER diagrams and real schema agree. | React, Python, PostgreSQL, Supabase |
| **Study Assistant Agent** | The API call was the easy part. Keeping the model on topic and managing context across turns took the rest. | Python, OpenAI API, Gradio |
| **PollyGlot** | A translation app, mostly an exercise in never leaking an API key. Every OpenAI call goes through a backend. | Node.js, Express, OpenAI API |
| **Movie Watchlist** | Live data from a public movie API, with the watchlist kept in `localStorage` so it never leaves your browser. Fully keyboard-navigable. | JavaScript, REST API |
| **n8n Automation Pipelines** | A university management system and a student feedback sentiment pipeline. Webhook in, routing, an LLM node, result out. | n8n, OpenAI API |

Also on GitHub: [world-notes](https://github.com/kusal630/world-notes) (handwriting-first notes with palm rejection, Flutter), [vellum](https://github.com/kusal630/vellum) (Kotlin), [razorpay_ai_buildaton_real_solution](https://github.com/kusal630/razorpay_ai_buildaton_real_solution) (TypeScript) and [web-dev](https://github.com/kusal630/web-dev) (JavaScript).

</details>

<br>

<div align="center">

Building something interesting? Write to me at <b>kottekvnkusal@gmail.com</b>.

</div>
