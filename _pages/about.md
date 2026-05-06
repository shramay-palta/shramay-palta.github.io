---
title: About
layout: about
permalink: /
subtitle: Ph.D. Student in Computer Science | NLP Researcher

profile:
  align: right
  image: Shramay.jpeg
  more_info: >
    <p>Iribe 4108</p> <p> 8125 Paint Branch Dr, College Park, MD 20742 </p>

news: true
selected_papers: true
social: true
---
<style>
  .job-alert-box {
    width: 100%; /* Forces it to span the center */
    padding: 15px;
    margin: 0 0 30px 0; /* Pushes the image and content down below it */
    border-radius: 8px;
    background-color: #d1ecf1;
    color: #1E7021;
    text-align: center;
    font-size: 1.1rem;
    font-weight: 500;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    animation: gentlePulse 2s infinite ease-in-out;
    box-sizing: border-box;
  }

  html[data-theme='dark'] .job-alert-box {
    background-color: #1E7021;
    color: #a8edf8;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  }

  @keyframes gentlePulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.02); }
    100% { transform: scale(1); }
  }
</style>

<div class="job-alert-box" id="job-alert">
  🚀 <strong>I am on the industry job market and actively looking for research positions.</strong> <br>
  Please reach out if you think we'd be a good fit.
</div>

<script>
  // This tiny script moves the box above the floating profile image 
  // without needing to hack the core al-folio layout files!
  document.addEventListener("DOMContentLoaded", function() {
    const banner = document.getElementById('job-alert');
    // Finds the main article container
    const article = document.querySelector('article'); 
    if (banner && article) {
      // Inserts the banner at the very top, pushing everything else down
      article.insertBefore(banner, article.firstChild); 
    }
  });
</script>

I am a [Ph.D. Candidate](https://www.cs.umd.edu/people/spalta) in the [Department of Computer Science](https://www.cs.umd.edu) at the [University of Maryland, College Park](https://www.umd.edu/) where I am advised by [Professor Rachel Rudinger](https://rudinger.github.io).

I am a member of the [Computational Linguistics and Information Processing (CLIP)](https://wiki.umiacs.umd.edu/clip/index.php/Main_Page) Lab in [UMIACS](https://www.umiacs.umd.edu). 

My research interests broadly lie in the areas of Computational Linguistics and Natural Language Processing with a focus on Commonsense Reasoning, Explainability and Interpretability, and Bias and Fairness in NLP. Specifically, I try to explore and understand:

1. Is commonsense reasoning prone to uncertainty?
2. How do humans and language models behave under this uncertainty?
3. Are there cases where models deviate from human values and notions about the real world?

I got my Master of Science in Computer Science from UMD in 2023. Before coming to Maryland, I graduated from [Birla Institute of Technology and Science (BITS), Pilani](https://www.bits-pilani.ac.in/Pilani/index.aspx) in 2021 with a Bachelor of Engineering (B.E.) in Electrical and Electronics Engineering.

For Summer 2025, I was a research intern in the Office AI team at [Microsoft Research](https://www.microsoft.com/en-us/research/), where I worked with [Mengting Wan](https://mengtingwan.github.io) and Michael Bentley.