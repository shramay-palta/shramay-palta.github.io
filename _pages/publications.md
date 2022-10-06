---
layout: page
permalink: /publications/
title: Publications
description: Publications by year in reversed chronological order.
years: [2022]
nav: true
---
<!-- _pages/publications.md -->
<!-- <div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div> -->

<!-- Content -->

  <div class="container mt-5">
    <div class="post">

  <header class="post-header">
    <h1 class="post-title">Publications</h1>
    <p class="post-description">Publications by years in reversed chronological order.</p>
  </header>

  <article>
    <div class="publications">


  <h2 class="year">2022</h2>
  <ol class="bibliography"><li><div class="row">
  <div class="col-sm-2 abbr">
  
    
    <abbr class="badge" style="display:inline-block; width:100px">
      <span style="background-color: transparent; color: var(--global-bg-color)">
        NeurIPS 2022
      </span>
    </abbr>
    
  
  </div>

  <div id="sriramanan:gor:feizi-neurips2022" class="col-sm-8">
    
      <div class="title">Toward Efficient Robust Training against Union of L<sub>p</sub> Threat Models</div>
      <div class="author">
        
          
          
          
          
          
          
            
              
                
                  Gaurang Sriramanan,
                
              
            
          
        
          
          
          
          
          
          
            
              
                <em><b>Maharshi Gor</b></em>,
              
            
          
        
          
          
          
          
          
          
            
              
                
                  and Soheil Feizi
                
              
            
          
        
      </div>

      <div class="periodical">
      
        <em>In Advances in Neural Information Processing Systems</em>
      
      
        2022
      
      </div>
    

    <div class="links">
    
      <a class="abstract btn btn-sm z-depth-0" role="button">Abs</a>
    
    
    
        <a class="bibtex btn btn-sm z-depth-0" role="button">Bib</a>
    
    
    
    
    
    
    
    
    
    </div>

    <!-- Hidden abstract block -->
    
    <div class="abstract hidden">
      <p>  The overwhelming vulnerability of deep neural networks to carefully crafted perturbations known as adversarial attacks has led to the development of various training techniques to produce robust models.  
  While the primary focus of existing approaches has been directed toward addressing the worst-case performance achieved under a single-threat model, it is imperative that safety-critical systems are robust with respect to multiple threat models simultaneously. 
  Existing approaches that address worst-case performance under the union of such threat models (e.g., \ell_∞, \ell_2, \ell_1) either utilize adversarial training methods that require multi-step attacks which are computationally expensive in practice, or rely upon fine-tuning of pre-trained models that are robust with respect to a single-threat model.
  In this work, we show that by carefully choosing the objective function used for robust training, it is possible to achieve similar, or even improved worst-case performance over a union of threat models while utilizing only single-step attacks during the training, thereby achieving a significant reduction in computational resources necessary for training.  
  Furthermore, prior work showed that adversarial training against the \ell_1 threat model is relatively difficult, to the extent that even multi-step adversarially trained models were shown to be prone to gradient-masking and catastrophic over-fitting.  
  However, our proposed method—when applied on the \ell_1 threat model specifically—enables us to obtain the first \ell_1 robust model trained solely with single-step adversarial attacks.
  Finally, to demonstrate the merits of our approach, we utilize a modern set of attack evaluations to better estimate the worst-case performance under the considered union of threat models.</p>
    </div>
    

    <!-- Hidden bibtex block -->
    
    <div class="bibtex hidden">
      <figure class="highlight"><pre><code class="language-bibtex" data-lang="bibtex"><span class="nc">@inproceedings</span><span class="p">{</span><span class="nl">sriramanan:gor:feizi-neurips2022</span><span class="p">,</span>
  <span class="na">abbr</span> <span class="p">=</span> <span class="s">{NeurIPS}</span><span class="p">,</span>
  <span class="na">bibtex_show</span> <span class="p">=</span> <span class="s">{true}</span><span class="p">,</span>
  <span class="na">title</span> <span class="p">=</span> <span class="s">{Toward Efficient Robust Training against Union of L&lt;sub&gt;p&lt;/sub&gt; Threat Models}</span><span class="p">,</span>
  <span class="na">author</span> <span class="p">=</span> <span class="s">{Sriramanan, Gaurang and Gor, Maharshi and Feizi, Soheil}</span><span class="p">,</span>
  <span class="na">booktitle</span> <span class="p">=</span> <span class="s">{Advances in Neural Information Processing Systems}</span><span class="p">,</span>
  <span class="na">year</span> <span class="p">=</span> <span class="s">{2022}</span><span class="p">,</span>
  <span class="na">location</span> <span class="p">=</span> <span class="s">{New Orleans, LA}</span><span class="p">,</span>
  <span class="na">selected</span> <span class="p">=</span> <span class="s">{true}</span>
<span class="p">}</span></code></pre></figure>
    </div>
    
  </div>
</div>
</li></ol>

</div></article>
</div></div>