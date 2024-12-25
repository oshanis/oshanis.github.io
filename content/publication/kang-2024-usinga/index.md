---
title: Using Large Language Models for Generating Smart Contracts for Health Insurance
  from Textual Policies
authors:
- Inwon Kang
- William Van Woensel
- Oshani Seneviratne
date: '2024-01-01'
publishDate: '2024-12-25T15:35:15.747451Z'
publication_types:
- chapter
publication: '*AI for Health Equity and Fairness: Leveraging AI to Address Social
  Determinants of Health*'
doi: 10.1007/978-3-031-63592-2_11
abstract: "We explore using Large Language Models (LLMs) to generate application code
  that automates health insurance processes from text-based policies. We target blockchain-based
  smart contracts as they offer immutability, verifiability, scalability, and a trustless
  setting: any number of parties can use the smart contracts, and they need not have
  previously established trust relationships with each other. Our methodology generates
  outputs at increasing levels of technical detail: (1) textual summaries, (2) declarative
  decision logic, and (3) smart contract code with unit tests. We ascertain LLMs are
  good at task (1), and the structured output is useful to validate tasks (2) and
  (3). Declarative languages (task 2) are often used to formalize healthcare policies,
  but their execution on blockchain is non-trivial. Hence, task (3) attempts to directly
  automate the process using smart contracts. To assess the LLM output, we propose
  completeness, soundness, clarity, syntax, and functioning code as metrics. Our evaluation
  employs three health insurance policies (scenarios) with increasing difficulty from
  Medicare's official booklet. Our evaluation uses GPT-3.5 Turbo, GPT-3.5 Turbo 16K,
  GPT-4, GPT-4 Turbo and CodeLLaMA. Our findings confirm that LLMs perform quite well
  in generating textual summaries. Although outputs from tasks (2)--(3) are useful
  starting points, they require human oversight: in multiple cases, even ``runnable''
  code will not yield sound results; the popularity of the target language affects
  the output quality; and more complex scenarios still seem a bridge too far. Nevertheless,
  our experiments demonstrate the promise of LLMs for translating textual process
  descriptions into smart contracts."
links:
- name: URL
  url: https://doi.org/10.1007/978-3-031-63592-2_11
---
