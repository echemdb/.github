## Welcome to EchemDB

With EchemDB we anticipate simplifying the process of finding specific 2D data in published figures and storing such data according to the [FAIR principles](https://www.go-fair.org/fair-principles/). In this first phase we focus on [cyclic voltammograms](https://en.wikipedia.org/wiki/Cyclic_voltammetry) recorded for single crystal electrodes in contact with a liquid electrolyte. Overall, EchemDB is an open-source project which is of equal interest for curious scientists, contributors, and developers. 

Our project covers so far the following aspects:
* The [svgdigitizer](https://echemdb.github.io/svgdigitizer) allows digitizing x-y plots found in scientific publications from carefully prepared scalable vector graphics. An electrochemistry module offers convenience functionality, e.g., to reconstruct a time axis based on a given scan rate, extract axes units or reference potentials. With an appropriate set of metadata manually compiled from the scientific publication, the figure data can be made available to the community as an entry in the EchemDB repository.
* The [Echemdb website](https://echemdb.github.io/website) provides an overview of the cyclic voltammograms digitized so far by the community, including plots, and metadata.
<!-- TODO: Change echemdb module link to docu. See #1-->
* The [echemdb module](https://github.com/echemdb/website/) offers a Python interface to create a database from these entries and browse those entries for specific data sets based on input parameters. Conveniently, this allows direct comparison between published datasets and/or data acquired in the laboratory.

## Contribution

We offer different ways to contribute to the project, which do not necessarily require programming skills. Please leave us a message if you are interested in any of the following aspects:
* digtize published data
* create content for the echemdb website, e.g., summarize resources related to cyclic voltammetry, single crystal research, or data evalution.
* enhance existing modules of echemdb and svgdigitizer
* create new modules for the svgdigitizer, supporting specific sets of x-y data 


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
