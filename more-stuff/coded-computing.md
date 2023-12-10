---
image: "{{ site.url }}/Coded-Computing/coded-computing.svg"
layout: page
title: Coded Computing for Straggler Mitigation, Security and Privacy
---

Introduction
------------

The massive size of modern datasets necessitates computational tasks to be performed in a distributed fashion, where the data is dispersed among many servers that operate in parallel. As we "scale out" computations across many servers, however, several fundamental challenges arise. Cheap commodity hardware tends to vary greatly in computation time, and it has been demonstrated that a small fraction of servers, referred to as stragglers, can be 5 to 8 times slower than the average, thus creating significant delays in computations. Also, as we distribute computations across many servers, massive amounts data must be moved between them to execute the computational tasks, often over many iterations of a running algorithm, and this creates a substantial bandwidth bottleneck. Distributed computing systems are also much more susceptible to adversarial servers, making security and privacy a major concern.

**Our presentation can be viewed below** 

<iframe src="https://www.youtube.com/embed/x0jxCYyXz98" allowfullscreen></iframe>

**The slides: [with pauses]({{ site.url }}/Coded-Computing/Coded%20Computing%20with%20pauses.pdf) and [without pauses]({{ site.url }}/Coded-Computing/Coded%20Computing%20without%20pauses.pdf).**

**The QnA can be viewed [here]({{ site.url }}/Coded-Computing/QnA.pdf).**

TeX-nical Details
-----------------

[This](https://github.com/paramrathour/Coded-Computing/blob/main/main.tex)
is the primary TeX file which is to be compiled to get the report.

[This](https://github.com/paramrathour/Coded-Computing/blob/main/references.bib)
is the BibTeX file containing the references used by me.