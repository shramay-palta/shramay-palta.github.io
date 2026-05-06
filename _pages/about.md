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
    display: none; 
    width: 100%;
    padding: 15px;
    margin: 0 0 30px 0;
    border-radius: 8px;
    background-color: #1E7021; 
    color: #FFFFFF; 
    text-align: center;
    font-size: 1.1rem;
    font-weight: 500;
    box-shadow: 0 4px 6px rgba(0,0,0,0.15);
    box-sizing: border-box;
    opacity: 0; 
  }

  /* Default (Light Mode) bold text - Bright Red */
  .job-alert-box strong {
    color: #ed1c24; 
  }

  /* Dark mode background settings */
  html[data-theme='dark'] .job-alert-box {
    background-color: #144d16; 
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  }

  /* Dark mode bold text - Back to Gold */
  html[data-theme='dark'] .job-alert-box strong {
    color: #FFC20E; 
  }

  /* 1. The GRACEFUL Fade-In Keyframes */
  @keyframes gracefulFadeIn {
    0% { 
      opacity: 0; 
      /* Starts slightly higher up and 2% smaller */
      transform: translateY(-20px) scale(0.98); 
    }
    100% { 
      opacity: 1; 
      /* Settles perfectly into place at full size */
      transform: translateY(0) scale(1); 
    }
  }

  /* 2. The Pulsing Keyframes */
  @keyframes gentlePulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.015); } /* Slightly softer pulse to match the graceful entrance */
    100% { transform: scale(1); }
  }

  /* Trigger BOTH animations */
  .job-alert-box.visible {
    display: block; 
    /* Animation 1: 1.2 seconds, custom smooth deceleration curve
      Animation 2: 2.5 second pulse, waiting 1.2 seconds to start so they don't overlap
    */
    animation: 
      gracefulFadeIn 1.2s cubic-bezier(0.25, 0.8, 0.25, 1) forwards, 
      gentlePulse 2.5s infinite ease-in-out 1.2s; 
  }
</style>

<div class="job-alert-box" id="job-alert">
  🚀 <strong>I am on the industry job market and actively looking for research positions.</strong> <br>
  <span style="color: #FFFFFF;">Please reach out if you think we'd be a good fit.</span>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const banner = document.getElementById('job-alert');
    const article = document.querySelector('article'); 
    
    if (banner && article) {
      article.insertBefore(banner, article.firstChild); 
      // Add a tiny 50ms delay before adding the class to ensure the browser registers the DOM move before animating
      setTimeout(() => {
        banner.classList.add('visible'); 
      }, 50);
    }
  });
</script>

I am a [Ph.D. Candidate](https://www.cs.umd.edu/people/spalta) in the [Department of Computer Science](https://www.cs.umd.edu) at the [University of Maryland, College Park](https://www.umd.edu/) where I am advised by [Professor Rachel Rudinger](https://rudinger.github.io).

I am a member of the [Computational Linguistics and Information Processing (CLIP)](https://wiki.umiacs.umd.edu/clip/index.php/Main_Page) Lab in [UMIACS](https://www.umiacs.umd.edu). 

My research interests broadly lie in the areas of Computational Linguistics and Natural Language Processing with a focus on Commonsense Reasoning, Explainability and Interpretability, and Bias and Fairness in NLP. Specifically, I try to explore and understand:

1. Is commonsense reasoning prone to uncertainty?
2. How do humans and large language models behave under this uncertainty?
3. Are there cases where models deviate from human values and notions about the real world?

I got my Master of Science in Computer Science from UMD in 2023. Before coming to Maryland, I graduated from [Birla Institute of Technology and Science (BITS), Pilani](https://www.bits-pilani.ac.in/Pilani/index.aspx) in 2021 with a Bachelor of Engineering (B.E.) in Electrical and Electronics Engineering.

For Summer 2025, I was a research intern in the Office AI team at [Microsoft Research](https://www.microsoft.com/en-us/research/), where I worked with [Mengting Wan](https://mengtingwan.github.io) and Michael Bentley.