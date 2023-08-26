[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

# D# Biomedical RE Expedition: Charting Relationships in Textual Realms 🌐


> Created by <br>
> [Sakhaa Alsaedi](https://cemse.kaust.edu.sa/cbrc/people/person/sakhaa-alsaedi)<sup>1</sup><br>
> King Abdullah University of Science and Technology (KAUST)<sup>1</sup>

This repository contains code for building a diffusion model to compress the FossilNET dataset and generate imges. This can generally be useful for high quality samples, or for model diversity.


# Introduction 

Diffusion models are a type of generative model used in machine learning to generate data that is similar to the data on which they are trained . They work by adding noise to the available training data and then gradually reducing the noise until the generated data closely resembles the training data. Diffusion models are a rising class of generative models because of their power-generating ability and tractability . They can also improve upon existing generative models, such as Generative Adversarial Networks (GANs), by being less reliant on adversarial training.


## Welcome to the Biomedical RE Tutorial Repository! 🌟

Embark on an exhilarating expedition into the heart of Relation Extraction (RE) amidst the intricate landscapes of biomedical language. Our tutorial is your compass to navigate the realms of extracting connections between entities, unveiling hidden narratives in textual domains.

## List of Contents 📜

1. **Introduction to Relation Extraction:**
   Plant the seeds of understanding as we delve into the pivotal role of RE in deciphering associations between entities. Uncover the essence of connections hidden within biomedical text.

2. **RE Techniques: From Tradition to Innovation:**
   Traverse the evolution of RE techniques, from rule-based approaches to the cutting-edge innovations powered by neural networks. Immerse yourself in a spectrum of methods for uncovering relationships.

3. **Navigating the RE Landscape: Case Studies & Applications:**
   Embark on a journey through real-world landscapes where RE reigns supreme. Unravel case studies across diverse domains, from drug-gene interactions to clinical notes, and witness the transformative impact of RE.

4. **The Art of Evaluating RE Models: Metrics & Insights:**
   Ascend to mastery by mastering the art of evaluating RE models. Explore metrics that quantify precision, recall, and F1 scores, and gain insights into model performance and the intricacies of biomedical evaluation.

5. **RE in the Age of Machine Learning: Strategies & Enhancements:**
   Empower your journey with strategies to enhance RE models in the age of machine learning. Discover techniques to handle class imbalance, domain adaptation, and the fusion of structured knowledge.


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

