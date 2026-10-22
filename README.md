<div align="center">

<img src="./assets/hero.gif" width="100%" alt="Animated Himanshu Gour coding and systems artwork" />

<p><strong>ECE student · Full-stack developer · Systems enthusiast</strong></p>
<p><em>Curious about the layers underneath. Happiest when an idea turns into something that actually runs.</em></p>

<a href="https://leetcode.com/himanshugour23"><img src="https://img.shields.io/badge/LeetCode-1818%20max%20rating-F4B860?style=for-the-badge&logo=leetcode&logoColor=111827" alt="LeetCode max rating 1818" /></a>
<a href="https://linkedin.com/in/himanshu-gour"><img src="https://img.shields.io/badge/LinkedIn-Connect-6AA9FF?style=for-the-badge&logo=linkedin&logoColor=111827" alt="LinkedIn" /></a>
<a href="mailto:gourhimanshu284@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-B8FFB3?style=for-the-badge&logo=gmail&logoColor=111827" alt="Email" /></a>

<br/><br/>

<img src="https://img.shields.io/badge/DSA-800%2B%20solved-5CE1E6?style=flat-square&labelColor=10182B" alt="800 plus DSA problems" />
<img src="https://img.shields.io/badge/Codeforces-Pupil-B7A7FF?style=flat-square&labelColor=10182B" alt="Codeforces Pupil" />
<img src="https://img.shields.io/badge/Focus-Build%20%2B%20Learn-FFB86B?style=flat-square&labelColor=10182B" alt="Build and learn" />

<br/><br/>

