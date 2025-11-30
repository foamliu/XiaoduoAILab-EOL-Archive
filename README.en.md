# Xiaoduo AI Lab - Project Archive

> Technical Discussion Records and Research Archive (2023-2025)

**Language Options**: [中文版本](README.md) | English Version

This repository contains technical discussion records and research archives from Xiaoduo AI Lab, which operated from October 2023 to September 2025. The lab focused on cutting-edge research in large language models, multimodal AI, and e-commerce AI applications.

- **`XiaoduoAILab_Discussion_LogBook_2023_11_14-2025_9_24.pdf`** - Complete technical discussion records during the lab's operation period
- **Research Papers** - Main publications and technical reports produced during the lab period

## 🎯 Research Directions

The lab focused on several key AI research areas:

- **Large Language Models** - Developing efficient, multilingual, and strongly reasoning lightweight large models
- **Multimodal Vision-Language Models** - Connecting visual and text understanding
- **Domain Models and Domain Agents** - Domain specialization of large models and agents

## 📚 Main Publications (2023-2025)

### Large Language Models
- **Xmodel-LM Technical Report** - *arXiv*
- **Xmodel-1.5: An 1B-scale Multilingual LLM** - *arXiv*
- **Xmodel-2 Technical Report** - *arXiv*

### Vision-Language Models
- **Xmodel-VLM: A Simple Baseline for Multimodal Vision Language Model** - *arXiv*

### Domain Models and Domain Agents
- **ECom-Bench: Can LLM Agent Resolve Real-World E-commerce Customer Support Issues?** - *EMNLP 2025*

<div align="center">
  
| | |
|:---:|:---:|
| <img src="assets/poster.jpg" width="400" alt="ECom-Bench EMNLP 2025 Poster"><br>**ECom-Bench Paper Poster**<br><small>EMNLP 2025 Conference Presentation</small> | <img src="assets/emnlp_2025.jpg" width="400" alt="Wang Haoxin presenting ECom-Bench"><br>**First Author Wang Haoxin presenting ECom-Bench**<br><small>EMNLP 2025 Conference Site</small> |

</div>

- **MindFlow: Revolutionizing E-commerce Customer Support with Multimodal LLM Agents** - *arXiv*
- **MemOrb: A Plug-and-Play Verbal-Reinforcement Memory Layer for E-Commerce Customer Service** - *arXiv*
- **Survey of Specialized Large Language Model** - *arXiv*

## 🔬 Technical Contributions

### Model Development
- **Xmodel Series**: Developed lightweight large models with multilingual capabilities, strong reasoning, and agent abilities
- **Multimodal Integration**: Proposed a new projection method (XDP) for unified vision-language understanding
- **Memory Systems**: Developed plug-and-play memory layers enabling agents to learn from experience

### Domain Agent Simulation Evaluation and Deployment
- **ECom-Bench**: Introduced new elements in domain agent simulation evaluation ("persona-driven user simulation" and "multimodal")
- **MindFlow**: Validated domain agent performance in real customer service scenarios

### Applied Research
- **Multilingual**: Collaborated with Chulalongkorn University to develop Thai evaluation dataset Xdata_Thai, validating cross-language capabilities of lightweight large models
- **Multimodal**: Explored architectural forms of multimodal agents in e-commerce customer service scenarios
- **Efficiency Validation**: Deployed and stress-tested Xmodel series models on server-side (SGLang/vLLM) and client-side (Ollama), validating the cost advantages of lightweight models

> **Note**
> Chulalongkorn University (Thai: จุฬาลงกรณ์มหาวิทยาลัย) is a national research university in the Siam area of Bangkok, Thailand, and is the oldest university in Thailand.

## 📊 Timeline
```mermaid
gantt
    title Lab Research Project Timeline
    dateFormat  YYYY-MM
    axisFormat %Y-%m
    
    section Lab Management
    Lab Establishment :done, 2023-10, 1M
    Lab Closure :crit, 2025-09, 1M
    
    section Large Language Models
    Xmodel-LM :active, 2023-11, 7M
    Xmodel-1.5 :active, 2024-05, 6M
    Xmodel-2 :active, 2024-08, 4M
    Xmodel-2.5 :active, 2025-09, 2M

    section Vision-Language Models
    Xmodel-VLM :active, 2024-01, 4M
    
    section Domain Models and Domain Agents
    MindFlow :active, 2024-05, 14M
    ECom-Bench :active, 2025-03, 4M
    Domain Model Survey :active, 2025-05, 3M
    MemOrb :active, 2025-07, 2M
```

## 📸 Lab Member Group Photos

The following are departure group photos of some lab members during the operation period, recording some members' names, schools, contributions, and photo dates:

<div align="center">

| | | |
|:---:|:---:|:---:|
| <img src="assets/yanyu.jpg" width="200" alt="Group Photo 1"><br>**Yan Yu** (Intern)<br>Harbin Institute of Technology, Weihai<br>**Custom Tokenizer**<br><small>2024/1</small> | <img src="assets/xuwanting.jpg" width="200" alt="Group Photo 2"><br>**Xu Wanting/He Langping**<br>(2nd from left/3rd from right, Interns)<br>East China Normal University/Donghua University<br>**Xmodel-VLM**<br><small>2024/5</small> | <img src="assets/wangyichuan.jpg" width="200" alt="Group Photo 3"><br>**Wang Yichuan** (Intern)<br>Shanghai Jiao Tong University<br>**Xmodel-LM**<br><small>2024/6</small> |
| <img src="assets/linqingquan.jpg" width="200" alt="Group Photo 4"><br>**Lin Qingquan/Qu Zhijiu**<br>(2nd from right/1st from right, Interns)<br>Wuhan University/Fudan University<br>**Xmodel-2**<br><small>2024/12</small> | <img src="assets/huangxucheng.jpg" width="200" alt="Group Photo 4"><br>**Liu Yang/Huang Xucheng**<br>(Right/Left, Full-time)<br>Peking University/Friedrich-Alexander-Universität Erlangen-Nürnberg<br>**Distributed Training Framework, etc.**<br><small>2025/6</small> | <img src="assets/wangqun.jpg" width="200" alt="Group Photo 5"><br>**Wang Qun** (Intern)<br>Shanghai Maritime University<br>**Xmodel-1.5+Xmodel-2**<br><small>2025/6</small> |
| <img src="assets/wanghaoxin.jpg" width="200" alt="Group Photo 6"><br>**Wang Haoxin/Peng Xianhan/Yang Chenghan**<br>(3rd from left/4th from left/2nd from left, Interns)<br>Shanghai Jiao Tong University<br>**ECom-Bench** (Wang/Peng)<br>**Domain LLM Survey** (Yang)<br><small>2025/6</small> | <img src="assets/gongming.jpg" width="200" alt="Group Photo 9"><br>**Gong Ming** (Intern)<br>University of Dayton<br>**MindFlow**<br><small>2025/8</small> | <img src="assets/huangyizhe.jpg" width="200" alt="Group Photo 8"><br>**Huang Yizhe** (1st from right, Intern)<br>Fudan University<br>**MemOrb**<br><small>2025/9</small> |

</div>

## 🤝 Acknowledgments

We have learned from and referenced numerous papers and open-source achievements from the AI community. Although we strive to contribute back with modest efforts, what we have gained far exceeds what we have given. Whenever we think of this, we often feel a sense of humility.

## 🔗 Related Resources

To access actual models, datasets, or implementation code, please refer to the independent repositories associated with each paper.

---

*This archive serves as a comprehensive record of Xiaoduo AI Lab's technical contributions from 2023-2025.*

---


