---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
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

## Software

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>GDBr</b></h4><i>Genome identification tool for Double-strand Break Repair</i><br>
<a href="https://github.com/Chemical118/GDBr" target="_blank"><button class="btn btn-info btn-sm">GITHUB</button></a>
<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/example_proceeding.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> -->
</div>
</div>
GDBr is a Python wrapper program that uses blast results to identify double-strand break repairs in the genome.
As long as you have a long-read sequenced genome, GDBr will do all the work in one steps, automatically converting all the results to Tab-separated values (TSV) and figures for you.
We also used appropriate multiprocessing to realize high performance.
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>TREW</b></h4><i>Telomeric Repeat motif Estimation tool with Whole-genome sequencing data</i><br>
<a href="https://github.com/Chemical118/TREW" target="_blank"><button class="btn btn-info btn-sm">GITHUB</button></a>
<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/example_proceeding.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> -->
</div>
</div>
TREW is tool that can identify Telomeric repeat motif (TRM) with any whole-genome sequencing data.
This tool looks for repeated sequences in a single read to find candidates for TRMs, iterating through them to finally find a TRM.
It also uses oneAPI Threading Building Blocks (oneTBB) for high performance and high-level multithreading, making it 10x faster than traditional tools.
</div>