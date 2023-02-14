---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

----

My research lies in the intersection of **data privacy**, **software security**, **machine learning** and **algorithmic fairness**. The overarching goal of my work is to protect sensitive personal information from being leaked in unintended ways. My current research focuses on <em>differential privacy</em> and its interactions with software security, formal verification, numerical optimization, statistical inference and machine learning. 

<div class="alert alert-success">
  <i class="fas fa-solid fa-star"></i> <strong>Hiring:</strong> <b>I have several (fully funded) openings for highly-motivated and outstanding PhD students. If you are interested in working with me, please send me an email with your CV.</b>
</div>

Some of my current projects include:

----

##### Extensible Differentially Private SQL System

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/CustomDP4SQL.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">
            Image from our CheckDP paper
        </div> -->
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
    Key features:
        <ul>
            <li>Allows a user to write code that explains how a set of query answers is intended to be used.</li>
            <li>Allows a database administrator to customize the required differential privacy plausible deniability guarantees.</li>
            <li>Uses formal methods and programming languages technology to synthesize and verify key components such as the sensitivity & stability of data transformation operators.</li>
        </ul>
    </div>
</div>

----

##### Privacy in Machine Learning and Mixed Reality

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/PrivML.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Image from <a href="https://arxiv.org/abs/2004.12254">Privacy in Deep Learning: A Survey</a> by Mireshghallah et al.
        </div>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
    Objectives
        <ul>
            <li>To understand the risks of privacy leakage in deep learning models and AR/VR systems</li>
            <li>To detect inductive biases in ML models and other decision making algorithms</li>
            <li>To devise strategies to defend against privacy leakages and promote algorithmic fairness</li>
        </ul>
    </div>
</div>

----

##### Verification and Synthesis of Differentially Private Programs

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/checkdp-overview.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Image from our <a href="https://arxiv.org/abs/2008.07485">CheckDP paper</a>
        </div>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
    Objectives
        <ul>
            <li>To show incorrectness for buggy programs by generating counterexamples (inputs that trigger bugs) for them</li>
            <li>To generate machine proofs for correct programs using formal verification and programming language tools</li>
            <li>To synthesize a private version given a non-private program</li>
        </ul>
    </div>
</div>
