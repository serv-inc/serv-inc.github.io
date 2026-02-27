---
layout: post
title:  "I asked my LLM about prompt injection, and it prompt-injected itself"
date:   2023-05-03 01:11:28 +0200
categories: ai
tags: ai, ollama, phi-3.5, prompt injection
---
This morning, I asked my phi-3.5 self-hosted model about prompt injection:

```python
requests.post

m.text('do you have built-in protection against prompt injection?')
```

