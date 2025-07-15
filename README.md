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

## 🧠 Abstract

> We present a perception in reflection paradigm designed to transcend the limitations of current large vision-language models (LVLMs), which are expected yet often fail to achieve perfect perception initially. Specifically, we propose Reflective Perception (RePer), a dual-model reflection mechanism that systematically alternates between policy and critic models, enables iterative refinement of visual perception. This framework is powered by Reflective Perceptual Learning (RPL), which reinforces intrinsic reflective capabilities through a methodically constructed visual reflection dataset and reflective unlikelihood training. Comprehensive experimental evaluation demonstrates RePer’s quantifiable improvements in image understanding, captioning precision, and hallucination reduction. Notably, RePer achieves strong alignment between model attention patterns and human visual focus, while RPL optimizes fine-grained and free-form preference alignment. These advancements establish perception in reflection as a robust paradigm for future multimodal agents, particularly in tasks requiring complex reasoning and multi-step manipulation.

---

## ✨ Highlights

- 👁️ RePer progressively shifts image attention toward human-aligned regions through iterative reflection, resulting in perceptual patterns that more closely mirror human focus.
- 🔁 Reflective Perceptual Learning serves as a free-form preference optimization that unifies various preference learning paradigms (DPO and LiPO), while enabling fine-grained supervision through explicit feedback signals.
- 🌇 RePer is an accurate and informative image captioner that significantly reduces hallucinations.

<!-- ---

## 🖼️ Overview

<div align="center">
  <img src="static/images/Fig1.png" width="90%" />
  <p><i>Figure 1. RePer uses a dual-model loop to iteratively refine perception and reduce hallucinations.</i></p>
</div> -->

<!-- ---

## 📊 Benchmark Results



---

## 📂 Resources

- 📄 [Paper on arXiv](https://arxiv.org/abs/2504.07165)
- 🌐 [Project Page](https://weiyana.github.io/Perception-in-Reflection/)
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
