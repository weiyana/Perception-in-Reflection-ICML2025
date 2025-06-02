# 🔁 **Perception in Reflection**  

<!-- <p align="center">
  <img src="static/images/Fig1.png" alt="RePer Teaser" width="70%">
</p> -->

<p align="center">
  <strong>RePer</strong> · <em>ICML 2025</em>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2504.07165"><img src="https://img.shields.io/badge/arXiv-2504.07165-b31b1b.svg" alt="arXiv"></a>
  <a href="https://weiyana.github.io/reper/"><img src="https://img.shields.io/badge/Website-reper-3776ab.svg" alt="Project Page"></a>
  <a href="https://github.com/yourname/reper"><img src="https://img.shields.io/badge/Code-RePer-4b8bbe.svg" alt="Code"></a>
  <img src="https://img.shields.io/badge/Model-ComingSoon-yellow.svg" alt="Model">
  <img src="https://img.shields.io/badge/Dataset-ComingSoon-orange.svg" alt="Dataset">
</p>

---

## ✨ Highlights

We introduce **RePer**, a reflective vision-language model that corrects its own hallucinations by:

- 🔁 Alternating between a **Policy** and a **Critic** model.
- 💬 Learning to revise generations, guided by **Reflective Perceptual Learning (RPL)**.
- 👁️ Iteratively improving alignment between model attention and human focus.
- 🚀 Achieving state-of-the-art performance on hallucination benchmarks like **HallusionBench**, **GAIVE**, and detailed captioning datasets.

---

## 🧠 Abstract

> We propose Reflective Perception (**RePer**), a dual-model architecture for vision-language models (LVLMs) that iteratively improves perception through a policy-critic loop. Using Reflective Perceptual Learning (**RPL**), RePer identifies and corrects hallucinated tokens during generation. Our framework demonstrates superior performance in caption detail, perception accuracy, and hallucination resistance—offering a robust paradigm for multimodal agents requiring complex visual reasoning.

<!-- ---

## 🖼️ Overview

<div align="center">
  <img src="static/images/Fig1.png" width="90%" />
  <p><i>Figure 1. RePer uses a dual-model loop to iteratively refine perception and reduce hallucinations.</i></p>
</div> -->

<!-- ---

## 📊 Benchmark Results

| Benchmark        | Metric        | Baseline | RePer |
|------------------|---------------|----------|--------|
| DetailCaps       | CAPTURE ↑     | 78.4     | **85.2** |
| HallusionBench   | Accuracy ↑    | 25.61%   | **31.28%** |
| GAIVE (GAPE)     | Total Score ↑ | 77.37    | **82.54** |

---

## 📂 Resources

- 📄 [Paper on arXiv](https://arxiv.org/abs/2504.07165)
- 🌐 [Project Page](https://yourdomain.com/reper)
- 💾 [Dataset - Coming Soon](#)
- 🧠 [Model Checkpoints - Coming Soon](#)

--- -->

## 🧾 BibTeX

```bibtex
@misc{wei2025perceptionreflection,
      title={Perception in Reflection}, 
      author={Yana Wei and Liang Zhao and Kangheng Lin and En Yu and 
      Yuang Peng and Runpei Dong and Jianjian Sun and 
      Haoran Wei and Zheng Ge and Xiangyu Zhang and Vishal M. Patel},
      year={2025},
      eprint={2504.07165},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2504.07165}, 
```
