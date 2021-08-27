---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: class
shastra: tarka
---

<div class="page-description">
A study of tarka -- particularly navya nyaya -- gives us the vocabulary which is used extensively in the discussion of all shastras. The basic requirement is a study of the tarka sangraha along with one of the commentaries (usually the dipika or nyaya bodhini).
</div>

{% capture paribhasha_content %}
One reason for the study of tarka shastra is to learn navya nyaya terminology. This is widely used in vedanta study. The following classes focus narrowly on basic paribhashas.
{% endcapture %}

{% include classes_by_tag.html tag="pravesha" display="tarka pravesha (paribhasha)" content=paribhasha_content %}

{% capture mulam_content %}
The tikas presuppose a basic understanding of the content of the tarka sangraha. Understanding it's structure and approach, as well a basic understanding of it's main teachings will be helpful in reading any of the tikas.
{% endcapture %}

{% include classes_by_tag.html tag="mula" display="tarka sangraha (mulam)" content=mulam_content %}

{% include classes_by_tag.html tag="pada" display="tarka sangraha with padakritya"%}

{% include classes_by_tag.html tag="bodhini" display="tarka sangraha with nyayabodhini"%}

{% include classes_by_tag.html tag="dipika" display="tarka sangraha with dipika"%}