RENCI Dataset
=========================

_Authors: Miltiadis Marios Katsakioris, Ioannis Konstas and Helen Hastie_

Download Link
-------------

**[Download the full release of the ROSMI dataset here (ZIP)](https://drive.google.com/open?id=12dmeL1SIgpt-8RKeR4Rl_RhJ9yJAo73v)**

Description
-----------

The RENCI dataset is a new multimodal synthetically generated corpus of ENC charts and natural language instruction pairs, in the domain of emergency response, whereby the subjects are given a scene in the form of a chart and are tasked to write an instruction to command a conversational assistant to direct a number of robots and autonomous systems to either inspect an area or extinguish a fire. These types of emergency scenarios usually have a central hub for operators to observe and command humans and RAS to perform specific functions aided by 'Command and Control' style interfaces, where the robotic assets are visually observable as an overlay on top of the map.
These chart-based interfaces are thus dynamic in nature, adding an extra layer of complexity that we attempt to capture herein.


Contents
--------

### Files ###

* renci_map.json – all 783 scenarios
* scenario[1,3,4,5,7,9,10].json – 7 json files containing the static meta-data of each unique map.

### renci_map.JSON Data Fields ###

  * "split" - train/val/test identification,
  * "image_filename" -  name of the corresponding image file,
  * "scenario_items" - name of the corresponding map file,
  * "landmarks"  - list of all mentioned landmarks and their corresponding annotations and meta-data,
  * "dynamo_obj" - list of all dynamic objects that make each scenario unique from each other,
  * "gold_coordinates" - Gold Standard Coordinate to be predicted,
  * "sentid" - id of sentence/scenario,
  * "sentence" - sentence of the corresponding scenario
  
  
  

License
-------

Distributed under the [Creative Commons 4.0 Attribution-ShareAlike license
(CC4.0-BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/).


Acknowledgements
----------------

This research received funding by Seebyte, Datalab and MASTS-S. This work was also supported by the EPSRC funded ORCA Hub (EP/R026173/1, 2017-2021).
