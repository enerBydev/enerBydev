<!-- ========================================= -->
<!--  enerBydev — Enterprise GitHub Profile README  -->
<!--  Crafted with precision. Inspired by the best. -->
<!-- ========================================= -->

<!-- Animated Header Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=220&section=header&text=enerBydev&fontSize=70&fontColor=e94560&animation=fadeIn&fontAlignY=38&desc=Rene%20de%20Jesus%20Mendoza%20Saucedo&descAlignY=55&descSize=18" width="100%" />
</div>

<!-- Animated Typing Introduction -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=E94560&center=true&vCenter=true&width=600&lines=Fullstack+Software+Engineer;Rust+%26+AI+Specialist;Building+NEXUS-AI-Gateway;High-Performance+Systems+Architect;Open+Source+Contributor" alt="Typing SVG" />
  </a>
</div>

<!-- Social & Contact Badges -->
<div align="center">
  <a href="https://enerbydev.pages.dev" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=e94560" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/enerbydev" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:rjmendoza.s@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://wa.me/528675712611" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="https://github.com/enerBydev?tab=repositories" target="_blank">
    <img src="https://img.shields.io/badge/Repos-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</div>

<br />

<!-- Location & Availability Badge -->
<div align="center">
  <img src="https://img.shields.io/badge/Nuevo%20Laredo,%20Mexico-00C853?style=flat-square&logo=google-maps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Available%20for%20hire-00C853?style=flat-square&logo=checkmarx&logoColor=white" alt="Available" />
  <img src="https://img.shields.io/badge/Remote%20%7C%20Hybrid%20%7C%20On--site-2962FF?style=flat-square&logo=microsoft-teams&logoColor=white" alt="Work Mode" />
  <img src="https://komarev.com/ghpvc/?username=enerBydev&color=e94560&style=flat-square&label=Profile+Views" alt="Profile Views" />
</div>

<br />

---

<!-- About Me Section - Code Styled -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" alt="Technologist" width="30" /> About Me

```rust
// enerby-core/src/profile.rs
#[derive(Debug, Clone)]
pub struct Developer {
    pub name: &'static str,
    pub handle: &'static str,
    pub location: &'static str,
    pub role: &'static str,
    pub specialization: Vec<&'static str>,
    pub languages: Vec<&'static str>,
    pub current_focus: &'static str,
    pub philosophy: &'static str,
}

impl Default for Developer {
    fn default() -> Self {
        Self {
            name: "Rene de Jesus Mendoza Saucedo",
            handle: "enerBydev",
            location: "Nuevo Laredo, Tamaulipas, Mexico",
            role: "Fullstack Software Engineer",
            specialization: vec![
                "High-Performance Rust Systems",
                "AI/LLM Proxy Architectures",
                "Distributed Backend Services",
                "Full-Stack Web Development",
                "UI/UX & Digital Design",
            ],
            languages: vec!["Spanish (Native)", "English (Technical Advanced)"],
            current_focus: "Building NEXUS-AI-Gateway ecosystem",
            philosophy: "Zero-cost abstractions. Maximum performance. Clean architecture.",
        }
    }
}

impl Developer {
    pub fn introduce(&self) {
        println!(
            "Hey, I'm {} (@{}). I build systems that don't break under pressure.",
            self.name, self.handle
        );
        println!(
            "Currently specializing in Rust + AI infrastructure — \
             from low-level proxy servers to full-stack applications."
        );
        println!("Open to collaborate on ambitious projects.");
    }
}
```

<br />

---

<!-- Tech Stack Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Tools" width="30" /> Tech Arsenal

#### Core Stack — Systems & Backend
<p align="left">
  <img src="https://skillicons.dev/icons?i=rust" height="40" alt="Rust" />
  <img src="https://skillicons.dev/icons?i=python" height="40" alt="Python" />
  <img src="https://skillicons.dev/icons?i=cs" height="40" alt="C#" />
  <img src="https://skillicons.dev/icons?i=bash" height="40" alt="Bash" />
  <img src="https://skillicons.dev/icons?i=postgresql" height="40" alt="PostgreSQL" />
  <img src="https://skillicons.dev/icons?i=sqlite" height="40" alt="SQLite" />
  <img src="https://skillicons.dev/icons?i=redis" height="40" alt="Redis" />
</p>

#### Rust Ecosystem
<p align="left">
  <img src="https://img.shields.io/badge/Tokio-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Tokio" />
  <img src="https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=orange" alt="Axum" />
  <img src="https://img.shields.io/badge/Dioxus-000000?style=for-the-badge&logo=rust&logoColor=00C7B7" alt="Dioxus" />
  <img src="https://img.shields.io/badge/Serde-000000?style=for-the-badge&logo=rust&logoColor=dea584" alt="Serde" />
  <img src="https://img.shields.io/badge/WebAssembly-000000?style=for-the-badge&logo=webassembly&logoColor=654FF0" alt="WASM" />
