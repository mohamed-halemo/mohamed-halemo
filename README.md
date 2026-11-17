<h1 align="center">Hi, I'm Mohamed Hafez 👋</h1>

<p align="center">
  <b>AI Researcher & Engineer · MASc Electrical and Computer Engineering @ Ontario Tech University</b><br>
  Efficient deep networks · Synthetic media & deepfakes · Trustworthy AI
</p>

<p align="center">
  <a href="https://mohamed-halemo-portfolio.vercel.app"><img src="https://img.shields.io/badge/Website-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/mohamed-abdelhalem-eng/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.youtube.com/@The-Mo-Lab"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="https://orcid.org/0009-0006-2415-7709"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://scholar.google.com/citations?user=FKvtaNQAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="mailto:mohamedabdelhalem.ns@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🧠 About me

- 🎓 **MASc in Electrical and Computer Engineering** at Ontario Tech University, in the **IoT Research Lab** with Prof. Khalid Elgazzar
- 🔬 I do AI research across **model efficiency**, **synthetic media**, and **trustworthy AI**
- 🛠️ I ship real systems too: LLM agents, RAG pipelines, APIs, and apps
- 🎥 I make short videos on how AI works on [The Mo Lab](https://www.youtube.com/@The-Mo-Lab)
- 🩺 Background in **Biomedical Engineering**: imaging, signal processing, and hardware

### 🔬 Research

| Area | Work |
|---|---|
| ⚡ **Efficient deep networks** | **LAGD-Net: Differentiable Block Gating for Depth Pruning of Residual Networks** *(in progress)*. Learned gates drop whole residual blocks during training: 14 of 33 blocks removed on CIFAR-10 ResNet-101, 1.63× faster at −0.17 points. |
| | **Block-selection benchmark for depth pruning** *(in progress)*. Which blocks to remove, and does it matter after fine-tuning? 8 architectures, 3 datasets, 740 runs. |
| 🎭 **Synthetic media & deepfakes** | **MOZAIC**: audio-video deepfake benchmark that tests *what* is fake (face, voice, or both). 137K clips, 1,000 identities, with Vector Institute. [Code](https://github.com/VectorInstitute/mozaic) |
| 🛡️ **Trustworthy AI** | **When Does Test-Time Augmentation Help Calibration?**  *VMV 2026*. [Paper](https://doi.org/10.2312/vmv20261020) · [Code](https://github.com/mustafaerensoyhan/uncertainty-tta-medmnist) |
| 🩺 **Medical AI** | **AI-based tool for early detection of Alzheimer's disease**. *Heliyon 2024*. 98.17% accuracy on ADNI. [Paper](https://doi.org/10.1016/j.heliyon.2024.e29375) · [Code](https://github.com/mohamed-halemo/Early-Alzheimer-s-Detection) · [Demo](https://mohamed-halemo.github.io/Early-Alzheimer-s-Detection/) |
| 🔐 **Medical data security** | **Smart Encryption: A Novel Hybrid Approach to Selectively Encrypt Medical Images**. *IEEE NoF 2025*. AES-256 on the heart ROI, ChaCha20 on the rest, 60–70% faster than full AES. [Paper](https://ieeexplore.ieee.org/abstract/document/11223323) · [Code](https://github.com/mohamed-halemo/Selective-Encryption) |

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**BrainAware: Early Alzheimer's Detection**](https://github.com/mohamed-halemo/Early-Alzheimer-s-Detection) | Classifies brain MRI into CN / MCI / AD (98.17% acc) + web app with 2D/3D viewer and patient history. *Heliyon 2024* · [Live demo](https://mohamed-halemo.github.io/Early-Alzheimer-s-Detection/) | TensorFlow, Django, React |
| [**MOZAIC**](https://github.com/VectorInstitute/mozaic) | Audio-video deepfake benchmark: 137K clips, 4-way labels (real/fake face × real/fake voice), 12 MLLMs + 5 detectors evaluated. With Vector Institute | Python, FaceFusion, Wan2.2, Seed-VC |
| [**When Does TTA Help Calibration?**](https://github.com/mustafaerensoyhan/uncertainty-tta-medmnist) | Test-time augmentation and calibration on 6 MedMNIST datasets, 3 backbones, 9 fusion methods. Entropy weighting cuts ECE by up to 41%. *VMV 2026* | PyTorch, MedMNIST |
| [**BioMed Lab**](https://mohamed-halemo.github.io/biomed-lab/) | 15 of my biomedical desktop apps rebuilt as browser tools: CT reconstruction, MRI viewer + 3D, ECG aliasing, Z-transform filter design, sequence alignment. [Try it](https://mohamed-halemo.github.io/biomed-lab/) · [Code](https://github.com/mohamed-halemo/biomed-lab) | React, TypeScript, Web Workers |
| [**Auto-Med-Agent**](https://github.com/mohamed-halemo/Auto-Med-Agent) | Generative AI research assistant: RAG over medical papers, PubMed and clinical-trial search tools, summaries, and question generation | Transformers, FAISS, Streamlit |
| [**AI Resume Screener**](https://github.com/mohamed-halemo/AI-Resume_Screener) | Parses resumes (local or Groq LLM), scores them against a job with spaCy + Sentence-BERT, and ranks applicants | FastAPI, PostgreSQL, Next.js |

<details>
<summary><b>More projects: imaging, signals, ML, and software</b></summary>
<br>

Most of the imaging, signal and bio projects below now run in the browser in [BioMed Lab](https://mohamed-halemo.github.io/biomed-lab/).

| Area | Projects |
|---|---|
| Medical imaging | [MRI Planes Viewer](https://github.com/mohamed-halemo/MRI-planes-viewer) · [Medical Image Rendering (VTK)](https://github.com/mohamed-halemo/Medical-images-rendering-VTK) · [Exudate Detection in Fundus Images](https://github.com/mohamed-halemo/Exudate-based-detection-in-fundus-images) · [Image Processing Tools from Scratch](https://github.com/mohamed-halemo/Image-processing-Tools-from-scratch) · [Cervical Spine Fracture (RSNA 2022)](https://github.com/mohamed-halemo/Cervical-Spine-Fracture-Detection) · [Trust in AI Retinal Screening (UI prototype)](https://github.com/mohamed-halemo/Trust-in-AI-Assisted-Retinal-Diagnosis_Static_Interface) |
| Signals and hardware | [Angry Birds Controlled by EMG (Arduino)](https://github.com/mohamed-halemo/Angry-birds-using-EMG-signal-Arduino) · [Digital Signal Processing Projects](https://github.com/mohamed-halemo/Digital-Signal-Processing-Projects) |
| ML and DL | [COVID-19 Prediction](https://github.com/mohamed-halemo/Covid_19_Prediction_ML) · [Machine Learning Models](https://github.com/mohamed-halemo/Machine-learning-models) · [Deep Learning Practice (AE, VAE, GANs)](https://github.com/mohamed-halemo/Deep_Learning_Practice) |
| Bioinformatics | [Sequence Alignment App (PyQt)](https://github.com/mohamed-halemo/Alignment_app) |
| Software | [Algorithms Toolbox](https://github.com/mohamed-halemo/Algorithms-Toolbox) · [Group Funding Website](https://github.com/mohamed-halemo/GroupFundingWebSiteProject) · [Secure Coding](https://github.com/mohamed-halemo/Secure_Coding) · [Smart Hospital Simulation](https://github.com/mohamed-halemo/Predictive-Task-Allocation-in-Smart-Hospitals-Using-Mobility-Aware-Edge-) |

</details>

### 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv,fastapi,docker,postgres,flutter,firebase,qt,git,linux,cpp,arduino&perline=15" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV, FastAPI, Docker, PostgreSQL, Flutter, Firebase, Qt, Git, Linux, C++, Arduino">
</p>

### 📈 GitHub activity

<p>
  <img src="https://streak-stats.demolab.com/?user=mohamed-halemo&theme=tokyonight&hide_border=true" alt="GitHub streak" height="165">
</p>
