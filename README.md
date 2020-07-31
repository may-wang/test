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

<param ve-map time-selector="4000 BCE:2000" basemap="Esri_WorldPhysical" center="15,25" zoom="2" hide-labels>
<param ve-map-layer geojson active url="https://raw.githubusercontent.com/may-wang/test/master/distribution.json" title="Distribution">

Ironically, the origins and history of the watermelon are obscured by its commonness, diversity, and its most iconic component — the tender, watery flesh, which does not survive well in the archaeological record. “Watermelon” today often refers specifically to the “sweet dessert” cultivars of the Citrullus lanatus species, but the Citrullus genus includes at least six other species of watermelons, including the citron (C. amarus) and egusi (C. mucosospermus) watermelons, which at one time either were called or were classified as subspecies of C. lanatus.  Thus the taxonomy of the sweet dessert watermelon is of minimal use for tracing its origins until further genetic analysis is confirmed; instead, literary references and depictions of watermelons stretching back millennia have been used to identify and trace the evolving phenotypes of the modern watermelon.
(Below: why do these have to be defined here? Can they be tagged with a date?)
<param title="Quseir al-Qadim" eid="Q310751" fill="#dcffc7">
<param title="Greece" eid="Q41" fill="#ffd080">

## Template Time-Selector Map

<param ve-map time-selector="7300 BCE:0" basemap="Esri_WorldPhysical" center="25,50" zoom="1" hide-labels>
<param ve-map-layer geojson active url="https://raw.githubusercontent.com/may-wang/visual-essays/master/docs/geojson/cities.json" date-field="inception" title="Cities">

Code to add a location with a custom marker on a map for every paragraph in this section.

Entity referred to only in this ## section (including in ### child sections). Appears only once in each ## and ### section.

## Test Annotated IIIF Image
<param ve-storiiies id="761fh">
Though a variety of watermelons appear throughout world cuisines, Citrullus lanatus alone enjoys no shortage of uses, especially resurging as healthy alternatives and attesting to the ongoing ubiquity of varieties and names. Seeds are roasted with a variety of oils and enjoyed as a snack in North African, Middle Eastern, and Chinese cuisines, and are entering the American healthy food scene. 
![via PicClick](https://www.picclickimg.com/00/s/ODAwWDgwMA==/z/cUIAAOSwax5Yrpqk/$/Snacks-Chinese-Food-Melon-Seeds-Guazi-_57.jpg)

“Watermelon steaks” have also become popular as substitutes for meat,  accomplished by grilling the flesh until the water evaporates, creating a fillet-like consistency.
![via Delish](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/screen-shot-2020-01-13-at-4-09-46-pm-1578949797.png)

Commonly in West Africa, seeds are dried and pressed into ootanga or Kalahari oil, which has also increasingly been promoted as a natural skincare product.[2] The rind has traditionally been boiled and preserved in the American South, and the flesh is blended and cooked to create the traditional Sicilian dessert gelo d’anguria, referencing an early modern name for today’s watermelon.
![via Watermelon.org](https://www.watermelon.org/wp-content/uploads/2019/11/watermelon-rind-pickles.jpg)

Below is the code for adding an IIIF annotated image created through Storiiies. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

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

The code below is an example of how to add a custom geojson overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="26.8206, 30.8025" 
    zoom="4"
    basemap="Esri_WorldPhysical">
<param ve-map-layer geojson 
    url="https://github.com/may-wang/test/blob/master/timemap.json" 
    title="Early distribution of watermelons" 
    fill="#FF0000" >

## Test Poem Block Quote

In Korea at the turn of the twentieth century, for instance, British mine-owners turned to banning watermelons from the camps of their workers in order to prevent outbreaks of cholera. The logic behind this seemed to lay in the “immense quantities” of watermelons consumed by Korean workers, including the “rind” (probably the white pith), again suggesting a continuity between a racialised critique of excess indulgence and the moralizing of disease. The campaign turned out to be successful, whether or not that was down to the lack of watermelons is unclear.[3] Similarly, posters such as that shown here from the USSR in 1921 used watermelons to illustrate how various acts of poor hygiene could lead to cholera, from drinking unboiled water to eating unwashed fruit.

> Who started the cholera?  
I, said the Melon,  
I am the felon,  
From warmth of a torrider  
Country than Florida,  
I carried the cholera.  
We sailed to Marseilles  
With favoring gales,  
And from there we went on  
To visit Toulon.  
Where next do we do?  
Just wait; time will show.  
But it will not be long  
Ere the Germans will find,  
That cholera loves  
A trip on the rind.  
>
      — **The Macon _Telegraph_ (1884) ‘Carried the Cholera’, The Milwaukee Daily Sentinel, Aug. 19, p. 4**
## Subtitle

The code below is an example of how to add a video from Youtube. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-video id="jk0ic0D0MRo" title="Hanami">

Code for adding a Mapwarper overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="38.88,-77.03" zoom="14">
<param ve-map-layer mapwarper title="Cherry festival map" mapwarper-id="37798" active>

Code to add a specimen from Global Plants. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-plant-specimen eid="Q12844029" max="1" reverse="true">
