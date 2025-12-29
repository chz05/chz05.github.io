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
<h4><b>Assassyn: An Event-Driven Hardware Design Framework (ISCA 2025)</b></h4>

Assassyn is an event-driven hardware design framework published at ISCA 2025. The project addresses a fundamental challenge in hardware development: RTL forces designers to manually manage low-level timing and parallelism, which often leads to errors and slows down the design process. Assassyn introduces a unified event-driven abstraction that simplifies hardware construction while maintaining performance.

Although the paper had already been accepted when I joined, the project still faced an important limitation—its memory subsystem only supported a trivial always-hit cache and could not model realistic DRAM behavior. My primary responsibility was extending the memory system by integrating <a href="https://github.com/CMU-SAFARI/ramulator2">Ramulator 2.0</a> as the DRAM simulator. I linked against the Ramulator shared library, implemented a custom C++ wrapper to expose its memory operations, and incorporated it into Assassyn's simulation pipeline. I also extended the Python frontend code generation layer so that users could write only <b>5 lines</b> of Python code to automatically generate correct Rust and Verilog backends for a DRAM module. We validated the generated modules using Ramulator 2.0's official test cases to ensure correctness.

In total, I contributed more than <b>5,000 lines</b> of code to this project. This experience deepened my understanding of memory modeling and system-level design, and strengthened my ability to build end-to-end hardware flows that bridge Python, Rust, and Verilog.

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Data-Movement Bottlenecks in Large MoE LLM Inference</b></h4>

This project investigates why large Mixture of Experts (MoE) LLMs suffer from severe data-movement bottlenecks during inference. We conducted data-movement-centric profiling across four state-of-the-art MoE models using over <b>24,000 requests</b> and collected more than <b>150 GB</b> of expert traces. Based on the discovered expert-selection patterns, we proposed architectural enhancements to future wafer-scale GPU systems, including a data-placement-aware task distribution mechanism and a hardware-managed prediction and caching framework for local HBM. These architectural modifications significantly reduced inter-die communication and improved MoE serving throughput by up to <b>6.3×</b> on DeepSeek V3 and <b>4.0×</b> on Qwen3.

My role was to help shape the research direction and validate the multi-chiplet GPU simulator using <a href="https://github.com/astra-sim/astra-sim">ASTRA-sim2</a>. I reproduced large-scale MoE workloads, verified timing, communication behavior, and resource utilization against real hardware measurements, and ensured the simulator faithfully reflected the architectural optimizations we proposed. In addition, I contributed to a SystemVerilog code generation benchmark project, taking responsibility for the majority of the implementation and core components.

Through these works, I gained a deep understanding of MoE inference bottlenecks and how model-driven insights can directly translate into concrete hardware architecture improvements, strengthening my ability to connect system-level analysis with chip-level design.

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Compiler-Based Simulation Infrastructure for Multiple Data Center Accelerators</b></h4>


Data center applications' diverse and complex nature necessitates a sea of accelerators to achieve end-to-end performance acceleration. Unfortunately, existing simulation techniques struggle to model data center accelerators at scale while maintaining rapid execution and sufficient detail. This paper introduces a compiler-based framework that enables fast simulation of data center accelerators at scale with comprehensive insights. The framework incorporates a novel MLIR dialect to model accelerator placements and invocation patterns, paired with a performance and energy estimation engine. This combination provides detailed performance metrics and energy analysis, empowering architects to optimize speed and efficiency early in the design process. We demonstrate the framework's effectiveness with two case studies: (1) a placement and invocation model for data center accelerators and (2) acceleration of data restructuring and movement. In both cases, the framework supports rapid simulation at scale with detailed insights, yielding results that align closely with previous work.

</div>
</div>
</div>
