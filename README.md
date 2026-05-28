<!-- ============ ANIMATED HEADER ============ -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Rakesh%20Utekar&fontSize=52&fontColor=ffffff&animation=fadeIn" alt="header" />
</p>

<!-- ============ ANIMATED TYPING SUBTITLE ============ -->
<p align="center">
  <a href="https://github.com/rakeshutekar">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=640&lines=AI+Engineer+%E2%80%94+RAG+%C2%B7+LLMs+%C2%B7+Speech-to-Speech;Fine-tuning+open+LLMs+%28Qwen+2.5%29;Building+retrieval+pipelines+on+vector+DBs;Shipping+low-latency+real-time+audio+systems" alt="typing-svg" />
  </a>
</p>

<!-- ============ SOCIAL / CONTACT ============ -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rakeshutekar&label=Profile%20views&color=0e75b6&style=flat" alt="profile-views" />
  &nbsp;
  <a href="https://linkedin.com/in/rakesh-utekar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="https://github.com/rakeshutekar"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>
  <a href="mailto:rakeshutekar60@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
</p>

---

AI Engineer working across the stack on RAG, LLM fine-tuning, and real-time speech systems. My work has moved from computer-vision and speech models toward applied GenAI — fine-tuning open LLMs, building retrieval pipelines on vector DBs, and shipping low-latency audio workflows to cloud. Based in San Francisco, CA.

## Experience

- **AI Fund** — *Technical Builder / AI Engineer* (Dec 2025–present, Mountain View, CA)
- **Ditto AI** — *AI Engineer* (May–Dec 2025, Berkeley, CA)
- **JetskiAI** — *Founding AI/ML Engineer* (Mar–Dec 2025, SF Bay Area)
- **SuperIntro** — *AI Software Engineer* (Dec 2024–Apr 2025, SF) — Fine-tuned Qwen 2.5 LLM and Stable Diffusion pipelines on Vertex AI with LightRAG; deployed fine-tuned models on GCP with cloud logging and monitoring; integrated via Azure AI Foundry.
- **Sizzle** — *AI Engineer* (Jan–Mar 2025, SF) — Designed a low-latency Whisper + Qwen 2.5 + BERT workflow with Librosa/TorchAudio feature extraction; **+15% metadata-tagging precision**, **+20% acoustic-linguistic alignment**.
- **Melp App, Inc.** — *Software Developer (AI/ML)* (May–Jun 2025, SF Bay Area)
- **Seattle University** — *Research Assistant* (Aug 2024–Dec 2025, Seattle, WA) — Under Prof. Pejman Khadivi: fine-tune Transformers and CNNs for NLP and predictive analytics, with emphasis on automation and model deployment.
- **Seattle University** — *Teaching Assistant, Visual Analytics* (Mar–Jun 2024, Seattle, WA)
- **SlashRTC** — *Machine Learning Engineer* (Sep 2021–Aug 2022) / *ML Intern* (Jun–Aug 2021), Mumbai, India — Built Speech-to-Text models with Python and TensorFlow.

## Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### Real-Time Sign Language → Speech

**Problem:** Bridge communication for the deaf and hard-of-hearing by translating American Sign Language signs into spoken audio.

**Approach:** Fine-tune an I3D (Inflated 3D ConvNet) on the WLASL dataset for word-level sign recognition, piping predictions into a TTS stage. I3D captures spatiotemporal features across stacked video frames rather than treating frames independently, which suits the motion-heavy nature of signing.

**Stack:** PyTorch · I3D · WLASL · OpenCV

<a href="https://github.com/rakeshutekar/Sign-Language-to-Speech-Translation">View repo →</a>

</td>
<td width="50%" valign="top">

### Real-Time Speech → Speech Translation

**Problem:** Enable live cross-language conversation without the stop-and-wait of batch translation.

**Approach:** A streaming pipeline chains Whisper (ASR) → translation → OpenAI TTS, with audio streamed in and out continuously. It prioritizes low end-to-end latency by keeping the stages pipelined rather than processing each utterance as a discrete block.

**Stack:** Whisper · OpenAI TTS · Python · streaming audio I/O

<a href="https://github.com/rakeshutekar/Speech-To-Speech-Translation-real-time-">View repo →</a>

</td>
</tr>
</table>

## Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

**ML / Deep Learning**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/BERT-1E88E5?style=for-the-badge" />
</p>

**GenAI / LLM**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Qwen%202.5-615CED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stable%20Diffusion-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LightRAG-FF6F61?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-5A67D8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vector%20DBs-4B32C3?style=for-the-badge" />
</p>

**Speech / Audio · Vision**

<p>
  <img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Librosa-FF8800?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TorchAudio-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</p>

**Cloud / Infra**

<p>
  <img src="https://img.shields.io/badge/GCP%20%2F%20Vertex%20AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20AI%20Foundry-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

## 🤝 Open to Collaborate

I enjoy giving back to the AI/ML community and am always happy to:

- 🏆 **Judge** hackathons, demo days, and AI/ML competitions
- 🎤 **Give interviews, talks & guest sessions** on applied GenAI, RAG, and real-time speech
- 🧭 **Mentor & guide** engineers and students breaking into AI/ML
- 💡 **Consult & advise** on AI/ML product direction and architecture

📫 Reach me at **rakeshutekar60@gmail.com** or on [LinkedIn](https://linkedin.com/in/rakesh-utekar).

## 📊 GitHub Analytics

<!-- Stats & language cards are generated by the profile-summary-cards Action and
     served from the `profile-summary-card-output` branch of this repo — no
     dependency on rate-limited third-party instances. -->
<p align="center">
  <img width="98%" src="https://raw.githubusercontent.com/rakeshutekar/RakeshUtekar/profile-summary-card-output/tokyonight/0-profile-details.svg" alt="profile-details" />
</p>

<p align="center">
  <img width="49%" src="https://raw.githubusercontent.com/rakeshutekar/RakeshUtekar/profile-summary-card-output/tokyonight/3-stats.svg" alt="stats" />
  <img width="49%" src="https://raw.githubusercontent.com/rakeshutekar/RakeshUtekar/profile-summary-card-output/tokyonight/4-productive-time.svg" alt="productive-time" />
</p>

<p align="center">
  <img width="49%" src="https://raw.githubusercontent.com/rakeshutekar/RakeshUtekar/profile-summary-card-output/tokyonight/1-repos-per-language.svg" alt="repos-per-language" />
  <img width="49%" src="https://raw.githubusercontent.com/rakeshutekar/RakeshUtekar/profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="most-commit-language" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=rakeshutekar&hide_border=true&theme=tokyonight" alt="streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=rakeshutekar&theme=tokyo-night&hide_border=true&area=true" alt="activity-graph" />
</p>

<!-- PACMAN_GRAPH_PLACEHOLDER (wired in after the action generates + verifies the SVGs) -->

## Education

- **MS, Computer Science** (Data Science Specialization) — Seattle University (Sep 2022–Aug 2024)
- **BTech, Computer Engineering** — University of Mumbai (2016–2021)

<!-- ============ ANIMATED FOOTER ============ -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" alt="footer" />
</p>
