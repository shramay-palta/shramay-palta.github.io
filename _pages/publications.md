---
layout: page
permalink: /publications/
title: Publications
description: Publications by year in reversed chronological order.
nav: true
---

<!--To add more papers, copy an entire content block and change details>

<!-- Content -->

  <div class="container mt-5">
    <div class="post">

  <article>
    <div class="publications">


  <h2 class="year">2024</h2>
  <ol class="bibliography"><li><div class="row">
  <div class="col-sm-2 abbr">
  
    
    <abbr class="badge" style="display:inline-block; width:100px; background-color: #3CC7EA">
      <span style="color: #ffffff">
        ECCV 2024
      </span>
    </abbr>
    
  
  </div>

  <div id="somepalli2024measuring" class="col-sm-8">
    
      <div class="title">Measuring Style Similarity in Diffusion Models
</div>
      <div class="author">
                Gowthami Somepalli,
                Anubhav Gupta,
                Kamal Gupta,
                <em><b>Shramay Palta</b></em>,
                Micah Goldblum, 
                Jonas Geiping, 
                Abhinav Shrivastava, 
                and Tom Goldstein
      </div>
      <div class="periodical">
        <em>The 18th European Conference on Computer Vision: ECCV 2024</em>
      </div>
    <div class="links">  
      <a class="abstract btn btn-sm z-depth-0" role="button">Abstract</a>
      <a class="bibtex btn btn-sm z-depth-0" role="button">Bib</a>
      <a href="https://arxiv.org/abs/2404.01292" class="btn btn-sm z-depth-0" role="button" target="_blank">PDF</a>
      <a href="https://github.com/learn2phoenix/CSD" class="bibtex btn btn-sm z-depth-0" role="button">Code</a>
    </div>

    <!-- Hidden abstract block -->
    
    <div class="abstract hidden">
      <p>Generative models are now widely used by graphic designers and artists. Prior works have shown that these models remember and often replicate content from their training data during generation. Hence as their proliferation increases, it has become important to perform a database search to determine whether the properties of the image are attributable to specific training data, every time before a generated image is used for professional purposes. Existing tools for this purpose focus on retrieving images of similar semantic content. Meanwhile, many artists are concerned with style replication in text-to-image models. We present a framework for understanding and extracting style descriptors from images. Our framework comprises a new dataset curated using the insight that style is a subjective property of an image that captures complex yet meaningful interactions of factors including but not limited to colors, textures, shapes, etc. We also propose a method to extract style descriptors that can be used to attribute style of a generated image to the images used in the training dataset of a text-to-image model. We showcase promising results in various style retrieval tasks. We also quantitatively and qualitatively analyze style attribution and matching in the Stable Diffusion model. Code and artifacts are available at this <a href="https://github.com/learn2phoenix/CSD">https URL.</a></p>
    </div>

    <!-- Hidden bibtex block -->
    
    <div class="bibtex hidden">
      <figure class="highlight"><pre><code class="language-bibtex" data-lang="bibtex"><span class="nc">@article</span><span class="p">{</span><span class="nl">somepalli2024measuring</span><span class="p">,</span>
  <span class="na">title</span> <span class="p">=</span> <span class="s">Measuring Style Similarity in Diffusion Models</span><span class="p">,</span>
  <span class="na">author</span> <span class="p">=</span> <span class="s">"Gowthami Somepalli and Anubhav Gupta and Kamal Gupta and Shramay Palta and Micah Goldblum and Jonas Geiping and Abhinav Shrivastava and Tom Goldstein"</span><span class="p">,</span>
  <span class="na">journal</span> <span class="p">=</span> <span class="s">{arXiv preprint arXiv:2404.01292}</span><span class="p">,</span>
  <span class="na">year</span> <span class="p">=</span> <span class="s">"2024"</span>
<span class="p">}</span></code></pre></figure>
    </div>
    
  </div>
</div>
</li></ol>
</div></article>
</div></div>

