---
layout: page
title: "Recruitment (EN)"
permalink: /recruitment_en/
subtitle: Update 2026-08-23
nav: false
nav_order: 2
---

<style>
.post article img, article img {
  max-width: 600px;
  height: auto;
  display: block;
  margin: 0 auto;
}

.post article p {
  text-align: justify !important;
  text-justify: inter-word;
  line-height: 1.8;
  margin-bottom: 1.2em;
}

.post article ul {
  text-align: justify;
  line-height: 1.8;
}

.post article li {
  margin-bottom: 0.8em;
  text-align: justify;
}

.post article h1 {
  text-align: center;
  margin-top: 2em;
  margin-bottom: 1em;
}

.post article h2, .post article h3, .post article h4 {
  text-align: left;
  margin-top: 2em;
  margin-bottom: 1em;
}

.post article blockquote {
  text-align: justify;
  line-height: 1.8;
  margin: 1.5em 0;
  padding: 1em;
  border-left: 4px solid #0066cc;
  background-color: #f8f9fa;
}

.post {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

@media (max-width: 768px) {
  .post article img, article img {
    max-width: 100% !important;
    height: auto !important;
  }
  .post {
    padding: 0 15px;
  }
  .post article p, .post article ul, .post article li {
    text-align: left;
  }
}
</style>

<div style="text-align: left; margin-bottom: 20px;">
<strong>Language:</strong> 
<a href="/recruitment/" style="color: #0066cc;">中文</a> | 
<span style="color: #666;">English</span>
</div>

# HKUST(GZ) DIGAI Lab PhD, Master's, Undergraduate, and Research Assistant Recruitment

<div align="center" style="margin: 20px 0;">
<img src="/assets/img/digai/lab_logo.webp" alt="DIGAI Lab Logo" style="max-width: 600px; height: auto;">
</div>

The Data Intelligence and Geometric AI Laboratory (DIGAI Lab) at HKUST(GZ) is actively seeking passionate students to join our cutting-edge AI research team. We offer opportunities for PhD studies and remote visiting research positions. Our research spans **representation learning, LLMs, geometric learning, and information retrieval**, with a focus on advancing geometric AI theory and its applications in network science and scientific discovery. We welcome students from diverse backgrounds and provide extensive research resources and international collaboration opportunities.

Update: 2026-08-23

---

## 1. Primary Research Directions

### Direction 1: Large Language Models (Fine-tuning, RAG, Memory, Reasoning)

This research direction focuses on gaining deep insights into the fundamental mechanisms of large language models while enhancing their reasoning capabilities, representation quality, and multi-modal integration. Our goal is to build more efficient, interpretable, and controllable intelligent systems.

**Core Research Areas:**

- **LLM Pretraining**: We explore efficient pretraining strategies and data mixture methods, investigating training dynamics, loss function design, and curriculum learning to fundamentally improve large models' language understanding and knowledge acquisition capabilities.

- **LLM Representation Analysis & Theoretical Foundations**: We investigate the internal representation mechanisms and geometric structures of large language models, exploring semantic space distributions of token embeddings, hierarchical representation learning, and the theoretical underpinnings of attention mechanisms. We develop interpretability analysis tools to reveal knowledge storage patterns, reasoning pathways, and decision-making processes in LLMs, providing theoretical guidance for model optimization and safety alignment.

- **LLM Implicit Reasoning & Logic Enhancement**: Our research examines the implicit reasoning capabilities and logical thinking mechanisms of large models, developing reasoning enhancement methods based on Chain-of-Thought, tool learning, and program synthesis. We explore complex cognitive tasks including mathematical reasoning, causal inference, and commonsense reasoning to build intelligent systems capable of multi-step logical deduction and problem-solving.

- **Multi-Modal Alignment & Fusion Learning**: We construct unified multi-modal representation spaces to achieve deep alignment and semantic fusion between different modalities such as text, images, audio, and video. Our research focuses on cross-modal attention mechanisms, inter-modal knowledge transfer, and unified encoder architectures to develop large-scale foundation models capable of understanding and generating multi-modal content.

- **Reinforcement Learning Reasoning & Parameter-Efficient Fine-tuning (PEFT)**: We combine reinforcement learning with Reinforcement Learning from Human Feedback (RLHF) techniques to improve reasoning accuracy and alignment effectiveness of large models. We explore parameter-efficient fine-tuning methods including LoRA, adapter networks, and prompt tuning to achieve rapid domain adaptation and task customization under limited computational resources while balancing model performance and computational efficiency.

- **LLM Memory Mechanisms**: We investigate the long-term and working memory mechanisms of large models, exploring external memory augmentation, context compression, and retrieval-based memory techniques to improve model performance in long-text understanding, multi-turn dialogue, and continual learning scenarios.

We welcome students and researchers interested in deep learning theory, natural language processing, computer vision, reinforcement learning, explainable AI, multi-modal learning, and related mathematical foundations and algorithmic optimization techniques to join our team.

---

### Direction 2: Personalized Modeling, Recommendation Algorithms, Knowledge Graphs & Social Networks

This research direction integrates knowledge graphs, localized data, and geometric modeling techniques to build recommendation systems and personalized analysis frameworks. We focus on addressing key challenges in personalized applications of large models, including hallucination problems, recommendation accuracy, social network dynamics, and group behavior prediction.

**Core Research Areas:**

- **Retrieval-Augmented Generation (RAG, GraphRAG)**: We develop personalized large models based on knowledge graphs and localized data, leveraging RAG (Retrieval-Augmented Generation) and Graph RAG technologies to enhance model performance for specific domains and user groups. By combining structured knowledge with unstructured text, we achieve precise information retrieval and generation while effectively mitigating hallucination problems and enhancing personalization capabilities.

- **Personalized LLMs & Adaptive Learning**: We investigate personalization techniques for large language models, including Parameter-Efficient Fine-Tuning (PEFT), Adapter Networks, Prompt Learning, and In-Context Learning methods. We explore user profiling, personal preference learning, and dynamic adaptation mechanisms to develop personalized intelligent assistants that continuously evolve based on user behavior and feedback.

- **Information Retrieval & Recommendation Systems**: We focus on scaling laws in recommendation models and generative recommendation, investigating efficiency, fairness, and interpretability in large-scale recommendation systems, and exploring new paradigms in multi-modal and cross-domain recommendation.

- **Large-scale Networks & Graph Learning**: We focus on modeling, representation learning, and optimization problems for large-scale complex networks, developing efficient algorithms and theoretical frameworks. Our research emphasizes community detection, influence analysis, node classification, graph classification, and link prediction, combining graph neural networks with geometric deep learning techniques to capture hierarchical structures and dynamic evolution patterns in network structures.

We welcome students and researchers interested in recommendation systems, social network analysis, knowledge graphs, graph neural networks, complex network theory, information retrieval, personalized large models, and related data mining and machine learning technologies to join our team.

---

### Direction 3: Hyperbolic Representation Learning & Non-Euclidean Geometric Machine Learning

This research direction explores the deep applications of non-Euclidean geometric spaces (particularly hyperbolic geometry) in machine learning and data representation. We aim to transcend the limitations of traditional Euclidean spaces, providing novel geometric perspectives and theoretical frameworks for hierarchical data, complex networks, and high-dimensional data modeling.

**Core Research Areas:**

- **Hyperbolic Deep Learning**: We develop neural network architectures and optimization algorithms based on hyperbolic spaces, including hyperbolic convolutional neural networks, hyperbolic graph neural networks, and hyperbolic attention mechanisms. We explore deep learning models and reasoning systems that can naturally handle hierarchical structures and tree-like data.

- **Hierarchical Representation Learning & Embedding**: We leverage the negative curvature properties of hyperbolic spaces to construct low-dimensional embedding representations for data with natural hierarchical structures (such as knowledge graphs, taxonomies, and organizational structures). We develop efficient hyperbolic embedding algorithms that preserve semantic similarity, encode hierarchical relationships, and enhance interpretability.

- **Manifold Learning & Geometric Optimization**: We study optimization theory and algorithms on Riemannian manifolds, including hyperbolic spaces, spherical surfaces, and other non-Euclidean geometric manifolds. We develop geometry-based optimization methods and explore applications of geodesic gradient descent, exponential maps, and logarithmic maps in machine learning, providing theoretical foundations for constrained optimization and geometric deep learning.

- **Geometric Network Representation**: We map complex networks into non-Euclidean geometric spaces to capture the intrinsic geometric structures and topological properties of networks. We study geometric invariance, scalability, and robustness of network embeddings, developing geometric representation methods that preserve network hierarchy, community structures, and dynamic evolution characteristics.

We welcome students and researchers interested in differential geometry, Riemannian optimization, graph theory, deep learning theory, computational geometry, and related mathematical foundations and application domains to join our team.

---

## 2. University Introduction

HKUST(GZ) is the first legally independent mainland-Hong Kong cooperative educational institution established under the Greater Bay Area development framework. Officially established in June 2022 with approval from China's Ministry of Education, HKUST(GZ) focuses on interdisciplinary innovation and exploring new talent cultivation models, dedicated to cultivating future-oriented, high-level innovative talents.

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/bridge.png" alt="HKUST(GZ) Bridge" style="max-width: 600px; height: auto;">
</div>

HKUST(GZ) awards **master's and doctoral degrees from The Hong Kong University of Science and Technology**. The University adopts a Hub-and-Thrust structure to advance cross-disciplinary education, research, and knowledge transfer, comprising four Hubs: Function, Information, Systems, and Society. It currently has over 300 substantiation-track faculty members, all of whom hold doctoral degrees.

HKUST and HKUST(GZ) operate under a **"Unified HKUST, Complementary Campuses"** framework, sharing resources including laboratories, libraries, courses, and faculty, integrating the best educational resources from the mainland and Hong Kong.

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/campus.png" alt="HKUST(GZ) Campus" style="max-width: 600px; height: auto;">
</div>

As of December 2025, the University's Research Department had supported 2,069 research project applications, with 827 projects awarded. HKUST(GZ) currently operates 16 provincial- and municipal-level research platforms, 29 institutes and theme-based laboratories, and 15 central research facilities that support cross-disciplinary research.

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/hkustgz.webp" alt="HKUST(GZ) Logo" style="max-width: 600px; height: auto;">
</div>

---

## 3. Team Introduction

DIGAI Lab is led by [Dr. Menglin Yang](https://yangmenglinsite.github.io/), who holds a Ph.D. from The Chinese University of Hong Kong and conducted postdoctoral research at Yale University. He currently serves as an Assistant Professor and PhD supervisor in the AI Thrust at HKUST(GZ). Our team has extensive experience in LLM memory and reasoning, recommender systems, and hyperbolic geometric machine learning, maintaining close collaborations with top universities and research institutions worldwide.

Our group is a **vibrant and supportive academic family** that emphasizes integrity and fairness, providing excellent office environments and computational resources. By joining us, you will benefit from:

- **Top-tier Publishing Opportunities**: Publish in leading ML, data mining, and AI journals and conferences, with full support for international conference participation.
- **Systematic Academic Mentoring**: Weekly one-on-one meetings with the supervisor; weekly group seminars for reading latest papers and systematic learning in ML, optimization, and statistics. We respect individual research interests and collaboratively determine specific research directions.
- **Research Skills Development**: Systematic training in research methodology and critical thinking, enabling students to independently lead research projects and manage lab activities early on.
- **Broad Collaboration & Exchange**: Long-term visits to HKUST Clear Water Bay campus, exchanges with world-class universities, and industry internships at leading companies such as Tencent, Huawei, and Peng Cheng Laboratory.

---

## 4. Recruitment Information

**We welcome applicants with:**

- Strong interest in large models, recommendation systems, network science, AI4SCI, and related fields
- Undergraduate or master's students with backgrounds in computer science, mathematics, physics, bioinformatics, network science, and related fields
- Strong English communication skills (IELTS 6.5 or TOEFL 80 required for admission)
- Solid programming skills in relevant languages

**PhD Students:** Entry available in February or August 2027. Program duration is 3 years (with relevant research master's degree) or 4 years (without). Tuition fees are subject to the latest requirements published on the [university's official website](https://fytgs.hkust-gz.edu.cn/admissions/before-submitting-an-application/scholarships-fees), with **full scholarships provided to all admitted students (~15,000 RMB/month)**.

**Research Assistants (RAs) & Interns:** We recruit multiple RAs and interns with competitive compensation based on experience and project involvement. Remote interns receive computational resources and comprehensive guidance, with opportunities to publish high-level papers. Outstanding performers receive priority consideration for doctoral admission.

{: .info }
> 📝 **Master's Student Application**: Master's applicants can apply directly through the university website without prior supervisor contact. If already admitted to a master's program and interested in joining our lab, please contact us directly via email.

---

## 5. How to Apply

Please send the following materials to: **`menglinyang[at]hkust-gz.edu.cn`**

- Resume/CV
- Undergraduate and graduate transcripts
- Professional ranking certificates (if available)
- Recommendation letters (if available)
- Representative papers or projects (if available)
- Research proposal (if available)

**Email subject format**: Position Applied + Your Name + Degree + Graduation University + Major

We will conduct preliminary screening and arrange interviews upon receipt of materials.

**Official application portal**: [https://fytgs.hkust-gz.edu.cn/](https://fytgs.hkust-gz.edu.cn/)
