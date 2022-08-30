This website is an accompanying website for the paper titled "Interactive and iterative visual exploration of knowledge graphs based on shareable and reusable visual configurations" which is currently under review.

## Table of contents
- [Project information](#project-info)
- [Demo](#demo)
- [Tutorial](#tutorial)
- [Useful links](#useful-links)

<a id="project-info"></a>
## Project information
Knowledge Graph Browser is a tool for visual exploration of knowledge graphs.

The basic principle of the browser is to enable users to discover different knowledge graphs through different views defined by various browsing configurations.
Real knowledge graphs are often too complex for human users and generic tools for knowledge graph visualisation and visual exploration are therefore quite hard to use.
The basic idea behind the Knowledge Graph Browser is to enable knowledge graph experts to configure a set of simpler views on knowledge graph nodes which can be then used by non-experts for browsing a knowledge graph from given points of view defined by the experts.
Anyone is free to create own configuration, publish it as Linked Open Data and let users to enjoy knowledge graph exploration.

If you are interested in the raw visual configurations demonstrated in the paper, you can browse them using the links below:

- scientists: [file](https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/configurations/config-scientists.ttl) [resource](https://linked.opendata.cz/resource/knowledge-graph-browser/configuration/wikidata/scientists)
- scientists with their works: [file](https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/configurations/config-scientists-works.ttl) [resource](https://linked.opendata.cz/resource/knowledge-graph-browser/configuration/wikidata/scientists-works)
- scientists with their works and groups: [file](https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/configurations/config-scientists-works-groups.ttl) [resource](https://linked.opendata.cz/resource/knowledge-graph-browser/configuration/wikidata/scientists-works-groups)

<a id="demo"></a>
## Demo
You can start exploring knowledge graphs using our [demo](https://try.kgbrowser.opendata.cz).

We also prepared various knowledge graph visualisations so that you can see what's possible to achieve with our tool.
The visualisations are not just images.
They are interactive and you can use them as a starting point for your own exploration.

You can start with famous personalities:

- [European Commissioners from Czechia and Germany](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/czech-and-german-european-commissioners.kgvb)
- [Signatories of Charter 77](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/charter-77-signatories.kgvb)
- [Marie Curie-Skłodowská's family and work](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/curie-family-and-work.kgvb)
- [Chemical elements in the periodic table and their discoverers](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/periodic-table.kgvb)
- [Family tree of Charles I of Austria](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/charles-I-of-austria-family-tree.kgvb)
- [What do Madeleine Albright, Bill Clinton, George W. Bush, Táňa Fischerová, Miloš Zeman, Mick Jagger, Charlie Watts, Keith Richards have in common?](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/common-albright-clinton-bush-fischerova-zeman-jagger-richards-watts.kgvb)

You can also try to explore MEPs (members of parliaments):
- [London and Prague mayors who were or are MEPs in their national parliaments](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/london-prague-mayors-as-meps.kgvb)
- [Aristocratic MEPs of the Czech Parliament](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/aristocratic-members-of-chamber-of-deputies-of-czechia.kgvb)
- [Moviemakers and writters in the Czech Parliament](https://try.kgbrowser.opendata.cz/?load=https://raw.githubusercontent.com/martinnec/knowledge-graph-browser-website/main/examples/moviemakers-and-writers-as-members-of-chamber-of-deputies.kgvb)

<a id="tutorial"></a>
## Tutorial
### Table of contents of the tutorial
- [Creating a new graph](#creating-graph)
- [Basic operations on a graph](#basic-operations-on-graph)
- [Faceted filtering](#faceted-filtering)

<a id="creating-graph"></a>
### Creating a new graph
To start exploring a knowledge graph you first need to select a configuration.
This can be done in various ways as depicted on the following screenshot:  
<br>
![Selecting a meta-configuration](https://github.com/JiriResler/knowledge-graph-browser-website/blob/main/tutorial-screenshots/selecting_a_meta-configuration.png)  
<br>
To select a configuration you can:  
**A)** Choose one of our existing meta-configurations  
**B)** Manually set the configuration using its IRI  
**C)** Open an existing graph which has a configuration already selected  

> **Note**  
> A meta-configuration is a set of specific configurations.

If you opted for **A** then you will also have to select a specific configuration as shown in the following screenshot (it shows how it looks when you choose the *Scientists* meta-configuration):  
<br>
![Selecting a configuration](https://github.com/JiriResler/knowledge-graph-browser-website/blob/main/tutorial-screenshots/selecting_a_configuration.png)  
<br>
After that you will be asked to choose a starting node for your exploration (the following screenshot was taken after choosing the *Scientists* configuration):  
<br>
![Selecting a starting node](https://github.com/JiriResler/knowledge-graph-browser-website/blob/main/tutorial-screenshots/selecting_a_starting_node.png)  
<br>

<a id="basic-operations-on-graph"></a>
### Basic operations on a graph

<a id="faceted-filtering"></a>
### Faceted filtering

<a id="useful-links"></a>
## Useful links
