---
title: Home
---

{% include figure.html img="colorai.png" alt="colorai logo" width="75%" %}

Many of the recent advancements in AI are due to exploiting <i><b>structured low-rank representations</b></i>, from  low-rank tensor factorizations (Kolda and Bader 2009) for scaling large language models (LLMs), e.g., via adapters (Hu et al. 2021) or structured matrices
(Dao et al. 2022); the diffusion of compact polynomial representations as powerful inductive biases for deep learning architectures (Cheng et al. 2024); the emergence of probabilistic circuits to provide tractable probabilistic inference with guarantees (Choi, Vergari, and Van den Broeck 2020) and reliable neuro-symbolic AI (Ahmed et al. 2022); and the wide application of tensor networks to solve and accelerate physics-related problems (Biamonte and Bergholm 2017) and quantum computing (Orus 2019). 

### "How are all these representations related to each others? and how can we transfer knowledge across communities?"




<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

# Organizers

- [Antonio Vergari](https://april-tools.github.io/)
- [Grigorios Chrysos](https://grigoris.ece.wisc.edu/)
- [Chao Li](https://scholar.google.com/citations?user=i4JrumAAAAAJ)
- [Deanna Needell](https://www.math.ucla.edu/∼deanna)

> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
