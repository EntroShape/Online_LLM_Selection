<div align="center">
    <h1> Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution
</div>


This repository provides an implementation of the algorithms presented in our paper: **"Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution."**

# Motivation

Large Language Models (LLMs) exhibit diverse capabilities, costs, and performance characteristics. Selecting the optimal LLM for a given user query, particularly in dynamic, multi-step interactions where the prompt evolves based on prior responses (unstructured context evolution), is a significant challenge. Traditional methods often struggle with this unpredictability.

This paper proposes a novel **contextual bandit framework** for adaptive multi-LLM selection in such online settings. By making "myopic" decisions—choosing the best LLM for the current context at each step—the framework avoids the need to model or predict complex future context changes. This approach enables efficient, theoretically grounded LLM selection without offline datasets or model-specific fine-tuning.

This repository implements the core algorithms from the paper, designed to improve accuracy and cost-efficiency in real-time, adaptive multi-LLM systems.

# How to Use

To run the code, please first create your own Openrouter API key with credit before running the code. If you want to run it on the Colab directly, then please upload the Math500 dataset under the same directory. After that, we can directly run the code. 

# Data Source and Note

In the paper, we have experimented with the method on four datasets (Math500, AIME, GPQA, MMLU-Pro). This repo, in particular, is the implementation of the math500 dataset only. Please cite also the corresponding dataset appropriately if used. 

# Citation
Please cite the work if our work have contributed to your work!

```bibtex
@misc{poon2025online,
      title={{Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution}}, 
      author={Manhin Poon and XiangXiang Dai and Xutong Liu and Fang Kong and John C.S. Lui and Jinhang Zuo},
      year={2025},
      eprint={2506.17670},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2506.17670}
}
```
