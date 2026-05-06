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
    display: none; /* Prevents initial flicker */
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
    opacity: 0; /* Ensures it starts invisible for the fade */
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

  /* 1. The Fade-In Keyframes */
  @keyframes fadeIn {
    0% { opacity: 0; transform: translateY(-10px) scale(1); }
    100% { opacity: 1; transform: translateY(0) scale(1); }
  }

  /* 2. The Pulsing Keyframes */
  @keyframes gentlePulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.02); }
    100% { transform: scale(1); }
  }

  /* Trigger BOTH animations */
  .job-alert-box.visible {
    display: block; 
    /* Animation 1: Fade in over 1 second, lock in place (forwards)
      Animation 2: Pulse every 2 seconds, infinitely, but WAIT 1 second to start
    */
    animation: 
      fadeIn 1s ease-out forwards, 
      gentlePulse 2s infinite ease-in-out 1s; 
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
      // 1. Move banner to the top
      article.insertBefore(banner, article.firstChild); 
      
      // 2. Add class to trigger the combined CSS animations
      banner.classList.add('visible'); 
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