## Welcome to the echemDB

The echemDB provides machine-readable 2D data from published figures and stores such data according to the [FAIR principles](https://www.go-fair.org/fair-principles/). We currently focus on [cyclic voltammograms](https://en.wikipedia.org/wiki/Cyclic_voltammetry) recorded for single crystal electrodes in contact with liquid electrolytes. The echemDB is an open-source project which is of equal interest for curious scientists, contributors, and developers. 

The echemDB consists of:
* A [public repository](https://github.com/echemdb/website/tree/main/literature) of data recovered from published articles.
* The [svgdigitizer](https://echemdb.github.io/svgdigitizer) which digitizes plots in scientific publications from carefully prepared scalable vector graphics. An electrochemistry module offers convenience functionality, e.g., to reconstruct a time axis based on the scan rate, extract axis units, or reference potentials. A digittized figure can then be included in the public echemDB repository.
* The [echemDB website](https://echemdb.github.io/website) which provides an overview of the data digitized by the community, including plots, and metadata.
* The [echemdb module](https://echemdb.github.io/website/doc/html/) is a Python interface to search the echemDB repository. Conveniently, this allows direct comparison between published datasets and data acquired in the laboratory.

## Contribution

Contributions are always welcome and do not necessarily require programming skills. Please leave us a message if you are interested in contributing to the echemDB ☺

You could get started by [digitizing some published data](https://echemdb.github.io/svgdigitizer/workflow.html) in your area of research or by extending any of the pages of the [echemDB website](https://echemdb.github.io/website/). If your interest is outside of cyclic voltammograms or electrochemistry, we would also be thrilled to hear about your ideas to extend these projects to other areas.