</p>

#### AI / LLM Integration
<p align="left">
  <img src="https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/NVIDIA_NIM-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA NIM" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/SSE_Streaming-FF6F00?style=for-the-badge&logo=server-sent-events&logoColor=white" alt="SSE" />
</p>

#### Frontend & Design
<p align="left">
  <img src="https://skillicons.dev/icons?i=html" height="40" alt="HTML" />
  <img src="https://skillicons.dev/icons?i=css" height="40" alt="CSS" />
  <img src="https://skillicons.dev/icons?i=vue" height="40" alt="Vue.js" />
  <img src="https://skillicons.dev/icons?i=nuxt" height="40" alt="Nuxt.js" />
  <img src="https://skillicons.dev/icons?i=react" height="40" alt="React" />
  <img src="https://skillicons.dev/icons?i=angular" height="40" alt="Angular" />
  <img src="https://skillicons.dev/icons?i=wordpress" height="40" alt="WordPress" />
  <img src="https://skillicons.dev/icons?i=figma" height="40" alt="Figma" />
</p>

#### DevOps & Infrastructure
<p align="left">
  <img src="https://skillicons.dev/icons?i=docker" height="40" alt="Docker" />
  <img src="https://skillicons.dev/icons?i=podman" height="40" alt="Podman" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="Git" />
  <img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub" />
  <img src="https://skillicons.dev/icons?i=linux" height="40" alt="Linux" />
  <img src="https://skillicons.dev/icons?i=cloudflare" height="40" alt="Cloudflare" />
  <img src="https://skillicons.dev/icons?i=nginx" height="40" alt="NGINX" />
</p>

#### Multimedia & Design Tools
<p align="left">
  <img src="https://skillicons.dev/icons?i=ps" height="40" alt="Photoshop" />
  <img src="https://skillicons.dev/icons?i=ai" height="40" alt="Illustrator" />
  <img src="https://skillicons.dev/icons?i=pr" height="40" alt="Premiere Pro" />
  <img src="https://skillicons.dev/icons?i=ae" height="40" alt="After Effects" />
</p>

<br />

---

<!-- Featured Projects Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" alt="Rocket" width="30" /> Featured Projects

<!-- Project 1: NEXUS-AI-Gateway -->
<div align="center">
  <table>
    <tr>
      <td width="50%" valign="top">
        <h4 align="center">
          <a href="https://github.com/enerBydev/nexus-ai-gateway" target="_blank">
            <img src="https://img.shields.io/badge/NEXUS--AI--Gateway-e94560?style=for-the-badge&logo=github&logoColor=white" alt="NEXUS-AI-Gateway" />
          </a>
        </h4>
        <p align="center">
          <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=dea584" alt="Rust" />
          <img src="https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=orange" alt="Axum" />
          <img src="https://img.shields.io/badge/LLM_Proxy-000000?style=flat-square" alt="LLM Proxy" />
          <img src="https://img.shields.io/badge/Production_Ready-00C853?style=flat-square" alt="Production" />
        </p>
        <p>High-performance proxy server in <strong>Rust</strong> that intercepts and routes LLM API traffic (Claude, OpenAI) to alternative backends (<strong>NVIDIA NIM</strong>, <strong>Ollama</strong>). Features request transformation, intelligent retry logic, advanced concurrency with semaphores, SSE streaming, and circuit breaker patterns.</p>
        <p align="center">
          <a href="https://github.com/enerBydev/nexus-ai-gateway" target="_blank">
            <img src="https://img.shields.io/badge/View_Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" />
          </a>
        </p>
      </td>
      <td width="50%" valign="top">
        <h4 align="center">
          <a href="https://github.com/enerBydev/nexus-beacon-receiver" target="_blank">
            <img src="https://img.shields.io/badge/NEXUS_Beacon_Receiver-e94560?style=for-the-badge&logo=github&logoColor=white" alt="NEXUS Beacon Receiver" />
          </a>
        </h4>
        <p align="center">
          <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=dea584" alt="Rust" />
          <img src="https://img.shields.io/badge/Microservice-000000?style=flat-square" alt="Microservice" />
          <img src="https://img.shields.io/badge/Telemetry-000000?style=flat-square" alt="Telemetry" />
          <img src="https://img.shields.io/badge/D1_Database-000000?style=flat-square" alt="D1" />
        </p>
        <p>Microservice that receives daily telemetry beacons from <strong>NEXUS AI Gateway</strong> instances, stores them in a <strong>D1 database</strong>, and provides global statistics on usage patterns. Built for observability at scale.</p>
        <p align="center">
          <a href="https://github.com/enerBydev/nexus-beacon-receiver" target="_blank">
            <img src="https://img.shields.io/badge/View_Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" />
          </a>
        </p>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <h4 align="center">
          <a href="https://github.com/enerBydev/enerby-dev" target="_blank">
            <img src="https://img.shields.io/badge/enerBydev_Portfolio-e94560?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio" />
          </a>
        </h4>
        <p align="center">
          <img src="https://img.shields.io/badge/Vue.js-000000?style=flat-square&logo=vuedotjs&logoColor=4FC08D" alt="Vue" />
          <img src="https://img.shields.io/badge/Nuxt-000000?style=flat-square&logo=nuxtdotjs&logoColor=00DC82" alt="Nuxt" />
          <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square" alt="Portfolio" />
        </p>
        <p>Personal developer portfolio showcasing projects, professional history, completed and in-development works, and objectives. Built with modern frontend stack.</p>
        <p align="center">
          <a href="https://enerbydev.pages.dev" target="_blank">
            <img src="https://img.shields.io/badge/Live_Demo-e94560?style=flat-square&logo=cloudflarepages&logoColor=white" alt="Live" />
          </a>
          <a href="https://github.com/enerBydev/enerby-dev" target="_blank">
            <img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" />
          </a>
        </p>
      </td>
      <td width="50%" valign="top">
        <h4 align="center">
          <img src="https://img.shields.io/badge/Next_Project-Coming_Soon-333333?style=for-the-badge" alt="Coming Soon" />
        </h4>
        <p align="center">
          <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=dea584" alt="Rust" />
          <img src="https://img.shields.io/badge/AI_Integration-000000?style=flat-square" alt="AI" />
          <img src="https://img.shields.io/badge/Distributed_Systems-000000?style=flat-square" alt="Distributed" />
        </p>
        <p align="center"><em>Building something extraordinary.<br/>Stay tuned.</em></p>
      </td>
    </tr>
  </table>