[![Profile Views](https://hits.sh/github.com/himanshugour23-dev.svg?style=for-the-badge&label=PROFILE%20VIEWS&color=5CE1E6&labelColor=0B1020)](https://hits.sh/github.com/himanshugour23-dev/)

</div>

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `01` &nbsp; A bit about me

> **Learn the fundamentals. Build the thing. Understand why it works.**

I'm Himanshu Gour, an Electronics & Communication Engineering student at **MANIT Bhopal**. I like working close to the machinery of software — from a Redis-compatible key-value store running over raw TCP sockets to full-stack products with real authentication, payments, and moderation flows.

I enjoy the point where theory becomes something tangible: a packet moving through a server, a database handling a request, or a feature surviving more than the happy path.

```cpp
struct Himanshu {
    string college  = "MANIT Bhopal (B.Tech, ECE)";
    string role     = "Problem Setter @ Zenith Programming Club";
    string goal     = "Entry-level SDE";
    string loves    = "C++, systems programming, full-stack products";
    string learning = "ML, NLP, Deep Learning, GenAI";
    int dsa         = 800; // and counting
};
```

<div align="center">

| FOUNDATION | PROBLEM SOLVING | COMMUNITY | NEXT FRONTIER |
|:---:|:---:|:---:|:---:|
| 🎓 **MANIT Bhopal**<br/>B.Tech, ECE<br/>CGPA **8.25** | 🧩 **800+ problems**<br/>LeetCode max rating **1818**<br/>Codeforces **Pupil** | 🏆 **Prometeo '26**<br/>Online-round qualifier<br/>IIT Jodhpur | 🌱 **ML · NLP · DL · GenAI**<br/>Currently learning<br/>Target: **SDE** |

</div>

- ✍️ Authoring and reviewing competitive programming problems at **Zenith Programming Club**.
- 💬 Ask me about **C++, Python, systems programming, Next.js, PostgreSQL, and MongoDB**.

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `02` &nbsp; My toolkit

<div align="center">

**LANGUAGES**

<img src="https://skillicons.dev/icons?i=cpp,py,js,ts,postgres&theme=dark" alt="C++, Python, JavaScript, TypeScript and PostgreSQL" />

**WEB & PRODUCT ENGINEERING**

<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,html,css,tailwind&theme=dark" alt="React, Next.js, Node.js, HTML, CSS and Tailwind CSS" />

**DATA, WORKFLOW & TOOLS**

<img src="https://skillicons.dev/icons?i=mongodb,postgres,git,github,docker,postman&theme=dark" alt="MongoDB, PostgreSQL, Git, GitHub, Docker and Postman" />

**LEARNING LAB**

<img src="https://skillicons.dev/icons?i=sklearn,pytorch&theme=dark" alt="scikit-learn and PyTorch" />

</div>

| AREA | TECHNOLOGIES |
|---|---|
| **Languages** | C++, Python, JavaScript, TypeScript, SQL |
| **Web** | React.js, Next.js, Node.js, HTML, CSS, Tailwind CSS, REST APIs |
| **Databases & Tools** | PostgreSQL, MongoDB, Git, GitHub, Postman, Docker |
| **ML / Data** | Python, scikit-learn |
| **Core CS** | Data Structures & Algorithms, DBMS, Operating Systems, Computer Networks |
| **Currently learning** | Machine Learning, NLP, Deep Learning, Generative AI |

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `03` &nbsp; Selected builds

*Different layers of the stack. One common thread: understanding how the pieces fit together.*

<table>
<tr>
<td width="50%" valign="top">

<img src="./assets/mini-redis.gif" width="100%" alt="Animated Mini Redis systems project artwork" />

### ⚙️ Mini Redis
**In-memory key-value store · C++17**

A systems build exploring networking, concurrency, and persistence beneath a familiar Redis-style interface.

- Redis-compatible server using the **RESP protocol** over raw TCP sockets.
- Thread-per-connection concurrency with a mutex-guarded singleton database.
- **20+ commands** across strings, lists, and hashes.
- TTL-based key expiration with lazy eviction.
- RDB-style persistence — snapshots every **300s**, reload on startup.

`C++17` · `Sockets` · `Multithreading`

</td>
<td width="50%" valign="top">

<img src="./assets/baclogged.gif" width="100%" alt="Animated Baclogged gaming product artwork" />

### 🎮 Baclogged
**Game review & collection platform**

A place for game discovery, reviews, and collection — with attention paid to the engineering behind the experience.

- MongoDB caching layer for the RAWG API — **50% fewer API calls** and **~200 ms** faster repeat searches.
- **Razorpay** integration with HMAC-SHA256 verification and idempotent callbacks.
- Role-based auth, moderation tooling, and review-reporting pipeline.
- Two-stage AI avatar moderation (**Gemini API + Cloudinary Rekognition**).

`React` · `Next.js` · `MongoDB` · `NextAuth`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<img src="./assets/ngo-platform.gif" width="100%" alt="Animated community network and volunteer platform artwork" />

### 🤝 NGO Volunteer Management Platform
**Connecting volunteers with verified NGOs**

- **Dual authentication** — Better Auth for volunteers, custom JWT system for NGOs.
- Certificate verification with moderator approval before NGO account activation.
- Task-assignment logic that prevents volunteers from holding multiple active tasks.

<div align="center">

`Next.js` · `TypeScript` · `PostgreSQL` · `Better Auth`

</div>

</td>
</tr>
</table>

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `04` &nbsp; Currently exploring

<div align="center">

*Moving from building software systems to exploring systems that learn.*

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/Machine%20Learning-6AA9FF?style=for-the-badge" alt="Machine Learning" />
<img src="https://img.shields.io/badge/NLP-B7A7FF?style=for-the-badge" alt="NLP" />
<img src="https://img.shields.io/badge/Deep%20Learning-FFB86B?style=for-the-badge&logo=pytorch&logoColor=111827" alt="Deep Learning" />
<img src="https://img.shields.io/badge/Generative%20AI-B8FFB3?style=for-the-badge&logoColor=111827" alt="Generative AI" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=2600&pause=700&color=5CE1E6&center=true&vCenter=true&width=530&height=35&lines=Currently+learning...;%3E+Machine+Learning;%3E+Natural+Language+Processing;%3E+Deep+Learning;%3E+Generative+AI" alt="Animated current learning topics" />

</div>

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `05` &nbsp; GitHub telemetry

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=himanshugour23-dev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&bg_color=0B1020&title_color=5CE1E6&icon_color=FFB86B&text_color=F3F7FF" alt="GitHub statistics" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshugour23-dev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1020&title_color=5CE1E6&text_color=F3F7FF" alt="Most used languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=himanshugour23-dev&theme=tokyonight&hide_border=true&background=0B1020&ring=5CE1E6&fire=FFB86B&currStreakLabel=5CE1E6" alt="GitHub contribution streak" />

<br/><br/>

<img src="https://ghchart.rshah.org/5CE1E6/himanshugour23-dev" width="95%" alt="GitHub contribution calendar" />

</div>

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `06` &nbsp; Problem-solving log

<div align="center">

<a href="https://leetcode.com/himanshugour23">
  <img src="https://leetcard.jacoblin.cool/himanshugour23?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode profile and activity" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/PROBLEMS%20SOLVED-800%2B-5CE1E6?style=for-the-badge&logo=leetcode&logoColor=111827" alt="800 plus problems solved" />
<img src="https://img.shields.io/badge/MAX%20RATING-1818-B7A7FF?style=for-the-badge" alt="LeetCode maximum rating 1818" />
<img src="https://img.shields.io/badge/CODEFORCES-PUPIL-B8FFB3?style=for-the-badge" alt="Codeforces Pupil" />

</div>

<img src="./assets/signal.gif" width="100%" alt="Animated code-signal divider" />

## `07` &nbsp; Open channel

<div align="center">

### Building toward an entry-level SDE role.

Open to **SDE opportunities** and cool collaborations — reach out anytime.

<br/>

<a href="https://linkedin.com/in/himanshu-gour"><img src="https://img.shields.io/badge/CONNECT-LINKEDIN-6AA9FF?style=for-the-badge&logo=linkedin&logoColor=111827" alt="Connect on LinkedIn" /></a>
<a href="mailto:gourhimanshu284@gmail.com"><img src="https://img.shields.io/badge/WRITE-EMAIL-B8FFB3?style=for-the-badge&logo=gmail&logoColor=111827" alt="Email" /></a>

<br/><br/>

<img src="./assets/footer.gif" width="100%" alt="Animated coding-themed footer: keep building, keep questioning" />

</div>
