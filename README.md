::: {align="center"}
# `WAIZ.AHMED()`

### 🛰️ Data Science Student · AI/ML Explorer · Builder of Strange Things

**UET Lahore · Institute of Data Science**

`Python` `SQL` `C#` `Data Science` `Machine Learning` `Deep Learning`

`<br>`{=html}

> **MISSION STATUS:** `ONLINE`
>
> 🐍 A snake is currently escaping the repository.\
> 🤖 The robots have stopped asking for permission.\
> 🌌 Somewhere between a dataset and a black hole, I'm building
> something.

`<br>`{=html}

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/waiz-ahmed-0a24693a3)
[![Email](https://img.shields.io/badge/EMAIL-FF4B4B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedwaiz157@gmail.com)
:::

------------------------------------------------------------------------

## 🪐 `BOOT_SEQUENCE`

``` text
[01] Initializing student...
[02] Loading curiosity.......................... OK
[03] Loading Python............................. OK
[04] Loading SQL................................ OK
[05] Loading Data Science....................... OK
[06] Loading AI / ML / DL....................... █████████░ 90%
[07] Searching for "normal" project ideas...... NOT FOUND
[08] Deploying questionable amounts of caffeine. OK

STATUS: READY TO BUILD.
```

I'm **Waiz Ahmed**, a Data Science student at **UET Lahore**.

I like taking ordinary problems and turning them into systems that feel
a little more like they belong in a control room on a spacecraft.

My current orbit is around:

-   📊 **Data Science & Analytics**
-   🧠 **Artificial Intelligence**
-   🤖 **Machine Learning**
-   🧬 **Deep Learning**
-   🐍 **Python**
-   🗄️ **SQL & Databases**
-   ⚙️ **Software / Backend Engineering**
-   🧪 Experimentation, automation and data-driven problem solving

I'm still early in the journey --- which is exactly why this GitHub is
going to document the experiments, failures, weird ideas and systems
built along the way.

------------------------------------------------------------------------

# 🛰️ `CURRENT_ORBIT`

  -----------------------------------------------------------------------
  Signal                              Status
  ----------------------------------- -----------------------------------
  🎓 Degree                           Data Science

  🏛️ University                       University of Engineering and
                                      Technology (UET), Lahore

  🧠 Main Interests                   DS · AI · ML · DL

  🐍 Primary Language                 Python

  🗃️ Data                             SQL · CSV · JSON

  ⚙️ Also Exploring                   C# · .NET · Databases · APIs

  🔭 Current Mode                     Learning → Building → Breaking →
                                      Rebuilding
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🤖 `PROJECT_ARCHIVE`

## 🛰️ RationPro

### `Smart Ration Distribution & Tracking System`

**Type:** Web Application · Python/Flask

RationPro is a digital welfare-management system designed around
transparent ration distribution.

The system explores:

-   🔐 Applicant registration and verification
-   🧮 Rule-based eligibility checking
-   📦 Smart ration allocation based on income and family size
-   🛡️ Duplicate-application detection
-   📊 Inventory and operational monitoring
-   👨‍💼 Separate applicant/admin workflows
-   📈 Dashboard analytics

The project uses **Python/Flask + SQLite**, with a web interface built
using **HTML/CSS** and interactive visualization through **Plotly.js**.

> `INPUT → VERIFY → DECIDE → ALLOCATE → TRACK`

The project presentation describes automated verification, tiered
allocation and separate public/admin interfaces as core parts of the
system.

------------------------------------------------------------------------

## 🌍 Smart Travel Itinerary Planner

### `Constraint-Based Travel System`

**Type:** OOP + Database Project · 2nd Semester

A C#/.NET travel-planning system that generates day-by-day itineraries
from:

`SOURCE + DESTINATION + BUDGET + DURATION + TRAVEL MODE`

The project combines application architecture with relational database
design.

### ⚙️ Engine Room

-   `C# / .NET 8`
-   `SQL Server`
-   `ADO.NET`
-   `T-SQL`
-   `Windows Forms`
-   `LINQ`
-   `Repository Pattern`
-   `Singleton`
-   `Observer`
-   `Factory`
-   Custom Exceptions
-   Transactions
-   Stored Procedures
-   Triggers
-   3NF Database Design

### 🧩 Core Modules

``` text
USER INPUT
    ↓
VALIDATION
    ↓
ROUTE ENGINE ────────┐
    ↓                 │
HOTEL SELECTOR        │
    ↓                 │
PLACE SELECTOR        │
    ↓                 │
BUDGET TRACKER ──────┘
    ↓
ITINERARY GENERATOR
    ↓
SAVE + AUDIT
```

The project proposal specifies six main relational tables plus a
status-log mechanism, with stored procedures for itinerary/cost logic
and an `AFTER UPDATE` trigger for itinerary status history.
fileciteturn0file0L52-L58

------------------------------------------------------------------------

# 🧪 `LAB_NOTES`

This repository is not meant to pretend that everything works on the
first try.

Expect:

``` text
experiments/
    ├── things-that-work/
    ├── things-that-almost-work/
    ├── why-is-this-NaN/
    ├── definitely-not-production/
    └── DO_NOT_DELETE_THIS_IT_SOMEHOW_WORKS/
```

Because debugging is just science with more error messages.

------------------------------------------------------------------------

# 🧠 `LEARNING_TREE`

``` text
                         🌌
                         │
                  ┌──────┴──────┐
                  │ DATA SCIENCE │
                  └──────┬──────┘
                         │
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
       DATA           MODELS         SYSTEMS
          │              │              │
     ┌────┼────┐      ┌──┼──┐       ┌───┼────┐
     ↓    ↓    ↓      ↓  ↓  ↓       ↓   ↓    ↓
   SQL  Pandas NumPy  ML AI DL     APIs DB  Apps
     │    │    │      │  │  │       │   │    │
     └────┴────┴──────┴──┴──┴───────┴───┴────┘
                         │
                         ↓
                  🚀 BUILD SOMETHING
```

------------------------------------------------------------------------

# 🐍 `THE_SNAKE_PROTOCOL`

The contribution graph is not a graph.

It is a **feeding ground**.

When GitHub contributions accumulate, the snake eats them.

```{=html}
<!-- Replace this with your username after creating your GitHub profile README -->
```
``` text
https://github.com/Platane/snk
```

Recommended GitHub Action for the actual animated contribution snake:

``` yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
        env:
          GH_PAT: ${{ secrets.GH_PAT }}
```

Then display the generated SVG in this README.

------------------------------------------------------------------------

# 🛸 `TECH_STACK`

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)

### Data / AI

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)

