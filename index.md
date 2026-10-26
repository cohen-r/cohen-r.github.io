---
layout: default
title: About
permalink: /
---

<section class="hero" aria-labelledby="hero-name">
  <div class="hero-text">
    <h1 id="hero-name">Rachel Cohen</h1>
    <p class="role">Postdoctoral Associate, Cai lab, University of Florida<br>PhD, Ecology, Evolution and Environmental Biology, Columbia University</p>
    <p class="lede">I study how flowering plants recognize other species, and how parasitism and pollination shape plant genomes.</p>
    {% include contact.html %}
  </div>

  <nav class="cladogram" aria-label="Sections of this site">
    <svg viewBox="0 0 330 190" role="img" aria-labelledby="clad-title">
      <title id="clad-title">A small phylogenetic tree whose tips link to the sections of this site</title>
      <g class="branches" fill="none" stroke-linecap="round">
        <path pathLength="1" d="M8 125.6 H50" />
        <path pathLength="1" d="M50 86.3 V165" />
        <path pathLength="1" d="M50 86.3 H90" />
        <path pathLength="1" d="M50 165 H170" />
        <path pathLength="1" d="M90 52.5 V120" />
        <path pathLength="1" d="M90 52.5 H130" />
        <path pathLength="1" d="M90 120 H170" />
        <path pathLength="1" d="M130 30 V75" />
        <path pathLength="1" d="M130 30 H170" />
        <path pathLength="1" d="M130 75 H170" />
      </g>
      <a href="#research"><circle cx="170" cy="30" r="4.5"/><text x="184" y="35">Research</text></a>
      <a href="#about"><circle cx="170" cy="75" r="4.5"/><text x="184" y="80">About me</text></a>
      <a href="{{ '/publications/' | relative_url }}"><circle cx="170" cy="120" r="4.5"/><text x="184" y="125">Publications</text></a>
      <a href="{{ '/teaching/' | relative_url }}"><circle cx="170" cy="165" r="4.5"/><text x="184" y="170">Teaching</text></a>
    </svg>
  </nav>
</section>

## Research {#research}

Plants are constantly deciding how to respond to other species. A parasitic plant has to recognize a suitable host before it attaches, and a flower has to tell its own pollen apart from the pollen of its neighbors. My work asks how these recognition systems evolve and what they leave behind in plant genomes, combining fieldwork with comparative genomics, transcriptomics, and phylogenomics.

### Parasitic plant genomes

Most of my work on parasitism uses *Pedicularis*, a large genus of root-parasitic plants in the Orobanchaceae. I assembled a reference genome and developmental transcriptome for *P. groenlandica* to trace how genes involved in building the haustorium, the organ parasites use to invade their hosts, have evolved across parasitic lineages ([Cohen et al. 2026, *Annals of Botany*](https://doi.org/10.1093/aob/mcag089)). Parasites can also pick up genes directly from their hosts, and with Liming Cai I developed HGTScanner to detect horizontal gene transfer at fine scales in organelle genomes ([Cai and Cohen 2026, *Methods in Ecology and Evolution*](https://doi.org/10.1111/2041-210x.70419)). As a postdoc in Liming Cai’s lab at the University of Florida, I am extending this work to comparative and population genomics of parasitic plants.

### Pollen recognition across species

In species-rich plant communities, flowers routinely receive pollen from other species. Working in alpine meadows at the Rocky Mountain Biological Laboratory, I ran more than 3,000 hand pollinations over three field seasons to measure how pistils respond to foreign pollen. How closely related two species are does not predict whether foreign pollen succeeds ([Cohen et al. 2025, *American Journal of Botany*](https://doi.org/10.1002/ajb2.70004)), but the pistil’s molecular and physiological responses do weaken with evolutionary distance, shifting from recognition to neglect ([preprint](https://doi.org/10.64898/2026.06.02.729600)).

My dissertation, *The Genetics of Recognition: Parasitism, Reproduction, and Genome Evolution in Flowering Plants*, received Columbia’s Don Jay Melnick Award in 2026.

## About me {#about}

<img class="portrait" src="https://avatars.githubusercontent.com/u/71609947?s=400&v=4" alt="Rachel Cohen" width="200" height="200">

I grew up in the San Francisco Bay Area and studied Biology at Amherst College, then did my PhD in the [Eaton lab](https://eaton-lab.org/) at Columbia University. Fieldwork has taken me to the Colorado Rockies, the Maritime Alps of Italy, Bhutan, Costa Rica, Maryland, Massachusetts, and New York. Before graduate school I spent a year in Peru’s lowland Amazon as a program assistant for the School for Field Studies, supporting undergraduates in environmental science and biology. I now live in Gainesville, Florida.

Outside the lab I love cooking, playing Scrabble, and hiking.
