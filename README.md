<div align="center">
  <a href="https://ritwik389.github.io/portfolio/"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/header.svg?v=4" width="100%" alt="Ritwik Jain. Machine learning research at DTU: vision-language models, speech separation and interpretability." /></a>
  <p>
    <strong>IT student at Delhi Technological University working on machine learning research.</strong><br />
    Mostly vision-language models and speech separation, plus full projects built around them.<br />
    <sub>B.Tech IT · GPA <strong>9.40</strong> · AI/ML intern at Deloitte, summer 2026</sub>
  </p>
  <p>
    <a href="https://ritwik389.github.io/portfolio/"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/portfolio-button.svg?v=4" width="110" height="30" alt="Visit my portfolio" /></a>
    <a href="https://ritwik389.github.io/portfolio/Ritwik_Jain_Resume.pdf"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/resume-button.svg?v=4" width="100" height="30" alt="Download my résumé" /></a>
    <a href="https://www.linkedin.com/in/ritwikjain0803/"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/linkedin-button.svg?v=4" width="110" height="30" alt="Connect on LinkedIn" /></a>
    <a href="mailto:ritwik8march@gmail.com"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/email-button.svg?v=4" width="88" height="30" alt="Contact me by email" /></a>
  </p>
</div>

## Research

**Reasoning segmentation for SAR sea-ice imagery** · *paper in preparation*<br />
Can a vision-language model take a text prompt and segment the right ice in a satellite radar image, including small, scattered floes? I benchmarked 7 language-guided segmentation models, fine-tuned 3B VLMs with GRPO, and built an evaluation protocol with per-class metrics and bootstrap confidence intervals. Now I'm designing an RL reward for the scattered targets existing models miss.

