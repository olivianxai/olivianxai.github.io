---
title: "Is AI Really Non-Deterministic? What Legal Practitioners Need to Know"
date: 2026-06-14
permalink: /posts/2026/06/14/is_AI_not_deterministic
tags:
  - Legal
  - AI
---

I was listening to the *Weekend Law* podcast from Bloomberg Law this morning, where Justin Daniels — an AI and tech law expert and shareholder at Baker Donelson — shared how lawyers are using AI. One point he made stuck with me: AI is good at pattern matching, but you shouldn't confuse probabilities with certainties.

He's right about generative AI. But the broader claim that *all* AI is probabilistic deserves more nuance.

## Not All AI Is Created Equal

Most people's exposure to AI today is through generative AI — specifically, Large Language Models (LLMs). These are indeed probabilistic, and that distinction matters enormously in a regulated field like law. But AI has a longer history, and understanding its three waves helps clarify what we should and shouldn't trust it to do.

**The First Wave: Symbolic AI.** Also known as expert systems or decision trees, symbolic AI is fundamentally *deterministic*. It follows explicit, handcrafted rules — much like the codebooks and statutes that govern legal practice. Take tax law: filing status, exemptions, and marital status feed into a structured decision tree that calculates your bracket and deductions with predictable, auditable results. Symbolic AI worked well, but handcrafting rules at scale proved to be its fatal bottleneck.

**The Second Wave: Neural Networks (Generative AI).** Neural networks solved the scalability problem symbolic AI couldn't, but introduced new ones: they are probabilistic, opaque, and essentially a black box. In high-stakes, regulated fields, you cannot guarantee correctness, and you cannot reliably audit the reasoning trail. This is why post-hoc human verification is not optional — it's a professional obligation. LLMs are the most prominent example of this wave today.

**The Third Wave: Neuro-Symbolic AI (NeSy).** Researchers recognized that neither approach alone was sufficient — neural networks aren't reliable, and symbolic AI isn't scalable — so they began combining them. The goal is to inherit scalability from neural networks and reliability from symbolic AI. The direction is sound, but the execution has largely fallen short. Most state-of-the-art NeSy models still position the neural network as the primary reasoning engine, which undermines the very purpose of reintroducing symbolic AI. Using an unreliable system as the reasoning core, even when wrapped in symbolic structure, is letting the fox guard the henhouse.

## So What Does This Mean for Legal Practitioners?

Understanding these distinctions isn't just academic — it should directly shape how you integrate AI into your practice.

I agree with Justin: the right way to use generative AI is as a tool for *better judgment*, not a substitute for it. A lawyer must sign off on their work and bear full ethical responsibility, regardless of what tools were used along the way. Blindly trusting AI output without verification edges dangerously close to malpractice.

But here's what often gets overlooked: **learning to use LLMs effectively is itself a professional skill that needs to be developed deliberately.**

Generative AI is very good at generating — which sounds obvious, but the implication is that its output tends to be lengthy, often repetitive, and easy to skim past without real scrutiny. Human nature, pressure, and fatigue are real factors, and an AI that produces confident-sounding paragraphs is a surprisingly easy thing to trust in a moment of weakness.

The antidote isn't avoidance — it's structure. The more specific and constrained the task you assign, the better the output. Think of it as fitting the model into a mold you've designed, so it does exactly what you ask and no more, while you remain the centerpiece that has to sign off on the mission. 

**A practical example for citation work:** Rather than asking an LLM to generate citations for you, break the task into verifiable steps. First, use a purpose-built tool like Bloomberg Law's case analyzer to surface relevant precedents. Then verify those cases exist in LexisNexis or Westlaw. Then — and only then — ask the LLM to explain *why* and *how* each case supports your argument, pointing to specific language, whether that looks like returning the line numbers or highlighting the relevant parts is up to you, but the key is to make it easy for you find and verify against it. Your job becomes checking whether that language actually exists and whether the LLM's interpretation genuinely holds up. Summarization gets delegated; legal interpretation stays with you.

This is the shift: from reading mountains of raw precedent yourself, to reading AI-generated digests *against* original documents, applying your legal judgment as the grounding mechanism. You remain the center of the decision system. The AI cannot make the call for you — by design.

## The Bottom Line

LLMs are not replacing lawyers anytime soon. But that's not a reason to be complacent. The legal profession will need to evolve — not by abandoning human judgment, but by learning which tasks are safe to delegate, which require close verification, and how to build workflows that make AI-assisted errors visible rather than invisible.

In the end, your name is on the line. But if you learn to use these tools deliberately, an LLM can be one of the most capable paralegals you've ever worked with — as long as you stay the one in charge.

---