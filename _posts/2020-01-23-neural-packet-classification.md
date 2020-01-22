---
layout: single
title: "Neural Packet Classification"
excerpt:  January 23, 2020
date: 2020-01-23
author_profile: true
author: Jennifer Rexford
categories: 
 - Webinars
---

**Date:** January 23, 2020<br/>
**Time:** 2:30-3:30pm ET<br/>
**Video:** {% include video id="xQn2kUWd4Jg" provider="youtube" %}

 
## Abstract
Packet classification is a fundamental problem in computer networking. This
problem exposes a hard tradeoff between the computation and state complexity,
which makes it particularly challenging. To navigate this tradeoff, existing
solutions rely on complex hand-tuned heuristics, which are brittle and hard to
optimize. 

We propose a deep reinforcement learning (RL) approach to solve the packet classification problem. There are several characteristics that make this problem a good fit for Deep RL. First, many existing solutions iteratively build a decision tree by splitting nodes in the tree. Second, the effects of these actions (e.g., splitting nodes) can only be evaluated once the entire tree is built. These two characteristics are naturally captured by the ability of RL to take actions that have sparse and delayed rewards. Third, it is computationally efficient to generate data traces and evaluate decision trees, which alleviate the notoriously high sample complexity problem of Deep RL algorithms. Our solution, NeuroCuts, uses succinct representations to encode state and action space, and efficiently explore candidate decision trees to optimize for a global objective. It produces compact decision trees optimized for a specific set of rules and a given performance metric, such as classification time, memory footprint, or a combination of the two. Evaluation on Class-Bench shows that NeuroCuts outperforms existing hand-crafted algorithms in classification time by 18% at the median, and reduces both classification time and memory footprint by up to 3X.

## Bio
Hang Zhu is a PhD student at Department of Computer Science, Johns Hopkins University, advised by Xin Jin. He is broadly interested in computer networks and distributed systems, with a focus on programmable networks and hardware-software co-design.
                      
