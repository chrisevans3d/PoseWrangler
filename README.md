poseWrangler
============

Overview
---------------
PoseWrangler is a simple UI to create and edit pose-driven relationships in Maya using the MayaUE4RBF plugin. This plugin is distributed by Epic Games and installed by Quixel Bridge, initially with MetaHuman source files.

Initially created by Chris Evans, maintained and prettied up throughout MetaHuman development by Judd Simantov.

Opening the tool
---------------
To load the tool, you can call it like so:
```
from poseWrangler import poseWranglerUI as ui
myWindow = ui.showUI()
```
