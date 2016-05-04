# TCGAsnake

This repository contains Snakefiles for TCGA data analysis workflows.
Directory paths are based on the folder structure on [Computerome][computerome wiki].

## Getting started

If you are new to [Snakemake], you might like to start by walking through my
[tutorial for beginners][beginners]. Next, have a look at Johannes Koster's
[introductory slides][slides], [tutorial], [documentation], and [FAQ].



## Workflows

### [kallisto/][1]

[1]: https://github.com/sidiropoulos/TCGAsnake/tree/master/rna-seq/kallisto

Quantify gene isoform expression in transcripts per million (TPM) with
[kallisto].

### [kallisto_single/][2]

[2]: https://github.com/sidiropoulos/TCGAsnake/tree/master/rna-seq/kallisto_single

Same for single-end rna-seq experiments.

## Achknowledgements
Snakefiles and repository structure (including this README file) are ~~stolen~~ inspired by [slowkow](https://github.com/slowkow/snakefiles)
and [pimentel](https://github.com/pimentel/bears_iplant)

[kallisto]: https://github.com/pachterlab/kallisto
[beginners]: http://slowkow.com/notes/snakemake-tutorial/
[Snakemake]: https://bitbucket.org/snakemake/snakemake/wiki/Home
[slides]: http://slides.com/johanneskoester/deck-1
[tutorial]: http://htmlpreview.github.io/?https://bitbucket.org/snakemake/snakemake/raw/master/snakemake-tutorial.html
[documentation]: https://bitbucket.org/snakemake/snakemake/wiki/Documentation
[FAQ]: https://bitbucket.org/snakemake/snakemake/wiki/FAQ
[computerome wiki]: http://wiki.bio.dtu.dk/computerome/index.php/Main_Page
