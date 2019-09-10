# Examples for umap reduction using 3D models of prehistoric animals

The models are taken from the [Smithsonians 3D-scanning efforts](https://3d.si.edu/), where you can explore them in all their glory. I have included the datapoints for a Wolly Mammoth and a Tyrannosaur eating a Triceratops in the two .csv-files. 

The Jupyter-Notebook contains code to produce embeddings, which are continously shifting with changes in the hyperparameters, as can be seen below. I tend to think that such animations should, wherever possible, be produced when umap-plots are published, so that the viewers can judge for themselves which properties remain constant under different parameters, and which are mere artefacts of a specific hyperparameter-setting or random-state.

## Here is an image of the original Mammoth:
![](mammoth_render2.png)

## And here are 2D-embeddings of it with shifting hyperparameters:
![](anim_min_dist_param.gif)

![](anim_nearest_neighbours.gif)

## And this is the T-Rex, and a series of embeddings with different random-states
![](T-rex_render.png)
![](t-rex-random.gif)

