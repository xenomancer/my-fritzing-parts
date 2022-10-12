# my-fritzing-parts
My user defined parts for the Fritzing software.

Fritzing parts are defined via a set of xml and svg files that specify the part parameters and the part graphics for use within the Fritzing software. Within the corresponding `..\parts\` folder, these files are respectively located within the `..\parts\user\` and `..\parts\svg\` folders. The `..\parts\svg\` folder mirrors the more general structure of the `..\parts\` folder and the svg files are respectively stored within the associated breadboard, icon, pcb, and schematic folders inside the `..\parts\svg\user\` folder. When exporting parts using the built-in parts editor, as of Fritzing version 0.9.4.64 for MS Windows, the software defaults to storing new user defined parts inside a folder named parts inside a folder named Fritzing inside the active user's Documents folder. This is one of the places that new parts can be stored. Alternatively, provided the Fritzing software still runs as a portable app similar to version 0.9.4.64, the parts folder inside the Fritzing software executable directory, named "*fritzing-parts*" may be used. While it is not possible to specify this location for saving or export, the Fritzing software, as of version 0.9.4.64, does search this location when building the internal parts list. These parts folders are interchangeable in this context. However, only one of the two folders should be used for a given part. A part should reside entirely in one and only one of the two parts folders or incomplete or duplicate parts with undefined behavior may present in the parts tray in the Fritzing software.
