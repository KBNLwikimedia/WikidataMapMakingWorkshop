# Map making workshop – from Wikidata to interactive off-Wiki maps in three steps
*Latest update: 21 November 2019*

<image src="images/generic-workshop-opening.jpg" width="500"/><br clear="all"/>

## Workshop description 
In this 90-120 minutes workshop you will learn how to make both flat, clustered, layered, embedded, interactive, on-Wiki and off-Wiki maps from sets of geo-referenced ([P625](https://www.wikidata.org/wiki/Property:P625)) items in Wikidata. 

You will do this in 3 modules of approx. 30-40 minutes each:

* **Module 1**: You will start by making various basic [flat](https://w.wiki/CSx) and [clustered maps](https://w.wiki/CSw) in Wikidata using SPARQL queries. Next you will make some [layered maps](https://bit.ly/3368DPk), where groups of items can be toggled on/off in the map. 
* **Module 2**: After having explored maps in the Wikidata query interface, you are now ready to learn how to embed Wikidata-driven maps in other Wikimedia projects, such as Wikipedia and Commons ([examples](https://nl.wikipedia.org/wiki/Gebruiker:OlafJanssen/KladblokMapMakingWorkshopWM2019)). In addition to SPARQL we will look at [OpenStreetMap](https://www.openstreetmap.org), [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON) and the Mediawiki [Kartographer extension](https://www.mediawiki.org/wiki/Help:Extension:Kartographer).
* **Module 3**: Finally you will learn the steps for creating interactive, layered Wikidata-driven maps that can be used off-Wiki, ie. in regular HTML pages. In addtition to the above tools & techniques, we will use some basic Python, [Jupyter Notebooks (PAWS)](https://www.mediawiki.org/wiki/PAWS), [Jupyter-Leaflet](https://ipyleaflet.readthedocs.io/en/latest/) and [Jupyter-widgets](https://ipywidgets.readthedocs.io/en/latest/).

See the [full outline of the workshop](OutlineAndNotes.md) for a more detailed description. 

## Intended audiences
While this workshop is tech-focused and will discuss basic Wikidata, Wikipedia and Wikimedia Commons techniques and programming tools, it is meant to be approachable by beginning Wikidata contributors and programmers. The [workshop leader](README.md#Workshop-leader-and-contact-details), by no means an advanced Python programmer nor Wikidata nor SPARQL guru himself, is providing examples and code snippets that you can easily adapt yourself with basic SPARQL, Wikidata and Python skills, to make them work for your own datasets.

As the workshop is comprised of three 30-40 minute modules, you can decide to skip the modules that you find too advanced (or basic) for your individual knowledge level.

## Learning objectives
After the workshop you will
* Understand the steps to make basic flat and layered maps in Wikidata, based on geo-referenced (P625) items and SPARQL queries (Module 1, basic) 
* Understand steps to embed maps in Wikimedia sites like Wikipedia, Wikimedia Commons and Wikidata (Module 2, intermediate)
* Understand the steps to create Wikidata-based maps than can be used in other (non-Wiki) websites (Module 3, advanced)
* Have access to map making resources, SPARQL examples and Python code snippets you can build upon for your own projects.

## Required preparations
In order to have an effective workshop, you will need to do some preparations before you start:
* Identify a geo-referenced (P625) set of coherent items in Wikidata to work with. Aim for 100-500 items or so. ([some examples](OutlineAndNotes.md#module-1--basic-flat--layered-maps))
* Create an account on Wikidata/ Wikimedia, if not yet done so.
* For Module 3, set up a working PAWS server and notebook ([Help 1](https://www.mediawiki.org/wiki/Manual:Pywikibot/PAWS), [Help 2](https://wikitech.wikimedia.org/wiki/PAWS), [Help 3](https://www.mediawiki.org/wiki/PAWS)) – only needed if you plan to do this module. Instead of running this notebook cloud-based on PAWS, you can also run it on a local Jupyter Notebooks installation, such as [Anaconda](https://dataiseasy.com/2019/03/how-to-install-anaconda-and-jupyter-notebook/)

## Workshop outline & resources
#### For entire workshop
* [Full outline of the workshop](OutlineAndNotes.md) 
* [Full workshop slides (pdf)](slides/Generic/WikidataMapMakingWorkshop_Generic.pdf)

#### For Module 2
* [Examples of embedded maps on Dutch Wikipedia](https://nl.wikipedia.org/wiki/Gebruiker:OlafJanssen/KladblokMapMakingWorkshopWM2019)

#### For Module 3
* [Jupyter notebook (PAWS)](https://paws-public.wmflabs.org/paws-public/User:OlafJanssen/WikidataMapMakingWorkshop/WikidataMapMakingWorkshop.ipynb) to make layered, interactive off-Wiki maps (and a backup [here on Github](module3stuff/WikidataMapMakingWorkshop.ipynb))
* [Raw json version of this notebook](https://paws-public.wmflabs.org/paws-public/User:OlafJanssen/WikidataMapMakingWorkshop/WikidataMapMakingWorkshop.ipynb?format=raw)
* Off-Wiki version of final map [NetherlandsPublicLibrariesHeatmap.html](http://kbnlwikimedia.github.io/WikidataMapMakingWorkshop/module3stuff/NetherlandsPublicLibrariesHeatmap.html) 

## Workshop leader and contact details
This workshop is given by Olaf Janssen, Wikimedia coordinator of the national library of The Netherlands 
* https://www.kb.nl/wikipedia
* olaf.janssen@kb.nl
* User:OlafJanssen on [(Dutch) Wikipedia](https://nl.wikipedia.org/wiki/Gebruiker:OlafJanssen), [Wikimedia Commons](https://commons.wikimedia.org/wiki/User:OlafJanssen) and [Wikidata](https://www.wikidata.org/wiki/User:OlafJanssen)

## Dates
So far, this workshop was given during
* [Wikimania 2019](https://wikimania.wikimedia.org/wiki/2019:Libraries/Map_making_workshop_%E2%80%93_from_Wikidata_to_interactive_off-wiki_maps_in_three_steps), Stockholm, 18 August 2019. Slides as pdfs here on [Github](slides/Wikimania2019/WikidataMapMakingWorkshop_Wikimania20190818.pdf), and also on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Map_making_workshop_-_from_Wikidata_to_interactive_off-Wiki_maps_in_three_steps_(Wikimania_18-08-2019).pdf) and [Zenodo](https://zenodo.org/records/12569740)
* [WikidataCon 2019](https://www.wikidata.org/w/index.php?title=Wikidata:WikidataCon_2019/Program/Self-organized_sessions&oldid=1037057861#Map_making_workshop_%E2%80%93_from_Wikidata_to_interactive_off-wiki_maps_in_three_steps), Berlin, 26 October 2019. Slides as pdfs here on [Github](slides/WikidataCon2019/WikidataMapMakingWorkshop_WikidataCon20191026.pdf) , and also on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Map_making_workshop_-_from_Wikidata_to_interactive_off-Wiki_maps_in_three_steps_(WikidataCon_25-10-2019).pdf) and [Zenodo](https://zenodo.org/records/13256191)
* [Wiki Techstorm III](https://www.mediawiki.org/wiki/Wiki_Techstorm/Programme/Creating_maps), Amsterdam, 23 November 2019. Slides as pdfs here on [Github](slides/WikiTechstormNov2019/WikidataMapMakingWorkshop_WikiTechstorm20191123.pdf) and also on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Map_making_workshop_-_from_Wikidata_to_interactive_off-Wiki_maps_in_three_steps_(Wiki_Techstorm_23-11-2019).pdf) and [Zenodo](https://zenodo.org/records/13256263).

*Note 21 Nov 2019*: The above pdfs might contain some broken links and/or outdated screenshots due to recent updates of the workshop materials. Always check the [generic workshop pfd](slides/Generic/WikidataMapMakingWorkshop_Generic.pdf) for the most up to date slides .

It will also be given during
* Open workshop in the [national library of The Netherlands](), The Hague, data t.b.d.

## Reusing workshop materials
You are free to reuse all workshop materials, as they are available under the license [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

![CC-BY-SA logo](https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/CC-BY-SA.svg/200px-CC-BY-SA.svg.png)





