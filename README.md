<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=header" width="100%">

<h1 align="center">
Hello <img src="https://raw.githubusercontent.com/avipatilpro/avipatilpro/master/Hi.gif" width="40"/> , I'm <b>Pappu Sunil Yadav</b>
</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9400D3&center=true&vCenter=true&width=900&lines=GenAI+%26+Machine+Learning+Engineer;LLMs+%7C+RAG+%7C+Multimodal+AI;Medical+AI+%7C+Document+Intelligence;Applied+AI+Engineer" />
</p>

<p align="center">
📍 India &nbsp; | &nbsp; 💼 Open to Remote GenAI / ML Opportunities
</p>

<!-- ===================== QUICK LINKS (BENTO STYLE) ===================== -->
<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="https://youtube.com/@pappuyadav-js3pq?si=gEMde-baJAv3ggG2" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https://www.youtube.com&subtitle=YouTube%20Demos&size=square">
      </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/pappu-yadav-3319ab289" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https://www.linkedin.com&subtitle=LinkedIn&size=square">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/revoker3661" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https://github.com&subtitle=GitHub&size=square">
      </a>
    </td>
  </tr>
</table>
</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=revoker3661&color=blueviolet&style=flat-square&label=Profile+Views">
</p>

---

<h2 align="center">🚀 About Me</h2>

<p align="center">
I am a <b>GenAI & Applied Machine Learning Engineer</b> focused on building <b>real-world, production-grade AI systems</b> rather than demo-only models.
<br><br>
My core expertise lies in <b>LLMs, Retrieval-Augmented Generation (RAG), multimodal AI, and document intelligence</b>, with a strong emphasis on system architecture — how data flows from raw sources to reliable, grounded AI outputs.
<br><br>
I enjoy working at the intersection of <b>ML engineering, GenAI system design, and practical deployment</b>, especially in high-impact domains like healthcare and medical AI.
</p>

---

<h2 align="center">🧠 Featured Projects</h2>

<h3>🔹 Multimodal Clinical RAG Assistant (Medical Text + Image)</h3>

<p>
<b>What it is:</b><br>
A doctor-assistive multimodal AI system that jointly understands <b>medical text, tables, diagrams, and patient images</b> to generate clinically grounded explanations using a multimodal LLM.
</p>

<ul>
<li><b>Architecture:</b> Dual-encoder retrieval using <b>MiniLM</b> for medical text/tables/JSONL entries and <b>OpenCLIP ViT-B/32</b> for diagrams and patient images.</li>
<li><b>Retrieval:</b> Hybrid multimodal search with <b>ChromaDB</b>, enabling cross-verification between symptoms, diagnosis text, and visual evidence.</li>
<li><b>Reasoning:</b> Dynamic prompt composition feeding retrieved text + images into <b>IDEFICS2-8B (4-bit)</b>.</li>
<li><b>Deployment:</b> Interactive <b>Streamlit UI</b> displaying matched visuals, source text, diagnosis, causes, and treatments in real time.</li>
</ul>

<p>
<b>Impact:</b><br>
• Achieved <b>100% text retrieval accuracy</b> and near-perfect image retrieval.<br>
• Significantly reduced hallucinations compared to text-only RAG systems.
</p>

<p>
🎥 Demo: <a href="https://youtube.com/@pappuyadav-js3pq?si=gEMde-baJAv3ggG2">YouTube Channel</a><br>
🔗 Repo: <a href="https://github.com/revoker3661/Multimodal-Clinical-RAG-Assistant-Medical-Text-Image-Retrieval-System-.git">GitHub</a>
</p>

---

<h3>🔹 AI Document Intelligence Pipeline (PDF → Structured JSONL)</h3>

<p>
Designed a high-accuracy document AI pipeline to convert <b>unstructured medical textbooks</b> into <b>structured JSONL datasets</b> optimized for RAG and multimodal LLMs.
</p>

