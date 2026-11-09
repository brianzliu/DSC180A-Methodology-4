---
layout: home
title: Home
---
Brian Liu
bzl002@ucsd.edu


Efficient AI: Algorithms and Systems for Foundation Models (D38)
Zhijian Liu

**What is the most interesting topic covered in your domain this quarter?**
The most interesting conceptual topic covered was speculative decoding, particularly my mentor's research on DFlash, which uses a cheap drafter language model to mitigate memory bottlenecks for a larger language model. Speculative decoding applies to not only large language models, but also image generation, structured data output, translation, etc.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
My team and I would like to investigate mitigating this same memory bottleneck, but for image models. This might be an interesting project since many image models are diffusion-based and highly parallelizable unlike LLMs. Starting from existing literature, we want to conceptualize a more or equivalently powerful decoding algorithm like DFlash.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
We would like to foremost see if a DFlash-like algorithm can be applied to image generation models, and how much such an algorithm would benefit diffusion language models compared to autoregressive language models.

**What other techniques would you be interested in using in your project?**
We want to perhaps see whether feedback from the target model's verification stage in speculative decoding can be used to "fine-tune" the drafter model such that it produces more accurate results on the next iteration. We would also like to explore how different drafter model architectures affect decoding performance. 
