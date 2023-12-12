TopicVelo is a novel approach for RNA velocity inference in general systems, including immune response studies. It infers the cells and genes associated with distinct active processes via probabilistic topic modeling, and uses these to estimate process-specific velocity parameters and transition probabilities, which are then integrated into large-scale transition matrices. Parameter accuracy is also improved by efficiently fitting unsmoothed counts to a transcriptional burst model. In biologically varied datasets, this approach outperformed the state-of-the-art method, recovering parameters and transitions that were better experimentally supported or recovered previously only with the aid of metabolic labeling or multiple time points.

For more information please see our preprint https://www.biorxiv.org/content/10.1101/2023.06.13.544828v1.full

![TopicVelo_Overview](/docs/Overview.png)

You can download the package using <code> pip install topicvelo </code>

If there are conflicts, you may wish to use a environment with topicvelo installed. Download the environment.yml file and run 
<br>
<code>conda env create -f environment.yml<code>

We include a tutorial using the scNT-seq data in the tutorial folder
