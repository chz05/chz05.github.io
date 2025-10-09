---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

## Welcome to My Website
{: .display-4 .fw-bold .mb-3 .text-center}

<p class="lead text-muted text-center">Exploring Computer Architecture & Compiler</p>

## About Me
{: .text-primary .mb-4}

I was a Master's student at **Columbia University** working in the field of Computer Architecture. 
I received my undergraduate degree in Computer Science from the University of California, San Diego (UCSD) in 2023.

During my Master's study, I was advised by **Prof. Tanvir Ahmed Khan**, working on a compiler-based 
simulation infrastructure research project. This work has been submitted to ISCA 2025. I am applying for PhD programs for Fall 2026. Please reach out to me if you are looking for PhD students.

### Research Interests
{: .text-primary .mb-3}

<span class="badge bg-primary fs-6 px-3 py-2">Hardware Accelerators</span>
<span class="badge bg-secondary fs-6 px-3 py-2">Simulation and Modeling</span>
<span class="badge bg-info fs-6 px-3 py-2">Compiler Design</span>
<span class="badge bg-success fs-6 px-3 py-2">Hardware-software co-design</span>

<!-- ## Selected Research
{: .text-primary .mb-4}

### Compiler-Based Simulation Infrastructure for Multiple Data Center Accelerators
{: .text-primary .mb-3}

<span class="badge bg-success fs-6 px-3 py-2">ISCA 2025</span>
**Authors:** *Chenyang Zhou, Chihao Yu, Tanvir Ahmed Khan*

#### Abstract
Data center applications' diverse and complex nature necessitates a sea of accelerators to achieve end-to-end 
performance acceleration. Unfortunately, existing simulation techniques struggle to model data center accelerators 
at scale while maintaining rapid execution and sufficient detail. 

This paper introduces a compiler-based framework that enables fast simulation of data center accelerators at scale 
with comprehensive insights. The framework incorporates a novel MLIR dialect to model accelerator placements and 
invocation patterns, paired with a performance and energy estimation engine. This combination provides detailed 
performance metrics and energy analysis, empowering architects to optimize speed and efficiency early in the 
design process.

We demonstrate the framework's effectiveness with two case studies: (1) a placement and invocation model for data 
center accelerators and (2) acceleration of data restructuring and movement. In both cases, the framework supports 
rapid simulation at scale with detailed insights, yielding results that align closely with previous work.

#### Key Technologies
<span class="badge bg-light text-dark border">MLIR</span>
<span class="badge bg-light text-dark border">Compiler Design</span>
<span class="badge bg-light text-dark border">Performance Simulation</span>
<span class="badge bg-light text-dark border">Energy Estimation</span>
<span class="badge bg-light text-dark border">Data Center Accelerators</span> -->

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