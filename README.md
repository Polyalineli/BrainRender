# BrainRender
Functions for the Allen Institute's Mouse Common Coordinate Framework (CCF) and Mouse Light (Janelia) neurons
reconstructions in Python. Check the [user guide](Docs/UserGuide.md) and the [examples](Examples) notebooks for more information
on how to use BrainRender.

<img src="Docs/Media/streamlines2.png" width="1000">


## Resources
### Allen Mouse Brain Atlas
Anatomical and projection data is downloaded from the  Allen Brain Atlas [reference atlas](http://atlas.brain-map.org)
and [connectivity atlas](http://connectivity.brain-map.org) using the Allen [API](http://help.brain-map.org/display/api/Allen%2BBrain%2BAtlas%2BAPI)
(© 2015 Allen Institute for Brain Science. Allen Brain Atlas API. Available from: [brain-map.org/api/index.html](brain-map.org/api/index.html)) ([1], [2]).

An interactive, in-browser 3D structure viewer, the Allen Brain Explorer, is available [here](http://connectivity.brain-map.org/3d-viewer?v=1). 

### Streamlines
Streamlines refer to the visualization of efferent projection as determined by local injections of an anterogradely transported virus (see [Allen's connectivity atlas](http://connectivity.brain-map.org)).
Streamlines reconstructions are made by [https://neuroinformatics.nl](https://neuroinformatics.nl) using the mouse connectome data from Allen (see [here](https://neuroinformatics.nl/HBP/allen-connectivity-viewer/streamline-downloader.html) for more details).

### Mouselight neurons morphology
Neurons morphological data is from Janelia's [mouse light](https://www.janelia.org/project-team/mouselight) database
(see the [neurons browser](http://ml-neuronbrowser.janelia.org)). [3]

### 3D rendering in python
To create the render BrainRender relies on [vtkplotter](https://vtkplotter.embl.es) [see [github repo](https://github.com/marcomusy/vtkPlotter)].

# Example screenshots. 
## Brain Regions anatomy from the Allen Mouse Brain
<img src="Docs/Media/brainregions.png" width="750">
Location of the Ventral posterior complex of the thalamus within the thalamus.

## Mouse Light neurons morphology rendering
<img src="Docs/Media/morphology.png" width="750">
Motor cortex piramidal neuron reconstruction from Mouse Light.

<img src="Docs/Media/neuronsandstreamlines2.png" width="750">
Motor cortex piramidal neurons reconstruction from Mouse Light alongside streamlines
tractography from the Allen Mouse Connectome data.

## Allen mouse connectome projection data rendering
<img src="Docs/Media/tractography.png" width="750">
Projections to the Zona Incerta, colored by projection area.

<img src="Docs/Media/streamlines.png" width="750">
Efferent projections from the PAG.

<img src="Docs/Media/streamlines2.png" width="750">
Efferent projections from the secondary motor cortex.

## Video
<img src="Docs/Media/brainrender.gif" width="500">



## Referencing Brain Render
If you found BrainRender useful and decided to include a rendering in your talks, posters or article, please acknowledge BrainRender's contribution.


# Similar tools
## In R
`cocoframer` is an R library for interacting with the Allen's Mouse CCF [github repository](https://github.com/AllenInstitute/cocoframer).

`mouselightr` package generates 3D CCF mouse brain plots, along with MouseLight neuron reconstructions [github repository](https://github.com/jefferis/nat.mouselight)

## References
* [1] Lein, E.S. et al. (2007) Genome-wide atlas of gene expression in the adult mouse brain, Nature 445: 168-176. doi:10.1038/nature05453
* [2] Oh, S.W. et al. (2014) A mesoscale connectome of the mouse brain, Nature 508: 207-214. doi:10.1038/nature13186
* [3]  Winnubst, J. et al. (2019) Reconstruction of 1,000 Projection Neurons Reveals New Cell Types and Organization of Long-Range Connectivity in the Mouse Brain, Cell 179: 268-281
<!-- * [4] [Papp et al. 2014](https://www.sciencedirect.com/science/article/pii/S1053811914002419)
* [5] [Kjonigsen et al. 2015](https://www.sciencedirect.com/science/article/pii/S105381191500004X) -->
