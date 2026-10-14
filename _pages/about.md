---
permalink: /
title: "Jiakun Fan"
excerpt: "Research in MLSys, efficient LLM inference, and RSI infrastructure."
author_profile: true
profile_page: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="profile-focus">MLSys, efficient LLM inference, and RSI infrastructure.</p>

I am a Computer Science Ph.D. student at [Virginia Tech](https://www.vt.edu/),
advised by [Dimitrios S. Nikolopoulos](https://dsniko.github.io/), with expected
graduation in May 2028. I am currently a Research Scientist Intern at ByteDance
in San Jose, working on efficient LLM inference.

My research connects model algorithms with the systems that make them useful:
diffusion-drafted speculative decoding, memory-efficient LLM serving,
heterogeneous CPU-GPU execution, and reliable long-horizon AI research loops.
I am especially interested in agents that improve through feedback and the
infrastructure needed to run, evaluate, and reproduce their experiments.

I am seeking research internships for Summer 2027 in these areas.

[Download my CV]({{ '/files/Jiakun_Fan_CV.pdf' | relative_url }}) ·
[Google Scholar]({{ site.author.googlescholar }}) ·
[LinkedIn](https://www.linkedin.com/in/jiakun-fan-6a748828a) ·
[Email](mailto:vincentdftbg@gmail.com)

## Research

- Long-horizon autonomous research infrastructure: coordinated GPU experiments,
  candidate evaluation, experiment lineage, and recovery from execution failures.
- Efficient LLM inference: diffusion-based speculative decoding, memory-aware
  serving, and heterogeneous execution.
- Agentic LLM serving: high-level research on KV cache management for
  long-context, multi-turn workloads.

[Selected research projects]({{ '/projects/' | relative_url }})

## Selected publications and manuscripts

{% include research-publications.html limit=3 %}

[All selected publications]({{ '/publications/' | relative_url }})