<!-- Content -->

  <div class="container mt-5">
    <div class="post">

  <article>
    <div class="publications">


  <!-- <h2 class="year">2024</h2> -->
  <ol class="bibliography"><li><div class="row">
  <div class="col-sm-2 abbr">
  
    
    <abbr class="badge" style="display:inline-block; width:100px; background-color: #FFC20E">
      <span style="color: #ffffff">
        ACL 2024
      </span>
    </abbr>
    
  
  </div>

  <div id="balepur_poe" class="col-sm-8">
    
      <div class="title">It’s Not Easy Being Wrong: Large Language Models Struggle with Process of Elimination Reasoning
</div>
      <div class="author">
                Nishant Balepur,            
                <em><b>Shramay Palta</b></em>,
                and Rachel Rudinger
      </div>
      <div class="periodical">
        <em>Findings of the Association for Computational Linguistics: ACL 2024</em>
      </div>
    <div class="links">  
      <a class="abstract btn btn-sm z-depth-0" role="button">Abstract</a>
      <a class="bibtex btn btn-sm z-depth-0" role="button">Bib</a>
      <a href="https://aclanthology.org/2024.findings-acl.604" class="btn btn-sm z-depth-0" role="button" target="_blank">PDF</a>
    </div>

    <!-- Hidden abstract block -->
    
    <div class="abstract hidden">
      <p>Chain-of-thought (COT) prompting can help large language models (LLMs) reason toward correct answers, but its efficacy in reasoning toward incorrect answers is unexplored. This strategy of process of elimination (PoE), when used with COT, has the potential to enhance interpretability in tasks like medical diagnoses of exclusion. Thus, we propose PoE with COT, a new task where LLMs must reason toward incorrect options on multiple-choice questions. We evaluate the ability of GPT-3.5, LLaMA-2, and Falcon to perform PoE with COT on 2-choice commonsense and scientific reasoning datasets. We show that PoE consistently underperforms directly choosing the correct answer. The agreement of these strategies is also lower than the self-consistency of each strategy. To study these issues further, we conduct an error analysis and give suggestions for future work.
</p>
    </div>

    <!-- Hidden bibtex block -->
    
    <div class="bibtex hidden">
    <figure class="highlight"><pre><code class="language-bibtex" data-lang="bibtex"><span class="nc">@inproceedings</span><span class="p">{</span><span class="nl">balepur-etal-2024-easy</span><span class="p">,</span>
    <span class="na">abbr</span> <span class="p">=</span> <span class="s">ACL</span><span class="p">,</span>
    <span class="na">title</span> <span class="p">=</span> <span class="s">"It's Not Easy Being Wrong: Large Language Models Struggle with Process of Elimination Reasoning"</span><span class="p">,</span>
    <span class="na">author</span> <span class="p">=</span> <span class="s">"Balepur, Nishant and Palta, Shramay  and Rudinger, Rachel"</span><span class="p">,</span>
    <span class="na">booktitle</span> <span class="p">=</span> <span class="s">"Findings of the Association for Computational Linguistics: ACL 2024"</span><span class="p">,</span>
    <span class="na">month</span> <span class="p">=</span> <span class="s">aug</span><span class="p">,</span>
    <span class="na">year</span> <span class="p">=</span> <span class="s">"2024"</span><span class="p">,</span>
    <span class="na">publisher</span> <span class="p">=</span> <span class="s">"Association for Computational Linguistics"</span><span class="p">,</span>
    <span class="na">address</span> <span class="p">=</span> <span class="s">"Bangkok, Thailand and virtual meeting"</span><span class="p">,</span>
    <span class="na">url</span> <span class="p">=</span> <span class="s">"https://aclanthology.org/2024.findings-acl.604"</span><span class="p">,</span>
    <span class="na">pages</span> <span class="p">=</span> <span class="s">"10143--10166"</span><span class="p">,</span>
    <span class="na">abstract</span> <span class="p">=</span> <span class="s">"Chain-of-thought (COT) prompting can help large language models (LLMs) reason toward correct answers, but its efficacy in reasoning toward incorrect answers is unexplored. This process of elimination (PoE), when used with COT, can enhance self-consistency, interpretability, and tasks such as medical diagnoses of exclusion. Thus, we propose PoE with COT, where LLMs must reason toward incorrect options on multiple-choice questions. We evaluate the ability of GPT-3.5, LLaMA-2, and Falcon to perform PoE with COT on a total of four commonsense and scientific reasoning datasets. We find that the strategy of PoE always underperforms the strategy of choosing the correct answer. The agreement of these strategies is also lower than the self-consistency of each strategy. To study these issues further, we conduct error analyses and give suggestions for future work"</span>
<span class="p">}</span></code></pre></figure>
    </div>
    
  </div>
