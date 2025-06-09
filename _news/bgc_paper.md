---
layout: post
title: Our preprint "Unified Genomic and Chemical Representations Enable Bidirectional Bio-synthetic Gene Cluster and Natural Product Retrieval" is now on bioRxiv!
date: 2025-05-31
inline: false
related_posts: false
---

🗿 In 1799, the discovery of the Rosetta Stone allowed us to decipher Egyptian hieroglpyhs by aligning them with Ancient Greek and Demotic scripts, giving us a common medium to understand 3 languages.

💥In our latest work, we're aiming to do something similar… but for genomes (biology) and molecules (chemistry)!

📄 Read the preprint here: [https://www.biorxiv.org/content/10.1101/2025.05.31.656985v1.full](https://www.biorxiv.org/content/10.1101/2025.05.31.656985v1.full)

🔍 What’s the challenge?
Microbial genomes contain biosynthetic gene clusters (BGCs) responsible for producing specialized metabolites, many of which are useful to us as pharmaceuticals, fragrances, and more! However, mapping BGCs to their chemical products, and vice versa, has been a bottleneck due to the complex relationship between a BGC's nucleotide sequence and the molecular structure of its chemical product. DNA and chemicals "speak" fundamentally different languages: one is a linear string of genetic code, the other is a tangled 3D web of atoms and bonds.

🧬🧪What we did:
We introduce BCCoE, a cross-modal deep learning framework that acts like a Rosetta Stone between genomics and chemistry. By projecting BGCs and small molecules into a shared embedding space, we can:
1. 🔄 Predict what BGC produces a given molecule and what molecule a given BGC produces (yes, both directions!)
2. 🧠Use pre-trained language models (like BiGCARP and MoLFormer) to encode genomic and chemical "languages"
3. ⏱️Prioritize microbial strains likely to produce a molecule of interest in retrobiosynthesis

📊Key results:
1. Retrieved up to 65% of true BGC-compound pairs in the top 10 search results (vs. <5% for random selection!)
2. Generalized across unseen compound classes and unseen data from new MIBiG updates
3. In a real-world case study, it correctly identified a microbial strain producing BE-54476-A/B tetramic acids—starting from the compound structure alone!🤯

💡Why it matters:
By bridging the gap between genes and molecules, BCCoE could streamline strain prioritization, bioprospecting, and retrosynthetic design. It’s a step toward a unified, data-driven future in natural product discovery and synthesis.
