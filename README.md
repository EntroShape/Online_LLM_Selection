<div align="center">
    <h1> Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution
</div>


This repository provides an implementation of the algorithms presented in our paper: **"Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution."**

# Motivation

Large Language Models (LLMs) exhibit diverse capabilities, costs, and performance characteristics. Selecting the optimal LLM for a given user query, particularly in dynamic, multi-step interactions where the prompt evolves based on prior responses (unstructured context evolution), is a significant challenge. Traditional methods often struggle with this unpredictability.

This paper proposes a novel **contextual bandit framework** for adaptive multi-LLM selection in such online settings. By making "myopic" decisions—choosing the best LLM for the current context at each step—the framework avoids the need to model or predict complex future context changes. This approach enables efficient, theoretically grounded LLM selection without offline datasets or model-specific fine-tuning.

This repository implements the core algorithms from the paper, designed to improve accuracy and cost-efficiency in real-time, adaptive multi-LLM systems.

# Data Source and Note

In the paper, we have experimented with the method on four datasets (Math500, AIME, GPQA, MMLU-Pro). This repo, in particular, is the implementation of the math500 dataset only. Please cite also the corresponding dataset appropriately if used. Also, please note that our code implementation uses Openrouter as a Unified API provider, please create your own API key before running the code.
