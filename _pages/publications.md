---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
.pub-title {
    font-weight: bold;
    margin-bottom: 5px;
}
.pub-authors {
    color: #555;
    margin-bottom: 5px;
}
.pub-venue {
    font-style: italic;
    margin-bottom: 10px;
}
.btn-pub {
    margin-right: 5px;
    margin-bottom: 5px;
    padding: 2px 10px;
    font-size: 12px;
    display: inline-block;
}
.bibtex-box {
    display: none;
    background-color: #f5f5f5;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    margin-top: 10px;
    font-family: monospace;
    font-size: 12px;
    white-space: pre-wrap;
    word-wrap: break-word;
}
</style>

## Publications

<div class="jumbotron">

<p class="pub-title">Assassyn: A Unified Abstraction for Architectural Simulation and Implementation</p>
<p class="pub-authors">Jian Weng, Boyang Han, Derui Gao, Ruijie Gao, Wanning Zhang, An Zhong, Ceyu Xu, Jihao Xin, Yangzhixin Luo, Lisa Wu Wills, et al.</p>
<p class="pub-venue">Proceedings of the 52nd Annual International Symposium on Computer Architecture (ISCA), pp. 1464–1479, 2025</p>

<button class="btn btn-danger btn-pub" onclick="toggleBibtex('bib1')">BibTeX</button>

<div id="bib1" class="bibtex-box">@inproceedings{weng2025assassyn,
  title={Assassyn: A Unified Abstraction for Architectural Simulation and Implementation},
  author={Weng, Jian and Han, Boyang and Gao, Derui and Gao, Ruijie and Zhang, Wanning and Zhong, An and Xu, Ceyu and Xin, Jihao and Luo, Yangzhixin and Wills, Lisa Wu and others},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture (ISCA)},
  pages={1464--1479},
  year={2025}
}
</div>

</div>

<div class="jumbotron">

<p class="pub-title">Orders in Chaos: Enhancing Large-Scale MoE LLM Serving with Data Movement Forecasting</p>
<p class="pub-authors">Zhongkai Yu, Yue Guan, Zihao Yu, <u>Chenyang Zhou</u>, Shuyi Pei, Yangwook Kang, Yufei Ding, Po-An Tsai</p>
<p class="pub-venue">arXiv preprint arXiv:2510.05497, 2025</p>

<a href="https://arxiv.org/abs/2510.05497" target="_blank"><button class="btn btn-primary btn-pub">arXiv</button></a>
<button class="btn btn-danger btn-pub" onclick="toggleBibtex('bib2')">BibTeX</button>

<div id="bib2" class="bibtex-box">@article{yu2025orders,
  title={Orders in Chaos: Enhancing Large-Scale MoE LLM Serving with Data Movement Forecasting},
  author={Yu, Zhongkai and Guan, Yue and Yu, Zihao and Zhou, Chenyang and Pei, Shuyi and Kang, Yangwook and Ding, Yufei and Tsai, Po-An},
  journal={arXiv preprint arXiv:2510.05497},
  year={2025}
}
</div>

</div>

<script>
function toggleBibtex(id) {
    var x = document.getElementById(id);
    if (x.style.display === 'none' || x.style.display === '') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</script>

