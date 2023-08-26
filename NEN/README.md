[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)


# Biomedical NEN Odyssey: Illuminating Entity Normalization 🌌

> Created by <br>
> [Sakhaa Alsaedi](https://cemse.kaust.edu.sa/cbrc/people/person/sakhaa-alsaedi)<sup>1</sup> <br>
> King Abdullah University of Science and Technology (KAUST)<sup>1</sup>

This repository contains code for building a diffusion model to compress the FossilNET dataset and generate imges. This can generally be useful for high quality samples, or for model diversity.


# Introduction 

Diffusion models are a type of generative model used in machine learning to generate data that is similar to the data on which they are trained . They work by adding noise to the available training data and then gradually reducing the noise until the generated data closely resembles the training data. Diffusion models are a rising class of generative models because of their power-generating ability and tractability . They can also improve upon existing generative models, such as Generative Adversarial Networks (GANs), by being less reliant on adversarial training.


## Welcome to the Biomedical NEN Tutorial Repository! 🚀

Embark on an awe-inspiring journey to the heart of entity normalization (EN) within the vibrant realm of biomedical language. Our tutorial is your compass to navigate the cosmos of transforming complex, varied entity mentions into a harmonious symphony of knowledge.

## Table of Contents 📜

1. **Introduction to Entity Normalization:**
   Lay the foundation by delving into the significance of Entity Normalization in the biomedical landscape. Explore how EN bridges the gap between entity mentions and structured knowledge bases.

2. **Unveiling the EN Process:**
   Peer behind the curtains to witness the magic of mapping entity mentions to canonical forms. Discover the alchemy of resolving synonyms, acronyms, and aliases to unveil the true essence of entities.

3. **From Text to Knowledge Graphs:**
   Embark on a voyage of semantic exploration as we transform unstructured text into structured knowledge representations. Marvel at the art of linking entities to domain-specific ontologies.

4. **EN in Action: Case Studies & Applications:**
   Immerse yourself in the real-world landscapes where Entity Normalization reigns supreme. Walk through captivating case studies, from biomedical literature to electronic health records, and witness the transformational power of EN.

5. **Steering EN: Techniques & Strategies:**
   Ascend to the next level by mastering advanced techniques for enhancing entity normalization accuracy. Dive into strategies for handling rare entities, handling ambiguity, and exploiting contextual clues.

## How to Navigate the Cosmos 🚀

- Secure your boarding pass with `git clone` to bring the repository's knowledge to your realm.
- Traverse the celestial chapters using meticulously crafted folders and filenames.
- Each chapter houses celestial notebooks, cosmic code samples, and astral datasets to fuel your understanding.


# Building the Diffusion Model steps:
- Step 1: The forward process ==> Noise scheduler
- Step 2: Parameterized backward process ==> NN Model [U-Net (autoencoder)](https://amaarora.github.io/2020/09/13/unet.html)
- step 3: Positional Encoding ==> [timestep encoding](colab.research.google.com/drive/1niCAKS1dJ74_De8Nk_V3_Rx2tpNLadYD#scrollTo=dc8120e5)

## Dependencies
[Google Colab](https://colab.research.google.com) provides all the necessary dependencies for running the code in this repository. You do not need to install any additional packages.

* ▬▬▬▬▬▬ Resources and Materials ▬▬▬▬▬▬

- Github implementation [Denoising Diffusion Pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch)
- Niels Rogge, Kashif Rasul, [Huggingface notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/annotated_diffusion.ipynb#scrollTo=3a159023)
- [Diffusion model tutorial 2](https://huggingface.co/blog/annotated-diffusion) by Rogge & Rasul and follows the [paper](https://arxiv.org/abs/2006.11239) by He et al.
- [Awesome Diffusion Models Github]([https://www.youtube.com/watch?v=HoKDTa5jHvg&t=1338s](https://github.com/diff-usion/Awesome-Diffusion-Models))
- [Outlier Diffusion Model Video: Paper Explanation | Math Explained](https://www.youtube.com/watch?v=HoKDTa5jHvg&t=1338s)  
- [Positional Embeddings](colab.research.google.com/drive/1niCAKS1dJ74_De8Nk_V3_Rx2tpNLadYD#scrollTo=dc8120e5)


* ▬▬▬▬▬▬▬ Papers ▬▬▬▬▬▬▬
- Papers on Diffusion models ([Dhariwal, Nichol, 2021], [Ho et al., 2020] ect.)
- [DDPM](https://arxiv.org/pdf/2006.11239.pdf)
- [DDPM Improved](https://arxiv.org/pdf/2105.05233.pdf)

