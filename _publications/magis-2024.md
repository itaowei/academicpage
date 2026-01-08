---
title: "MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution"
collection: publications
permalink: /publication/magis-2024
excerpt: 'In software development, resolving the emergent issues within GitHub repositories is a complex challenge that involves not only the incorporation of new code but also the maintenance of existing code. Large Language Models (LLMs) have shown promise in code generation but face difficulties in resolving Github issues, particularly at the repository level. To overcome this challenge, we empirically study the reason why LLMs fail to resolve GitHub issues and analyze the major factors. Motivated by the empirical findings, we propose a novel LLM-based Multi-Agent framework for GitHub Issue reSolution, MAGIS, consisting of four agents customized for software evolution: Manager, Repository Custodian, Developer, and Quality Assurance Engineer agents. This framework leverages the collaboration of various agents in the planning and coding process to unlock the potential of LLMs to resolve GitHub issues. In experiments, we employ the SWE-bench benchmark to compare MAGIS with popular LLMs, including GPT-3.5, GPT-4, and Claude-2. MAGIS can resolve 13.94% GitHub issues, significantly outperforming the baselines. Specifically, MAGIS achieves an eight-fold increase in resolved ratio over the direct application of GPT-4, the advanced LLM. '
date: 2024-3-26
---

## Abstract

In software development, resolving the emergent issues within GitHub repositories is a complex challenge that involves not only the incorporation of new code but also the maintenance of existing code. 

Large Language Models (LLMs) have shown promise in code generation but face difficulties in resolving Github issues, particularly at the repository level.

To overcome this challenge, we empirically study the reason why LLMs fail to resolve GitHub issues and analyze the major factors. Motivated by the empirical findings, we propose a novel LLM-based **M**ulti-**A**gent framework for **G**itHub **I**ssue re**S**olution, **MAGIS**, consisting of four agents customized for software evolution: Manager, Repository Custodian, Developer, and Quality Assurance Engineer agents.

This framework leverages the collaboration of various agents in the planning and coding process to unlock the potential of LLMs to resolve GitHub issues.

In experiments, we employ the SWE-bench benchmark to compare MAGIS with popular LLMs, including GPT-3.5, GPT-4, and Claude-2.

MAGIS can resolve **13.94**% GitHub issues, significantly outperforming the baselines. Specifically, MAGIS achieves an eight-fold increase in resolved ratio over the direct application of GPT-4, the advanced LLM. 

## Links

- [View at Arxiv](https://arxiv.org/abs/2403.17927)

- [View at NeurIPS](https://neurips.cc/virtual/2024/poster/93481)


## Related Works

[KADEL: Knowledge-Aware Denoising Learning for Commit Message Generation](./tosem-2024)


## Recommended citation

### BibTex

```bibtex
@inproceedings{DBLP:conf/nips/0003ZWZ0C24,
  author       = {Wei Tao and
                  Yucheng Zhou and
                  Yanlin Wang and
                  Wenqiang Zhang and
                  Hongyu Zhang and
                  Yu Cheng},
  editor       = {Amir Globersons and
                  Lester Mackey and
                  Danielle Belgrave and
                  Angela Fan and
                  Ulrich Paquet and
                  Jakub M. Tomczak and
                  Cheng Zhang},
  title        = {{MAGIS:} LLM-Based Multi-Agent Framework for GitHub Issue Resolution},
  booktitle    = {Advances in Neural Information Processing Systems 38: Annual Conference
                  on Neural Information Processing Systems 2024, NeurIPS 2024, Vancouver,
                  BC, Canada, December 10 - 15, 2024},
  year         = {2024},
  url          = {http://papers.nips.cc/paper\_files/paper/2024/hash/5d1f02132ef51602adf07000ca5b6138-Abstract-Conference.html},
  timestamp    = {Wed, 02 Jul 2025 18:51:55 +0200},
  biburl       = {https://dblp.org/rec/conf/nips/0003ZWZ0C24.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
