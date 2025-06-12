---
title: "Unifying Textual Prompt and Reference Image for Context-Preserving Object Insertion"
excerpt: "Given a background, a prompt and a reference image of the object, insert the object into the background at a reasonable location while preserving visual consistency.<br/><img src='/xiangyu_zhang.github.io/images/projects/ImageEdit.png'>"
collection: projects
---

We are solving the problem of realistically inserting specific objects into a given background image at locations described by a user prompt, while preserving spatial, semantic, and visual consistency. This is crucial for designers, content creators, and researchers in fields such as digital media, virtual scene generation, and human-AI collaborative design. These users often face difficulty when needing to place objects into scenes with fine-grained control over positioning and minimal disruption to the background, especially when only a textual description and a reference image of the object are available.

Existing research in image inpainting, layout-to-image generation, and text-conditioned diffusion models shows significant progress in manipulating visual content. However, most existing methods struggle with integrating an external object while keeping background context intact and rarely support text-driven spatial intent. 

We propose a multi-modal generation pipeline that takes as input a background image, a textual prompt describing the desired composition, and a reference image of the object. Our method first parses the attention-map-based spatial intent from the prompt and the background by a self-supervision process, then generates a layout or region proposal, followed by an object-aware generation step that inserts the referenced object into the scene while preserving background structure and style. The system leverages image-conditioned diffusion models with controllable attention and region masking to ensure both semantic alignment and visual consistency.

Report: Coming Soon

<!-- [Enhancing LLM’s Coding Ability by Tree-Based Searching Methods](/files/projects/Reinforced_Learning_Project_Report.pdf) -->

Link: Coming Soon