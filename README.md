<p align="center">
  <img src="assets/header.svg" alt="Prathmesh Pandya – Software Engineer · LLM Applications · Backend · Data" width="100%"/>
</p>

<p align="center">
  <a href="https://prathmesh-pandya.vercel.app"><img src="https://img.shields.io/badge/Portfolio-134e4a?style=flat&logo=vercel&logoColor=2dd4bf"/></a>
  <a href="mailto:ph.pandya1414@gmail.com"><img src="https://img.shields.io/badge/Email-ph.pandya1414%40gmail.com-0b1220?style=flat&logo=gmail&logoColor=2dd4bf&labelColor=0b1220&color=134e4a"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Regensburg%2C%20Germany-0b1220?style=flat&logo=googlemaps&logoColor=2dd4bf&labelColor=0b1220&color=134e4a"/>
  <img src="https://img.shields.io/badge/Status-open%20to%20internships-0b1220?style=flat&logo=checkmarx&logoColor=2dd4bf&labelColor=0b1220&color=134e4a"/>
</p>

<br/>

## `> whoami`

```python
class PrathmeshPandya:
    study     = "M.Sc. Computer Science @ TH Deggendorf"   # focus: AI & LLM systems, Security
    degree    = "B.E. Computer Science (AI/ML) · grade 1.4 (German scale)"
    based_in  = "Regensburg, Germany"
    focus     = ["LLM applications", "Backend", "Data"]
    building  = ["real-time voice AI", "multimodal RAG", "backend, data & test infrastructure"]
    open_to   = ["LLM applications", "agentic software pipelines", "data engineering"]   # internships
    languages = {"English": "C1", "German": "B1"}
```

I work on the part of AI **after the demo**: streaming, cancellation, latency budgets, failure cases and tests.

<br/>

## `> ls ./projects`

<!-- featured -->
<table>
  <tr>
    <td>
      <p>
        <img src="https://img.shields.io/badge/FEATURED-2dd4bf?style=flat-square&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/Real--time%20LLM%20service-0b1220?style=flat-square"/>
      </p>
      <h2>🎙️ AI Call Assistant</h2>
      <p>An <b>offline, real-time voice assistant that runs entirely on CPU</b>. Live audio streams through a FastAPI WebSocket backend into voice activity detection, streaming speech-to-text, a local LLM via an OpenAI-compatible API and sentence-level text-to-speech. Supports <b>barge-in</b>, <b>request cancellation</b> and ordered LLM/TTS streaming, and discloses that it is an AI while storing no audio.</p>
      <p>
        <img src="https://img.shields.io/badge/speech%20%E2%86%92%20transcript-~0.7%20s-134e4a?style=for-the-badge&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/first%20audio-2.0%E2%80%933.2%20s-134e4a?style=for-the-badge&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/pytest-41%20tests-134e4a?style=for-the-badge&labelColor=0b1220"/>
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-0b1220?style=flat-square&logo=python&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/FastAPI-0b1220?style=flat-square&logo=fastapi&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/WebSockets-0b1220?style=flat-square&logo=socketdotio&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/llama.cpp-0b1220?style=flat-square&logo=meta&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/Qwen3%20%2F%20Llama%203.2-0b1220?style=flat-square&logo=alibabacloud&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/sherpa--onnx-0b1220?style=flat-square&logo=onnx&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/Piper%20TTS-0b1220?style=flat-square&logo=audiomack&logoColor=2dd4bf"/>
        <img src="https://img.shields.io/badge/React%20%2B%20TS-0b1220?style=flat-square&logo=react&logoColor=2dd4bf"/>
      </p>
      <a href="https://github.com/prathmeshpandya/AI-Call-Assistant"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=for-the-badge&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
  </tr>
</table>

<!-- grid -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 Multimodal RAG over Technical Docs</h3>
      <p>Knowledge base over technical manuals that extracts <b>text, tables, diagrams and wiring schematics</b>, indexes embeddings and answers with a <b>vision-language model</b>.</p>
      <p><img src="https://img.shields.io/badge/benchmarked-text%20%C2%B7%20image%20%C2%B7%20hybrid%20retrieval-134e4a?style=flat-square&labelColor=0b1220"/></p>
      <p><code>OCR</code> <code>CLIP</code> <code>ViT</code> <code>FAISS</code> <code>Chroma</code> <code>VLMs</code></p>
      <img src="https://img.shields.io/badge/status-completed-2dd4bf?style=flat-square&labelColor=0b1220"/>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ GPU Image Processing in CUDA</h3>
      <p>Parallel <b>CUDA C++ kernels</b> for brightness, Gaussian blur and Sobel edge detection with a CMake build, <b>benchmarked against a CPU baseline</b>.</p>
      <p><img src="https://img.shields.io/badge/GPU%20vs%20CPU-benchmarked-134e4a?style=flat-square&labelColor=0b1220"/></p>
      <p><code>CUDA C++</code> <code>OpenCV</code> <code>CMake</code></p>
      <a href="https://github.com/prathmeshpandya/Real-Time-Image-Enhancement-with-CUDA---Parallel-Computing"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=flat-square&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 Real Estate Price Prediction API</h3>
      <p>Feature engineering and <b>cross-validated regression</b> for Bengaluru property prices, served through a <b>Flask REST API</b>.</p>
      <p><img src="https://img.shields.io/badge/R%C2%B2-0.79-134e4a?style=flat-square&labelColor=0b1220"/></p>
      <p><code>Pandas</code> <code>scikit-learn</code> <code>Flask</code></p>
      <a href="https://github.com/prathmeshpandya/Real-Estate-Price-Prediction"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=flat-square&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
    <td width="50%" valign="top">
      <h3>💳 Razorpay Payment Integration</h3>
      <p>Razorpay (<b>UPI, cards, net banking</b>) integrated into a <b>production Django app</b>, with webhook-based event handling and order verification.</p>
      <p><img src="https://img.shields.io/badge/payments-webhook%20verified-134e4a?style=flat-square&labelColor=0b1220"/></p>
      <p><code>Django</code> <code>REST</code> <code>Webhooks</code></p>
      <a href="https://github.com/prathmeshpandya/Razorpay-Integration"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=flat-square&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 E-commerce Insights Dashboard</h3>
      <p>Interactive <b>Power BI</b> dashboard turning e-commerce data into <b>KPIs and business insights</b>.</p>
      <p><code>Power BI</code> <code>data visualisation</code> <code>KPIs</code></p>
      <a href="https://github.com/prathmeshpandya/E-commerce_Insights_dashboard"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=flat-square&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
    <td width="50%" valign="top">
      <h3>📸 Best Photo Identifier</h3>
      <p>Hackathon build with team <b>Square Pants</b>: a Python tool that identifies the best photo from a set of similar shots.</p>
      <p><code>Python</code> <code>computer vision</code> <code>hackathon</code></p>
      <a href="https://github.com/prathmeshpandya/Best-Photo-Identifier"><img src="https://img.shields.io/badge/View%20code-%E2%86%92-2dd4bf?style=flat-square&logo=github&logoColor=white&labelColor=0b1220"/></a>
    </td>
  </tr>