</div>
</li></ol>
</div></article>
</div></div>

<!-- Content -->

  <div class="container mt-5">
    <div class="post">

  <article>
    <div class="publications">


  <h2 class="year">2023</h2>
  <ol class="bibliography"><li><div class="row">
  <div class="col-sm-2 abbr">
  
    
    <abbr class="badge" style="display:inline-block; width:100px; background-color:#FFC20E">
      <span style="color: #ffffff">
        ACL 2023
      </span>
    </abbr>
    
  
  </div>

  <div id="palta_rudinger_fork_2023" class="col-sm-8">
    
      <div class="title">FORK: A Bite-Sized Test Set for Probing Culinary Cultural Biases in Commonsense Reasoning Models
</div>
      <div class="author">            
                <em><b>Shramay Palta</b></em>,
                and Rachel Rudinger
      </div>
      <div class="periodical">
        <em>Findings of the Association for Computational Linguistics: ACL 2023</em>
      </div>
    <div class="links">  
      <a class="abstract btn btn-sm z-depth-0" role="button">Abstract</a>
      <a class="bibtex btn btn-sm z-depth-0" role="button">Bib</a>
      <a href="https://aclanthology.org/2023.findings-acl.631/" class="btn btn-sm z-depth-0" role="button" target="_blank">PDF</a>
      <a href="https://shramay-palta.github.io/assets/pdf/FORK_ACL2023/poster.pdf" class="bibtex btn btn-sm z-depth-0" role="button">Poster</a>
      <a href="https://github.com/shramay-palta/FORK_ACL2023" class="bibtex btn btn-sm z-depth-0" role="button">Dataset</a>
      <a href="https://drive.google.com/file/d/1REHB7vjxcyeTSy80nuR02bCtf6aEhTPU/view?usp=sharing" class="bibtex btn btn-sm z-depth-0" role="button">Video</a>
    </div>

    <!-- Hidden abstract block -->
    
    <div class="abstract hidden">
      <p>It is common sense that one should prefer to eat a salad with a fork rather than with a chainsaw. However, for eating a bowl of rice, the choice between a fork and a pair of chopsticks is culturally relative. We introduce FORK, a small, manually-curated set of CommonsenseQA-style questions for probing cultural biases and assumptions present in com- monsense reasoning systems, with a specific focus on food-related customs. We test several CommonsenseQA systems on FORK, and while we see high performance on questions about the US culture, the poor performance of these systems on questions about non-US cultures highlights systematic cultural biases aligned with US over non-US cultures.
</p>
    </div>

    <!-- Hidden bibtex block -->
    
    <div class="bibtex hidden">
      <figure class="highlight"><pre><code class="language-bibtex" data-lang="bibtex"><span class="nc">@inproceedings</span><span class="p">{</span><span class="nl">palta-rudinger-2023-fork</span><span class="p">,</span>
  <span class="na">abbr</span> <span class="p">=</span> <span class="s">ACL</span><span class="p">,</span>
  <span class="na">title</span> <span class="p">=</span> <span class="s">"{FORK}: A Bite-Sized Test Set for Probing Culinary Cultural Biases in Commonsense Reasoning Models"</span><span class="p">,</span>
  <span class="na">author</span> <span class="p">=</span> <span class="s">"Palta, Shramay  and Rudinger, Rachel"</span><span class="p">,</span>
  <span class="na">booktitle</span> <span class="p">=</span> <span class="s">"Findings of the Association for Computational Linguistics: ACL 2023"</span><span class="p">,</span>
  <span class="na">month</span> <span class="p">=</span> <span class="s">jul</span><span class="p">,</span>
  <span class="na">year</span> <span class="p">=</span> <span class="s">"2023"</span><span class="p">,</span>
  <span class="na">publisher</span> <span class="p">=</span> <span class="s">"Association for Computational Linguistics"</span><span class="p">,</span>
  <span class="na">address</span> <span class="p">=</span> <span class="s">"Toronto, Canada"</span><span class="p">,</span>
  <span class="na">url</span> <span class="p">=</span> <span class="s">"https://aclanthology.org/2023.findings-acl.631"</span><span class="p">,</span>
  <span class="na">pages</span> <span class="p">=</span> <span class="s">"9952--9962"</span><span class="p">,</span>
  <span class="na">abstract</span> <span class="p">=</span> <span class="s">"It is common sense that one should prefer to eat a salad with a fork rather than with a chainsaw. However, for eating a bowl of rice, the choice between a fork and a pair of chopsticks is culturally relative. We introduce FORK, a small, manually-curated set of CommonsenseQA-style questions for probing cultural biases and assumptions present in commonsense reasoning systems, with a specific focus on food-related customs. We test several CommonsenseQA systems on FORK, and while we see high performance on questions about the US culture, the poor performance of these systems on questions about non-US cultures highlights systematic cultural assumptions aligned with US over non-US cultures."</span>
<span class="p">}</span></code></pre></figure>
    </div>
    
  </div>
