---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

⭐ If you have opportunities or collaborations in mind, please feel free to reach out. ⭐

## 🎓 **Background**
I am currently an Applied Research Scientist at AWS, Amazon, working on Generative AI.

I was a **Ph.D.** candidate at [**University of Illinois at Urbana-Champaign**](https://illinois.edu/), guided by [**Prof. Naira Hovakimyan**](https://naira.mechse.illinois.edu/sciencex_teams/naira-hovakimyan/).

I've also been a research scientist in machine learning at [**Intelinair**](https://www.intelinair.com/), mentored by [**Jennifer Hobbs**](https://scholar.google.com/citations?user=zeWhseAAAAAJ&hl=en). Additionally, I interned as an applied research scientist at [**Amazon**](https://www.amazon.jobs/en/teams/buyer-risk-prevention).

## 🔍 **Research Interests**

My research is primarily in the fields of **LLM**, **computer vision** and **multi-modality learning**. In particular, I'm interested in exploring **improved representation learning** techniques to aid machines in comprehending the structure of massive amounts of unlabeled data.

In industry applications, my efforts are devoted to **remote sensing**, **robotics** and **sustainable agriculture**. My philosophy towards research is centered around bringing people's lives and AI technology together at scale. 

Deeply motivated by the challenges associated with creating innovative technologies.


## 🎓 **Background**
I am currently an Applied Research Scientist at AWS, Amazon, working on Generative AI.

I was a **Ph.D.** candidate at [**University of Illinois at Urbana-Champaign**](https://illinois.edu/), guided by [**Prof. Naira Hovakimyan**](https://naira.mechse.illinois.edu/sciencex_teams/naira-hovakimyan/). 

I've also been a research scientist in machine learning at [**Intelinair**](https://www.intelinair.com/), mentored by [**Jennifer Hobbs**](https://scholar.google.com/citations?user=zeWhseAAAAAJ&hl=en). Additionally, I interned as an applied research scientist at [**Amazon**](https://www.amazon.jobs/en/teams/buyer-risk-prevention).

## 🔍 **Research Interests**

My research is primarily in the fields of **LLM**, **computer vision** and **multi-modality learning**. In particular, I'm interested in exploring **improved representation learning** techniques to aid machines in comprehending the structure of massive amounts of unlabeled data.

In industry applications, my efforts are devoted to **remote sensing**, **robotics** and **sustainable agriculture**. My philosophy towards research is centered around bringing people's lives and AI technology together at scale. 

Deeply motivated by the challenges associated with creating innovative technologies.


## 📰 **News & Updates**

- **May 2024**:
  - I am pleased to announce the successful defense of my Ph.D. thesis.

- **April 2024**:
  - Our paper, "The new agronomists: Language models are experts in crop management" has been accepted at **CVPR in AgVision**.
  - Our paper, "Residual-based Language Models are Free Boosters for Biomedical Imaging" has been accepted at **CVPR in AI-MIA** as **oral** presentation.

- **Jan 2024**:
  - Our paper, "SwitchTab: Switched Autoencoders Are Effective Tabular Learners" has been accepted at **AAAI**.

- **Oct 2023**:
  - Our work on "ReConTab: Regularized Contrastive Representation Learning for Tabular Data" has been accepted at **NeurIPS** workshop.

- **September 2023**:
  - Our paper titled "Balanced Training for Sparse GANs" has been accepted at **NeurIPS**.

- **July 2023**: 
  - Our paper, "Hallucination Improves the Performance of Contrastive Learning," got accepted at **ICCV**. [Read the paper here](https://arxiv.org/pdf/2307.12168.pdf).
  - Our work "GenCo: An Auxiliary Generator from Contrastive Learning for Enhanced Few-Shot Learning in Remote Sensing" received the **spotlight** at **ECAI**. [Read the paper here](https://arxiv.org/pdf/2307.14612.pdf).

- **May 2023**: 
  - I'm joining **Amazon** as an Intern Applied Research Scientist.

- **April 2023**: 
  - Our research on "Optimizing Crop Management with Reinforcement Learning and Imitation Learning" has been accepted at **IJCAI**. [Read the paper here](https://arxiv.org/pdf/2209.09991.pdf).

- **March 2023**: 
  - New paper on **Arxiv** titled "Dynamic Sparse Training for GANs". [Read the paper here](https://arxiv.org/pdf/2302.14670.pdf).
  - Our work "Extended Agriculture-Vision: An Extension of a Large Aerial Image Dataset for Agricultural Pattern Analysis" got accepted at **TMLR**. [Read the paper here](https://arxiv.org/pdf/2303.02460.pdf).

- **June 2022**: 
  - Presented our research at **CVPR** in New Orleans.

- **May 2022**: 
  - Our paper, "Optimizing Nitrogen Management with Deep Reinforcement Learning and Crop Simulations", was accepted for an **oral** presentation at **CVPR in AgVision**. [Read the paper here](https://arxiv.org/pdf/2204.10394.pdf).

## 📑 **Selected Publications**

{% raw %}
<!-- This section will hold the scrolling images from papers -->
<div class="carousel">
  <div class="slides">
    <figure>
      <figcaption>SwitchTab: Switched Autoencoders Are Effective Tabular Learners</figcaption>
      <img src="images/Switch.png" alt="SwitchTab: Switched Autoencoders Are Effective Tabular Learners">
    </figure>
    <figure>
      <figcaption>Extended Agriculture-Vision Dataset for Agricultural Pattern Analysis</figcaption>
      <img src="images/ExtendedAG.png" alt="Extended Agriculture-Vision Dataset for Agricultural Pattern Analysis">
    </figure>
    <figure>
      <figcaption>LLM-Based Reinforcement Learning for Crop Management</figcaption>
      <img src="images/LLM_AG.png" alt="LLM-Based Reinforcement Learning for Crop Management">
    </figure>
    <figure>
      <figcaption>Hallucination Improves Performance in Contrastive Learning</figcaption>
      <img src="images/Hallucination.png" alt="Hallucination Improves Performance in Contrastive Learning">
    </figure>
  </div>
  <button class="carousel-btn prev-btn" onclick="moveSlides(-1)">&#10094;</button>
  <button class="carousel-btn next-btn" onclick="moveSlides(1)">&#10095;</button>
</div>

<script>
  let currentSlide = 0;
  const slides = document.querySelector('.slides');
  const totalSlides = slides.children.length;

  function moveSlides(n) {
    currentSlide = (currentSlide + n + totalSlides) % totalSlides;
    slides.style.transform = `translateX(-${currentSlide * 100}%)`;
  }
</script>

<!-- Add the appropriate styles for the carousel -->
<style>
  .carousel {
    width: 100%;
    max-width: 800px;
    margin: 20px auto;
    position: relative;
    overflow: hidden; /* Ensures only one slide is shown at a time */
  }

  .carousel img {
    width: 100%;
    max-height: 380px; /* Set the max height */
    object-fit: contain; /* Ensures the images fit without distortion */
    display: block;
  }

  .slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
  }

  figure {
    min-width: 100%; /* Each figure takes up the full width of the carousel */
    text-align: center;
    padding: 0; /* Remove padding */
    position: relative;
  }

  figcaption {
    position: absolute;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    font-size: 1.2em; /* Increase the font size */
    font-weight: bold; /* Make the title bold */
    color: #333; /* Customize the color if needed */
    background-color: rgba(255, 255, 255, 0.8); /* Add a background to make the text more readable */
    padding: 5px 10px;
    width: 100%;
    text-align: center;
  }

  .carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
  }

  .prev-btn {
    left: 10px;
  }

  .next-btn {
    right: 10px;
  }
</style>
{% endraw %}
