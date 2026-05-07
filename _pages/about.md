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
    background-color: #FFC20E; 
    color: #FFFFFF; 
    text-align: center;
    font-size: 1.1rem;
    font-weight: 500;
    box-shadow: 0 4px 6px rgba(0,0,0,0.15);
    box-sizing: border-box;
    opacity: 0; 
  }

  .job-alert-box strong {
    color: #ed1c24; 
  }

  html[data-theme='dark'] .job-alert-box {
    background-color: #144d16; 
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  }

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
  🚀 <strong>I am on the industry job market and actively looking for research positions!</strong> <br>
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

I am a [Ph.D. Candidate](https://www.cs.umd.edu/people/spalta) in the [Department of Computer Science](https://www.cs.umd.edu) at the [University of Maryland, College Park](https://www.umd.edu/), where I am advised by [Professor Rachel Rudinger](https://rudinger.github.io). I am a member of the [Computational Linguistics and Information Processing (CLIP)](https://wiki.umiacs.umd.edu/clip/index.php/Main_Page) Lab in [UMIACS](https://www.umiacs.umd.edu). 

My research centers on commonsense reasoning, human-AI alignment, and explainability of generative models, with a focus on natural language processing. Specifically, my work explores:

1. **Reliability under Uncertainty**: Evaluating LLM behavior in ambiguous contexts to identify failure modes, mitigate hallucinations, and ensure robust performance.
2. **Human-AI Alignment**: Studying how models and humans process information differently and developing methods to align model reasoning with human expectations.
3. **Trust & Safety**: Identifying and mitigating instances where models deviate from human values, facts, or societal norms, focusing on explainability and fairness.

I earned my Master's degree in Computer Science from UMD in 2023 and my Bachelor's degree in Electrical and Electronics Engineering from [BITS Pilani](https://www.bits-pilani.ac.in/Pilani/index.aspx) in 2021.

During my Ph.D., I interned twice at [Microsoft Research](https://www.microsoft.com/en-us/research/): first with [Scott Counts](https://www.microsoft.com/en-us/research/people/counts/) and the [Special Projects Group](https://www.microsoft.com/en-us/research/group/microsoft-research-special-projects/) in Summer 2024, and then with [Mengting Wan](https://mengtingwan.github.io), Michael Bentley, and the Office AI ScienceTeam in Summer 2025.