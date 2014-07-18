perform
=======

Perform is a master system for hosting other generative systems, made with TouchDesigner.

## Goals
* shared infrastructure for things like parameter mappings, midi, and post-processing
* mix and combine output from multiple generative systems

## Obstacles
* performance
    * unload or disable unused subsystems
    * switches to bypass individual post-processing steps
* control ui
    * separate shared ui panels from project-specific panels and have areas for hosting the project-specific panels
* midi mappings / sharing controllers between projects
    * the BCR2000 and CodeV2 have basically the same layout and controls, so they could be dynamically allocated to projects as they are loaded
    * maybe use a third controller for global stuff (possibly the ReMOTE ZeRO SL) - USE *ALL* THE CONTROLLERS!! :)
* editing and misc annoyances with working with external tox files
    * have a shared shell component for working with projects on their own
    * use scripting to automatically save nested tox files when saving projects