</div>
</li></ol>
</div></article>
</div></div>

<!-- Content -->

  <div class="container mt-5">
    <div class="post">

  <article>
    <div class="publications">


  <h2 class="year">2022</h2>
  <ol class="bibliography"><li><div class="row">
  <div class="col-sm-2 abbr">
  
    
    <abbr class="badge" style="display:inline-block; width:100px; background-color: #430868">
      <span style="color: #ffffff">
        arXiv
      </span>
    </abbr>
    
  
  </div>

  <div id="palta2022investigating" class="col-sm-8">
    
      <div class="title">Investigating Information Inconsistency in Multilingual Open-Domain Question Answering</div>
      <div class="author">            
                <em><b>Shramay Palta</b></em>,
                Haozhe An,
                Yifan Yang,
                Shuaiyi Huang,
                and Maharshi Gor
      </div>
      <div class="periodical">
        <em>arXiv preprint, 2022</em>
      </div>
    <div class="links">  
      <a class="abstract btn btn-sm z-depth-0" role="button">Abstract</a>
        <a class="bibtex btn btn-sm z-depth-0" role="button">Bib</a>
        <a href="https://arxiv.org/pdf/2205.12456.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank">PDF</a>
    </div>

    <!-- Hidden abstract block -->
    
    <div class="abstract hidden">
      <p>Multilingual open-domain question answering can unlock information that might be unavailable in a user's primary language. However, can that user trust the information they get? But multilingual question answering can potentially expose users to unreliable information through cultural differences, divergent national laws, or uneven resources. To understand the effects of the biased availability of information and cultural influence, we analyze the behavior of multilingual open-domain question answering models with a focus on retrieval bias. We analyze if different retriever models present different passages---and answers---given the same question in different languages on TyDi QA and XOR-TyDi QA, two multilingual QA datasets. While most answers are consistent, where they differ reveals valuable information about per-language resources disparity, and linguistic variation.</p>
    </div>

    <!-- Hidden bibtex block -->
    
    <div class="bibtex hidden">
      <figure class="highlight"><pre><code class="language-bibtex" data-lang="bibtex"><span class="nc">@article</span><span class="p">{</span><span class="nl">palta2022investigating</span><span class="p">,</span>
  <span class="na">title</span> <span class="p">=</span> <span class="s">{Investigating Information Inconsistency in Multilingual Open-Domain Question Answering}</span><span class="p">,</span>
  <span class="na">author</span> <span class="p">=</span> <span class="s">{Palta, Shramay and An, Haozhe and Yang, Yifan and Huang, Shuaiyi and Gor, Maharshi}</span><span class="p">,</span>
  <span class="na">journal</span> <span class="p">=</span> <span class="s">{arXiv preprint arXiv:2205.12456}</span><span class="p">,</span>
  <span class="na">year</span> <span class="p">=</span> <span class="s">{2022}</span>
<span class="p">}</span></code></pre></figure>
    </div>
    
  </div>
</div>
</li></ol>
</div></article>
</div></div>