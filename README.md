<div align="center">

# Venkata Naga Kusal Kotte

</div>

```
$ whoami
AI & Data Science undergrad, Shiv Nadar University Chennai (2028)

$ cat current_focus.txt
LLM agents, ML pipelines, and the gap between "it works on my machine"
and "a stranger could open this and use it"

$ git log --oneline --graph
* Dec 2025 - Mar 2026   Built a study assistant agent at IIT Jammu's
|                       Gen AI & AI Agents Winter School
* ongoing               Predictive Maintenance Scheduling System
|                       (full-stack, 21-table Postgres schema)
* Kaggle                Shell.ai Hackathon - top 100 globally,
                        fuel property prediction
```

---

## The short version

I got into this field the way most people probably do — by being annoyed that a tutorial stopped right before the interesting part. So instead of finishing another course, I started building the thing myself and figuring out the interesting part the hard way.

That's more or less the pattern behind everything below. A translation app that taught me why API keys don't belong in frontend code. A study assistant that taught me conversation context doesn't manage itself. An automation pipeline that taught me half of "integration engineering" is just wiring the right triggers to the right conditions.

None of it was assigned. All of it was because I wanted to see if I could.

---

## Field notes from each project

<table>
<tr><th width="30%">Project</th><th>What actually happened</th></tr>

<tr>
<td><b>Predictive Maintenance<br>Scheduling System</b></td>
<td>Started as a DBMS assignment, turned into a full-stack rabbit hole. React frontend, Python backend, a 21-table Postgres schema on Supabase, and an ML pipeline predicting equipment failure underneath it all. The unglamorous truth: most of the effort went into making the SRS docs, the ER diagrams, and the actual schema agree with each other — not into the ML.<br><code>React · Python · PostgreSQL · Supabase</code></td>
</tr>

<tr>
<td><b>PollyGlot</b></td>
<td>A translation tool, but really an exercise in not being the person who leaks an API key on GitHub. Every OpenAI call routes through a backend server — the frontend never sees the key. Small project, but it's the pattern I now reach for by default.<br><code>Node.js · Express · OpenAI API</code></td>
</tr>

<tr>
<td><b>Study Assistant Agent</b><br><i>— IIT Jammu Winter School</i></td>
<td>Built during a Gen AI & AI Agents internship. The API call was the easy 10%. The rest was prompt discipline (keeping the model from wandering off-topic) and context management across turns, since the API itself remembers nothing between requests.<br><code>Python · OpenAI API · Gradio</code></td>
</tr>

<tr>
<td><b>Movie Watchlist</b></td>
<td>Pulls live data from a public movie API but keeps your watchlist entirely in <code>localStorage</code> — no backend, no database, your list never leaves your browser. Built accessibility-first: semantic HTML, ARIA labels, and a layout you can navigate with a keyboard alone.<br><code>JavaScript · REST API · Accessibility</code></td>
</tr>

<tr>
<td><b>n8n Automation Pipelines</b></td>
<td>A university management system and a student feedback sentiment pipeline, both built on the same idea: not every integration needs hand-written glue code. Webhook in, conditional routing, an LLM node in the middle, output out.<br><code>n8n · OpenAI API · Webhooks</code></td>
</tr>

<tr>
<td><b>FuelPropertiesPredictor</b></td>
<td>The project behind the Shell.ai Hackathon result. Gradient-boosted models predicting fuel properties from raw data — the leaderboard climb had less to do with picking a fancier model and more to do with grinding through feature engineering and validation.<br><code>XGBoost · CatBoost · LightGBM</code></td>
</tr>

</table>

---

## Currently

```
[####################----------] learning: LLM agent design, RAG pipelines
[#####################---------] building: things people can actually open and use
[###############---------------] debugging: my own assumptions, mostly
```

---

<div align="center">

Reach out if you're building something interesting: **kottekvnkusal@gmail.com**
[LinkedIn](https://linkedin.com/in/venkata-naga-kusal-kotte-314268240) · [Kaggle](https://kaggle.com/venkatanagakusal)

</div>
