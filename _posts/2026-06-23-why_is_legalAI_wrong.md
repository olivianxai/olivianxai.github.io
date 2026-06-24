---
title: "What's Wrong With Where Legal AI Is Heading"
date: 2026-06-23
permalink: /posts/2026/06/23/why_is_legal_ai_wrong
tags:
  - Legal
  - AI
---

Full disclaimer before I begin: I'm not saying all Legal AI is wrong, and I won't pretend I've evaluated every product on the market. My assessment draws from podcasts, YouTube videos, and articles I've read — so take it in that spirit. I'm also specifically focused on legal reasoning products, or products positioned to assist with legal reasoning.

A question I've been sitting with lately: if I were to build my own legal AI product, what would I do differently?

I remember a conversation with a recruiter from Thomson Reuters at NeurIPS in December 2025. I was pitching my idea for a neuro-symbolic model built for reliable, trustworthy legal applications. He looked at me and said they were hiring people to build foundation models. (disclaimer: no shades on TR lab. I am just using this incident as an example.)

Right. Another one chasing the foundation model hype.

Which raises a genuine question — is a foundation model actually the right approach for this field? Or is everyone scrambling to build one simply out of FOMO?

I get it. FOMO is real. Look at K&E committing $500 million to build their own internal AI tool. Even if that's a rounding error for a firm their size, building it right at least means you end up with something useful, rather than just torching the money. But here's the problem: for high-stakes domains like law, where reliability is non-negotiable and mistakes carry serious consequences, general-purpose generative AI is not the answer.


The core issue with generative models is that there's no guarantee the model will actually internalize the rules of a domain just from the data it's trained on. Magesh et al. demonstrated this well — RAG (Retrieval-Augmented Generation) helped, but it wasn't enough. RAG is an information retrieval technique: when you need relevant precedent, it will surface related cases. But it has no understanding of how legal systems actually work. If a case was later overturned, RAG doesn't know that. Without a human actively checking, the wrong information gets used and propagates through legal reasoning. That's just one failure mode. Scaling up with more data, more parameters, a bigger model doesn't fix this. It doesn't give the model an understanding of legal structure. Assuming it'll figure that out from training data alone is, frankly, naive.
So what's the alternative?


Structure needs to be built into the model from the start, not hoped for as an emergent property. This is where neuro-symbolic AI comes in — and yes, it's no secret that's where my research sits, with a particular focus on legal applications.


The idea isn't to throw out generative AI entirely. It's to use it for what it's actually good at, while letting symbolic AI serve as the reasoning engine. Symbolic AI alone has scalability problems, but that's where neural networks can help, for instance by assisting in constructing legal ontologies, with a human in the loop to verify the output. The overarching principle is to keep symbolic AI as the decision-making backbone and use neural networks to fill in the gaps where symbolic AI falls short.


We need to be honest about the limits of each approach and design systems around those limits, not paper over them by throwing more compute at the problem.



Magesh, V., Surani, F., Dahl, M., Suzgun, M., Manning, C. D., & Ho, D. E. (2025). Hallucination‐free? Assessing the reliability of leading AI legal research tools. Journal of empirical legal studies, 22(2), 216-242.