# Periodic Table of Harmony

Twelve-tone harmony visualized

[<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b963a7da-4dc5-4386-b9fe-646347bd9ba5" />
](https://barionleg.github.io/periodic_ttonaton_table_of_harmony)



Check it out here: https://aibolem.github.io/periodic_ttonaton_table_of_harmony/

Table of Contents
=================

* [periodic_ttonaton_table_of_harmony](#periodic-ttonaton-table-of-harmony)
   * [About The periodic_ttonaton_table_of_harmony](#about-the-periodic-ttonaton-table-of-harmony)
   * [About the Website](#about-the-website)
      * [Navigation](#navigation)
      * [Selection](#selection)
      * [Sidebar menu](#sidebar-menu)
      * [Information modal](#information-modal)
      * [Buttons](#buttons)
         * [Show/hide nodes](#showhide-nodes)
         * [Show/hide links](#showhide-links)
         * [Clear Selection](#clear-selection)
         * [Select connected](#select-connected)
         * [Root](#root)
   * [Technicalities](#technicalities)
   * [Other Thoughts](#other-thoughts)
   * [Links](#links)

## About The Periodic Table of Harmony
The Periodic Table of Harmony as a concept is a method of organizing harmony in 2 dimensions where each row contains a set of scale types of equal cardinality (number of intervals). A scale type is defined as a cycle (circular sequence) of intervals. Vertically on the table, each scale type is connected to the row above and/or below it via on or more lines indicating a parent/child relationship. A child scale type consists of all the intervals of a parent, but with any two adjacent intervals from the parent merged (their values summed). Conversely, a parent scale type is formed by inserting an interval, splitting two adjacent intervals since the total number of half steps is held constant.

Due to their periodic nature, each scale type is visually represented as a ring. Each rotation of a ring corresponds to a mode of a scale or inversion of a chord (depending upon your perspective).

*Note: Though I've updated some if it, nomenclature in this project may be inconsistent; I sometimes use the term scale, scale type, harmony set (how I usually describe the data in the dataset), ring (visual representation), or a node (graph terminology) interchangeably.*

## About the Website
The website features an interactive periodic table of harmony. The buttons centered above the bottom of the page provide selection and filtering options to help navigate the graph. The transparent nodes represent cohemitonic scale types (those which contain contiguous half steps).

### Navigation
Click and drag anywhere except on a node to pan around the graph. Scroll to zoom.

### Selection
Click on a node to select/deselect it. Hovering over a node highlights its links. A selected node's links will remain highlighted.

### Sidebar menu
![image](https://user-images.githubusercontent.com/74752740/130615265-f222d749-f30a-488e-b85e-970875aad20a.png)

The sidebar menu can be opened from the icon in the upper left corner. The menu is currently empty. 

I will ask Chat-gpt to link to sidemenu that links with  thumbinalls of that images:

https://github.com/barionleg/chords_synesthesia/wiki 

file: chords_synesthesia.md

<img width="685" height="131" alt="newton_colors" src="https://github.com/user-attachments/assets/c0edc358-5660-4164-ab8d-6093e5c0d883" />

file: dbarcasio.md

<img width="788" height="810" alt="Newton&#39;s_color_circle_colorÅÄd" src="https://github.com/user-attachments/assets/b9bec139-e98a-435f-8a48-294da7560cfe" />


https://github.com/aibolem/ising_2d_model/wiki

file: ising_2d_model.md

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3fec8618-d20d-4b47-8e6f-830322e71f4b" />


https://github.com/aibolem/c-ho-ladn-a-i-ck/wiki

file: c-ho-ladn-a-i-ck.md

<img width="843" height="474" alt="image" src="https://github.com/user-attachments/assets/1839634b-167f-41cc-a5f4-3936fcda5ce3" />


https://en.wikipedia.org/wiki/Piano_key_frequencies

image:  P8iAHO

link: https://github.com/aibolem/dbarcasio/blob/gh-pages/P8iAHO_%26%26.png

<img width="2101" height="5065" alt="P8iAHO_" src="https://github.com/user-attachments/assets/8699e582-d760-42ee-86fa-b86eee30e2df" />



https://github.com/aibolem/dbarcasio/wiki/

file: dbarcasio.md

<img width="922" height="360" alt="image" src="https://github.com/user-attachments/assets/af2e4afb-95cb-42ec-8e43-abb94c23dd40" />


https://github.com/aibolem/Color_Translator_austereich/wiki/

file: Color_Translator_aus_ter_e_ich.md


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/db0afc0e-bbfc-463a-84e3-885e3e09254e" />


https://github.com/barionleg/qpi/wiki

file: qpi.md

<img width="420" height="400" alt="image" src="https://github.com/user-attachments/assets/fb02637b-6366-410a-a791-ad3ae6e1bf85" />


https://github.com/barionleg/ising.js/wiki

file: ising.js.md

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1682e0f3-89ae-4ab5-950d-dba90e6aa33a" />

end of sidemenu.


### Information modal
![image](https://user-images.githubusercontent.com/74752740/130615379-b157bd49-1fa0-4f2b-8261-291ab248feba.png)

The information modal appears upon first landing on the website and can be viewed again at any time by clicking on the info icon (i) in the upper right corner of the graph. The info modal gives a description of the website in hopes that visiters will have an easier time understanding what they're looking at and how to navigate it. 

### Buttons
#### Show/hide nodes
This button is actually the show/hide popup menu. It is used to show/hide a selection, or toggle between showing all nodes and just the ones without contiguous half steps. The latter option can be useful because the most musically useful nodes, at least traditionally speaking, are those which harmonize well, which tends to mean that they don't contain contiguous half steps.

![image](https://user-images.githubusercontent.com/74752740/130614468-b6d1ad78-d51d-4027-b045-3dcfa11e41fe.png)

#### Show/hide links
This is another popup menu used to toggle displaying links. Links can either be shut off entirely, or only shown if they're connected to a selected node. This can be useful to more easily see relationships, as it removes a lot of overlapping or irrelevant links.

#### Clear Selection
The center button is in fact a button which clears a selection. It also dynamically displays the current number of selected nodes.

#### Select connected
The select connected popup menu offers a few options for automatically creating selections of related notes. It can select:
* parents
* children
* immediate family (both parents and children)
* family tree (parents of all parents and children of all children)

It is expected that these selections will be made after selecting a single reference node, but that expectation is not enforced; all selected nodes will respond to this menu.

#### Root
The root menu is used to select the displayed note names in each node. A root note must be paired with a "starting" interval, which is an arbitrary decision. Once a reference interval is chosen, the rest of the notes can be found. 

## Technicalities
The dataset is the complete set of all circular permutations of compositions of 12, which represents all harmony possible in [12-TET](https://en.wikipedia.org/wiki/12_equal_temperament). The graph is an undirected unweighted network diagram of the dataset. The graph is drawn using the [D3 Javascript library](https://github.com/d3/d3). Each graph node is drawn using D3's pie chart tools. There's a to-do list and other files on the development branch.

### Files
The data used to build the graph lives in `data.js`. All the magic happens in `graph.js`. The other files are fairly self-explanatory.

## Other Thoughts
Since I started this project I have changed the way I think about some musical concepts that I used in this project. I used to refer to the data type abstracting each scale type as a "harmony set" (among other things), but I have since arrived at a more nuanced and rigorous definition of things like chords, scales, modes, etc. What I formerly referred to as "harmony sets" I now call "interval cycles" or "scale types." I also don't describe the Periodic Table of Harmony (PToH) as a visualization of all *chords,* since chords requires a root, a voicing, and an expression in time. While the PToH can certainly be used as effectively an index of all scales and chords in [12-TET](https://en.wikipedia.org/wiki/12_equal_temperament), the PToH is more accurately thought of as representing all possible scale types, not chords or chord qualities. I also had made references to "voices" in some documentation on the project. Voices are also features of chords, not scales or scale types, so I've removed those references. 

## Links
The project is hosted on GitHub Pages here: https://aibolem.github.io/periodic_ttonaton_table_of_harmony/

Here are some links I have used or that may be useful for continuing this project:
* https://www.data-to-viz.com/graph/network.html
* https://bl.ocks.org/Andrew-Reid/a73f9af9ccd9ef901a0c33c624096049
* https://stackoverflow.com/questions/39076826/how-to-rotate-any-shape-continuously-in-d3-js
* 

___
___

d'bARNOTATiO²H H²OTÅтØИЯАd'b


### Auth²or (poppulistic Au or Ai Thor of past civilisations). Today we say at we remembaerng ... 

All Classic Music & Architect was eBERNA_вАкеД иииииииииииииииииииииииииии sience 1932, to prepear my mothers (my lovely 'frau Mutter' 🔩) world at her born @1934.

I'm a software engineer specializing in machine learning and interested in DSP/audio programming. I'm also a jazz ₽8iani$t in ₽Å$T lifes (Aii_JAZZ_IRA) and music producer (©°mPoSARC) CliMÆтОЯRµølogisck [Climateorologist at nova days].

Just in тААСС АуdA AbyA SААТ И тСµЛ ☘ 

Thanks to all link wearers, like people do ... or does ... did ... no matter when; It ar memored in my gen

Our scrips are back!

## d'barionleg ♬ Aibolem <> MelodiA 🎶  [Author](https://db-comrubo-c-sa-ch-union-oqtavae.gitbook.io/326-and-beyond) of [extented ₽ TbIiCSÅ](https://aibolem.github.io/TbIICSA_p_beta_Ch/1_326_&_beyond.html) 

*[git wiki About](https://github.com/aibolem/TbIICSA_p_beta_Ch/wiki/326_&&_B%C3%A4yond_of_d'ARTZ_W%C3%84TTER)*

*[u₽p to 400](https://aibolem.github.io/TbIICSA_p_beta_Ch/)*

*[git wiki About](https://github.com/aibolem/TbIICSA_p_beta_Ch/wiki)*