<ul>
<li>Implemented document layout segmentation using <b>Detectron2 + PubLayNet</b>.</li>
<li>Engineered dual-stage table verification with <b>Microsoft Table Transformer (DETR)</b>.</li>
<li>Integrated <b>PaddleOCR</b> for extracting dense labels from scanned diagrams.</li>
<li>Generated spatially grounded metadata including bounding boxes and captions.</li>
</ul>

<p>
<b>Results:</b><br>
• Processed <b>500+ pages per book</b>, generating <b>40,000+ JSONL entries</b>.<br>
• Achieved <b>95% table extraction accuracy</b>.<br>
• Orchestrated on <b>NVIDIA L4 Cloud GPU</b>.
</p>

🔗 <a href="https://github.com/revoker3661/AI-Document-Intelligence-Pipeline-PDF-Structured-JSONL-for-Multimodal-RAG-.git">GitHub</a>

---

<h3>🔹 Pneumonia Detection Using Deep Learning (VGG19)</h3>

<p>
Built an automated pneumonia detection system using chest X-ray images to assist radiologists in early and accurate diagnosis.
</p>

<ul>
<li>Applied image preprocessing and augmentation using <b>ImageDataGenerator</b>.</li>
<li>Developed a transfer-learning pipeline with <b>VGG19</b> and custom dense layers.</li>
<li>Used <b>EarlyStopping</b> and <b>ReduceLROnPlateau</b> to prevent overfitting.</li>
</ul>

<p>
<b>Performance:</b> Achieved <b>92–97% accuracy</b> for NORMAL vs PNEUMONIA classification.
</p>

---

<h3>🔹 Personalized Medicine Recommendation System</h3>

<p>
Developed a symptom-based medical recommendation system that predicts diseases and provides actionable healthcare guidance.
</p>

<ul>
<li>Trained an <b>SVC classifier</b> achieving <b>100% test accuracy</b>.</li>
<li>Built a complete ML pipeline including feature encoding and model comparison.</li>
<li>Integrated medical knowledge modules for medications, diets, precautions, and workouts.</li>
<li>Delivered as a full <b>Flask web application</b> with dynamic UI.</li>
</ul>

---

<h3>🔹 Other Projects</h3>

<ul>
<li>Breast Cancer Classification (Neural Network)</li>
<li>Heart Disease Prediction (Logistic Regression)</li>
<li>Route Optimization System (A*) — Hackathon 2025</li>
<li>Women Safety App — Android + Firebase</li>
<li>Steganography Encryption System</li>
<li>RASA Tour Chatbot</li>
</ul>

---

<h2 align="center">🛠️ Tech Stack</h2>

<p align="center">
<b>Languages:</b> Python, SQL, C/C++<br>
<b>ML / DL:</b> TensorFlow, PyTorch, Scikit-learn<br>
<b>GenAI:</b> Hugging Face, LangChain, LangGraph, LLMs, RAG<br>
<b>Computer Vision & OCR:</b> OpenCV, Detectron2, PaddleOCR<br>
<b>Vector Databases:</b> ChromaDB<br>
<b>Deployment:</b> Flask, Streamlit, Docker<br>
<b>Infrastructure:</b> NVIDIA L4 GPU
</p>

---

<h2 align="center">📫 Let’s Connect</h2>

<p align="center">
📧 Email: <a href="mailto:yadavpappu3661@gmail.com">yadavpappu3661@gmail.com</a><br>
💼 LinkedIn: <a href="https://www.linkedin.com/in/pappu-yadav-3319ab289">linkedin.com/in/pappu-yadav-3319ab289</a><br>
💻 GitHub: <a href="https://github.com/revoker3661">github.com/revoker3661</a><br>
🎥 YouTube: <a href="https://youtube.com/@pappuyadav-js3pq?si=gEMde-baJAv3ggG2">youtube.com/@pappuyadav-js3pq</a>
</p>

---

<p align="center">
⭐️ Thanks for visiting — let’s build impactful GenAI systems together!
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=footer" width="100%">
