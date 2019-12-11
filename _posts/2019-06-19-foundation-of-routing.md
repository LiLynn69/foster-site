---
layout: single
title: "Workshop on Foundations of Routing"
excerpt:  This workshop will bring together leading researchers and industrial practitioners from the theory and networking communities to discuss recent successes and future challenges related to routing. 
categories: 
  - Events
header:
  overlay_image: /assets/img/fibre.jpg
  teaser: /assets/img/fibre.jpg
---

## Overview
A common objective in many computer networks is to balance traffic across multiple paths in order to improve throughput, reduce congestion, and achieve higher utilization. But while there is an extensive theoretical literature on how best to route traffic through a capacitated network, many networks today rely on schemes that are easy to implement but do not perform well in practice.

This workshop will bring together leading researchers and industrial practitioners from the theory and networking communities to discuss recent successes and future challenges related to routing.

## Program
    <section id="program" class="bg-light-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">Program</h2>
                </div>
                <div class="col-lg-8 col-lg-offset-2">
                    <p><table class="table">
                            <tr><td colspan="2" align="center"><b>June 19th, 2019</b></td></tr>

                            <tr><td style="width:20%">8:15am-9:00am</td>
                                <td style="width:80%">
                                    <i class="text-muted">Breakfast</i>
                            </td></tr>

                            <tr><td>9:00am-9:15am</td><td>
                                    <i class="text-muted">Welcome</i>
                            </td></tr>

                            <tr><td>9:15am-10:15am</td><td>
                                    Synthesizing Load-Sensitive Routing Protocols for Programmable Switches
                                    <br/>
                                    <a href="http://www.cs.princeton.edu/~jrex/">Jennifer Rexford</a>
                                    <i class="text-muted">(Princeton)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#rexford_abstract" aria-expanded="true" aria-controls="rexford_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="rexford_abstract">
                                        <small class="text-muted">
                                            We show how a distributed set of network switches can adapt routing to traffic changes at hardware speeds.  While existing work has developed point solutions for a fixed topology (e.g., a Fattree) with a fixed routing policy (e.g., use least-utilized paths), our solution can be configured to operate seamlessly over any network topology and a wide variety of sophisticated routing policies.  Users write network-wide policies that rank network paths given their current performance.  A compiler then analyzes such policies in conjunction with the network topology and decomposes them into switch-local P4 programs, which collectively implement a new, specialized distance-vector protocol. This protocol generates compact probes that traverse the network, gathering path metrics to optimize for the user policy dynamically. Switches respond to changing network conditions at hardware speeds by routing flowlets along the best policy-compliant paths. Our system scales to large networks, and in terms of flow completion times, is competitive with hand-crafted systems that have been customized for specific topologies and policies.
                                    </small></div>
                            </td></tr>

                            <tr><td>10:15am-10:30am</td><td>
                                    Scalable Verification of Probabilistic Networks
                                    <br/>
                                    <a href="http://www.cs.cornell.edu/~smolka/">Steffen Smolka</a>
                                    <i class="text-muted">(Cornell)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#smolka_abstract" aria-expanded="true" aria-controls="smolka_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="smolka_abstract">
                                        <small class="text-muted">
                                            I will present McNetKAT, a scalable tool for verifying probabilistic network programs. McNetKAT is based on a new semantics for the guarded and history-free fragment of Probabilistic NetKAT in terms of finite-state, absorbing Markov chains. This view allows the semantics of all programs to be computed exactly, enabling construction of an automatic verification tool. Domain-specific optimizations and a parallelizing backend enable McNetKAT to analyze networks with thousands of nodes, automatically reasoning about general properties such as probabilistic program equivalence and refinement, as well as networking properties such as resilience to failures.
                                    </small></div>
                            </td></tr>

                            <tr><td>10:30am-11:00am</td><td>
                                    <i class="text-muted">Coffee Break</i>
                            </td></tr>

                            <tr><td>11:00am-12:00pm</td><td>
                                    Compact Oblivious Routing
                                    <br/>
                                    <a href="http://www.professoren.tum.de/en/raecke-harald/">Harald Räcke </a>
                                    <i class="text-muted">(TU Munich)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#raecke_abstract" aria-expanded="true" aria-controls="raecke_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="raecke_abstract">
                                        <small class="text-muted">
                                            Oblivious routing is an attractive paradigm for large distributed systems in which centralized control and frequent reconfigurations are infeasible or undesired (e.g., costly).  Over the last almost 20 years, much progress has been made in devising oblivious routing schemes that guarantee close to optimal load and also algorithms for constructing such schemes efficiently have been designed.  However, a common drawback of existing oblivious routing schemes is that they are not compact: they require large routing tables (of polynomial size), which does not scale.<br/>
                                            This talk presents an oblivious routing scheme which guarantees close to optimal load and is compact at the same time -- requiring routing tables of polylogarithmic size. Our algorithm maintains the polynomial runtime and polylogarithmic competitive ratio of existing algorithms, and is hence particularly well-suited for emerging large-scale networks.<br/>
                                            This is joint work with Stefan Schmid.<br/>
                                    </small></div>
                            </td></tr>

                            <tr><td>12:00pm-12:15pm</td><td>
                                    Semi-Oblivious Traffic Engineering
                                    <br/>
                                    <a href="http://www.cs.cornell.edu/~praveenk/">Praveen Kumar</a>
                                    <i class="text-muted">(Cornell)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#kumar_abstract" aria-expanded="true" aria-controls="kumar_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="kumar_abstract">
                                        <small class="text-muted">
                                            Networks are expected to provide reliable performance under a wide range of operating conditions, but existing traffic engineering (TE) solutions optimize for performance or robustness, but not both. A key factor that impacts the quality of a TE system is the set of paths used to carry traffic. Some systems rely on shortest paths, which leads to excessive congestion in topologies with bottleneck links, while others use paths that minimize congestion, which are brittle and prone to failure. In this talk, I will present SMORE--a TE system that uses a static set of paths based on oblivious routing, and dynamically adapts sending rates using a centralized controller. Although oblivious routing and centralized TE have been studied previously in isolation, their combination is novel and powerful. We built a software framework to model TE solutions and conducted extensive experiments across a large number of topologies and scenarios, including the production backbone of a large content provider and an ISP. Our results show that semi-oblivious routing provides near-optimal performance and is far more robust than state-of-the-art systems.
                                    </small></div>
                            </td></tr>

                            <tr><td>12:00pm-1:30pm</td><td>
                                    <i class="text-muted">Lunch</i>
                            </td></tr>

                            <tr><td>1:30pm-2:30pm</td><td>
                                    TeaVaR: Striking the Right Utilization-Availability Balance in WAN Traffic Engineering
                                    <br/>
                                    <a href="http://people.csail.mit.edu/ghobadi/">Manya Ghobadi</a>
                                    <i class="text-muted">(MIT)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#ghobadi_abstract" aria-expanded="true" aria-controls="ghobadi_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="ghobadi_abstract">
                                        <small class="text-muted">
                                            To keep up with the continuous growth in demand, cloud providers spend millions of dollars augmenting the capacity of their wide-area backbones and devote significant effort to efficiently utilizing WAN capacity. A key challenge is striking a good balance between network utilization and availability, as these are inherently at odds; a highly utilized network might not be able to withstand unexpected traffic shifts resulting from link/node failures. We advocate a novel approach to this challenge that draws inspiration from financial risk theory: leverage empirical data to generate a probabilistic model of network failures and maximize bandwidth allocation to network users subject to an operator-specified availability target (e.g., 99.9% availability). Our approach enables network operators to strike the utilization-availability balance that best suits their goals and operational reality. In this talk, I will present TeaVaR (Traffic Engineering Applying Value at Risk), a system that realizes this risk management approach to traffic engineering (TE). I will explain the optimization formulation and show that with TeaVaR operators can support up to twice as much throughput as state-of-the-art TE schemes, at the same level of availability.
                                    </small></div>
                            </td></tr>

                            <tr><td>2:30pm-3:30pm</td><td>
                                    Routing via Network Design: Overlay Routing with Dissemination Graphs
                                    <br/>
                                    <a href="http://www.cs.jhu.edu/~mdinitz/">Michael Dinitz </a>
                                    <i class="text-muted">(JHU)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#dinitz_abstract" aria-expanded="true" aria-controls="dinitz_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="dinitz_abstract">
                                        <small class="text-muted">
                                            Emerging applications such as remote manipulation and remote robotic surgery require communication that is both timely and reliable, but the Internet natively supports only communication that is either completely reliable with no timeliness guarantees (e.g., TCP) or timely with best-effort reliability (e.g., UDP).  Is there a practical way, with theoretical justification, that will allow us to achieve both?  In this talk I will discuss a system and supporting theory that uses overlay networks and structures which we call "dissemination graphs" to achieve this.  The core idea is to route along subgraphs, rather than along paths.  This allows us to turn routing problems into network design problems, which we can then design efficient algorithms for.  In particular, we study the fixed-parameter tractability of the key algorithmic problem, deriving FPT algorithms for some important cases (which we can use in our system) and proving intractability in others (forcing our system to use heuristics).
                                    </small></div>
                            </td></tr>

                            <tr><td>3:30pm-4:00pm</td><td>
                                    <i class="text-muted">Coffee Break</i>
                            </td></tr>

                            <tr><td>4:00pm-5:00pm</td><td>
                                    Traffic Engineering with Forward Fault Correction
                                    <br/>
                                    <a href="http://www.hongqiangliu.com/">Hongqiang Liu </a>
                                    <i class="text-muted">(Alibaba Group)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#liu_abstract" aria-expanded="true" aria-controls="liu_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="liu_abstract">
                                        <small class="text-muted">
                                            Network faults such as link failures and high switch configuration delays can cause heavy congestion and packet loss. Because it takes time for the traffic engineering systems to detect and react to such faults, these conditions can last long—even tens of seconds. We propose the concept of “Forward Fault Correction (FFC)” which proactively prevents a network from congestion caused by faults. FFC requires a traffic engineering (TE) to guarantee no congestion without reconfiguring the network as long as the number of faults is under k. The challenges to realize FFC lie in the overhead in network throughput and the computational complexity to prepare for a huge number of fault cases. We develop an efficient and uniform method to obtain a TE with FFC under diverse kinds of faults.
                                    </small></div>
                            </td></tr>

                            <tr><td>6:30pm-8:30pm</td><td>
                                    <i class="text-muted">Dinner</i>
                            </td></tr>

                            <tr><td colspan="2" align="center"><b>June 20th, 2019</b></td></tr>

                            <tr><td>8:30am-9:00am</td><td>
                                    <i class="text-muted">Breakfast</i>
                            </td></tr>

                            <tr><td>9:00am-10:00am</td><td>
                                    Parallel Reachability in Almost Linear Work and Square Root Depth
                                    <br/>
                                    <a href="http://www.aaronsidford.com/">Aaron Sidford</a>
                                    <i class="text-muted">(Stanford)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#sidford_abstract" aria-expanded="true" aria-controls="sidford_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="sidford_abstract">
                                        <small class="text-muted">
                                            Solving single source reachability, i.e. computing all vertices reachable from a given vertex, is perhaps one of the simplest and most well-studied graph optimization and routing problems.  While obtain work-efficient parallel algorithms for this problem in undirected graphs is trivial, obtaining comparable results for directed graphs is notoriously difficult and a key barrier towards obtaining a broader range of parallel graph algorithms.  In this talk I will present recent work which shows that this problem can be solved with nearly linear work and parallel depth proportional to the square root of the number of vertices in the graph, improving upon the previous best depth bound achieved by Fineman in 2018. Further, I will discuss how these result lead to the near optimal distributed algorithms for directed reachability in the CONGEST model in certain parameter regimes.<br/>

