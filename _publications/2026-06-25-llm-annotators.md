---
title: "The Context Dependency of Demographic Bias in LLM Annotation"
collection: publications
category: conferences
permalink: /publication/2026-06-25-llm-annotators
excerpt: "Generative large language models (LLMs) are now widely used in computational social science for automated annotation tasks. Using datasets..."
date: 2026-06-25
venue: 'ACM Conference on Farness, Accountability, and Transparency'
#slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://dl.acm.org/doi/10.1145/3805689.3812212'
citation: 'Brown, M. A., Atreja, S., Hemphill, L., & Wu, P. Y. (2026, June). The Context Dependency of Demographic Bias in LLM Annotation. In The 2026 ACM Conference on Fairness, Accountability, and Transparency (pp. 7475-7497).'
---

Generative large language models (LLMs) are now widely used in computational social science for automated annotation tasks. Using datasets where ground truth labels are associated with the demographics of the human annotator, recent research has demonstrated that generative LLMs may produce annotations that agree more frequently with socially dominant groups. These findings raise important concerns about deploying LLM-as-a-judge for social science annotation tasks. However, it remains unclear whether this demographic bias is consistent across subjective annotation tasks and datasets to warrant uniform mitigation strategies, or whether bias manifests differently depending on the annotation contexts. In this paper, we use four annotation tasks on four datasets to show that LLMs do not show systematic, substantial disagreement with annotators on the basis of demographics. Rather, we find that within datasets, LLMs exhibit bias in the same directions, but across datasets, LLMs differ in which demographics they agree with. We conclude by arguing that neither generic bias benchmarks nor switching to a different LLM guarantees different demographic alignments; both may provide false assurances. Rather, fairness evaluations must be bespoke for each dataset and task.1


