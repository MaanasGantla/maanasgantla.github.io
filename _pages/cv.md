---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. + M.S. in Computer Science, University of California, Los Angeles, September 2023 – June 2027
  * Relevant Coursework: Data Structures & Algorithms, Neural Networks & Deep Learning I & II (Graduate), Operating Systems, Software Construction Lab, Robotics, Computer Architecture, Digital System Design, Probability and Statistics, Theory of Computation, Discrete Math, Differential Equations, Linear Algebra, Multivariable Calculus

Experience
======
* 2025: Software Development Engineer Intern — Amazon, Alexa Customer Journeys (Irvine, CA)
  * Designed and implemented a serverless ETL pipeline using AWS Lambda and OpenSearch to process Alexa device discovery data, improving data freshness for team-critical analytics
  * Developed an AWS Lambda that automatically ingests S3 data into OpenSearch, reducing data latency for analysis from 2 hours to 20 minutes
  * Automated infrastructure deployment using AWS CDK and integrated it into the CI/CD pipeline for continuous delivery

* April 2025 – Present: Undergraduate Research Intern — University of California, Los Angeles (Los Angeles, CA)
  * Built a stratified sampling pipeline using the Small2Large (S2L) data selection method to construct a 1K subset of the M23K dataset, preserving original domain proportions across four QA sources
  * Launched S2L training experiments with domain-aware and reasoning-based sampling, improving out-of-domain accuracy by 4.2%
  * Developed Python tools to analyze token counts, domain mix, and prompt/reasoning length variation across 8K+ QA samples

* 2021 – 2025: AI and Bioinformatics Research Intern — University of California, San Diego (San Diego, CA)
  * Developed five binary classification machine learning models with 91.5%–99% accuracy for drug repurposing using supervised learning algorithms
  * Extracted and cleaned data from PubChem, ZINC, and the Protein Data Bank for model training and testing
  * Published project in a scientific journal and as a book chapter under Prof. Tsigelny and Prof. Kouznetsova
  * Conducted data analysis by querying the KEGG Pathway Database to find biological pathways related to Hepatocellular Carcinoma (HCC) and HBV mutations

Skills
======
* Languages: Python, C++, C, Java, JavaScript/TypeScript, HTML/CSS, Shell, Makefile, X86-64 Assembly
* Frameworks/Tools: React.js, Node.js, Next.js, Flask, Bootstrap, Bash, PyTorch/TensorFlow, MongoDB, Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
