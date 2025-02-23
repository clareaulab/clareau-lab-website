---
title: Research
nav:
  order: 3
  tooltip: Scientific focuses
---

# {% include icon.html icon="fa-solid fa-flask" %} Research Philosophy

We are a team of interdisciplinary scientists that specializes in <b>computational and systems immunology</b>.
Our lab is a hybrid "wet" (experimental) and "dry" (bioinformatics) team. We broadly focus on three themes:


<b>1. Computational systems virology</b>. Current estimates of the human virome indicate
that for every one human cell, there are ~10 viral particles (or 380 trillion total) within the human body.
Despite the ubiquity of these viruses, our knowledge about the commensal virome, tolerogenic mechanisms,
and response to pathogenic infection is in its infancy. Rather than conventional virology approaches,
we scour the totality of existing DNA sequencing libraries to 
uncover new biological associa?ons hidden in large-scale data. 
In our previous work, we found unexpected signals in discarded data, including somatic mitochondrial DNA mutations 
that could be [utilized for lineage tracing](https://clareaulab.com/protocols/mitotracing/index.html) 
and reads from herpesviruses that could be used to uncover a potenial mechanism for a toxicity during 
[adoptive cell therapy](https://www.statnews.com/2023/11/08/car-t-cancer-therapy-complications-herpes-encephalitis/).

For our future efforts, our lab was recently awarded a U01 grant as part of the
[Human Virome Program](https://commonfund.nih.gov/humanvirome), 
a new NIH-funded initiative to map viral infection, pathogenesis, and clinical correlates using high-dimensional sequencing data.


<b>2. Genomics technology development</b>. Data-driven hypotheses can crystalize
from reanalyses but often lack definitive evidence. Our prior work has taught us that new
technologies are often required to test retrospective findings rigorously or 
scale up the number of measurements for proper inference. Thus, a major focus of the
experimental component of our group is to establish new technologies that, once developed, 
explain phenomenon in high-dimensional data or enable foundational new directions. 

Recently, and as the first paper from our lab, we described the 
[Programmable Enrichment via RNA FlowFISH by sequencing (PERFF-seq)](https://clareaulab.com/perffseq/) 
that enables studying rare populations using arbitrary nucleic acid 
cytometry to isolate and profile rare cell states.
We continue innovative single-cell technology development in close collaboration with 
the [Single-cell Analytics Innovation Lab (SAIL)](https://www.mskcc.org/research/ski/innovation-labs/single-cell-analytics-innovation-lab-sail), 
our next-door neighbor.

<b>3. Computational protein design</b>. 
A new area that our lab is actively exploring is the computational design of proteins. 
Based on rapid advances in deep learning architectures like Alphafold and corresponding innovations in 
generative artificial intelligence (e.g., hallucination, diffusion), 
we anticipate that programmable protein design will be as commonplace as DNA primer design within the next 10-15 years.
Accordingly, our lab has initiated high-risk, high-reward projects utilizing deep learning to 
create new proteins that may enable new therapies. These include developing protein binders for known and novel cancer
antigens that may be utilized in clinical practice at MSKCC.

{% include section.html background="images/scistories-clear-cut.png" dark=false %}

{% include section.html %}

## Focus areas

Check out our publications on each of the lab's major areas of focus:

{% include list.html component="card" data="projects" style="small" %}

{% include section.html background="images/scistories-clear-cut.png" dark=false %}

{% include section.html %}

## Funding

We are incredibly grateful to the many generous donors, foundations, and institutes that enable our most ambitious research. 
Our trainees have an exceptional track record of securing independent funding to support their research in the lab:

- [Arthur Chow](https://clareaulab.com/members/arthur-chow.html), Ludwig Center Postdoctoral Scholar Award
- [Erica Sun](https://clareaulab.com/members/erica-sun.html), MSK T32 Investigational Cancer Therapeutics Training Grant
- [Laura Kida](https://clareaulab.com/members/laura-kida.html), Boehringer Ingelheim Fonds (BIF) MD Fellowship
- [Jacob Gutierrez](https://clareaulab.com/members/jacob-gutierrez.html), GSK Harold Varmus Fellowship
- [Austin Varela](https://clareaulab.com/members/austin-varela.html), NSF Graduate Research Fellowship
- [Sherry Nyeo](https://clareaulab.com/members/sherry-nyeo.html), NSF Graduate Research Fellowship

{% include section.html background="images/scistories-clear-cut.png" dark=false %}

{% include section.html %}

The lab's overall research program is currently supported by the generous contributions from these sources:

{% capture mskcc %}
{%
  include figure.html
  image="images/funding/mskcc.png"
%}
{% endcapture %}

{% capture kravis %}
{%
  include figure.html
  image="images/funding/kravis-ecosystems.png"
%}
{% endcapture %}

{% capture nhgri %}
{%
  include figure.html
  image="images/funding/nhgri.png"
%}
{% endcapture %}

{% capture c4s %}
{%
  include figure.html
  image="images/funding/c4s.png"
%}
{% endcapture %}

{% capture hvp %}
{%
  include figure.html
  image="images/funding/hvp.png"
%}
{% endcapture %}

{% capture commonfund %}
{%
  include figure.html
  image="images/funding/commonfund.png"
%}
{% endcapture %}

{% capture ncicc %}
{%
  include figure.html
  image="images/funding/nci-cc.png"
%}
{% endcapture %}


{% capture michelson %}
{%
  include figure.html
  image="images/funding/michelson.png"
%}
{% endcapture %}


{% include cols.html col1=c4s col2=michelson col3=hvp %}
{% include cols.html col1=commonfund col2=ncicc col3=nhgri %}

