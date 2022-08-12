---
title: Software
main:
  - title: Web of Life (WoL)
    image_path: assets/images/software/wol.png
    image_caption: "[Zhu et al., _Nat Commun_, 2019](https://www.nature.com/articles/s41467-019-13443-4)"
    url: https://biocore.github.io/wol/
    btn_label: "Learn More"
    btn_class: "btn--info"
    excerpt: >
        The WoL project aims at building a reference phylogeny which accurately defines the evolutionary relationships among all microbes. In Phase I of the project, we built a phylogeny of 10,575 genomes using 381 marker genes, making this the single largest dataset upon which _de novo_ phylogenetic trees had been built, yet the bioinformatic approaches we adopted or invented are significantly more robust than previous works. It means to serve as a reference for researchers to explore the evolution and diversity of microbes, and to improve the study of microbial communities.
  - title: Woltka
    image_path: assets/images/software/woltka.png
    image_caption: "[Zhu et al., _mSystems_, 2022](https://journals.asm.org/doi/10.1128/msystems.00167-22)"
    url: https://github.com/qiyunzhu/woltka
    btn_label: "Learn More"
    btn_class: "btn--info"
    excerpt: >
        Woltka is a bioinformatics package for shotgun metagenomic data analysis. It highlights: 1) fine-grain community ecology featuring individual reference genomes; 2) tree-based, rank-free classification to maximize resolution and flexibility; 3) combined taxonomic & functional analysis through one alignment to ensure consistency and accuracy. It takes full advantage of, but not limited by, the [WoL](https://biocore.github.io/wol/) reference phylogeny. It comes with an interface for the [QIIME 2](https://qiime2.org/) package, and has been integrated into the [Qiita](https://qiita.ucsd.edu/) web server.
  - title: BinaRena
    image_path: assets/images/software/binarena.jpg
    image_caption: "[Pavia et al., _bioRxiv_, 2022](https://www.biorxiv.org/content/10.1101/2022.06.28.498025v1)"
    url: https://github.com/qiyunlab/binarena
    btn_label: "Learn More"
    btn_class: "btn--info"
    excerpt: >
        Binarena ("bin arena") is an interactive visualizer and operator of metagenomic contigs to facilitate discovery of biological patterns and recovery of MAGs. It is dedicated to **human-guided** research in order to complement algorithmic workflows. It lets the user conveniently observe various characteristics of large metagenomic datasets, efficiently manipulate contig-bin assignments, and calculate bin quality metrics in real time. BinaRena is an installation-free, client-end web application. Here is a [live demo](https://qiyunlab.github.io/binarena/demo.html).
  - title: HGTector2
    image_path: assets/images/software/hgtector2.png
    image_caption: "[Zhu et al., _BMC Genomics_, 2014](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-15-717); new manuscript in prep."
    url: https://github.com/qiyunlab/HGTector
    btn_label: "Learn More"
    btn_class: "btn--info"
    excerpt: >
        HGTector is a pipeline for genome-wide detection of putative horizontal gene transfer (HGT) events based on sequence homology search hit distribution statistics. HGTector2 is a completely re-engineered software tool, featuring a fully automated analytical pipeline with smart determination of parameters which requires minimum human involvement, a re-designed command-line interface which facilitates standardized scientific computing, and a high-quality Python 3 codebase.
contrib:
  - title: QIIME 2
    url: https://qiime2.org/
    image_path: assets/images/software/qiime2.png
    excerpt: >
        QIIME 2 is an integrated software package for microbiome data analysis. It provides a complete and flexible solution from raw sequencing data to publication-grade tables and figures. It highlights transparent and reproducible science. It has been the most widely-used bioinformatics tool in the field of microbiomics. <br/><br/>
        [Estaki et al., _Curr Protoc Bioinformatics_, 2020](https://currentprotocols.onlinelibrary.wiley.com/doi/full/10.1002/cpbi.100) <br/>
        [Bolyen et al., _Nat Biotechnol_. 2019.](https://www.nature.com/articles/s41587-019-0209-9)
  - title: Qiita
    url: https://qiita.ucsd.edu/
    image_path: assets/images/software/qiita.png
    excerpt: >
        Qiita is a web server for managing microbiome studies, datasets and analyses. It implements a wide range of state-of-the-art programs and databases for the analysis of amplicon, metagenomic and metabolomic data. It enables meta-analysis of an extremely large volume of datasets across many studies. <br />
        [Gonzalez et al., _Nat Methods_, 2018](https://www.nature.com/articles/s41592-018-0141-9)
  - title: scikit-bio
    url: http://scikit-bio.org/
    image_path: assets/images/software/skbio.png
    excerpt: >
        scikit-bio is an open-source Python package for bioinformatics researchers and developers. It provides algorithms and data structures for sequence alignments, phylogenetic trees, distance matrices, ordinations and diversity metrics. It powers QIIME 2, Qiita and multiple other bioinformatics tools.
---

Check out our software projects at <i class='fab fa-github fa-lg'></i> [GitHub](https://github.com/qiyunlab/).

## Projects we lead

{% include feature_row id="main" type="left" %}

## Projects we contribute to

{% include feature_row id="contrib" %}
