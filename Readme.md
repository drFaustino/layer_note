# Layer Note
## Add contextual annotations to layers and features in a QGIS project

### Utility
Many QGIS users feel the need to leave contextual notes on:
+ Specific layers (e.g. "layer to update with 2025 census data")
+ Specific features (e.g. "verify this cadastral parcel")

Currently workarounds are used such as:
+ Text fields in the layer → impractical
+ Comments in QGIS projects → not tied to specific layers or features
+ External sticky notes → disconnected from the GIS context

### Functionality
1. Add text annotations to:
+ Entire layers
+ Single features (stored by ID)
  
2. Quick view of annotations from a side panel
3. Option to export/import annotations as JSON
4. Announcements can be saved in the QGIS project (in the .qgs file) or in a dedicated directory
5. Automatic notifications when opening a project with active annotations

### Description
It is a widget that appears as a side panel docked, by default, on the right of the main QGIS interface. It can be easily undocked by dragging it with the mouse to another position, and re-docked by double-clicking on the title bar.

Its use is extremely simple: select a layer from the list (if it does not appear, you can refresh it with the appropriate button), insert a text note and save. The process can be repeated for each layer.

The notes are saved directly within the QGIS project as custom metadata, remaining associated with the layer even after the project is closed.
