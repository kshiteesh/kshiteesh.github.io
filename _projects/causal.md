---
layout: page
title: Cause and Effect -- Can Large Language Models Truly Understand Causality?
description: abstract, paper, and some slides
img: 
importance: 1
category: work
giscus_comments: true
---
# Abstract
> With the rise of Large Language Models (LLMs), it has become crucial to understand their capabilities and limitations in deciphering and explaining the complex web of causal relationships that language entails. Current methods use either explicit or implicit causal reasoning, yet there is a strong need for a unified approach combining both to tackle a wide array of causal relationships more effectively. This research proposes a novel architecture called Context-Aware Reasoning Enhancement with Counterfactual Analysis (CARE-CA) to enhance causal reasoning and explainability. The proposed framework incorporates an explicit causal detection module with ConceptNet and counterfactual statements, as well as implicit causal detection through LLMs. Our framework goes one step further with a layer of counterfactual explanations to accentuate LLMs' understanding of causality. The knowledge from ConceptNet enhances the performance of multiple causal reasoning tasks such as causal discovery, causal identification, and counterfactual reasoning. The counterfactual sentences add explicit knowledge of 'not caused by' scenarios. By combining these powerful modules, our model aims to provide a deeper understanding of causal relationships, enabling enhanced interpretability. Evaluation of benchmark datasets shows improved performance across all metrics, such as accuracy, precision, recall, and F1 scores. We also present CausalNet, a novel dataset specifically curated to benchmark and enhance the causal reasoning capabilities of LLMs. This dataset is accompanied by code designed to facilitate further research in this domain.

# Intuition
> - It is crucial to understand LLMs' causal understanding capabilities
> - CARE-CA framework is proposed which uses explicit (ConcepNet) and implicit (counterfactual statements) causal reasoning to improve LLM performance
> - A new dataset CausalNet is provided that is specifically curated for benchmarking purposes

# Slides
Download [here](/assets/pdf/causal_aaai_2024_slides.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/causal_aaai_2024_slides.pdf" width="100%" height="500" type='application/pdf'></object>

# Paper
Download [here](/assets/pdf/causal_aaai_2024.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/causal_aaai_2024.pdf" width="100%" height="800" type='application/pdf'></object>
