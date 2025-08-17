---
title: "Bridge-Coder: Unlocking LLMs' Potential to Overcome Language Gaps in Low-Resource Code"
collection: publications
category: manuscripts
permalink: _publications/2024-10-24-BridgeCoder
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-10-24
# venue: 'Journal 1'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2410.18957'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Large Language Models (LLMs) demonstrate strong proficiency in generating code for high-resource programming languages (HRPLs) like Python but struggle significantly with low-resource programming languages (LRPLs) such as Racket or D. This performance gap deepens the digital divide, preventing developers using LRPLs from benefiting equally from LLM advancements and reinforcing disparities in innovation within underrepresented programming communities. While generating additional training data for LRPLs is promising, it faces two key challenges: manual annotation is labor-intensive and costly, and LLM-generated LRPL code is often of subpar quality. The underlying cause of this issue is the gap between natural language to programming language gap (NL-PL Gap), which is especially pronounced in LRPLs due to limited aligned data. In this work, we introduce a novel approach called Bridge-Coder, which leverages LLMs' intrinsic capabilities to enhance the performance on LRPLs. Our method consists of two key stages. Bridge Generation, where we create high-quality dataset by utilizing LLMs' general knowledge understanding, proficiency in HRPLs, and in-context learning abilities. Then, we apply the Bridged Alignment, which progressively improves the alignment between NL instructions and LRPLs. Experimental results across multiple LRPLs show that Bridge-Coder significantly enhances model performance, demonstrating the effectiveness and generalization of our approach. Furthermore, we offer a detailed analysis of the key components of our method, providing valuable insights for future work aimed at addressing the challenges associated with LRPLs.
