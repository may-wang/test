<param ve-config
       title="Watermelon Test Narrative"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Cherry20190331105300.jpg/1024px-Cherry20190331105300.jpg"
       layout="vtl"
       num-maps="x"
       num-specimens="x"
       num-images="x"
       num-primary-sources="x"
       author="Names of Authors">

<param title="Watermelon" eid="Q38645">
<param title="_Citrullus lanatus_" eid="Q17507129">
Entities defined above will be defined throughout the essay.

There are many varieties of watermelon. Some people looked at all seven species that exist in addition to the commonly known _Citrullus lanatus_ variety.
<param ve-image
    title="Watermelon species"
    url="https://scitechdaily.com/images/Watermelon-Diversity.jpg"
    attribution="SciTechDaily"
    fit="contain">
<param ve-image
    url="https://scitechdaily.com/images/Cultivated-Watermelon-Wild-Relatives.jpg"
    title="Watermelon varieties"
    attribution="SciTechDaily"
    fit="contain">
<param ve-map basemap="Esri_WorldPhysical" center="0,50">


## Test Custom Time-Selector Map

<param ve-map time-selector="4000 BCE:2000" basemap="Esri_WorldPhysical" center="25,50" zoom="2" hide-labels>
<param ve-map-layer geojson active url="https://raw.githubusercontent.com/may-wang/test/master/distribution.json" title="Distribution">
<param title="Quseir al-Qadim" eid="Q57477018" fill="#dcffc7">

Ironically, the origins and history of the watermelon are obscured by its commonness, diversity, and its most iconic component — the tender, watery flesh, which does not survive well in the archaeological record. “Watermelon” today often refers specifically to the “sweet dessert” cultivars of the Citrullus lanatus species, but the Citrullus genus includes at least six other species of watermelons, including the citron (C. amarus) and egusi (C. mucosospermus) watermelons, which at one time either were called or were classified as subspecies of C. lanatus.  Thus the taxonomy of the sweet dessert watermelon is of minimal use for tracing its origins until further genetic analysis is confirmed; instead, literary references and depictions of watermelons stretching back millennia have been used to identify and trace the evolving phenotypes of the modern watermelon.

## Template Time-Selector Map

<param ve-map time-selector="7300 BCE:0" basemap="Esri_WorldPhysical" center="25,50" zoom="1" hide-labels>
<param ve-map-layer geojson active url="https://raw.githubusercontent.com/may-wang/visual-essays/master/docs/geojson/cities.json" date-field="inception" title="Cities">

Code to add a location with a custom marker on a map for every paragraph in this section.
<param title="Washington, D. C." eid="Q61" fill="#FF0000" marker-symbol="landmark">
Entity referred to only in this ## section (including in ### child sections). Appears only once in each ## and ### section.

## Test GIF
Insert GIF Test. This watermelon displays a common fear of losing seeds, aka hair.
<param ve-image
title="Watermelon gif"
url="https://media3.giphy.com/media/yeMg2ckHHvrOw/giphy.gif"
fit="contain">

Paragraph text-Paste the text for the first paragraph in your narrative here. Below is the code for adding a simple image. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Frightened watermelon ![Watermelon gif](https://media3.giphy.com/media/yeMg2ckHHvrOw/giphy.gif) Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-image
static
title="Tidal basin cherry blossom" url="https://upload.wikimedia.org/wikipedia/commons/2/2a/Tidal_basin_cherry_blossom_closeup.JPG"
       fit="cover"
       region="pct:25,25,50,50"
       attribution="Wikimedia Commons">
This declaration only once within the preceding paragraph. (Can also do directly in-line.) "Cover" fit forces entire space to be taken up entirely by the image. "Contain" tries to  fit entire image, based on shortest edge. Region defines specific area in  x% in, y% in (example above accomplishes middle region)."Static" declaration prevents user from zooming on image within essay. Only clicking will open zoomable IIIF viewer.
<param ve-map primary center="Q61">
"primary" attribute makes item default view;  i.e. default is map rather than image.

Below is the code for adding a map. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="Q17" zoom="5" basemap="Esri_WorldPhysical">

Below is the code for adding a map with premade Geojson overlays. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map prefer-geojson center="Q17" zoom="5" basemap="Esri_WorldPhysical">
<param title="Italy" eid="Q38">
<param title="Iran" eid="Q794">

Below is the code for adding an IIIF annotated image created through Storiiies. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-storiiies id="fc1dn">

The code below is an example of how to add a custom geojson overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="26.8206, 30.8025" 
    zoom="4"
    basemap="Esri_WorldPhysical">
<param ve-map-layer geojson 
    url="https://github.com/may-wang/test/blob/master/timemap.json" 
    title="Early distribution of watermelons" 
    fill="#FF0000" >

## Subtitle

The code below is an example of how to add a video from Youtube. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-video id="jk0ic0D0MRo" title="Hanami">

Code for adding a Mapwarper overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="38.88,-77.03" zoom="14">
<param ve-map-layer mapwarper title="Cherry festival map" mapwarper-id="37798" active>

Code to add a specimen from Global Plants. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-plant-specimen eid="Q12844029" max="1" reverse="true">

