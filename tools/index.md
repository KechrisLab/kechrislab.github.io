---
title: Tools
nav:
  order: 5
  tooltip: Tools
---

# Tools

{%
  include link.html
  type=""
  icon= "fab fa-github"
  text= "Kechris Lab Github"
  link = "https://github.com/kechrislab"
  style="button"
%}
{:.center}

{% include search-info.html %}

{% include section.html %}

<style>

  p{
    text-align: center;
}
  
</style>


## OMICS INTEGRATION

{% include list.html component="card" data="tools" filters="group: OMICS INTEGRATION" style="large" %}

{% include section.html %}

## METABOLOMICS

{% include list.html component="card" data="tools" filters="group: METABOLOMICS" style="large" %}

{% include section.html %}

{% capture col1 %}

## MICROBIOME

{% include list.html component="card" data="tools" filters="group: MICROBIOME" style="large" %}
{% endcapture %}

{% capture col2 %}

## EPIGENETICS

{% include list.html component="card" data="tools" filters="group: EPIGENETICS" style="large" %}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}

{% include section.html %}

## TRANSCRIPTOMICS

{% include list.html component="card" data="tools" filters="group: TRANSCRIPTOMICS" style="large" %}


{% include section.html %}
## TRANSCRIPTION FACTOR BINDING

{% include list.html component="card" data="tools" filters="group: TRANSCRIPTION FACTOR BINDING" style="large" %}
