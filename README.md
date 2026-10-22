<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║  PROFILE BUILD: 0XMFBK / SECURITY RESEARCH LAB                              ║
║  Design language: midnight terminal · signal cyan · boundary lime           ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->

<p align="center">
  <img src="./assets/hero.svg" alt="Mustafa Bani Khalaf — Security Research Lab banner" width="100%" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/mustafabanikhalaf"><img src="https://img.shields.io/badge/CONNECT-LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="mailto:mustafabanikhalaf772@gmail.com"><img src="https://img.shields.io/badge/OPEN-A_CONVERSATION-67E8F9?style=for-the-badge&logo=minutemailer&logoColor=07111d" alt="Email Mustafa" /></a>
  <a href="https://reddit.com/user/0xmfbk"><img src="https://img.shields.io/badge/FOLLOW-0XMFBK-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit profile" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2600&pause=700&color=67E8F9&center=true&vCenter=true&repeat=true&width=800&height=34&lines=Offensive+Security+%2F+Runtime+Research;Container+Boundaries+%2F+Kernel-Level+Curiosity;DevSecOps+%2F+AI-Agentic+Automation;Observe+carefully.+Test+responsibly.+Document+clearly." alt="Rotating security research focus lines" />
</p>

> **I investigate the assumptions between systems.** The interesting failure is often not a single line of code — it is the boundary where an application, identity, runtime, infrastructure, and kernel expect different things from one another.

<p align="center">
  <img src="https://img.shields.io/badge/FOCUS-Offensive%20Security-67E8F9?style=flat-square" alt="Offensive Security" />
  <img src="https://img.shields.io/badge/RESEARCH-eBPF%20%2F%20Container%20Isolation-A3E635?style=flat-square" alt="eBPF and container isolation" />
  <img src="https://img.shields.io/badge/BUILDING-Security%20Tooling-E879F9?style=flat-square" alt="Security tooling" />
  <img src="https://img.shields.io/badge/TEACHING-CyberA4U-FBBF24?style=flat-square" alt="CyberA4U instructor" />
</p>

---

## `00 / SYSTEM IDENTITY`

```text
┌──(mustafa㉿research-lab)-[~]
└─$ whoami
   Mustafa Bani Khalaf

┌─$ mission
│  Turn security assumptions into testable questions.
│  Build tools that help people see system behavior more clearly.
│  Explore failure modes across application, infrastructure, and kernel boundaries.
└─$ current_mode
   researching · building · teaching · learning Rust
```

I'm a cybersecurity practitioner and **Cyber Security Instructor at CyberA4U**. My interests sit where offensive security meets infrastructure: understanding how systems behave under pressure, turning repeatable investigation into tooling, and connecting security work with automation.

### Quick navigation

