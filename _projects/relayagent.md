---
layout: page
title: RelayAgent
description: Mobile task automation through delegation to in-app AI assistants.
img: assets/img/publication_preview/relayagent-architecture.png
importance: 1
category: research
related_publications: true
---

RelayAgent is a mobile agent that decomposes a user request into app-local subtasks and delegates each subtask to a suitable in-app AI assistant. When no assistant can complete a subtask, RelayAgent falls back to screenshot-driven GUI automation.

The system uses **dynamic capability cards** to describe how assistants are invoked and what they can do. Across AndroidDaily, MobileWorld, and RelayBench, RelayAgent improves task success while reducing completion time and token consumption compared with a pure GUI-agent baseline.

[Code and documentation](https://github.com/ShadowNearby/RelayAgent) · [Paper](https://github.com/ShadowNearby/RelayAgent/blob/main/paper/relayagent.pdf)

{% cite yan2026relayagent %}