### Development

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQL
Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

------------------------------------------------------------------------

# 📡 `RADAR`

### Now exploring

``` text
DATA SCIENCE       █████████░░  85%
PYTHON             █████████░░  85%
SQL / DATABASES    ████████░░░  75%
MACHINE LEARNING   ██████░░░░░  55%
DEEP LEARNING      ████░░░░░░░  35%
AI SYSTEMS         █████░░░░░░  45%
SOFTWARE DESIGN    ██████░░░░░  55%
```

These are not skill ratings.

They are **current learning targets**.

------------------------------------------------------------------------

# 🧠 `RULES_OF_THE_LAB`

``` python
while not excellent:
    build()
    break_things()
    read_docs()
    debug()
    learn()
    repeat()
```

### Prime directive

> Don't just learn the tool.\
> **Build something that makes the tool necessary.**

------------------------------------------------------------------------

# 🪐 `FUTURE_TRANSMISSIONS`

Things I want to explore deeper:

-   🧠 Machine Learning systems
-   🧬 Deep Learning
-   👁️ Computer Vision
-   💬 NLP / LLM systems
-   📈 Advanced Data Analytics
-   🗄️ Large-scale data engineering
-   ⚡ Model deployment & APIs
-   ☁️ Cloud-based data systems
-   🧪 Real-world experimentation
-   🤖 Autonomous / intelligent applications

------------------------------------------------------------------------

# 📬 `CONTACT`

Want to talk data, AI, projects, debugging or unnecessarily ambitious
ideas?

**Email:** `ahmedwaiz157@gmail.com`

**LinkedIn:**\
https://www.linkedin.com/in/waiz-ahmed-0a24693a3

------------------------------------------------------------------------

::: {align="center"}
### 🌌 END OF TRANSMISSION

``` text
     .       *        .       🚀
  *       .     🪐       *
       .       /\
   🤖         /  \       🐍
             /____\
       DATA → KNOWLEDGE → SYSTEMS
             ↑
          KEEP BUILDING
```

**`01000110 01001111 01010010 01010111 01000001 01010010 01000100`**

*The repository is alive. Probably.*
:::
