# Project for the course advanced machine learning for computer vision (2025)

## Background
### Intro
The Varroa destructor is a parasitic mite that infests honey bee colonies.

Varroa mites weaken and eventually kill beehives by feeding on bees and by acting as carriers for a wide range of diseases. 
The mites reproduce inside capped brood cells, where the female lays eggs that mature and mate on the developing bee.

### Control
Control decisions are usually based on infestation levels. A common guideline in beekeeping is that a 3% infestation rate within a colony represents the economic threshold at which treatment becomes necessary.

### Treatment
Treatment combines miticides, organic acids that can suffocate mites through vapor exposure, Furthermore mechanical methods to keep populations in check.

### more on the mite
[Wikipedia/Varroa_destructor](https://en.wikipedia.org/wiki/Varroa_destructor)

## Approach
### Main Idea
Classifying infected from non infected bees

### Data Sets
- [(Stefan & Kampel, 2020)](https://zenodo.org/records/4085044) 
    - (13509, 160, 280) where pos: 3,947 & neg: 9,562 

### Possible Starting Points
- inception v3
- pretrained model on insects -> see huggingface