<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Sreerama%20M%20P&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Systems%20Programmer%20%E2%80%A2%20Researcher%20%E2%80%A2%20Carnatic%20Technologist&descAlignY=60&descSize=18&animation=fadeIn" />

<!-- TYPING ANIMATION -->
<a href="https://github.com/sreeramamp123">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&random=false&width=700&height=60&lines=Building+things+that+live+close+to+the+metal+%F0%9F%A6%80;Reinforcement+Learning+%2B+OS+internals+%3D+RATM;Carnatic+music+meets+computer+science+%F0%9F%8E%B5;pYIN+%7C+just+intonation+%7C+22+shrutis+%7C+one+tool;72+Melakartha+Talas%2C+zero+drift+%E2%8F%B1%EF%B8%8F" alt="Typing SVG" />
</a>

<br/>

<!-- SOCIAL BADGES -->
<a href="https://linkedin.com/in/sreerama-mp">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/sreeramamp123">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://doi.org/10.1109/ICMCSI67283.2026.11412692">
  <img src="https://img.shields.io/badge/IEEE%20Paper-00629B?style=for-the-badge&logo=ieee&logoColor=white" />
</a>
<a href="mailto:drsreeramamp123@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=sreeramamp123&color=7c3aed&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

<!-- ABOUT -->
## `$ whoami`

```rust
struct Sreerama {
    role:        "Final-year CS @ Rajarajeswari College of Engineering (VTU) · GPA 8.25",
    currently:   ["Java Full Stack Intern @ Ethnotech", "Building Tala App", "Veena Shruthi Analyser"],
    published:   "RATM — ICMCSI 2026 (IEEE)",
    obsessions:  ["systems programming", "Carnatic music tech", "RL for OS problems"],
    fun_fact:    "I write Rust. I also play veena. These are not unrelated.",
}
```

> *I like problems that sit at the intersection of things that don't usually talk to each other — operating systems and machine learning, Carnatic music theory and signal processing. If it's a weird crossover, I'm probably already thinking about it.*

---

<!-- RESEARCH HIGHLIGHT -->
## 📄 Research — ICMCSI 2026 (IEEE)

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  RATM: Reinforcement Learning for Co-Optimised CPU Scheduling               │
│        and NUMA Memory Management in Compiler Design                        │
│                                                                             │
│  ▸ Presented at ICMCSI 2026 (International Conference on Machine            │
│    Computing and Software Intelligence)                                     │
│  ▸ DOI: https://doi.org/10.1109/ICMCSI67283.2026.11412692                   │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

Built a NUMA-Aware Adaptive Tiered Allocator in Rust — three layers: **Thread-Local Caches → NUMA-Node-Local Arenas → Global Page Allocator** — then layered an RL agent on top to co-optimise CPU scheduling and memory placement. The kind of thing that sounds academically clean until you're debugging arena fragmentation at 2am.

---

<!-- PROJECTS -->
## 🛠️ Things I've Built

<details open>
<summary><b>🦀 Minimal Kernel Simulator with RL</b> &nbsp;·&nbsp; <code>Rust</code> &nbsp;·&nbsp; Jan 2025 – Jan 2026</summary>

<br/>

Simulated OS-level memory management from scratch. Designed a **NUMA-Aware Adaptive Tiered Allocator** that models hardware-software interaction at the memory subsystem level — thread-local caches, NUMA-node-local arenas, and a global page allocator working in concert. Applied Reinforcement Learning to co-optimise CPU scheduling and NUMA memory placement. This became the ICMCSI 2026 paper.

</details>

<details open>
<summary><b>🎵 Tala App</b> &nbsp;·&nbsp; <code>Flutter + Rust</code> &nbsp;·&nbsp; Feb 2026 – Present</summary>

<br/>

A metronome that actually understands Carnatic music. Most apps count beats. This one understands **Angas**.

- All **72 Melakartha Talas** + Sapta Talas with every Jati variation
- Mathematically precise beat timing — **zero drift**, because Carnatic performance demands it
- Anga-aware bouncing ball visualisation: Laghu, Dhrutha, Anudhrutha, Guru, Plutha boundaries rendered correctly
- **Vilamba Kala** slow-tempo mode — something no existing metronome app does

</details>

<details open>
<summary><b>🔬 Veena Shruthi Analyser</b> &nbsp;·&nbsp; <code>Python · librosa · NumPy</code> &nbsp;·&nbsp; Mar 2026 – Present</summary>

<br/>

Western pitch tools are deaf to Carnatic microtones. This fixes that.

- Extracts fundamental frequency (F0) from Carnatic Veena audio via **pYIN** probabilistic pitch estimation
- Maps against all **22 Carnatic shrutis** using just intonation frequency ratios — not the A440 equal-temperament model
- **Tonic-relative model**: analysis works regardless of tuning reference, which is how Carnatic music actually works
- Computes cent deviation between detected pitch and ideal shruti — exposing microtonal characteristics that no Western tool captures

</details>

<details>
<summary><b>🚌 RedBus Clone — Bus Booking System</b> &nbsp;·&nbsp; <code>Java · MariaDB</code> &nbsp;·&nbsp; Feb 2026</summary>

<br/>

Full-featured bus-booking backend built with strict layered DAO/Service architecture. Modelled entities (Bus, Route, Booking, Seat, User), wrote MariaDB DDL schemas, implemented all CRUD and booking-logic service methods. Business logic wired through JDBC. Clean separation of concerns throughout.

</details>

---

<!-- TECH STACK -->
## ⚙️ Tech Stack

<div align="center">

### Languages
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />

### Frameworks & Tools
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/JDBC-007396?style=for-the-badge&logo=java&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />

### Databases
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />

### Audio / Signal Processing
<img src="https://img.shields.io/badge/librosa-FF6B35?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" />

</div>

---

<!-- GITHUB STATS -->
## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=sreeramamp123&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sreeramamp123&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=sreeramamp123&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=a78bfa&currStreakLabel=a78bfa" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sreeramamp123&bg_color=0d1117&color=a78bfa&line=7c3aed&point=ffffff&area=true&hide_border=true" />

</div>

---

<!-- WORK EXPERIENCE -->
## 💼 Work Experience

| Role | Company | Period |
|------|---------|--------|
| **Java Full Stack Development Intern** | Ethnotech Academic Solutions Pvt. Ltd. | Feb 2026 – Present |
| **Android App Developer Intern** | Prodigy Infotech | Apr 2025 |

---

<!-- THE CARNATIC ANGLE -->
## 🎵 The Carnatic Connection

<div align="center">

```
                    ♩  ♪  ♫  ♬  ♩  ♪  ♫  ♬
    
    72 Melakartha Ragas.   22 Shrutis.   Infinite Gamakas.
    
    These aren't just musical concepts to me —
    they're the design requirements for software nobody else thought to build.
    
                    ♬  ♫  ♪  ♩  ♬  ♫  ♪  ♩
```

</div>

I come from a family with deep roots in Carnatic music. with my father a Veena Vidwan and scholar. Growing up surrounded by ragas, talas, and the precise mathematics of Indian classical music gave me a strange lens for computing problems. Carnatic music is extraordinarily systematic: 72 parent scales, each with defined microtonal relationships, rhythmic structures with named subdivisions. It practically *asks* to be modelled computationally.

The **Tala App** and **Veena Shruthi Analyser** are my attempt to give back — to build tools that actually serve this tradition rather than flattening it into Western approximations.

---

<!-- FOOTER -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

*"The code compiles. The shruti is in tune. Both feel the same."*

</div>
