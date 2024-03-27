---
title: "MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution"
collection: publications
permalink: /publication/magis-2024
excerpt: 'In software evolution, resolving the emergent issues within GitHub repositories is a complex challenge that involves not only the incorporation of new code but also the maintenance of existing functionalities. Large Language Models (LLMs) have shown promise in code generation and understanding but face difficulties in code change, particularly at the repository level. To overcome these challenges, we empirically study the reason why LLMs mostly fail to resolve GitHub issues and analyze some impact factors. Motivated by the empirical findings, we propose a novel LLM-based Multi-Agent framework for GitHub Issue reSolution, MAGIS, consisting of four kinds of agents customized for the software evolution: Manager, Repository Custodian, Developer, and Quality Assurance Engineer agents. This framework leverages the collaboration of various agents in the planning and coding process to unlock the potential of LLMs to resolve GitHub issues. In experiments, we employ the SWE-bench benchmark to compare MAGIS with popular LLMs, including GPT-3.5, GPT-4, and Claude-2. MAGIS can resolve 13.94% GitHub issues, which significantly outperforms the baselines. Specifically, MAGIS achieves an eight-fold increase in resolved ratio over the direct application of GPT-4, the based LLM of our method. We also analyze the factors for improving GitHub issue resolution rates, such as line location, task allocation, etc.'
date: 2024-3-26
---

## Abstract

In software evolution, resolving the emergent issues within GitHub repositories is a complex challenge that involves not only the incorporation of new code but also the maintenance of existing functionalities. 

Large Language Models (LLMs) have shown promise in code generation and understanding but face difficulties in code change, particularly at the repository level. To overcome these challenges, we empirically study the reason why LLMs mostly fail to resolve GitHub issues and analyze some impact factors. 

Motivated by the empirical findings, we propose a novel LLM-based Multi-Agent framework for GitHub Issue reSolution, **MAGIS**, consisting of four kinds of agents customized for the software evolution: Manager, Repository Custodian, Developer, and Quality Assurance Engineer agents. This framework leverages the collaboration of various agents in the planning and coding process to unlock the potential of LLMs to resolve GitHub issues. 

In experiments, we employ the SWE-bench benchmark to compare MAGIS with popular LLMs, including GPT-3.5, GPT-4, and Claude-2. MAGIS can resolve **13.94%** GitHub issues, which significantly outperforms the baselines. Specifically, MAGIS achieves an eight-fold increase in resolved ratio over the direct application of GPT-4, the based LLM of our method. We also analyze the factors for improving GitHub issue resolution rates, such as line location, task allocation, etc.

## Links

- [View at Arxiv](https://arxiv.org/abs/2403.17927)

## Related Works

[KADEL: Knowledge-Aware Denoising Learning for Commit Message Generation](./tosem-2024)


## Recommended citation

### BibTex

```bibtex
@article{magis_24,
  author    = {Wei Tao and
               Yucheng Zhou and
               Wenqiang Zhang and
               Yu Cheng},
  title     = {MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution},
  journal   = {% raw %}{Arxiv Preprint}{% endraw %},
  url       = {https://arxiv.org/abs/2403.17927}
  year      = {2024}
}
```
