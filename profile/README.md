## Welcome to the echemdb

Our [echemdb projects](https://www.echemdb.org) aim at creating, interacting and providing machine-readable 2D (or time series) data from experiments, computational results and published figures. These data are stored according to the [FAIR principles](https://www.go-fair.org/fair-principles/) using the [frictionless framework](https://framework.frictionlessdata.io/) and a [metadata standard](https://github.com/echemdb/metadata-schema) to describe the underlying data. To develop our tools we focus on data found in the field of electrochemistry. The base modules can, however, be modified to meet any other kind of time series data.
The echemdb aims at creating open-source projects which are of equal interest for curious scientists, contributors, and developers.

The echemdb consists of:

* The [svgdigitizer](https://echemdb.github.io/svgdigitizer) allows digitizing plots in scientific publications from carefully prepared scalable vector graphics (SVG). The tool supports different kinds of plots and allows reconstructing a time axis based on the scan rate ot extract axis units. Additional modules offer convenience functionality to create frictionless datapackages for specific types of plots, such as [cyclic voltammograms](https://en.wikipedia.org/wiki/Cyclic_voltammetry) found in electrochemistry.
* The [unitpackage module](https://echemdb.github.io/unitpackage/) is a Python interface to create and interact with a collection of frictionless datapackges. Conveniently, this allows direct comparison between similar kinds of published datasets and data acquired in the laboratory.
* The [echemdb website](https://www.echemdb.org) provides an overview on our activities and illustrates how datapackages provided by the community, including plots, and metadata can be [visualized in a web interface](https://www.echemdb.org/cv).
* The [autoag-metadata] allows recording metadata from a template during file creation, for example, upon recording data in the lab or saving any other file in your file system.
* The [RawToFigure website](https://echemdb.github.io/rawtofigure/intro.html) provides a short example on how to use frictionless datapackages for organizing your local scientific data in a meaningful way.

## Suggestions and Contributions

Contributions are always welcome and do not necessarily require programming skills. Please [leave us a message](https://github.com/orgs/echemdb/discussions). We would also be thrilled to hear about your ideas to extend the echemdb projects to other areas. ☺
