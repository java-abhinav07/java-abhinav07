---
title: "One Shot Doc Snippet Detection: Powering Search in Documents beyond Text"
collection: publications
permalink: /publication/monomer
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-03-03
venue: 'Preprint'
paperurl: 'https://arxiv.org/abs/2209.06584'
citation: '<b>Java, A.</b>, Deshmukh, S., Aggarwal, M., Jandial, S., Sarkar, M., & Krishnamurthy, B (2022). One-Shot Doc Snippet Detection: Powering Search in Document Beyond Text
.'
image: "../images/monomer.png"
---
Active consumption of digital documents has yielded scope for research in various applications, including search. Traditionally, searching within a document has been cast as a text matching problem ignoring the rich layout and visual cues commonly present in structured documents, forms, etc. To that end, we ask a mostly unexplored question: "Can we search for other similar snippets present in a target document page given a single query instance of a document snippet?". We propose MONOMER to solve this as a one-shot snippet detection task. MONOMER fuses context from visual, textual, and spatial modalities of snippets and documents to find query snippet in target documents. We conduct extensive ablations and experiments showing MONOMER outperforms several baselines from one-shot object detection (BHRL), template matching, and document understanding (LayoutLMv3). Due to the scarcity of relevant data for the task at hand, we train MONOMER on programmatically generated data having many visually similar query snippets and target document pairs from two datasets - Flamingo Forms and PubLayNet. We also do a human study to validate the generated data.