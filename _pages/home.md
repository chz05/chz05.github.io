---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<div class="hero-section mb-5">
  <div class="text-center mb-4">
    <h1 class="display-4 fw-bold mb-3">Welcome to My Research</h1>
    <p class="lead text-muted">Exploring Computer Architecture & Hardware Acceleration</p>
  </div>
</div>

## About Me

<div class="about-section mb-5">
  <div class="row align-items-center">
    <div class="col-md-8">
      <p class="fs-5 mb-4">
        I am a Master's student at <strong>Columbia University</strong> working in the field of Computer Architecture. 
        I received my undergraduate degree in Computer Science from the University of California, San Diego (UCSD) in 2023 
        and went on to earn my Master's degree from Columbia University in 2024.
      </p>
      <p class="fs-5 mb-4">
        During my Master's study, I am advised by <strong>Prof. Tanvir Ahmed Khan</strong>, working on a compiler-based 
        simulation infrastructure research project. This work has been submitted to ISCA 2025. I am applying for PhD programs 
        and expect to graduate in Fall 2024. Please reach out to me if you are looking for PhD students.
      </p>
      
      <div class="research-interests">
        <h4 class="text-primary mb-3">
          <i class="fa fa-microchip me-2"></i>Research Interests
        </h4>
        <div class="d-flex flex-wrap gap-2">
          <span class="badge bg-primary fs-6 px-3 py-2">Hardware Accelerators</span>
          <span class="badge bg-secondary fs-6 px-3 py-2">Simulation</span>
          <span class="badge bg-info fs-6 px-3 py-2">Compiler Design</span>
          <span class="badge bg-success fs-6 px-3 py-2">Performance Optimization</span>
        </div>
      </div>
    </div>
    <div class="col-md-4 text-center">
      <img src="{{ site.url }}{{ site.baseurl }}/images/Myheadshot.jpg" 
           alt="Chenyang Zhou" 
           class="img-fluid rounded-circle shadow-lg" 
           style="max-width: 250px;">
    </div>
  </div>
</div>

## Selected Research

<div class="research-card">
  <div class="card border-0 shadow-lg">
    <div class="card-body p-4">
      <div class="d-flex justify-content-between align-items-start mb-3">
        <h3 class="card-title text-primary mb-0">
          <i class="fa fa-cogs me-2"></i>
          Compiler-Based Simulation Infrastructure for Multiple Data Center Accelerators
        </h3>
        <div class="badge bg-success fs-6 px-3 py-2">ISCA 2025</div>
      </div>
      
      <div class="authors mb-3">
        <h5 class="text-secondary mb-2">Authors:</h5>
        <p class="fw-semibold text-dark mb-0">
          <em>Chenyang Zhou, Chihao Yu, Tanvir Ahmed Khan</em>
        </p>
      </div>
      
      <div class="research-description">
        <h5 class="text-secondary mb-3">Abstract:</h5>
        <p class="lh-lg">
          Data center applications' diverse and complex nature necessitates a sea of accelerators to achieve end-to-end 
          performance acceleration. Unfortunately, existing simulation techniques struggle to model data center accelerators 
          at scale while maintaining rapid execution and sufficient detail. 
        </p>
        <p class="lh-lg">
          This paper introduces a compiler-based framework that enables fast simulation of data center accelerators at scale 
          with comprehensive insights. The framework incorporates a novel MLIR dialect to model accelerator placements and 
          invocation patterns, paired with a performance and energy estimation engine. This combination provides detailed 
          performance metrics and energy analysis, empowering architects to optimize speed and efficiency early in the 
          design process.
        </p>
        <p class="lh-lg mb-0">
          We demonstrate the framework's effectiveness with two case studies: (1) a placement and invocation model for data 
          center accelerators and (2) acceleration of data restructuring and movement. In both cases, the framework supports 
          rapid simulation at scale with detailed insights, yielding results that align closely with previous work.
        </p>
      </div>
      
      <div class="research-tags mt-4">
        <h6 class="text-secondary mb-2">Key Technologies:</h6>
        <div class="d-flex flex-wrap gap-2">
          <span class="badge bg-light text-dark border">MLIR</span>
          <span class="badge bg-light text-dark border">Compiler Design</span>
          <span class="badge bg-light text-dark border">Performance Simulation</span>
          <span class="badge bg-light text-dark border">Energy Estimation</span>
          <span class="badge bg-light text-dark border">Data Center Accelerators</span>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
.hero-section {
  background: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
  border-radius: 20px;
  padding: 3rem 2rem;
  margin: 2rem 0;
}

.about-section {
  background: #ffffff;
  border-radius: 16px;
  padding: 2rem;
  border: 1px solid #e2e8f0;
}

.research-card {
  margin: 2rem 0;
}

.card {
  border-radius: 16px !important;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1) !important;
}

.badge {
  border-radius: 8px;
}

.research-interests .badge {
  font-size: 0.9rem;
  padding: 0.5rem 1rem;
}

@media (max-width: 768px) {
  .hero-section {
    padding: 2rem 1rem;
  }
  
  .about-section {
    padding: 1.5rem;
  }
  
  .display-4 {
    font-size: 2rem;
  }
}
</style>