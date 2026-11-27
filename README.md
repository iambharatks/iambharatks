<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Bharat Kumar Sharma — Backend & AI Engineer" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/iambharatks">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2DD4BF&center=true&vCenter=true&width=640&lines=Software+Engineer+%40+Gartner;Building+multi-agent+systems+with+LangGraph+%2B+MCP;Production+RAG+%C2%B7+LLMs+%C2%B7+Vector+DBs;Serverless+data+pipelines+on+AWS;Google+Code+Jam+%E2%80%94+All+India+Rank+40" alt="Typing headline" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/iambharatks"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/iambharatks/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="https://codeforces.com/profile/bharatks"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="https://medium.com/@iambharatks"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:iambharatks@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <!-- Add once you host your resume (e.g. a Google Drive / GitHub Pages link):
  <a href="RESUME_URL"><img src="https://img.shields.io/badge/Resume-2DD4BF?style=for-the-badge&logo=readdotcv&logoColor=black" alt="Resume" /></a>
  -->
</p>

---

## 👋 About Me

I'm a **Backend & AI Engineer** with **3+ years** of experience shipping production systems on **AWS**: serverless data pipelines, high-throughput APIs, and **Generative AI** applications that real teams use every day.

- ⚡ **Currently:** Software Engineer at **Gartner**, building config-driven ETL platforms, agentic retrieval systems, and observability pipelines
- 🤖 **Focus:** Agentic AI (LangGraph, MCP, Bedrock AgentCore), RAG, and running LLM systems reliably in production
- 🌱 **Leveling up in:** LLM evaluation (Ragas, DeepEval), LLM observability (Langfuse, OpenTelemetry), and AIOps
- 🏆 **Competitive programmer:** Google Code Jam **All India Rank 40**
- 📍 Gurugram, India · open to **AI Engineer / AIOps** conversations

---

## 🚀 Production Highlights

> Work projects (proprietary, so no public repos). Ask me about the architecture.

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What I built</th>
    <th align="left">Impact</th>
  </tr>
  <tr>
    <td><b>🤖 Agentic Retrieval</b><br/><sub>Gartner</sub></td>
    <td>Multi-agent workflows with <b>LangGraph + MCP</b>; agentic retrieval over S3 data with <b>AWS Bedrock AgentCore</b></td>
    <td><b>40%</b> faster lookups for 25+ internal users</td>
  </tr>
  <tr>
    <td><b>🔄 GDX: G-DataXpress</b><br/><sub>Gartner</sub></td>
    <td>Config-driven ETL framework on <b>AWS Lambda / PySpark</b> with bidirectional DB ↔ Salesforce sync and a DAG engine using Kahn's topological sort</td>
    <td>Integrations in <b>hours instead of 1–2 months</b> · 45+ mappings · 4+ teams · <b>35%</b> fewer false alerts</td>
  </tr>
  <tr>
    <td><b>🔎 EventSearch</b><br/><sub>Gartner</sub></td>
    <td>Event diagnostics platform: <b>FastAPI + React</b>, Redis cluster cache, SSE streaming, DynamoDB, deployed on <b>EKS</b></td>
    <td>20–40 min investigations down to <b>&lt;100 ms</b> lookups · <b>~800×</b> cheaper than Athena</td>
  </tr>
  <tr>
    <td><b>📡 Observability Pipeline</b><br/><sub>Gartner</sub></td>
    <td>Streaming pipeline: CloudWatch → <b>Kinesis Firehose</b> → Lambda → <b>Apache Iceberg</b> on S3 → Athena</td>
    <td>MTTD <b>45 → 10 min</b> · removed ~$2/query Insights costs</td>
  </tr>
  <tr>
    <td><b>💬 SRE RAG Chatbot</b><br/><sub>Infosys</sub></td>
    <td><b>Mistral-7B</b> with <b>Milvus + Qdrant</b>, plus automated chunking and embedding pipelines over enterprise data</td>
    <td><b>200%</b> higher throughput via FastAPI optimizations</td>
  </tr>
  <tr>
    <td><b>📄 Document AI</b><br/><sub>Infosys</sub></td>
    <td>Extraction from images and PDFs with <b>YOLOv8</b>, PyMuPDF, Tesseract / EasyOCR</td>
    <td><b>200+ hrs/week</b> of manual entry removed · <b>95%+</b> accuracy</td>
  </tr>
</table>

---

## 🛠️ Open-Source Projects

