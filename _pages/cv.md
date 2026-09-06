---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, specializing in Large Language Models, 2023-present
* M.S. in Artificial Intelligence, 2020-2023
* B.S. in Computer Science, 2016-2020

Research Experience
======
* 2023-Present: Lead Researcher
  * Focus: Large Language Model optimization, contextual reasoning, adaptive learning systems
  * Projects:
    - Enhancing LLMs with improved contextual understanding (`enhancing-llms`)
    - Optimizing LLM contextual reasoning capabilities (`optimizing-llms-contextual-reasoning`)
    - Developing adaptive learning frameworks for AI education (`llm-adaptive-learning`)
    - Building benchmark task collections for LLM evaluation (`BenchTasksCollv3`)

* 2020-2023: Research Assistant
  * Worked on LLM fine-tuning techniques and educational AI applications
  * Contributed to multiple peer-reviewed publications on LLM performance optimization

Skills
======
* Programming Languages: Python, PyTorch, TensorFlow, JavaScript
* AI/ML: Large Language Models (LLMs), Fine-tuning, Prompt Engineering, RAG
* Research: Experimental design, benchmarking, academic writing, peer review
* Tools: Git, GitHub, Jupyter, Docker, Kubernetes, Hugging Face Ecosystem
* Domains: Adaptive Learning, AI Education, Contextual Reasoning, LLM Optimization

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  * Multiple peer-reviewed publications on LLM optimization and adaptive learning systems

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  * Presented research findings at AI/ML conferences and workshops

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  * Taught courses on Machine Learning, Natural Language Processing, and AI Education

Service and leadership
======
* Active reviewer for top AI/ML conferences (NeurIPS, ICML, ICLR, ACL)
* Organizer of workshops on LLM Education and Adaptive Learning
* Open source contributor to multiple AI/ML projects and educational tools
