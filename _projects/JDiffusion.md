---
title: "Controllable Image Generation and Artistic Style Transfer"
excerpt: "We implement Dreambooth-LoRA and Text Inversion for style transfer based on Stable Diffusion v2.1.<br/><img src='/images/projects/diffusion.png'>"
collection: projects
---

In recent years, with the rapid development of diffusion models, a variety of image generation and editing algorithms have emerged. One significant topic in this field is **controllable generation**. Within this area, a particularly artistic research problem is **style transfer**, which aims to apply the style of one image to another while preserving the content structure of the latter.

This project focuses on generating images in a specified style. Given a series of reference images sharing the same style, along with a designated prompt, we train models to guide the generation of images in the same style. 

Our approach requires separate weight fine-tuning for each style. For each style, 10 images are used for training. By inputting a prompt describing a new object, the model generates images of the object in the desired style.

Report: Coming Soon
<!-- [Enhancing LLM’s Coding Ability by Tree-Based Searching Methods](/files/projects/Reinforced_Learning_Project_Report.pdf) -->

Link: [GitHub Repository](https://github.com/ljr040929/jittor-I_do_not_play_Honkai_StarRail-2)