<table>
  <tr>
    <td width="55%" valign="top">
      <a href="https://iambharatks.github.io/ryuk/"><img src="https://github.com/iambharatks/ryuk/raw/HEAD/docs/screenshots/gaze.png" alt="Ryuk dashboard" width="100%" /></a>
    </td>
    <td valign="top">
      <h3>📓 <a href="https://github.com/iambharatks/ryuk">Ryuk</a></h3>
      <i>Write your life one line at a time. An LLM turns it into data.</i>
      <br/><br/>
      🧠 Free text from Telegram becomes typed rows via <b>Gemini</b> with JSON-schema output, validation and model fallback<br/>
      🔒 Privacy by design: bank SMS and health data are parsed by <b>regex</b> and never sent to the LLM<br/>
      🔑 Passkeys (WebAuthn) on the web and a <b>Secure Enclave</b> key in the iOS app<br/>
      ☁️ Two <b>Cloudflare Workers</b> + D1 + R2, costing <b>₹0/month</b>
      <br/><br/>
      <a href="https://iambharatks.github.io/ryuk/"><img src="https://img.shields.io/badge/▶%20Live%20demo-2DD4BF?style=for-the-badge&logoColor=black" alt="Live demo" /></a>
      <a href="https://github.com/iambharatks/ryuk"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code" /></a>
      <br/><sub>TypeScript · React · Cloudflare Workers · D1 · R2 · Gemini · Capacitor/Swift</sub>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <b>📚 <a href="https://github.com/iambharatks/almanac">Almanac</a></b> · My engineering almanac: notes on <b>backend, system design, DSA and competitive programming</b>. Learning in public.
      &nbsp;<a href="https://github.com/iambharatks/almanac"><img src="https://img.shields.io/badge/Read%20notes-181717?style=flat-square&logo=github&logoColor=white" alt="Read notes" /></a>
    </td>
  </tr>
</table>

---

## 🧰 Tech Stack

**🤖 AI & GenAI**<br/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" />
<img src="https://img.shields.io/badge/Bedrock%20AgentCore-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/LlamaIndex-6B46C1?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-2DD4BF?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white" />

**⚙️ Languages, Backend & Data**<br/>
<img src="https://skillicons.dev/icons?i=python,rust,java,cpp,ts,js,fastapi,spring,react,graphql,postgres,mysql,mongodb,redis&perline=14" alt="Languages and backend" />

**☁️ Cloud & Infrastructure**<br/>
<img src="https://skillicons.dev/icons?i=aws,cloudflare,terraform,docker,kubernetes,githubactions,git,linux&perline=14" alt="Cloud and infrastructure" />

<details>
<summary><b>More: AWS services, data engineering & others</b></summary>
<br/>

| Area | Tools |
|---|---|
| **AWS** | Lambda · S3 · EventBridge · DynamoDB · Athena · Glue · CloudWatch · Kinesis Firehose · EKS · CDK |
| **Data Engineering** | PySpark · ETL pipelines · Apache Iceberg · DAG orchestration · Event streaming (SSE) |
| **Architecture** | Microservices · Serverless · REST · GraphQL |
| **Computer Vision / Doc AI** | YOLOv8 · PyMuPDF · Tesseract · EasyOCR |
| **Mobile** | Flutter · Dart |

</details>

---

## 🏆 Achievements

| Contest | Result |
|---|---|
| 🥇 **Google Code Jam 2022** (Qualification) | **All India Rank 40** · Global Rank 725 |
| 🔵 **Google Kickstart** (Round A) | All India Rank 890 · Global Rank 1294 |
| 🟦 **Meta Hacker Cup 2022** (Rounds 1 & 2) | All India Rank &lt; 1000 |
| 🟢 **GeeksforGeeks Job-A-Thon** 5 & 7 | Global Rank **70** & **93** |
| 🟤 **CodeChef** contests | Global Rank 196 & 346 |

<p align="center">
  <a href="https://leetcode.com/u/iambharatks/"><img src="https://leetcard.jacoblin.cool/iambharatks?theme=dark&font=Fira%20Code&ext=contest" alt="LeetCode stats" height="180" /></a>
  <a href="https://codeforces.com/profile/bharatks"><img src="https://codeforces-readme-stats.vercel.app/api/card?username=bharatks&theme=github_dark&disable_animations=false&force_username=true" alt="Codeforces stats" height="180" /></a>
</p>

---

## ✍️ Latest Writing

<!-- Updated automatically every day by .github/workflows/blog-posts.yml -->
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

➡️ [More on Medium](https://medium.com/@iambharatks)

---

<details>
<summary><b>📊 GitHub Stats</b></summary>
<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=iambharatks&show_icons=true&include_all_commits=true&theme=github_dark&hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api?username=iambharatks&show_icons=true&include_all_commits=true&theme=default&hide_border=true" alt="GitHub stats" height="165" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=iambharatks&layout=compact&theme=github_dark&hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iambharatks&layout=compact&theme=default&hide_border=true" alt="Top languages" height="165" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=iambharatks&theme=github-dark-blue&hide_border=true" />
    <img src="https://streak-stats.demolab.com/?user=iambharatks&theme=default&hide_border=true" alt="GitHub streak" />
  </picture>
</p>

</details>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iambharatks/iambharatks/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iambharatks/iambharatks/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/iambharatks/iambharatks/output/github-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="" />
</p>
