[![arXiv](https://img.shields.io/badge/arXiv-2610.11736-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2610.11736)

# Towards Unified Evaluation of Prompt Enhancers for Video Generation

## ✅ TODO List

 - [x] Prompt data & Reference assets
 - [ ] Evaluation code

## 📝 Abstract

Modern video generators can realize increasingly complex visual narratives, positioning the prompt enhancer (PE) as a critical bridge from concise user instructions and multimodal references to structured cinematic plans. However, existing PE evaluation relies on rendered videos, imposing substantial computational and human costs, slowing PE training and iteration, and conflating PE quality with downstream generator behavior. To address this gap, we introduce PEBench, the first unified benchmark for direct PE evaluation across text-to-video, image-to-video, and reference-to-video prompt enhancement. It comprises 1,100 expert-verified cases and 1,005 visual assets, spanning 35 fine-grained tasks with diverse temporal, cinematic, audiovisual, and multi-reference requirements. In addition, we develop PEBench evaluation, an evidence-grounded framework that combines modality-aware fact extraction with rubric-based assessment across 24 criteria. Our systematic evaluation of representative open- and closed-source PE methods reveals an emerging shift from fine-grained descriptive expansion toward intent-preserving cinematic planning, while the caption-reconstruction and forward-refinement methods show complementary strengths in cinematic coverage and semantic fidelity or internal coherence, respectively. Human validation shows that PEBench scores align closely with expert judgments of enhanced prompts and downstream videos from Wan3.0 and MiniMax-H3, indicating that prompt-level evaluation reliably reflects downstream utility.

## 💡 Overview

<p align="center">
    <img src="./images/overview.png" width="100%"/>
</p>

## 🏗️ Data Construction Pipeline

<p align="center">
    <img src="./images/data_construct.png" width="100%"/>
</p>

## 📊 Data Statistics and Diversity

<p align="center">
    <img src="./images/data_analysis.png" width="100%"/>
</p>

## 🔍 Qualitative Failure Cases

<p align="center">
    <img src="./images/fail_case.png" width="100%"/>
</p>

## 🌟 Citation

If you find this code useful for your research, please cite our paper:

```
@misc{PEBench,
      title={Towards Unified Evaluation of Prompt Enhancers for Video Generation}, 
      author={Yawen Shao and Yubo Zhu and Ziyun Dai and Zixun Fang and Kai Zhu and Zeyinzi Jiang and Yufeng Ai and Siyang Sun and Haolan Xue and Yu Shang and Yuxiang Bao and Zoubin Bi and Jingming Luo and Jie Xiao and Chaojie Mao and Zhehan Kan and Hongchen Luo and Yu Liu and Sheng Zhong and Wei Tong and Xueyang Fu and Yang Cao and Wei Zhai and Zheng-Jun Zha},
      year={2026},
      eprint={2610.11736},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2610.11736}, 
}
```
