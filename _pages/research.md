---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

## Research

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Compiler-Based Simulation Infrastructure for Multiple Data Center Accelerators</b></h4>
<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<!-- <a href="https://github.com" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a> -->
<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/example_proceeding.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>  -->

<b>Authors:</b>
<i>Chenyang Zhou, Chihao Yu, Tanvir Ahmed Khan</i>

Data center applications' diverse and complex nature necessitates a sea of accelerators to achieve end-to-end performance acceleration. Unfortunately, existing simulation techniques struggle to model data center accelerators at scale while maintaining rapid execution and sufficient detail. This paper introduces a compiler-based framework that enables fast simulation of data center accelerators at scale with comprehensive insights. The framework incorporates a novel MLIR dialect to model accelerator placements and invocation patterns, paired with a performance and energy estimation engine. This combination provides detailed performance metrics and energy analysis, empowering architects to optimize speed and efficiency early in the design process. We demonstrate the framework's effectiveness with two case studies: (1) a placement and invocation model for data center accelerators and (2) acceleration of data restructuring and movement. In both cases, the framework supports rapid simulation at scale with detailed insights, yielding results that align closely with previous work.

</div>
</div>
</div>
