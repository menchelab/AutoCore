# AutoCore
This folder contains the code and some data for the AutoCore project.

The following scripts can be found here:

1. AutoCore_definition.ipynb - a Jupyter notebook to define the AutoCore from monogenic AIM and AIF gene defects.
2. AutoCore_clustering.ipynb - a Jupyter notebook to define and visualise molecular subclusters within the AutoCore defined with step 1.
3. Minumum_distance.ipynb    - a Jupyter notebook to calculate the minimum distance between the AutoCore and various drugs from the DrugBank resource. Significance is calculated by comparing the results to 1000 random permuations.
4. Average_distance          - a Jupyter notebook to calculate the average distance between gene groups. The example here computes the separation of AIM AIF gene defects on the interactome. Significance is calculated by comparing the results to 1000 random permuations.
5. Pathway_diversity - a Jupyter notebook to calculate the pathway diversity of gene sets on a network. In the example, the interactome and autoimmune and autoinflammatory gene defects are used.
