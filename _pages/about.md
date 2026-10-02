---
permalink: /
title: "Junhong Cheng"
author_profile: true
excerpt: "Computer science undergraduate at Shanghai Jiao Tong University studying secure and efficient computing systems."
---

I am an undergraduate in the **ACM Honors Class** at **Shanghai Jiao Tong University**, pursuing a B.S. in Computer Science (expected June 2027).

My research focuses on **secure and efficient computing systems**, including trusted execution environments (TEEs), microarchitectural security, and oblivious architectures such as ORAM-based memory systems. I am interested in improving performance while preserving security guarantees.

At SJTU's Network Security and Privacy Protection (NSEC) Lab, I worked with **Prof. Guoxing Chen** on reducing enclave cold-start latency through dynamic page loading. I am the second author of *Attest the Whole, Verify Incrementally*, currently under minor revision for CCS 2026.

I am also working with **Prof. Dean Tullsen**, **Luyi Li**, and **Hosein Yavarzadeh** at UCSD's DCASL on reverse engineering Intel defense mechanisms, measuring their overhead, and exploring lower-latency alternatives.

[Download CV](/files/CV.pdf){: .btn .btn--primary} [Email](mailto:cheng_junhong_2023@sjtu.edu.cn){: .btn} [GitHub](https://github.com/ChengJH-HEhe){: .btn}

## Research highlights

- **TEE acceleration:** dynamic enclave-page loading to reduce cold-start latency. [Research details](/research/#tee-acceleration)
- **Intel defense profiling:** reverse engineering and overhead measurement of microarchitectural defenses. [Research details](/research/#intel-defense-profiling)

## Selected projects

I have built a Java compiler for Mx, a Verilog CPU with Tomasulo scheduling, and a Go implementation of Raft. [View projects](/projects/)

## Recent articles

{% for post in site.posts limit:3 %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[All articles →](/articles/)
