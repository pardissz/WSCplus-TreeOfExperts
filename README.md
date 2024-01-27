# WSC+: Enhancing The Winograd Schema Challenge Using Tree-of-Experts

## Introduction
Welcome to the GitHub repository for our EACL 2024 paper, "WSC+: Enhancing The Winograd Schema Challenge Using Tree-of-Experts". This project explores the capabilities of Large Language Models (LLMs) in generating questions for the Winograd Schema Challenge (WSC), a benchmark for evaluating machine understanding. We introduce a novel prompting method, Tree-of-Experts (ToE), and a new dataset, WSC+, to provide deeper insights into model overconfidence and bias.

## Abstract
The Winograd Schema Challenge (WSC) serves as a prominent benchmark for evaluating machine understanding. While Large Language Models (LLMs) excel at answering WSC questions, their ability to generate such questions remains less explored. In this work, we propose Tree-of-Experts (ToE), a novel prompting method which enhances the generation of WSC instances (50% valid cases vs. 10% in recent methods). Using this approach, we introduce WSC+, a novel dataset comprising 3,026 LLM-generated sentences. Notably, we extend the WSC framework by incorporating new 'ambiguous' and 'offensive' categories, providing a deeper insight into model overconfidence and bias. Our analysis reveals nuances in generation-evaluation consistency, suggesting that LLMs may not always outperform in evaluating their own generated questions when compared to those crafted by other models. On WSC+, GPT-4, the top-performing LLM, achieves an accuracy of 68.7%, significantly below the human benchmark of 95.1%.

## Contributions
Our key contributions in this work are threefold:

1. **WSC+ Dataset**: We unveil WSC+, featuring 3,026 LLM-generated instances. This dataset augments the original WSC with categories like 'ambiguous' and 'offensive'. Intriguingly, GPT-4 (OpenAI, 2023), despite being a front-runner, scored only 68.7% on WSC+, well below the human benchmark of 95.1%.

2. **Tree-of-Experts (ToE)**: We present Tree-of-Experts, an innovative method which we apply to WSC+ instance generation. ToE improves the generation of valid WSC+ sentences by nearly 40% compared to recent methods such as Chain-of-Thought (Wei et al., 2022).

3. **Generation-Evaluation Consistency**: We explore the novel concept of generation-evaluation consistency in LLMs, revealing that models, such as GPT-3.5, often underperform on instances they themselves generate, suggesting deeper reasoning disparities.

## Overview of WSC+ Generation and Evaluation Processes
![MAIN_H](https://github.com/pardissz/WSCplus-TreeOfExperts/assets/81924808/b3f7cba6-afa3-414a-bed6-9b0d0a10ddfa)

## Contact
For any questions or inquiries, please feel free to reach out to us at pardis.zahraei01 [at] sharif [dot] edu