**[Feature drift under domain fine-tuning](https://github.com/Ritwik389/Mechanistic-Interpretability)** · *independent study*<br />
TopK sparse autoencoders on Pythia-160M before and after fine-tuning on Python code, with features matched by cosine similarity and the Hungarian algorithm to separate expected drift from collateral drift.

## Featured · Jensen Huang Digital Twin

A Jensen Huang chatbot that answers in his voice, with sources. Streamed replies, zero-shot voice cloning, and a clickable map of the ideas behind each answer.

[![Jensen's World: a clickable knowledge graph showing CUDA, accelerated computing, digital twins, and source evidence](https://raw.githubusercontent.com/Ritwik389/digital-twin/main/docs/images/jensen-map.jpg)](https://rj8307-digital-twin-2.hf.space)

- **Retrieval:** Chroma semantic search and bounded Neo4j graph paths feed a cross-encoder reranker with era-aware filtering.
- **Evaluation:** a 50-question labelled set with era limits, unanswerable and misleading-premise cases. Reranking took Recall@5 from **33.3% to 47.2%** and MRR@5 from **0.248 to 0.394**, at a 1.35 s median latency cost.
- **Voice:** sentence-by-sentence Pocket TTS with zero-shot voice cloning, streaming text and cancellable replies.

<p>
  <a href="https://rj8307-digital-twin-2.hf.space"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/demo-button.svg?v=4" width="108" height="30" alt="Try the live demo" /></a>
  <a href="https://github.com/Ritwik389/digital-twin"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/source-button.svg?v=4" width="116" height="30" alt="View source code" /></a>
  <a href="https://rj8307-digital-twin-2.hf.space/showcase"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/showcase-button.svg?v=4" width="104" height="30" alt="View project showcase" /></a>
  <a href="https://github.com/Ritwik389/digital-twin/blob/main/reports/benchmark.json"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/evaluation-button.svg?v=4" width="110" height="30" alt="Read the evaluation report" /></a>
</p>

## More things I've built

<p align="center">
  <a href="https://github.com/Ritwik389/VoiceSep"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/card-voicesep.svg?v=4" width="49%" alt="VoiceSep: separates up to five overlapping speakers in English and Hindi. 8.84 to 12.41 dB SI-SDRi with 4 to 5 speakers." /></a>
  <a href="https://github.com/sarthakv162/PRAMANA-SIH"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/card-pramana.svg?v=4" width="49%" alt="PRAMANA: a legal research assistant that cites and checks its sources. Smart India Hackathon 2026 team project." /></a>
</p>
<p align="center">
  <a href="https://github.com/sarthakv162/CIPHER-SIH"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/card-cipher.svg?v=4" width="49%" alt="CIPHER: a multimodal intelligence tool that runs fully offline. Smart India Hackathon 2026 team project." /></a>
  <a href="https://github.com/Ritwik389/MorphLab"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/card-morphlab.svg?v=4" width="49%" alt="MorphLab: real-time face swapping on live video, 19.6 to 21.3 FPS." /></a>
</p>

<details>
<summary><strong>Smaller projects</strong></summary>
<br />

| Project | What it does |
| --- | --- |
| [Analyzing Autoencoders](https://github.com/Ritwik389/Analyzing-Autoencoders) | 8 autoencoder architectures on EMNIST; the best CNN cut validation MSE 99.86% below the ANN baseline. |
| [Anomaly Detection Pipeline](https://github.com/Ritwik389/anomaly-detection-pipeline) | VideoMAE scoring, then Gemma multimodal review, then Telegram alerts. |
| [SEOAuditor](https://github.com/Ritwik389/SEOAuditor_TinyFish) | An evidence-first AI search visibility auditor, built for TinyFish × AIMS-DTU. |
| [Desktop Gesture Control](https://github.com/Ritwik389/Gesture-based-desktop-control-system) | Personalised gestures learned from 50 frames, with 90% recognition accuracy. |
| [AI Stadium Command Centre](https://github.com/Ritwik389/AI-Stadium-Command-Centre) | YOLOv8 crowd analytics from CCTV, with a zone-drawing GUI. |
| [Snowball](https://github.com/Ritwik389/Snowball) | Turns goals into AI micro-tasks ranked by urgency × importance. |
| [Drone Gesture Classification](https://github.com/Ritwik389/drone-gesture-classfication) | Webcam hand gestures mapped to drone commands. |

</details>

## Experience

- **AI/ML Intern, Deloitte** (Apr – Jul 2026): built multiclass classification pipelines on SageMaker, Glue, S3 and Athena, and moved 10+ notebook workflows into automated AWS Glue jobs.
- **Open source:** [pgmpy #3739](https://github.com/pgmpy/pgmpy/pull/3739) (BDeu/BDs validation fix) and [neural-lam #893](https://github.com/mllam/neural-lam/pull/893) (datastore CLI docs fix).

## Achievements

- 🏆 **Visionary Award**, Open Scientific Intelligence Hackathon 2026
- 🥈 **2nd prize, GreenTag** at APOGEE ’26, BITS Pilani: led a 5-member team, 2nd of 20+ teams.
- **Smart India Hackathon 2026**: both my teams, PRAMANA and CIPHER, cleared the DTU internal round.

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,ts,pytorch,tensorflow,sklearn,opencv,aws,docker,fastapi,react,linux&amp;perline=6" width="420" alt="Python, C++, TypeScript, PyTorch, TensorFlow, scikit-learn, OpenCV, AWS, Docker, FastAPI, React and Linux" />
</p>

<p align="center"><sub>Also Hugging Face Transformers, ONNX Runtime, MediaPipe, Chroma, Neo4j, PySpark and SQL.</sub></p>

## GitHub activity

<p align="center">
  <a href="https://github.com/Ritwik389">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Ritwik389&amp;theme=github-dark-blue&amp;hide_border=true&amp;disable_animations=true" />
      <img src="https://streak-stats.demolab.com/?user=Ritwik389&amp;theme=default&amp;hide_border=true&amp;disable_animations=true" width="495" alt="Ritwik389's GitHub contribution count, current streak, and longest streak" />
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Ritwik389?tab=repositories"><img src="https://raw.githubusercontent.com/Ritwik389/Ritwik389/main/assets/repositories-button.svg?v=4" width="146" height="30" alt="Browse all my repositories" /></a>
</p>
