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

## 📑 **Selected Papers**

{% raw %}
<!-- This section will hold the scrolling images from papers -->
<div class="carousel">
  <div class="slides">
    <figure>
      <img src="images/Switch.png" alt="SwitchTab: Switched Autoencoders Are Effective Tabular Learners">
      <figcaption>SwitchTab: Switched Autoencoders Are Effective Tabular Learners</figcaption>
    </figure>
    <figure>
      <img src="images/ExtendedAG.png" alt="Extended Agriculture-Vision Dataset for Agricultural Pattern Analysis">
      <figcaption>Extended Agriculture-Vision Dataset for Agricultural Pattern Analysis</figcaption>
    </figure>
    <figure>
      <img src="images/LLM_AG.png" alt="LLM-Based Reinforcement Learning for Crop Management">
      <figcaption>LLM-Based Reinforcement Learning for Crop Management</figcaption>
    </figure>
    <figure>
      <img src="images/Hallucination.png" alt="Hallucination Improves Performance in Contrastive Learning">
      <figcaption>Hallucination Improves Performance in Contrastive Learning</figcaption>
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
    max-width: 600px;
    margin: 20px auto;
    position: relative;
    overflow: hidden;
  }

  .carousel img {
    width: 100%;
    max-height: 300px; /* Set the max height */
    object-fit: contain; /* Ensures the images fit without distortion */
    display: block;
  }

  .slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
  }

  figure {
    text-align: center;
    padding: 10px 0;
  }

  figcaption {
    font-size: 0.9em;
    color: #555; /* Customize the color if needed */
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
