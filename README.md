[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

# Biomedical_NLP_Tutorial
> Created by <br>
> [Sakhaa Alsaedi](https://cemse.kaust.edu.sa/cbrc/people/person/sakhaa-alsaedi)<sup>1</sup> and [Sara Althubaiti](https://cemse.kaust.edu.sa/cs/people/person/sara-althubaiti).<sup>1</sup> <br>
> King Abdullah University of Science and Technology (KAUST)<sup>1</sup>
Biomedical NLP Tutorial: Introduction to NLP, Named Entity Recognition (NER), and Relation Extraction (RE)

# Biomedical NLP Tutorial: Illuminating Insights from Textual Healthscapes 

## Welcome to the Biomedical NLP Tutorial Repository!

Embark on an exhilarating journey through the intricate terrain where the realms of Natural Language Processing (NLP) and Biomedical Science converge. Our meticulously crafted tutorial unfurls the enigmatic nuances of NLP, unveils the power of Named Entity Recognition (NER), and uncovers the hidden treasures of Relation Extraction (RE) within the context of the riveting biomedical narrative.

This repository contains code for building a diffusion model to compress the FossilNET dataset and generate imges. This can generally be useful for high quality samples, or for model diversity.

# Building the Diffusion Model steps:
- Step 1: The forward process ==> Noise scheduler
- Step 2: Parameterized backward process ==> NN Model [U-Net (autoencoder)](https://amaarora.github.io/2020/09/13/unet.html)
- step 3: Positional Encoding ==> [timestep encoding](colab.research.google.com/drive/1niCAKS1dJ74_De8Nk_V3_Rx2tpNLadYD#scrollTo=dc8120e5)


# Scripts :space_invader:

| Parts | Notebook  | Open in Colab| 
| :---: | :---:         |     :---:      |  
| Introduction of NLP | [Notebook 1](https://colab.research.google.com/drive/1DDsachehj0bE4_y4sCg70NG9PDvTB4zX?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DDsachehj0bE4_y4sCg70NG9PDvTB4zX?usp=sharing)|
| Named Entity Recognition (NER)   | [Notebook 2](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)|
| Named Entity Normalization (NEN)   | [Notebook 3](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)|
| Relationship Extraction (RE)   | [Notebook 4](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Y1Vp-X6FoEf-tw7caNyx3_ageSdlQhu_?usp=sharing)|

## List of Contents 📖

1. **Introduction to NLP:**
   Lay the cornerstone by deciphering the art and science of NLP. Traverse the verdant landscapes of tokenization, linguistic preprocessing, and voyage through the lexicon of challenges unique to biomedical linguistics.

2. **Named Entity Recognition (NER) in Biomedical Context:**
   Unleash the linguistic sleuth within you! Delve deep into the fascinating world of NER, where genes, diseases, chemicals, and a cornucopia of entities spring to life from the textual canvas. Embark on a quest to unravel their identities with the precision of a virtuoso.

3. **Diving into Biomedical NER Implementation:**
   Don your coder's mantle as we embark on a code-laden odyssey. Traverse the fertile coding grounds of Python, leveraging the might of SpaCy, NLTK, and specialized biomedical NER tools to extract entities. Illuminate the dim alleys of biomedical text with your code's brilliance.

4. **Weaving Relations in Biomedical Text:**
   Enter the intricate dance of entities as they pirouette through the grammatical maze. With Relation Extraction, you're not just reading text—you're deciphering the intricate web of connections between entities. Marvel at the tales spun by genes, proteins, and diseases as they waltz through sentences.

5. **Crafting Biomedical RE Implementations:**
   Master the arcane arts of machine learning as you construct Relation Extraction models. Empower your code with the might of TensorFlow, PyTorch, and more. Cast your models into the textual sea, reeling in relationships with performance metrics as your guiding stars.

6. **Horizons of Mastery and the Beyond:**
   Ascend the summit of knowledge with advanced concepts like distant supervision, domain adaptation, and infusing domain expertise into your models. Peer through the mists of the future as you glimpse emerging trends and potential breakthroughs in the tapestry of Biomedical NLP.

## How to Navigate 🧭

- Clone this repository to your machine with `git clone`.
- Traverse the chapters using folders and files thoughtfully named after the chapters.
- Each chapter holds the keys to enlightenment—notebooks, code snippets, and datasets await your eager curiosity.
- Engage, tinker, and explore. Let your creativity merge with code as you embark on a transformative learning journey.

## Dependencies 🛠️
[Google Colab](https://colab.research.google.com) provides all the necessary dependencies for running the code in this repository. You do not need to install any additional packages.
- Necessary libraries and frameworks are detailed in each chapter's readme.

## Useful resources 📚

  * ▬▬▬▬▬▬ Resources and Materials ▬▬▬▬▬▬
- [Python for Data Analysis by Wes McKinney](https://wesmckinney.com/book/)
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
  
