---
title: "Tracking"
subtitle: "Generate brain connectomes using a combination fiber tracking method."
layout: app
starturl: "/legacy/tracking"
giturl: "https://github.com/brain-life/app-tracking"
permalink: /home/tracking
---

Automated access to [Compute clouds](https://jetstream-cloud.org) to process diffusion data using multiple tractography methods. This service combines multiple tractography methods by implementing [Ensemble Tractography](https://doi.org/10.1371/journal.pcbi.1004692). It creates a large set of candidate streamlines using an ensemble of algorithms and parameter values and then selects the streamlines with strong support from the data using a global fascicle evaluation method.  *Ensemble Tractography* connectomes predict diffusion MRI signals better and cover a wider range of white matter volume then single algorithm and single parameter connectomes. The *Ensemble Tractography* service tracks using [MRtrix](http://www.mrtrix.org).

<br>
<h3>Sample Output</h3>
<center>
<img src="/images/screenshots/tracking.png" class="screenshot">
</center>
<br>