</div>

<br />

---

<!-- Architecture & Patterns Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" alt="Gear" width="30" /> Architecture & Design Patterns

```
┌─────────────────────────────────────────────────────────────────┐
│                      SYSTEMS ARCHITECTURE                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐       │
│  │   LLM APIs   │───▶│ NEXUS-AI-    │───▶│   Backends   │       │
│  │Claude/OpenAI │    │   Gateway    │    │NVIDIA/OLLAMA │       │
│  └──────────────┘    └──────┬───────┘    └──────────────┘       │
│                             │                                    │
│                    ┌────────▼────────┐                           │
│                    │  Circuit Breaker │                           │
│                    │  Retry Logic    │                           │
│                    │  SSE Streaming   │                           │
│                    └────────┬────────┘                           │
│                             │                                    │
│                    ┌────────▼────────┐                           │
│                    │ Beacon Receiver │                           │
│                    │   Telemetry     │                           │
│                    │     D1 DB       │                           │
│                    └─────────────────┘                           │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│  PATTERNS: Proxy ◆ Circuit Breaker ◆ SSE ◆ Microservices       │
│            ◆ Async/Await ◆ Concurrency ◆ Fault Tolerance        │
└─────────────────────────────────────────────────────────────────┘
```

<br />

---

<!-- GitHub Stats Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Chart%20Increasing.png" alt="Stats" width="30" /> GitHub Analytics

<div align="center">
  <!-- GitHub Stats Card -->
  <img src="https://github-readme-stats.vercel.app/api?username=enerBydev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=e94560&icon_color=e94560&text_color=c9d1d9&count_private=true" height="165" alt="GitHub Stats" />
  <!-- Top Languages Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=enerBydev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=e94560&text_color=c9d1d9&langs_count=8" height="165" alt="Top Languages" />
</div>

<br />

<div align="center">
  <!-- Streak Stats -->
  <img src="https://streak-stats.demolab.com?user=enerBydev&theme=tokyonight&hide_border=true&background=0d1117&stroke=e94560&ring=e94560&fire=ff6b6b&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=c9d1d9&sideLabels=c9d1d9" alt="GitHub Streak" />
</div>

<br />

<div align="center">
  <!-- Trophy Stats -->
  <img src="https://github-profile-trophy.vercel.app/?username=enerBydev&theme=tokyonight&no-frame=true&margin-w=10&margin-h=10&column=7&bg_color=0d1117" alt="GitHub Trophies" width="100%" />
</div>

<br />

<div align="center">
  <!-- Activity Graph -->
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=enerBydev&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=e94560&line=e94560&point=ff6b6b" alt="Activity Graph" width="100%" />
</div>

<br />

---