</table>

<br/>

## `> cat research.md`

<table>
  <tr>
    <td>
      <p>
        <img src="https://img.shields.io/badge/RESEARCH%20PAPER-2dd4bf?style=flat-square&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/2026-0b1220?style=flat-square"/>
        <img src="https://img.shields.io/badge/Deggendorf%20Institute%20of%20Technology-0b1220?style=flat-square"/>
      </p>
      <h3>🔐 “Harvest Now, Decrypt Later”: Threat Modeling, Data Exposure Risk Classification and Organizational Prioritization Frameworks for the Post-Quantum Era</h3>
      <p>Adversaries can record encrypted traffic today and decrypt it once a cryptographically relevant quantum computer exists. The paper treats this as a <b>present-day threat</b> for any data that must stay confidential beyond Q-Day.</p>
      <ul>
        <li>🧭 <b>Threat model</b>: a two-phase HNDL model (collection today, decryption after Q-Day), with an <b>Exposure Window</b> metric <code>EW = max(0, Dm − TQ)</code>.</li>
        <li>🗂️ <b>Risk taxonomy</b>: five high-risk data categories (diplomatic, financial, healthcare and genomic, IP and R&amp;D, critical infrastructure credentials), ranked by confidentiality lifetime.</li>
        <li>🪜 <b>Three-tier migration framework</b>: immediate action (now–2026), strategic planning (2026–2029), compliance and hardening (2029–2033).</li>
        <li>📜 <b>Policy alignment</b>: maps the framework to NIST FIPS 203/204/205, NSA CNSA 2.0, NSM-10 and ENISA guidance.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/NIST-FIPS%20203%20%C2%B7%20204%20%C2%B7%20205-134e4a?style=flat-square&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/NSA-CNSA%202.0-134e4a?style=flat-square&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/topic-post--quantum%20cryptography-134e4a?style=flat-square&labelColor=0b1220"/>
        <img src="https://img.shields.io/badge/topic-threat%20modelling-134e4a?style=flat-square&labelColor=0b1220"/>
      </p>
      <a href="assets/HNDL-Research-Paper.pdf"><img src="https://img.shields.io/badge/Read%20the%20paper-PDF-2dd4bf?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=0b1220"/></a>
    </td>
  </tr>
</table>

<br/>

## `> stack --list`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,ts,mysql,fastapi,django,flask,react,git&perline=10&theme=dark" alt="Languages and frameworks"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,docker,linux,aws,github,githubactions,cmake&perline=10&theme=dark" alt="ML, infra and tooling"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CUDA%20C++-0b1220?style=flat&logo=nvidia&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/llama.cpp-0b1220?style=flat&logo=meta&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-0b1220?style=flat&logo=huggingface&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/Claude%20Code-0b1220?style=flat&logo=anthropic&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/RAG-0b1220?style=flat&logo=databricks&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/FAISS-0b1220?style=flat&logo=meta&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/Chroma-0b1220?style=flat&logo=googlecloud&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/WebSockets-0b1220?style=flat&logo=socketdotio&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/pytest-0b1220?style=flat&logo=pytest&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/Pandas-0b1220?style=flat&logo=pandas&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/NumPy-0b1220?style=flat&logo=numpy&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/Power%20BI-0b1220?style=flat&logo=powerbi&logoColor=2dd4bf"/>
  <img src="https://img.shields.io/badge/n8n-0b1220?style=flat&logo=n8n&logoColor=2dd4bf"/>
</p>

<br/>

## `> git log --stats`

<p align="center">
  <img width="98%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=prathmeshpandya&theme=github_dark" alt="Profile details"/>
</p>

<p align="center">
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=prathmeshpandya&theme=github_dark" alt="Stats"/>
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=prathmeshpandya&theme=github_dark" alt="Repos per language"/>
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=prathmeshpandya&theme=github_dark" alt="Most commit language"/>
</p>

<br/>

<p align="center">
  <sub><code>~/regensburg $ exit</code> &nbsp;·&nbsp; thanks for stopping by &nbsp;·&nbsp; <a href="https://prathmesh-pandya.vercel.app">Portfolio</a></sub>
</p>
