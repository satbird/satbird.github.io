---
title: 'SatBird: a Dataset for Bird Species Distribution Modeling using Remote Sensing and Citizen Science Data'
layout: default
---

<style>thead { display: none; }</style>


## SatBird Dataset and Benchmark

SatBird is a dataset and benchmark for the task of predicting bird species encounter rates jointly at a specific location using remote sensing data. The dataset was obtained from publicly available [eBird](https://ebird.org/home) bird observation records Sentinel-2 satellite data, and [WorldClim](https://www.worldclim.org/) and [SoilGrids](https://soilgrids.org/) environmental data. \\
SatBird is composed of 3 sub-datasets: (i) USA summer dataset, generally corresponding to the breeding season, (ii) USA winter dataset, the nonbreeding season, (iii) Kenya dataset, as an example of a low-data regime.


SatBird is designed with the goal of completing species distribution mapping in places that have yet not been surveyed, leveraging the presence-absence nature of complete checklists in the eBird database. 

<p class="cover" align="center"> <img src="assets/pipeline.jpg" width="85%" /> </p>

## Dataset and Benchmark details


SatBird demonstrate the relevance of using both environmental and remote sensing data for species distribution modelling.
The SatBird dataset is available for [download](https://drive.google.com/drive/folders/1eaL2T7U9Imq_CTDSSillETSDJ1vxi5Wq?usp=sharing), and we release the [code](https://github.com/mila-iqia/SatBird/) for building the dataset in other regions of the world and for the benchmark. 



Citing
------
If you find this open source release useful, please reference in your paper:

> Teng, M., Elmustafa, A., Akera, B., Radi, H., Bengio, B., Larochelle, H., Rolnick, D.
> SatBird: a Dataset for Bird Species Distribution Modeling using Remote Sensing and Citizen Science Data
> *Conference on Neural Information Processing Systems (NeurIPS) 2023, Datasets and Benchmarks track*.

    @inproceedings{
    }

## Authors

<div style="text-align: left;">
{%- for person in site.data.authors -%}
<div class="person">
  <img src="{{ person.image }}" />
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a><br>
  <span>{{ person.title | replace: '&', '<br>' }}</span>
  <!--span>({{ person.topics }})</span-->
</div>
{%- endfor -%}
</div>

<p style="text-align: left">
For questions, please contact us at:
<a href="mailto:tengmeli@mila.quebec">tengmeli@mila.quebec</a>,
<a href="mailto:ecosystem-embeddings@mila.quebec">ecosystem-embeddings@mila.quebec</a>.
</p>