This talk reflects joint work with Arun Jambulapati and Yang P. Liu and is based on <a href=https://arxiv.org/abs/1905.08841>https://arxiv.org/abs/1905.08841</a>.
                                    </small></div>
                            </td></tr>

                            <tr><td>10:00am-10:30am</td><td>
                                    Intent-Driven Optimization of Network Objectives: Preliminary work and open challenges
                                    <br/>
                                    <a href="https://users.ece.cmu.edu/~vsekar/">Vyas Sekar</a>
                                    <i class="text-muted">(CMU)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#sekar_abstract" aria-expanded="true" aria-controls="sekar_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="sekar_abstract">
                                        <small class="text-muted">
                                            As software-defined networking deployments mature, operators need to manage and compose multiple resource-management applications, such as traffic engineering and service chaining. Today such applications’ resource management algorithms run separately and composition approaches are output-driven, e.g., running each application on a statically provisioned slice of the network and then combining the flow rules output for each slice. Such approaches result in inefficient use of developer time, resource utilization, and unfairness. Instead, we argue for intent-driven optimization and composition, where a unified resource optimization formulation is composed from applications’ high-level intents and the solution to this problem formulation is realized in the network. In this talk, we will provide a brief overview of our recent work in this space (SOL [NSDI'16] and Chopin [Conext'18]) and present some potential open problems in this space.
                                    </small></div>
                            </td></tr>

                            <tr><td>10:30am-11:00am</td><td>
                                    <i class="text-muted">Coffee Break</i>
                            </td></tr>

                            <tr><td>11:00am-12:00pm</td><td>
                                    Scalable Routing Strategies for Network Robustness
                                    <br/>
                                    <a href="https://marchiesa.bitbucket.io/">Marco Chiesa</a>
                                    <i class="text-muted">(KTH)</i>
                                    <br/>
                                    <a data-toggle="collapse" href="#chiesa_abstract" aria-expanded="true" aria-controls="chiesa_abstract">
                                        Abstract
                                    </a>
                                    <div class="collapse" id="chiesa_abstract">
                                        <small class="text-muted">
                                            Network operators have long relies on a variety of route computation approaches to make efficient utilization of network resources. Unfortunately, failures of network devices and highly variable traffic conditions make this routing operation a gruelling task. Sudden changes in the network conditions may, in fact, lead to severe routing performance degradation (e.g., packet losses, increased delays). To address this problem, extensive efforts have been devoted to proactive routing approaches, in which operators precompute routing solutions that are robust to a variety of changes in the network conditions. In this talk, we will embark upon a systematic algorithmic study of the resiliency of forwarding tables in a variety of packet processing models (i.e., deterministic/probabilistic routing, with packet-header-rewriting, with packet-duplication, dynamic tables). Surprisingly, our results show that significant network resiliency can be achieved even in the simplest and highly scalable per-destination routing models. 
                                    </small></div>
                            </td></tr>


                            <tr><td>12:00pm-12:15pm</td><td>
                                    <i class="text-muted">Wrapup</i>
                            </td></tr>


                            <tr><td>12:15pm-1:30pm</td><td>
                                    <i class="text-muted">Lunch</i>
                            </td></tr>

                            <tr><td></td><td></td></tr>
                    </table></p>
                </div>
            </div>
        </div>
    </section>
