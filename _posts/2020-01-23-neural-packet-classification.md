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

<table class="table">
                        <tr><td><strong>Date</strong></td><td>January 23, 2020</td></tr>
                        <tr><td><strong>Time</strong></td><td>2:30-3:30pm ET</td></tr>
                        <tr><td><strong>Video</strong></td><td>Coming soon.</td></tr>
                        <tr><td><strong>Abstract</strong></td><td><p>
Packet classification is a fundamental problem in computer networking. This
problem exposes a hard tradeoff between the computation and state complexity,
which makes it particularly challenging. To navigate this tradeoff, existing
solutions rely on complex hand-tuned heuristics, which are brittle and hard to
optimize. </br>

We propose a deep reinforcement learning (RL) approach to solve the packet classification problem. There are several characteristics that make this problem a good fit for Deep RL. First, many existing solutions iteratively build a decision tree by splitting nodes in the tree. Second, the effects of these actions (e.g., splitting nodes) can only be evaluated once the entire tree is built. These two characteristics are naturally captured by the ability of RL to take actions that have sparse and delayed rewards. Third, it is computationally efficient to generate data traces and evaluate decision trees, which alleviate the notoriously high sample complexity problem of Deep RL algorithms. Our solution, NeuroCuts, uses succinct representations to encode state and action space, and efficiently explore candidate decision trees to optimize for a global objective. It produces compact decision trees optimized for a specific set of rules and a given performance metric, such as classification time, memory footprint, or a combination of the two. Evaluation on Class-Bench shows that NeuroCuts outperforms existing hand-crafted algorithms in classification time by 18% at the median, and reduces both classification time and memory footprint by up to 3X.
                        </p></td></tr>
                        <tr><td><strong>Bio</strong></td><td><p>
Hang Zhu is a PhD student at Department of Computer Science, Johns Hopkins University, advised by Xin Jin. He is broadly interested in computer networks and distributed systems, with a focus on programmable networks and hardware-software co-design.
<tr><td colspan="2"></tr>
                        </table>
