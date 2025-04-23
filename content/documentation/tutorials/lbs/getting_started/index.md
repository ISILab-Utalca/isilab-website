+++
date = "2025-04-08T11:05:31-04:00"
draft = false
title = "LBS - Getting Started"
tags = [ "Documentation", "Tutorial", "LBS" ]
weight = 15
showtoc = true
tocopen = false
+++

## Usage

To start working, select the ISILab window in **Window>ISILab>LevelBuildingSidekick**, this will open the main window of the tool with which you can start working. Next, we will provide a series of general descriptions that you can follow to manage the tool:

---
## Main Windows

![LBS Main Window](/Unity_1OnOncbeB3.png  "Main Window")

In the main window, you will find a large working area visualized with a tiling of squares, in this area you can place, move, and remove elements to shape your levels. To the right of this, you will find an internal inspector that will allow you to work with the specific values of the elements to be modified, their base behaviors, and the assistants that will help you work with this tool.


In addition to this, we can find in the vertical bar between these two aforementioned elements 3 general buttons, which will allow showing and hiding 3 main panels to organize the work. The first corresponds to a panel to organize the content of the level by layers, the second corresponds to a panel to work by layers the quests that are created on these levels, and the third corresponds to the panel that will allow us to pass these levels to structures directly usable in unity.

### Layers

![Layer Panel](/layer_info_01.png)

The layers that are created are displayed here. For each type of layer you will have different working tools, and the inspector view will change as well.

currently there a 3 types of layer:
- Map generation layer. [See Module-1A](../module_1a_layer/) or [Module-1B](../module_1b_layer/)
- Entities population layer.
- Quest design layer.


### 3D Generation

![3D Size panel](/3DInfo_01.png)

The 3D generator window can be displayed by toggle the `3D` button in the side panel, you can press it again to hide the panel.

#### Features

When generating you can choose to build a single layer (the current selected one) or all the layers in the current project. The generator can be tweak with some configuration option:
    
- **Replace Previous:** Allow replace same name tile.
- **Tile Size:** override the default tile size of the set.
-  **Generate Ceiling:** (*Only in step 1A*) Close the room and use the `Ceiling` bundle.
- **Build Light Probe:** (*Only in step 1A*) Generate light probes inside each room, allow easy dynamic lighting.
- **Bake Lights:** (*Only in step 1A*) Automatically bake light for high quality static lighting.
- **Build Reflections:** (*Only in step 1A*) Generate a `ReflectionProbe` Object in the center of each room.

---
## LBS Inspector Panel

![Side Panel Info](/Step_1A_Info_Side_panel_01.png)

From the bottom-left side panel you can access to a variety of layer specific sections: 

- **Current data:** The information of the selected object in the workspace is displayed.
- **Layer Behavior / Manual Mode:**  You can access the brushes and other options for working manually in the workspace.
- **Assistants / IA:** The assistants belonging to each type of layer can be displayed.
 