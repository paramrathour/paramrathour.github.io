---
image: Projects/Thumbnails/DDLtp.png
layout: page
title: Distributed Deep Learning
---

This project is a part of the **Institute Technical Summer Project** of the [Institute Technical Council, IIT Bombay](https://www.tech-iitb.org/).

The Team consists of Sumit Jain, Aditya Bhaskar, Ritik Mandal and me

Introduction
------------

Deep learning models are now extensively used in various domains ranging from medical imaging to automobile industry. Yet, till date deep learning models fail when it comes to play around with **High-resolution data**, such as CT Scans, X Rays, other medical imaging, satellite images, data used for weather and natural calamity. This lack of capability to process such a high resolution data limit the applicability of deep learning models.
A lot of research is underway, to efficiently use distributed systems in training deep learning models. Conventionally, this is being done by **data parallelism**, **model parallelism**, and **spatial distribution with halo exchange**. These have some shortcomings though.

Our Idea
------------

Our model uses a hierarchy-based model to achieve synchronous parallel computations distributed to multiple machines.  
We distribute the task to individual models both vertically and horizontally. Nodes at the same level have the same task and those at a higher level decide the final say of lower ones in the decision made by the model as a whole. 

**In a Nutshell:**
- Hierarchical use of neural networks
- Distributing breadth wise (parallel computations).
- Extraction of localized details in data

**The Two Pager Documentation can be viewed** [here](https://docs.google.com/document/d/1TAhDH4TmWtORCAD1HUtSDKvHyF_aypTlR9J6Z29Vzp0/edit?usp=sharing).

**The Final Documentation can be viewed** [here](https://docs.google.com/document/d/11M9R2pojlNDRBcGGw4Iz9tKQlFkmiyXBFqZN4cq8zMc/edit?usp=sharing).