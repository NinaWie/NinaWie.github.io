---
layout: page
title: FeatOut
description: Remove features to avoid shortcut learning
img: assets/img/projects/featout.png
importance: 3
category: research
giscus_comments: false
---

I had an idea for tackling shortcut learning with neural networks. Shortcut learning refers to the problem that the network just learns to classify samples based on few features, e.g. distinguishing dogs and cats only by their ears. These models fail to generalize (e.g. when the ears are not visible in the test set). The idea was to use gradient-based methods for detecting which features the model currently uses, and then to blur these features and retrain. I started a code base and did some initial tests, and we gave it to students in a one-day hackathon, but I would still like to explore this idea more in depth.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/featout_overview.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of our approach
</div>

Resources:
* [Code](https://github.com/NinaWie/featout/tree/master)