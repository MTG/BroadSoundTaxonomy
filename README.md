# The Broad Sound Taxonomy 
This repository contains information about the **Broad Sound Taxonomy**, a simple general-purpose taxonomy for the classification of a broad range of sounds.
This taxonomy organizes sounds into a two-level hierarchical structure comprising 29 classes: 
- 5 broad top-level categories
- 24 semantically finer second-level categories

<img src="images/bst_diagram.png" alt="A diagram with all top-level and second-level categories of the BST." style="width:70%; height:auto;">

A description and examples of each category can be found in the [`taxonomy_description`](bst_description.ods).

## Taxonomy creation 
The taxonomy was developed based on principles and design criteria described in our [upcoming journal paper].

Supplementary material related to the taxonmy design is available in the `taxonomy_creation/` folder. 
Materials include information such as the [`design criteria scores`](taxonomy_creation/taxonomy_design_criteria_scores.ods), the [`tag_mappings`](taxonomy_creation/tag_mappings.csv), and the [`query_mappings`](taxonomy_creation/query_mappings.csv).
To support and refine the taxonomy, we conducted a user experiment. The sound files used in the experiment are hosted on [Zenodo](#). *(Link to be inserted)*

For more details, please refer to the full paper.

## Uses 
The Broad Sound Taxonomy is well-suited for diverse tasks such as organizing and retrieving heterogeneous sound collections. 

One of its main real-world deployments is on [Freesound](https://freesound.org), a large collaborative database of audio clips contributed by users around the world. 
On the Freesound [search page sidebar](https://freesound.org/search/), you can browse or filter sounds by BST categories by clicking a category (second-level categories will appear after you click a top-level category).  

*To be continued.*

## Datsets
- **BSD10k** (Broad Sound Dataset 10k). It contains over 10,000 audio clips sourced from Freesound, each labeled with BST categories. BSD10k serves as a benchmark for heterogeneous sound classification and provides a semantically diverse testbed for evaluating machine learning models.

*To be continued.*

## Citation
If you use this material, please cite our paper (citation coming soon).

## License
[GNU General Public License v3.0](LICENSE)
