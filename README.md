# Metabotropic signaling within somatostatin interneurons controls transient thalamocortical inputs during development

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11074523.svg)](https://doi.org/10.5281/zenodo.11074523)


## Authors
 Deepanjali Dwivedi, Dimitri Dumontier, Mia Sherer, Sherry Lin, Andrea MC Mirow, Yanjie Qiu, Qing Xu, Samuel A Liebman, Djeckby Joseph, Sandeep R Datta, Gord Fishell, Gabrielle Pouchelon

## Abstract
During brain development, neural circuits undergo major activity-dependent restructuring. Circuit wiring mainly occurs through synaptic strengthening following the Hebbian “fire together, wire together” precept. However, select connections, essential for circuit development, are transient. They are effectively connected early in development, but strongly diminish during maturation. The mechanisms by which transient connectivity recedes are unknown. To investigate this process, we characterize transient thalamocortical inputs, which depress onto somatostatin inhibitory interneurons during development, by employing optogenetics, chemogenetics, transcriptomics and CRISPR-based strategies. We demonstrate that in contrast to typical activity-dependent mechanisms, transient thalamocortical connectivity onto somatostatin interneurons is non-canonical and involves metabotropic signaling. Specifically, metabotropic-mediated transcription, of guidance molecules in particular, supports the elimination of this connectivity. Remarkably, we found that this developmental process impacts the development of normal exploratory behaviors of adult mice.
# Overview

The repository holds the Jupyter Notebook to run MoSeq related analysis (fig. 6) for the publication: Metabotropic signaling within somatostatin interneurons controls transient thalamocortical inputs during development.

The preprint could be found here: https://www.biorxiv.org/content/10.1101/2023.09.21.558862v2.full
 
The installation and documentation for MoSeq could be found here: https://dattalab.github.io/moseq2-website/index.htm


# Data

All data needed to run this notebook is available on Zenodo: https://doi.org/10.5281/zenodo.11074523

The data includes:
1. **crowd_movies.zip**: a zip file containing the videos of superimposed examples of mice performing the syllables identified by MoSeq.
2. **moseq_df.csv**: a csv file containing the frame-by-frame MoSeq output for all the depth videos. The output includes the syllable labels, the mouse coordinates, velocity, and other kinematic features.
3. **stats_df.csv**: a csv file containing a summarized version of the moseq_df.csv by session and by syllable. The output includes the min, max, median, mean and standard deviation of the kinematic features for each syllable in each session and the syllable usage frequency for each session.
4. **syll_info.yaml**: a yaml file containing the syllable information for each syllable. The labels are generated by a human scorer watching the syllable crowd movies. 

Please save the notebook in the same folder as the data, or change the path in the notebook to the location of the data.


# Troubleshooting

Please submit an issue if you experience problems running the codes, or have any additional questions.
