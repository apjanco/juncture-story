<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="An Esay on the Essay"
       author="Andy Janco"
       banner="https://iiif-cloud.princeton.edu/iiif/2/5e%2F23%2F0b%2F5e230b2cee4243809b22c96ee443d885%2Fintermediate_file/full/1200,1500/0/default.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q15180"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# In the beginning

Many people stop to consider the obvious, but what about the less contrite? How might the word salad of the mind become an essay, how might an essay become a salad bar? Where would the herbariums of the intellect live witout? Why of the within? 
<param ve-image 
       manifest="https://figgy.princeton.edu/concern/scanned_resources/7e4de14b-7a29-4315-8f70-6209acf21638/manifest?manifest=https://figgy.princeton.edu/concern/scanned_resources/7e4de14b-7a29-4315-8f70-6209acf21638/manifest">

# Basic usage

Here's a buch of crap tha twill break this <hr/ > <element> {"hi': such 'baed json' } this is gonnna breeeak 
## Wikidata

So I'm changing some of the values from [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page). If you lookup an entity, you can paste the id and add it to params.  Now Soviet Union, shoould have a popup. Right? [^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://static.parade.com/wp-content/uploads/2019/11/salad-bar-FTR.jpg">

## Map

This is an island with a NASA base on it.  They were talking about in on start date on the radio.  Sounds like a cool place with a nice view of the stars. 
<param ve-map center="Q46197" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Soviet Union](https://en.wikipedia.org/wiki/Soviet_Union)