| Sector | What you'll find |
|:--|:--|
| [`01 / Research map`](#01--research-map) | The boundaries that keep me curious |
| [`02 / Active builds`](#02--active-builds) | Current projects and research themes |
| [`03 / Collaboration signals`](#03--collaboration-signals) | What I'd like to build with others |
| [`04 / Field toolkit`](#04--field-toolkit) | Selected tools, languages, and the wider ecosystem |
| [`05 / GitHub telemetry`](#05--github-telemetry) | Public activity and repository signals |
| [`06 / Contact channel`](#06--contact-channel) | Where to reach me |

---

## `01 / RESEARCH MAP`

<p align="center">
  <img src="./assets/boundary-map.svg" alt="Conceptual map of application, identity, infrastructure, container runtime, and kernel/eBPF trust boundaries" width="100%" />
</p>

### The questions behind the work

- **Runtime & container security** — where do isolation assumptions meet real runtime behavior?
- **Kernel-level research** — how do low-level mechanisms shape the security properties above them?
- **Offensive security tooling** — how can investigation become more repeatable, observable, and useful?
- **DevSecOps & infrastructure hardening** — how do we make security part of the pipeline instead of a late-stage surprise?
- **AI-agentic automation** — how can agents help with vulnerability discovery while keeping the workflow measurable and human-reviewable?

My mental model is simple: **map the boundary, state the assumption, test the assumption, document what happened.** A finding is more useful when someone else can understand the conditions that produced it.

---

## `02 / ACTIVE BUILDS`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⌁ eBPF Container Escape Framework</h3>
      <p><code>RUNTIME SECURITY / CONTAINER BOUNDARIES</code></p>
      <p>A current build exploring the seam between container isolation, runtime behavior, and the Linux kernel. The goal is to make low-level security questions concrete enough to investigate and validate in controlled environments.</p>
      <p><img src="https://img.shields.io/badge/STATE-ACTIVE%20RESEARCH-A3E635?style=flat-square" alt="Active research" /> <img src="https://img.shields.io/badge/LAYER-eBPF%20%2B%20KERNEL-67E8F9?style=flat-square" alt="eBPF and kernel" /></p>
    </td>
    <td width="50%" valign="top">
      <h3>⌁ SecureSK-20</h3>
      <p><code>SECURITY PROJECT / ITERATIVE DEVELOPMENT</code></p>
      <p>A second project in my current workbench. I'm keeping this profile-level description intentionally high-level rather than inventing implementation details that should be established by the project itself.</p>
      <p><img src="https://img.shields.io/badge/STATE-IN%20PROGRESS-A3E635?style=flat-square" alt="In progress" /> <img src="https://img.shields.io/badge/NOTES-EVOLVING-E879F9?style=flat-square" alt="Notes evolving" /></p>
    </td>
  </tr>
</table>

### Build principles

| Principle | What it means in practice |
|:--|:--|
| **Evidence over vibes** | Make the hypothesis explicit; gather signals that can support or challenge it. |
| **Boundaries before payloads** | Understand the trust model and execution context before testing a failure mode. |
| **Reproducibility matters** | Prefer a repeatable test case over a dramatic but unexplained result. |
| **Automation with inspection** | Reduce repetitive work without making the reasoning invisible. |
| **Responsible research** | Work in authorized, controlled environments and communicate limitations clearly. |

---

## `03 / COLLABORATION SIGNALS`

I'm especially interested in collaborating with people building at the intersection of:

<details>
  <summary><strong>Signal A — Offensive security tooling</strong></summary>
  <p>Practical tools that improve reconnaissance, validation, analysis, or reporting — with clear scope and outputs that another researcher can reason about.</p>
</details>

<details>
  <summary><strong>Signal B — DevSecOps & infrastructure</strong></summary>
  <p>Security checks that fit into real delivery workflows, infrastructure hardening, observability, and useful feedback loops between development and security.</p>
</details>

<details>
  <summary><strong>Signal C — AI agents for vulnerability discovery</strong></summary>
  <p>Ways to scale investigative workflows with agents while preserving traceability, evaluation, human oversight, and safe testing boundaries.</p>
</details>

<details>
  <summary><strong>Signal D — Kernel and runtime exploration</strong></summary>
  <p>Technical discussions around Linux internals, eBPF runtime security, container isolation, and the gap between a security model and what actually executes.</p>
</details>

**What I'm learning now:** Rust for security tooling, with a deeper dive into eBPF runtime security.

**What you can ask me about:** Web application penetration testing, infrastructure hardening, Splunk, and cybersecurity education.

---

## `04 / FIELD TOOLKIT`

The badges below are a **tool and technology inventory**, not a claim that every item has the same depth of experience. The visible set emphasizes the themes closest to my current work; the broader ecosystem is grouped into expandable sections so the profile stays navigable.

### Current signal set

![eBPF](https://img.shields.io/badge/eBPF-5B5BD6?style=flat-square&logo=linux&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=FFD43B) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Splunk](https://img.shields.io/badge/Splunk-111827?style=flat-square&logo=splunk&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Languages & low-level building blocks

![AssemblyScript](https://img.shields.io/badge/AssemblyScript-007AAC?style=flat-square&logo=assemblyscript&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Apache Groovy](https://img.shields.io/badge/Apache%20Groovy-4298B8?style=flat-square&logo=apachegroovy&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) ![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white) ![Markdown](https://img.shields.io/badge/Markdown-111827?style=flat-square&logo=markdown&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![Perl](https://img.shields.io/badge/Perl-394057?style=flat-square&logo=perl&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=FFD43B) ![Bash Script](https://img.shields.io/badge/Bash%20Script-121011?style=flat-square&logo=gnubash&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-4D4D4D?style=flat-square&logo=windowsterminal&logoColor=white)

<details>
  <summary><strong>Web engineering, frameworks & APIs</strong> — expand toolkit</summary>

  ![AngularJS](https://img.shields.io/badge/AngularJS-E23237?style=flat-square&logo=angularjs&logoColor=white) ![Astro](https://img.shields.io/badge/Astro-232052?style=flat-square&logo=astro&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-8511FA?style=flat-square&logo=bootstrap&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-111827?style=flat-square&logo=bun&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-111827?style=flat-square&logo=expo&logoColor=white) ![Framework7](https://img.shields.io/badge/Framework7-EE350F?style=flat-square&logo=framework7&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-111827?style=flat-square&logo=flask&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-111827?style=flat-square&logo=fastify&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=61DAFB) ![Grav](https://img.shields.io/badge/Grav-FFFFFF?style=flat-square&logo=grav&logoColor=221E1F) ![JWT](https://img.shields.io/badge/JWT-111827?style=flat-square&logo=jsonwebtokens&logoColor=white) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white) ![Joomla](https://img.shields.io/badge/Joomla-5091CD?style=flat-square&logo=joomla&logoColor=white) ![Jinja](https://img.shields.io/badge/Jinja-FFFFFF?style=flat-square&logo=jinja&logoColor=111827) ![Jasmine](https://img.shields.io/badge/Jasmine-8A4182?style=flat-square&logo=jasmine&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Nodemon](https://img.shields.io/badge/Nodemon-323330?style=flat-square&logo=nodemon&logoColor=white) ![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white) ![pnpm](https://img.shields.io/badge/pnpm-4A4A4A?style=flat-square&logo=pnpm&logoColor=F69220) ![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=flat-square&logo=p5dotjs&logoColor=white) ![Radix UI](https://img.shields.io/badge/Radix%20UI-161618?style=flat-square&logo=radixui&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Query](https://img.shields.io/badge/React%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white) ![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white) ![Redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-111827?style=flat-square&logo=socketdotio&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-111827?style=flat-square&logo=threedotjs&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white) ![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=111827) ![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=flat-square&logo=web3dotjs&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-117AC9?style=flat-square&logo=wordpress&logoColor=white) ![Xamarin](https://img.shields.io/badge/Xamarin-3199DC?style=flat-square&logo=xamarin&logoColor=white) ![Yarn](https://img.shields.io/badge/Yarn-2C8EBB?style=flat-square&logo=yarn&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)

</details>

<details>
  <summary><strong>Cloud, systems & infrastructure</strong> — expand toolkit</summary>

  ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-111827?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=111827) ![OpenStack](https://img.shields.io/badge/OpenStack-F01742?style=flat-square&logo=openstack&logoColor=white) ![Alibaba Cloud](https://img.shields.io/badge/Alibaba%20Cloud-FF6701?style=flat-square&logo=alibabacloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Apache](https://img.shields.io/badge/Apache-D42029?style=flat-square&logo=apache&logoColor=white) ![Cisco](https://img.shields.io/badge/Cisco-049FD9?style=flat-square&logo=cisco&logoColor=111827) ![TOR](https://img.shields.io/badge/TOR-7E4798?style=flat-square&logo=torproject&logoColor=white) ![XFCE](https://img.shields.io/badge/XFCE-2284F2?style=flat-square&logo=xfce&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![Zigbee](https://img.shields.io/badge/Zigbee-EB0443?style=flat-square&logo=zigbee&logoColor=white)

</details>

<details>
  <summary><strong>Data platforms & storage</strong> — expand toolkit</summary>

  ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-111827?style=flat-square&logo=apachekafka&logoColor=white) ![Apache Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=111827) ![Apache Hive](https://img.shields.io/badge/Apache%20Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=111827) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![ArangoDB](https://img.shields.io/badge/ArangoDB-DDE072?style=flat-square&logo=arangodb&logoColor=111827) ![Apache Cassandra](https://img.shields.io/badge/Apache%20Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white) ![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Amazon DynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=flat-square&logo=cratedb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Realm](https://img.shields.io/badge/Realm-39477F?style=flat-square&logo=realm&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=111827) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=111827)

</details>

<details>
  <summary><strong>Delivery, observability & collaboration</strong> — expand toolkit</summary>

  ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=flat-square&logo=apacheant&logoColor=white) ![Apache Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) ![Apache Tomcat](https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=111827) ![Gunicorn](https://img.shields.io/badge/Gunicorn-298729?style=flat-square&logo=gunicorn&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-181717?style=flat-square&logo=gitlab&logoColor=white) ![Gitee](https://img.shields.io/badge/Gitee-C71D23?style=flat-square&logo=gitee&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-181717?style=flat-square&logo=gitlab&logoColor=white) ![CloudBees](https://img.shields.io/badge/CloudBees-1997B5?style=flat-square&logo=cloudbees&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Crowdin](https://img.shields.io/badge/Crowdin-2E3340?style=flat-square&logo=crowdin&logoColor=white) ![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=flat-square&logo=babel&logoColor=111827) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-111827?style=flat-square&logo=notion&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=111827) ![Splunk](https://img.shields.io/badge/Splunk-111827?style=flat-square&logo=splunk&logoColor=white)

</details>

<details>
  <summary><strong>Design, creative tools & wider ecosystem</strong> — expand toolkit</summary>

  ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Sketch](https://img.shields.io/badge/Sketch-F7B500?style=flat-square&logo=sketch&logoColor=111827) ![Adobe](https://img.shields.io/badge/Adobe-FF0000?style=flat-square&logo=adobe&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square&logo=canva&logoColor=111827) ![Krita](https://img.shields.io/badge/Krita-203759?style=flat-square&logo=krita&logoColor=EEF37B) ![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white) ![Meta](https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white) ![Plex](https://img.shields.io/badge/Plex-E5A00D?style=flat-square&logo=plex&logoColor=111827) ![Uber](https://img.shields.io/badge/Uber-111827?style=flat-square&logo=uber&logoColor=white) ![AMD](https://img.shields.io/badge/AMD-111827?style=flat-square&logo=amd&logoColor=white) ![Epic Games](https://img.shields.io/badge/Epic%20Games-313131?style=flat-square&logo=epicgames&logoColor=white) ![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=111827) ![itch.io](https://img.shields.io/badge/itch.io-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white) ![Steam](https://img.shields.io/badge/Steam-111827?style=flat-square&logo=steam&logoColor=white) ![Xbox](https://img.shields.io/badge/Xbox-107C10?style=flat-square&logo=xbox&logoColor=white)
  ![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=firefox&logoColor=FF7139)

</details>

---

## `05 / GITHUB TELEMETRY`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=0xmfbk&show_icons=true&hide_border=true&bg_color=0D1117&title_color=67E8F9&text_color=C9D1D9&icon_color=A3E635&include_all_commits=true" alt="GitHub overview statistics for 0xmfbk" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xmfbk&layout=compact&hide_border=true&bg_color=0D1117&title_color=67E8F9&text_color=C9D1D9&langs_count=8" alt="Most used public languages for 0xmfbk" />
</p>

<p align="center">
  <img width="72%" src="https://streak-stats.demolab.com?user=0xmfbk&hide_border=true&background=0D1117&ring=67E8F9&fire=A3E635&currStreakLabel=67E8F9&sideLabels=C9D1D9&dates=64748B&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="GitHub contribution streak for 0xmfbk" />
</p>

<p align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=0xmfbk&bg_color=0d1117&color=c9d1d9&line=67e8f9&point=a3e635&area=true&hide_border=true" alt="GitHub contribution activity graph for 0xmfbk" />
</p>

<p align="center">
  <img width="96%" src="https://github-profile-trophy.vercel.app/?username=0xmfbk&theme=onestar&no-frame=true&no-bg=true&margin-w=8&column=6" alt="GitHub profile trophies for 0xmfbk" />
</p>

<sub>Telemetry widgets are provided by external community services. Their availability, theme rendering, and reported numbers can vary; GitHub remains the source of truth for repository activity.</sub>

---

## `06 / CONTACT CHANNEL`

<p align="center">
  <strong>Have a hypothesis worth testing, a useful tool to build, or a security problem that needs careful thinking?</strong><br />
  Let's compare notes.
</p>

<p align="center">
  <a href="mailto:mustafabanikhalaf772@gmail.com"><img src="https://img.shields.io/badge/EMAIL-mustafabanikhalaf772%40gmail.com-67E8F9?style=for-the-badge&logo=gmail&logoColor=07111d" alt="Email Mustafa" /></a>
  <a href="https://linkedin.com/in/mustafabanikhalaf"><img src="https://img.shields.io/badge/LINKEDIN-LET'S_CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://reddit.com/user/0xmfbk"><img src="https://img.shields.io/badge/REDDIT-0XMFBK-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit" /></a>
</p>

### Support the work

If you'd like to support future experiments and learning, the original profile included these channels:

<p>
  <a href="https://paypal.me/MUSTAFABANIKHALAF"><img src="https://img.shields.io/badge/PayPal-Support%20the%20work-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal" /></a>
  <a href="https://ko-fi.com/0xmfbk"><img src="https://img.shields.io/badge/Ko--fi-Buy%20me%20a%20coffee-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=0xmfbk&style=flat-square&color=0e7490&label=PROFILE%20SIGNALS" alt="Profile view counter" />
</p>

<p align="center">
  <sub>Built with curiosity. Tested with care. Shared with context.</sub><br />
  <sub><code>END OF TRANSMISSION // 0XMFBK</code></sub>
</p>
