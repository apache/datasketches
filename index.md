---
published: true
title: DataSketches
layout: html_page
id: home
---
<!-- Start index.md -->
<link rel="stylesheet" type="text/css" href="css/index.css">
<link rel="stylesheet" type="text/css" href="css/header.css">

<main class="ds-masthead">
  <div class="container">
  <div class="row">
    <div class="col-md-8 col-md-offset-2 text-center">
      <span class="ds-bootlogo"></span>
      <p class="lead" style="font-size: 28px; margin-bottom: 10px">Sketches Library from <span class="y-bootlogo"></span></p>
      <p class="lead" style="font-size: 16px; line-height: 1.0; margin-bottom: 15px">A software library of 
        <a href="https://en.wikipedia.org/wiki/Stochastic" style="color: #EDE379"><i>stochastic</i></a> 
        <a href="https://en.wikipedia.org/wiki/Streaming_algorithm" style="color: #EDE379"><i>streaming algorithms</i></a></p>
      <!--<p class="lead" style="font-size: 16px; line-height: 1.0; margin-bottom: 15px"><i>"Excellence in theoretically informed algorithm engineering" -- Graham Cormode</i></p> -->
      <p>
        <a class="btn btn-lg btn-outline-inverse" href="overview.html"><span class="fa fa-info-circle"></span> Overview</a>
        <a class="btn btn-lg btn-outline-inverse" href="/docs/downloads.html"><span class="fa fa-download"></span> Download</a>
        <a class="btn btn-lg btn-outline-inverse" href="https://github.com/datasketches"><span class="fa fa-github"></span> GitHub</a>
        <a class="btn btn-lg btn-outline-inverse" href="/docs/Research.html"><span class="fa fa-paper-plane"></span> Research</a>
        <a class="btn btn-lg btn-outline-inverse" href="https://groups.google.com/forum/#!forum/sketches-user"><span class="fa fa-comment"></span> Forum</a>
      </p>
    </div>
  </div>
  </div>
</main>

<div class="container">
  <div class="row">
    <div class="text-justify" style="font-size: 18px; padding-left: 25px; padding-right: 25px">
<h1>NOTE: The DataSketches Library is being moved to <a href="https://github.com/apache/incubator-datasketches/blob/master/README.md">ASF</a></h1>
<p><b>The Business Challenge:</b> Analyzing Big Data Quickly.</p>
<p>In the analysis of big data there are often problem queries that don’t scale because they require huge compute resources and time to generate exact results. Examples include <i>count distinct</i>, quantiles, most frequent items, joins, matrix computations, and graph analysis.</p>

<p>If approximate results are acceptable, there is a class of specialized algorithms, called streaming algorithms, or <a href="/docs/SketchOrigins.html">sketches</a> that can produce results orders-of magnitude faster and with mathematically proven error bounds. For interactive queries there may not be other viable alternatives, and in the case of real-time analysis, sketches are the only known solution.</p>

<p>For any system that needs to extract useful information from big data these sketches are a required toolkit that should be tightly integrated into their analysis capabilities. This technology has helped Yahoo successfully reduce data processing times from days to hours or minutes on a number of its internal platforms.</p>

<p>This site is dedicated to providing key sketch algorithms of production quality. Contributions are welcome from those in the big data community interested in further development of this science and art.</p>
    </div>
  </div>
  <div class="row text-center main-marketing">
    <div class="col-md-4">
      <p><a href="/docs/KeyFeatures.html">
        <span class="fa fa-fighter-jet fa-4x"></span><br>
        <h2>Fast</h2>
      </a></p>
      <p class="text-justify"><a href="/docs/SketchOrigins.html">Sketches</a> are <i>fast</i>. 
      The sketch algorithms in this library process data in a single pass and are suitable for 
      both real-time and batch. 
      Sketches enable streaming computation of set expression cardinalities, quantiles, frequency estimation and more. 
      This allows simplification of system's architecture and fast queries of heretofore difficult computational tasks.</p>
    </div>

    <div class="col-md-4">
      <a href="/docs/KeyFeatures.html">
        <span class="fa fa-database fa-4x"></span>
        <h2>Big Data</h2>
      </a>
      <p class="text-justify">This library has been specifically designed for big data systems. 
      Included are adaptors for Hadoop Pig and Hive, which also can be used as examples for other systems, 
      and many other capabilities typically required in big data analysis systems. 
      For example, a Memory package for managing large off-heap memory data structures.</p>
    </div>

    <div class="col-md-4">
      <p><a href="/docs/KeyFeatures.html">
        <span class="fa fa-bar-chart-o fa-4x"></span><br>
        <h2>Analysis</h2>
      </a></p>
      <p class="text-justify">Built-in Theta Sketch set operators (Union, Intersection, Difference) 
      produce sketches as a result (and not just a number) enabling full set expressions of cardinality, 
      such as ((A &#8746; B) &#8745; (C &#8746; D)) \ (E &#8746; F). 
      This capability along with predictable and superior accuracy 
      (compared with <i>Include/Exclude</i> approaches) enable unprecedented analysis capabilities 
      for fast queries. </p>
    </div>
  </div>
</div>

<div class="ds-panel">
  <div class="container">
    <div class="row-fluid text-center">
      <div class="col-sm-4 col-sm-offset-2">
        <h3>Get Started</h3>
        <p><a href="/docs/Architecture.html">Architecture</a></p> <!-- add {{site.stable_version}} -->
        <!-- <p><a href="/docs/tutorials.html">Tutorials</a></p>  add {{site.stable_version}} -->
        <!-- ><p style="color:rgba(177,186,198,0.7)">Latest Stable Release</p> add {{site.stable_version}} -->
      </div>
      <div class="col-sm-4">
        <h3>Learn More</h3>
        <p><a href="/docs/KeyFeatures.html">Key Features</a></p>
        <p><a href="/docs/TheChallenge.html">The Challenge</a></p>
        <p><a href="/docs/WhoUses.html">Who uses DataSketches?</a></p>
      </div>
    </div>
  </div>
</div>
<!-- End index.md -->
