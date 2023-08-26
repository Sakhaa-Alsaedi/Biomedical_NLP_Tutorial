[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

# Biomedical NER Masterclass: Deciphering the Genomic Lexicon 🧬

> Created by <br>
> [Sakhaa Alsaedi](https://cemse.kaust.edu.sa/cbrc/people/person/sakhaa-alsaedi)<sup>1</sup><br>
> King Abdullah University of Science and Technology (KAUST)<sup>1</sup>

## Welcome to the Biomedical NER Tutorial Repository! 🌟

Unveil the secrets hidden within the labyrinth of biomedical text with our comprehensive Named Entity Recognition (NER) masterclass. This tutorial is your gateway to mastering the art of unraveling genes, diseases, chemicals, and a plethora of entities embedded in the intricate tapestry of biomedical discourse.

# Introduction 

Diffusion models are a type of generative model used in machine learning to generate data that is similar to the data on which they are trained . They work by adding noise to the available training data and then gradually reducing the noise until the generated data closely resembles the training data. Diffusion models are a rising class of generative models because of their power-generating ability and tractability . They can also improve upon existing generative models, such as Generative Adversarial Networks (GANs), by being less reliant on adversarial training.

# Building the Diffusion Model steps:
- Step 1: The forward process ==> Noise scheduler
- Step 2: Parameterized backward process ==> NN Model [U-Net (autoencoder)](https://amaarora.github.io/2020/09/13/unet.html)
- step 3: Positional Encoding ==> [timestep encoding](colab.research.google.com/drive/1niCAKS1dJ74_De8Nk_V3_Rx2tpNLadYD#scrollTo=dc8120e5)

## List of Contents 📜

1. **Introduction to Biomedical NER:**
   Lay the cornerstone for your NER odyssey by delving into the foundations of biomedical text analysis. Understand the significance of entity recognition and its pivotal role in unlocking the language of life sciences.

2. **The Power of Preprocessing:**
   Embark on an exploration of text preprocessing techniques tailored to biomedical language. Immerse yourself in the world of tokenization, stop-word removal, and stemming that lay the groundwork for accurate entity extraction.

3. **Harnessing the Magic of Machine Learning:**
   Traverse the realm of machine learning for NER, from traditional rule-based approaches to modern deep learning methods. Equip yourself with the tools to train your own biomedical NER models.

4. **Biomedical NER in Action:**
   Dive into the practical realm as we dissect real-world examples. Witness the application of NER models on diverse biomedical texts and gain insights into performance evaluation.

5. **Domain Adaptation and Beyond:**
   Elevate your expertise by learning how to adapt NER models to specialized biomedical domains. Grasp the nuances of transferring knowledge from general NER to medical and biological contexts.

* ▬▬▬▬▬▬ Resources and Materials ▬▬▬▬▬▬

- Github implementation [Denoising Diffusion Pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch)
- Niels Rogge, Kashif Rasul, [Huggingface notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/annotated_diffusion.ipynb#scrollTo=3a159023)
- [Diffusion model tutorial 2](https://huggingface.co/blog/annotated-diffusion) by Rogge & Rasul and follows the [paper](https://arxiv.org/abs/2006.11239) by He et al.
- [Awesome Diffusion Models Github]([https://www.youtube.com/watch?v=HoKDTa5jHvg&t=1338s](https://github.com/diff-usion/Awesome-Diffusion-Models))
- [Outlier Diffusion Model Video: Paper Explanation | Math Explained](https://www.youtube.com/watch?v=HoKDTa5jHvg&t=1338s)  
- [Positional Embeddings](colab.research.google.com/drive/1niCAKS1dJ74_De8Nk_V3_Rx2tpNLadYD#scrollTo=dc8120e5)


* ▬▬▬▬▬▬▬ Papers ▬▬▬▬▬▬▬
- Papers on Diffusion models ([Dhariwal, Nichol, 2021], [Ho et al., 2020] ect.)
- [BioTagger-GM](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2649315/pdf/247.S1067502708002491.main.pdf)

