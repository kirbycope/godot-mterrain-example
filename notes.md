# Notes

## Setup
https://github.com/mohsenph69/Godot-MTerrain-plugin/wiki/
1. Create a new Forward+ project in Godot 4.4
1. Select "AssetLib"
1. Search for "M"
1. Select "M Terrain plugin" and then "Download"
1. Select "Project" > "Project Settings..."
1. Select "Plugins"
1. Select the box to enable "Heightmap Terrain"
1. Create a new 3d Scene
1. Rename the scene "Main" and save as `scenes/main.tscn`
1. Select "Add Child Node..." > "MTerrain"
1. In the Inspector for the MTerrain, select the folder icon next to "Data Dir"
1. Create a new folder named `data` and select that folder
	1. Data directory should now be set as "res://data"
    1. Layer directory should now be set as "res://data/layers"

## Textures
https://youtu.be/Af1f2JPvSIs?t=178
</br>https://github.com/Arnklit/TutorialResources/blob/main/Simple%20Terrain/grass.png
1. In the root of the project, create a new folder named `assets`
1. Download the 1K-JPG.zip for:
	- https://ambientcg.com/view?id=Ground037
	- https://ambientcg.com/view?id=Rocks006
	- https://ambientcg.com/view?id=Rocks007
	- https://ambientcg.com/view?id=Rock028
1. Unarchive the zip files in the assets directory
1. Select "3D"
1. Select the HTerrain node from the scene tree

## Models
- [SketchUp Residency Title Stonehenge](https://sketchfab.com/3d-models/sketchup-residency-title-stonehenge-b045d1987a2e44388a9c1431fe6db55e) - SKETCHUP RESIDENCY
