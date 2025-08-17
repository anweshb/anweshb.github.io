---
title: "Bridging Both Worlds in Semantics and Time: Domain Knowledge Based Analysis and Correlation of Industrial Process Attacks"
date: 2023-01-01
publishDate: 2023-01-01
authors: ["Moses Ike", "Kandy Phan", "**Anwesh Badapanda**", "Matthew Landen", "Keaton Sadoski", "Wanda Guo", "Asfahan Shah", "Saman Zonouz", "Wenke Lee"]
publication_types: ["3"]
abstract: "Modern industrial control systems (ICS) attacks infect supervisory control and data acquisition (SCADA) hosts to stealthily alter industrial processes, causing damage. To detect attacks with low false alarms, recent work detects attacks in both SCADA and process data. Unfortunately, this led to the same problem - disjointed (false) alerts, due to the semantic and time gap in SCADA and process behavior, i.e., SCADA execution does not map to process dynamics nor evolve at similar time scales. We propose BRIDGE to analyze and correlate SCADA and industrial process attacks using domain knowledge to bridge their unique semantic and time evolution. This enables operators to tie malicious SCADA operations to their adverse process effects, which reduces false alarms and improves attack understanding. BRIDGE (i) identifies process constraints violations in SCADA by measuring actuation dependencies in SCADA process-control, and (ii) detects malicious SCADA effects in processes via a physics-informed neural network that embeds generic knowledge of inertial process dynamics. BRIDGE then dynamically aligns both analysis (i and ii) in a time-window that adjusts their time evolution based on process inertial delays. We applied BRIDGE to 11 diverse real-world industrial processes, and adaptive attacks inspired by past events. BRIDGE correlated 98.3% of attacks with 0.8% false positives (FP), compared to 78.3% detection accuracy and 13.7% FP of recent work."
featured: true
publication: "arXiv 2023 "
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://arxiv.org/abs/2311.18539'
---
