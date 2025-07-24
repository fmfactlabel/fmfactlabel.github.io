---
title: FM Fact Label
feature_text: |
  ## FM Fact Label
  A tool to generate visualizations of feature model characterizations as a fact label similar to the [nutritions fact label](https://en.wikipedia.org/wiki/Nutrition_facts_label).
feature_image: "assets/fact_label_fondo.png"
excerpt: "FM Fact Label is an online web-based application that builds a feature model's characterization and generates its visualization as a fact label."
---

*FM Fact Label* is an online web-based application that builds an FM characterization and generates its visualization as a fact label.

{% include button.html text="Try it online 🏷️" link="app/" color="#11b786" %} {% include button.html text="View it on GitHub" icon="github" link="https://github.com/jmhorcas/fm_characterization" color="#555555" %}

## Features

- Clear and elegant design to visualize the metrics of your feature models
- Inspired by the nutrition fact label used in the food industry
- Up to 76 different measures reported
- Metadata, structural (syntactical) metrics, and analysis (semantical) results
- Powered by [flamapy](https://www.flamapy.org/) for the automated analysis of feature models
- Part of the [UVL](https://universal-variability-language.github.io/) ecosystem
- Support all language extensions of [UVL](https://universal-variability-language.github.io/)
- Easy to use standalone web-based online application
- Configure and customize the fact label visualization
- Export the fact label to SVG, PNG, or PDF
- Export the characterization to JSON or TXT
- Load a previous computed characterization in JSON


## Publications

- José Miguel Horcas, José A. Galindo, Lidia Fuentes, David Benavides. *FM Fact Label*. Science of Computer Programming (SCP). 2025. DOI: <a href="https://doi.org/10.1016/j.scico.2024.103214">https://doi.org/10.1016/j.scico.2024.103214</a>
<button type="button" onclick="copyBibTeX(bibtexEntry1)">Copy BibTex 🗎</button>

- José Miguel Horcas, José A. Galindo, Mónica Pinto, Lidia Fuentes, David Benavides. *FM Fact Label: A Configurable and Interactive Visualization of Feature Model Characterizations*. 26th International Systems and Software Product Line Conference (SPLC). Demo and Tools Track. 2022. DOI: <a href="https://doi.org/10.1145/3503229.3547025">https://doi.org/10.1145/3503229.3547025</a>
<button type="button" onclick="copyBibTeX(bibtexEntry2)">Copy BibTex 🗎</button>


## Example

A fact label of the Linux feature model

<img src="assets/linux_factlabel.png" alt="Fact Label of the Linux feature model" width="200"/>

## Entities involved

<a href="https://www.uma.es/"><img src="assets/uma.svg" alt="Universidad de Málaga" width="200"/></a>
<a href="https://www.us.es/"><img src="assets/us.svg" alt="Universidad de Sevilla" width="200"/></a>

<script>
 // Store the BibTeX entry in a JavaScript variable
  {% raw %}
  const bibtexEntry1 = `
@article{Horcas2025_FMFactLabel,
  author       = {Jos{\'{e}} Miguel Horcas and Jos{\'{e}} A. Galindo and Lidia Fuentes and David Benavides},
  title        = {{FM} fact label},
  journal      = {Sci. Comput. Program.},
  volume       = {240},
  pages        = {103214},
  year         = {2025},
  url          = {https://doi.org/10.1016/j.scico.2024.103214},
  doi          = {10.1016/J.SCICO.2024.103214},
  timestamp    = {Mon, 21 Oct 2024 11:11:55 +0200},
  biburl       = {https://dblp.org/rec/journals/scp/HorcasGFB25.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}

    {% raw %}
  const bibtexEntry2 = `
@inproceedings{Horcas2022_FMFactLabel,
  author       = {Jos{\'{e}} Miguel Horcas and Jos{\'{e}} Angel Galindo and M{\'{o}}nica Pinto and Lidia Fuentes and David Benavides},
  title        = {\emph{FM fact label}: a configurable and interactive visualization of feature model characterizations},
  booktitle    = {26th {ACM} International Systems and Software Product Line Conference ({SPLC})},
  pages        = {42--45},
  publisher    = {{ACM}},
   volume    = {B},
  year         = {2022},
   address   = {Graz, Austria},
  month     = sep,
  url          = {https://doi.org/10.1145/3503229.3547025},
  doi          = {10.1145/3503229.3547025},
  timestamp    = {Tue, 21 Mar 2023 00:00:00 +0100},
  biburl       = {https://dblp.org/rec/conf/splc/HorcasGPF022.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}`;
  {% endraw %}
  function copyBibTeX(bibtexEntry) {
      // Create a temporary textarea to hold the BibTeX entry
      const tempTextarea = document.createElement("textarea");
      tempTextarea.value = bibtexEntry;
      document.body.appendChild(tempTextarea);

      // Select and copy the text
      tempTextarea.select();
      document.execCommand("copy");

      // Remove the temporary textarea
      document.body.removeChild(tempTextarea);
  }
</script>