<!-- Professional Experience Timeline -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Clipboard.png" alt="Experience" width="30" /> Professional Journey

```mermaid
timeline
    title Career Path
    2019 : Production Materials Handler
         : Security Systems Installation
    2020 : Web Designer · Data Entry
    2022 : Collection Executive · CRM
    2023 : Security & Multimedia Systems Tech
    2025 : FULLSTACK SOFTWARE ENGINEER
         : Rust & AI Specialist
         : NEXUS-AI-Gateway
```

<br />

---

<!-- Soft Skills Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Brain.png" alt="Brain" width="30" /> Competencies

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/Adaptability%20%26%20Fast%20Learning-e94560?style=for-the-badge&logo=fastapi&logoColor=white" alt="Adaptability" /><br/>
        <sub>Rapid context switching across tech stacks</sub>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Technical%20Troubleshooting-e94560?style=for-the-badge&logo=codecrafters&logoColor=white" alt="Troubleshooting" /><br/>
        <sub>From code to field diagnostics</sub>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Results--Oriented-e94560?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Results" /><br/>
        <sub>Shipping what matters</sub>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/Client%20Communication-e94560?style=for-the-badge&logo=microsoft-teams&logoColor=white" alt="Communication" /><br/>
        <sub>Technical translation for stakeholders</sub>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Time%20Management-e94560?style=for-the-badge&logo=clockify&logoColor=white" alt="Time Management" /><br/>
        <sub>Prioritization under pressure</sub>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Negotiation%20%26%20Leadership-e94560?style=for-the-badge&logo=handshake&logoColor=white" alt="Negotiation" /><br/>
        <sub>From fieldwork to boardroom</sub>
      </td>
    </tr>
  </table>
</div>

<br />

---

<!-- What I Bring Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Target.png" alt="Target" width="30" /> What I Bring to Your Team

| Dimension | Value |
|-----------|-------|
| **Systems Engineering** | Production-grade Rust applications with Tokio async runtime, memory-safe concurrency, and zero-cost abstractions |
| **AI Infrastructure** | Deep expertise in LLM API integration, proxy architectures, request transformation, and multi-backend routing |
| **Full-Stack Delivery** | End-to-end ownership from backend services to polished frontend interfaces |
| **Design Thinking** | Professional-grade UI/UX, branding, and multimedia production capabilities |
| **Operational Resilience** | Circuit breakers, retry logic, SSE streaming, fault-tolerant distributed patterns |
| **Cross-Domain Agility** | Unique blend of software engineering, technical systems, and business operations experience |

<br />

---

<!-- Currently Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" alt="Light Bulb" width="30" /> Currently

- 🔨 **Building:** [NEXUS-AI-Gateway](https://github.com/enerBydev/nexus-ai-gateway) — Enterprise-grade LLM proxy infrastructure
- 🦀 **Deepening:** Advanced Rust patterns — zero-copy parsing, lock-free data structures
- 🤖 **Exploring:** Multi-modal AI agents and autonomous system orchestration
- 🌐 **Open to:** Remote/hybrid opportunities — Fullstack · Backend · AI Infrastructure roles
- 📍 **Based in:** Nuevo Laredo, Mexico · Willing to relocate

<br />

---

<!-- Contact Section -->
### <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Telephone%20Receiver.png" alt="Contact" width="30" /> Let's Build Something

<div align="center">
  <p><em>"Great software is built by people who care about the craft."</em></p>

  <a href="mailto:rjmendoza.s@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Schedule%20a%20Call-e94560?style=for-the-badge&logo=google-meet&logoColor=white" alt="Schedule Call" />
  </a>
  <a href="https://linkedin.com/in/enerbydev" target="_blank">
    <img src="https://img.shields.io/badge/Send%20a%20Message-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Message" />
  </a>
  <a href="https://wa.me/528675712611" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp%20Direct-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
</div>

<br />

<!-- Tech Stack Summary Badges -->
<div align="center">
  <img src="https://img.shields.io/badge/Focus-Rust%20%7C%20AI%20%7C%20Systems-0d1117?style=flat-square&logoColor=e94560" alt="Focus" />
  <img src="https://img.shields.io/badge/Experience-Fullstack%20%7C%20DevOps%20%7C%20Design-0d1117?style=flat-square&logoColor=e94560" alt="Experience" />
  <img src="https://img.shields.io/badge/Mindset-Ship%20Fast.%20Ship%20Right.-0d1117?style=flat-square&logoColor=e94560" alt="Mindset" />
</div>

<br />

<!-- Animated Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=120&section=footer" width="100%" />
</div>

<!-- Signature -->
<div align="center">
  <sub>Built with precision by <strong>enerBydev</strong> · <em>Fearless concurrency. Zero compromises.</em></sub>
</div>
