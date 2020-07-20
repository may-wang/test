<param ve-config
       title="Title of Your Narrative"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Cherry20190331105300.jpg/1024px-Cherry20190331105300.jpg"
       layout="vtl"
       num-maps="x"
       num-specimens="x"
       num-images="x"
       num-primary-sources="x"
       author="Names of Authors">

<param title="Beatrix Farrand" eid="Q437714">
<param title="cherry blossom" eid="Q871991">
<param title="Dumbarton Oaks" eid="Q1264942" aliases="DO">
Entities used throughout the essay.

## Subtitle
Code to add a location with a custom marker on a map for every paragraph in this section.
<param title="Washington, D. C." eid="Q61" fill="#FF0000" marker-symbol="landmark">
Entity referred to only in this ## section (including in ### child sections). Appears only once in each ## and ### section.

Paragraph text-Paste the text for the first paragraph in your narrative here. Below is the code for adding a simple image. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-image
static
title="Tidal basin cherry blossom" url="https://upload.wikimedia.org/wikipedia/commons/2/2a/Tidal_basin_cherry_blossom_closeup.JPG"
       fit="cover"
       region="pct:25,25,50,50"
       attribution="Wikimedia Commons">
This declaration only once within the preceding paragraph. (Can also do directly in-line.) "Cover" fit forces entire space to be taken up entirely by the image. "Contain" tries to  fit entire image, based on shortest edge. Region defines specific area in  x% in, y% in (example above accomplishes middle region)."Static" declaration prevents user from zooming on image within essay. Only clicking will open zoomable IIIF viewer.

Below is the code for adding a map. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="Q17" zoom="5" basemap="Esri_WorldPhysical">

Below is the code for adding a map with premade Geojson overlays. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map prefer-geojson center="Q17" zoom="5" basemap="Esri_WorldPhysical">
<param title="Italy" eid="Q38">
<param title="Iran" eid="Q794">

Below is the code for adding an IIIF annotated image created through Storiiies. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-storiiies id="fc1dn">

The code below is an example of how to add a custom geojson overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="41.651031, -83.541939" zoom="6">
<param ve-map-layer geojson url="geojson/great-lakes-fruit-belt.json" title="Great Lakes Fruit Belt" fill="#FF0000" marker-symbol="landmark" active>

## Subtitle

The code below is an example of how to add a video from Youtube. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-video id="jk0ic0D0MRo" title="Hanami">

Code for adding a Mapwarper overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="38.88,-77.03" zoom="14">
<param ve-map-layer mapwarper title="Cherry festival map" mapwarper-id="37798" active>

Code to add a specimen from Global Plants. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-plant-specimen eid="Q12844029" max="1" reverse="true">

