---
layout: page
title: Recruitment
permalink: /recruitment/
subtitle: update date 2025-07-17
nav: true
nav_order: 4
---

<style>
@media (max-width: 768px) {
  div[style*="position: fixed"] {
    display: none !important;
  }
  .post article img, article img {
    max-width: 100% !important;
    height: auto !important;
  }
}
.post article img, article img {
  max-width: 900px;
  height: auto;
  display: block;
  margin: 0 auto;
}

/* Balanced and justified text layout */
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

/* Page content container */
.post {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Responsive adjustments */
@media (max-width: 768px) {
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
<span style="color: #666;">中文</span> | 
<a href="/recruitment_en/" style="color: #0066cc;">English</a>
</div>

<!-- Table of Contents -->
<div style="position: fixed; top: 120px; left: 20px; width: 250px; background: #f8f9fa; border: 1px solid #dee2e6; border-radius: 8px; padding: 15px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); z-index: 1000; font-size: 14px; max-height: 80vh; overflow-y: auto;">
<h4 style="margin-top: 0; margin-bottom: 15px; color: #495057; font-size: 16px; border-bottom: 1px solid #dee2e6; padding-bottom: 8px;">目录</h4>
<ul style="list-style: none; padding: 0; margin: 0; line-height: 1.6;">
<li style="margin-bottom: 8px;"><a href="#1-实验室主要研究方向" style="color: #007bff; text-decoration: none;">1. 主要研究方向</a>
<ul style="list-style: none; padding-left: 15px; margin-top: 5px;">
<li style="margin-bottom: 5px;"><a href="#方向1-大模型与几何拓扑流形" style="color: #6c757d; text-decoration: none; font-size: 13px;">方向1: 大模型与几何</a></li>
<li style="margin-bottom: 5px;"><a href="#方向2-个性化建模推荐算法知识图谱与社交网络" style="color: #6c757d; text-decoration: none; font-size: 13px;">方向2: 个性化建模与推荐系统</a></li>
<li style="margin-bottom: 5px;"><a href="#方向3-ai4sci人工智能赋能科学研究" style="color: #6c757d; text-decoration: none; font-size: 13px;">方向3: AI4SCI</a></li>
</ul>
</li>
<li style="margin-bottom: 8px;"><a href="#2-学校介绍" style="color: #007bff; text-decoration: none;">2. 学校介绍</a></li>
<li style="margin-bottom: 8px;"><a href="#3-团队介绍" style="color: #007bff; text-decoration: none;">3. 团队介绍</a></li>
<li style="margin-bottom: 8px;"><a href="#4-招聘说明" style="color: #007bff; text-decoration: none;">4. 招聘说明</a></li>
<li style="margin-bottom: 8px;"><a href="#5-如何申请" style="color: #007bff; text-decoration: none;">5. 如何申请</a></li>
</ul>
</div>

# 香港科技大学（广州）DIGAI Lab博士生、硕士生、本科生/研究助理招聘


Update: 2025-09-12

香港科技大学（广州）数据智能与几何人工智能实验室（DIGAI Lab) 诚邀有志于AI前沿研究的优秀学子加入，攻读博士学位或进行（远程）访问研究。实验室专注于表示学习、大模型、几何拓扑、信息检索，致力于推动几何与人工智能的理论发展，以及其在网络科学、科学发现领域的应用。欢迎具有不同学科背景的同学共同探索前沿领域，并提供丰富的科研资源与国际合作机会。

<div align="center" style="margin: 20px 0;">
<img src="/assets/img/digai/lab_logo.webp" alt="DIGAI Lab Logo" style="max-width: 900px; height: auto;">
</div>

---

## 1. 实验室主要研究方向

### 方向1: 大模型(微调，RAG，推理)

本研究方向致力于深入理解大模型的内在机理，提升其推理能力、表示质量和多模态融合效果，构建更加高效、可解释和可控的智能系统。

**核心研究领域包括：**

- **大模型表示分析与理论基础(LLM Embedding & Theory)**：深入研究大模型的内部表示机制和几何结构，探索Token嵌入的语义空间分布、层次化表示学习和注意力机制的理论基础。开发可解释性分析工具，揭示大模型的知识存储、推理路径和决策过程，为模型优化和安全对齐提供理论指导。

- **大模型隐式推理与逻辑增强(LLM Implicit Reasoning)**：研究大模型的隐式推理能力和逻辑思维机制，开发基于思维链(Chain-of-Thought)、工具使用(Tool Learning)和程序合成的推理增强方法。探索数学推理、因果推理、常识推理等复杂认知任务，构建能够进行多步骤逻辑推导和问题求解的智能系统。

- **多模态对齐与融合学习(Multi-Modal LLMs)**：构建统一的多模态表示空间，实现文本、图像、音频、视频等不同模态之间的深度对齐和语义融合。研究跨模态注意力机制、模态间知识迁移和统一编码器架构，开发能够理解和生成多模态内容的大规模基础模型。

- **强化学习推理与高效微调(RL Reasoning & PEFT)**：结合强化学习和人类反馈优化(RLHF)技术，提升大模型的推理准确性和对齐效果。探索参数高效微调方法，包括LoRA、适配器网络、提示调优等技术，实现在有限计算资源下的快速领域适应和任务定制，平衡模型性能与计算效率。

我们欢迎对深度学习理论、自然语言处理、计算机视觉、强化学习、可解释AI、多模态学习以及相关数学基础和算法优化技术感兴趣的学生和研究者加入我们的团队。


---


### 方向2: 个性化建模、推荐算法、知识图谱与社交网络

本研究方向致力于融合知识图谱、本地化数据和几何建模技术，构建推荐系统和个性化分析框架。专注于解决大模型在个性化应用中的关键挑战，包括幻觉问题、推荐准确性、社交网络动态演化以及群体行为预测等复杂问题。

**核心研究领域包括：**

- **检索增强生成(RAG, GraphRAG)**：基于知识图谱和本地化数据构建个性化大模型，通过RAG（检索增强生成）和Graph RAG技术，提升模型在特定领域和用户群体中的表现。结合结构化知识和非结构化文本，实现精准的信息检索和生成，有效缓解幻觉问题并增强个性化能力。

- **个性化大模型与适应性学习(Personalized LLMs & Adaptive Learning)**：研究大语言模型的个性化定制技术，包括参数高效微调(PEFT)、适配器网络(Adapter Networks)、提示学习(Prompt Learning)和上下文学习(In-Context Learning)等方法。探索用户画像建模、个人偏好学习和动态适应机制，开发能够根据用户行为和反馈持续演化的个性化智能助手，实现多轮对话中的个性化记忆和知识积累。

- **检索与推荐(Recommender Systems)**：开发基于深度学习和几何约束的新一代推荐算法，融合用户行为数据、内容特征和社交关系，构建多模态推荐模型。探索协同过滤、内容推荐、序列推荐等核心技术，解决冷启动、数据稀疏性和推荐多样性等关键挑战。

- **大规模网络、图的表示与优化(Network Science & Graph Learning)**：针对大规模复杂网络的建模、表示学习和优化问题，开发高效的算法和理论框架。重点研究社区发现、影响力分析、节点分类，图分类，链路预测等关键问题，结合图神经网络和几何深度学习技术，捕捉网络结构中的层次性和动态演化规律。

我们欢迎对推荐系统、社交网络分析、知识图谱、图神经网络、复杂网络理论、信息检索、个性化大模型、参数高效微调以及相关数据挖掘和机器学习技术感兴趣的学生和研究者加入我们的团队。

---

### 方向3: 双曲表示学习与非欧几何机器学习

本研究方向专注于探索非欧几何空间（特别是双曲几何）在机器学习和数据表示中的深层应用，致力于突破传统欧几里得空间的局限性，为层次结构数据、复杂网络和高维数据建模提供全新的几何视角和理论框架。

**核心研究领域包括：**

- **双曲几何深度学习(Hyperbolic Deep Learning)**：开发基于双曲空间的神经网络架构和优化算法，包括双曲卷积神经网络、双曲图神经网络和双曲注意力机制。探索能够自然处理层次结构和树状数据的深度学习模型,推理模型等。

- **层次表示学习与嵌入(Hierarchical Representation Learning)**：利用双曲空间的负曲率特性，为具有天然层次结构的数据（如知识图谱、分类树、组织结构）构建低维嵌入表示。开发高效的双曲嵌入算法，实现语义相似性保持、层次关系编码和可解释性增强，特别针对自然语言处理、计算机视觉和生物信息学中的层次数据。

- **流形学习与几何优化(Manifold Learning & Geometric Optimization)**：研究黎曼流形上的优化理论和算法，包括双曲空间、球面和其他非欧几何流形。开发基于几何结构的优化方法，探索测地线梯度下降、指数映射和对数映射在机器学习中的应用，为约束优化和几何深度学习提供理论基础。

- **复杂网络的几何表示(Geometric Network Representation)**：将复杂网络映射到非欧几何空间中，捕捉网络的内在几何结构和拓扑性质。研究网络嵌入的几何不变性、可扩展性和鲁棒性，开发能够保持网络层次性、社区结构和动态演化特征的几何表示方法。

我们欢迎对微分几何、黎曼优化、图论、深度学习理论、计算几何以及相关数学基础和应用领域感兴趣的学生和研究者加入我们的团队。


---

## 2. 学校介绍

香港科技大学（广州）是《粤港澳大湾区发展规划纲要》及《广州南沙深化面向世界的粤港澳全面合作总体方案》颁布实施以来成立的首家具有独立法人资格的内地与香港合作办学机构，经国家教育部批准于2022年6月正式成立。香港科技大学（广州）锐意创新，以发展融合学科为特色，探索创新人才培养模式，以建设成为内地与香港教育融合发展的典范、国际知名的高水平大学为己任，致力于培养面向未来的高水平创新型人才。

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/bridge.png" alt="HKUST(GZ) Bridge" style="max-width: 900px; height: auto;">
</div>

香港科技大学（广州）依据有关规定及学校的毕业要求颁发香港科技大学硕士学位和博士学位证书。截至2024年9月，学校共有学术人员300余人，其中，长聘制学术人员240余人，100%拥有博士学位，98%拥有境外教育背景或工作经历，近20%获国家级人才项目，近50%入选省部级及以上人才项目，15%入选全球前2%顶尖科学家榜单。

港科大和港科大(广州)在“两校一体，双校互补”的框架下实行资源共享，如在实验室、图书馆、课程和教师等方面，学校融合内地与香港优质教育资源，以发展融合学科为特色，探索创新型人才培养模式，立足中国，面向世界，矢志建设成为世界一流高等学府。

香港科技大学（广州）的学科设置优先考虑国家发展的战略需求和大湾区发展的产业需要，致力于解决当前国家产业所面临的“卡脖子”科技和培养未来科技的创新型人才。学校采用全新的、融合学科的学术架构，以“枢纽”（Hub）和“学域”（Thrust）取代传统的“学院”和“学系”，推动学科交叉融合，大力发展新兴学科和前沿学科。

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/campus.png" alt="HKUST(GZ) Campus" style="max-width: 900px; height: auto;">
</div>


自建校以来，香港科技大学（广州）已获批3个广东省重点实验室（研究基地、平台），11个广州市重点实验室, 已获批各级政府资助科研项目300余项，包含国家级项目66项，承担和参与国家级重点重大专项18项。

学校已与阿里云、粤芯半导体、深圳湾实验室等90余家领军企业和知名科研机构签订合作协议，与近10家行业龙头建立了联合实验室；校内创业孵化项目100余项，注册企业40余家。环港科大（广州）创新区正加快推进建设。学校与广州产投集团共同设立10亿元环港科大（广州）科技成果转化母基金，还牵手一批直投基金合作伙伴，总基金规模达到24亿元。

<div align="center" style="margin: 40px 0;">
<img src="/assets/img/digai/hkustgz.webp" alt="HKUST(GZ) Logo" style="max-width: 900px; height: auto;">
</div>

---

## 3. 团队介绍

DIGAI Lab团队由杨萌林(Menglin Yang, https://yangmenglinsite.github.io/)导师带领。杨老师博士毕业于香港中文大学，在耶鲁大学从事博士后研究。目前担任香港科技大学广州人工智能学域的博士生导师，副研究员，助理教授。导师所在团队在机器学习、几何AI及科学计算领域拥有丰富的研究经验，并与全球多所顶尖大学及科研机构有密切合作。研究团队目前正在积极招募多名博士研究生与研究助理，参与前沿研究项目，积累宝贵的科研经验。顺利录取的博士研究生，将获得全额奖学金。课题组是一个充满活力与温暖分为的学术大家庭，注重学术诚信与公平，能提供良好的办公环境与算力支持，保障课题组成员顺利开展科研工作。加入我们团队，

- 发表顶级学术论文的机会：在机器学习、数据挖掘、人工智能领域的顶级期刊和会议上发表学术论文并参加国际会议
- 良好的学术氛围与系统性的指导：每位学生与导师每周至少一次一对一讨论。组内科研氛围融洽，每周一次的组会帮学生潜心研读最新的科研论文及系统化学习机器学习、优化、统计相关课程，为科研打好关键基础，厚积薄发。我们鼓励学生间合作以取长补短，并碰撞出更多科研想法。导师尊重学生科研兴趣，仅进行领域限定，具体研究问题方法由导师与学生商定
- 科研方法及思维培养：对于有志于科研事业的学生，导师将提高学生在各科研环节中的系统性方法和思维方式，使学生能尽早独立承担科研课题和管理实验室
- 广泛的合作交流机会：包括但不限于在香港科技大学清水湾校园长期访问，以及丰富的世界级大学交换学习和业界研究院实习访问机会，如学生有机会到腾讯、华为、鹏城实验室等头部互联网公司或科研机构进行实习和联合研究
  
---

## 4. 招聘说明

我们欢迎以下背景的申请者：

- 对大模型、推荐系统、网络科学，AI4SCI等领域有浓厚兴趣的学生
- 拥有计算机科学、数学、物理、生物信息、网络科学等相关背景的本科生，硕士研究生
- 良好的英文口头和书面表达能力（入学需取得雅思 6.5 或托福 80)
- 具有扎实的编程能力，熟练使用相关编程语言
- 招收多名科研助理（RA）和实习生（Interns)。依个人经历经验，以及项目推进速度，提供有竞争力的工资待遇，远程实习生提供计算资源和充分的指导。有机会发表高水平论文。表现优异者优先博士录取资格。

博士生可选择2026年2月和8月入学, 博士研究生的学制为 3 年（对于已有相关研究型硕士学位的申请者）或 4 年（对于没有相关研究型硕士学位的申请者），学费为4万人民币/年，所有录取的博士生将获得全额奖学金（约1.5万人民币/月)。

{: .info }
> 📝 **硕士研究生申请说明**：硕士研究生申请人无需提前联系导师，直接通过学校官网申请即可。如已经被硕士项目录取并希望加入实验室开展科研工作，请直接发送邮件联系。

香港科技大学（广州）的硕士研究生和本科生申请人欢迎直接联系导师。

---

## 5. 如何申请

请将个人简历、本科硕士成绩单、专业排名证明（如有）、推荐信（如有）、代表性论文或项目（如有）、Research Proposal (如有)等发送至：

**`menglinyang[at]hkust-gz.edu.cn` or `digailab[at]outlook.com`**

邮件标题格式：申请岗位名称+本人姓名+学位+毕业学校+所学专业。在收到申请材料后，进行初步筛选，并安排合适的面试时间。

正式申请入口：[https://fytgs.hkust-gz.edu.cn/](https://fytgs.hkust-gz.edu.cn/)