AFE TOOLS
=====================
This is a small but expanding collection of tools that I have developed for use in Autodesk Maya. The tools have been compiled for maya 2016, 2016.5 and 2017. However, the source code is also provided so you can recompile them for whatever version you desire.

Shaders
=====================
In addition to tools, the package also contains some useful shaders that were designed to be used in Autodesk Maya with Solidangle's Arnold renderer. However, since the shaders are developed using [Open Shading Language](https://github.com/imageworks/OpenShadingLanguage/) they should also work in all supporting renderers such as Pixar's Renderman or Blender's Cycles, even though the shaders have not been tested in any renderer other than Arnold.

Installation
=====================
The plugins can be used in maya by loading the .mll files (Located in the <i>Plugins/PLUGINNAME/Compiled</i> folder) from Maya's plugin manager. Most plugins also have an accompanying GUI, which consists of a python script located in the <i>Scripts</i> folder. This folder also contains a few standalone scripts for maya. The GUI and tool scripts can easily be added to the maya shelf or tool bar. Refer to the [Maya User Guide on the Shelf](https://knowledge.autodesk.com/support/maya/learn-explore/caas/CloudHelp/cloudhelp/2016/ENU/Maya/files/GUID-C693E884-F81A-4858-B5D6-3856EB8F394E-htm.html) for more information on adding a script to the shelf.

To utilize the shaders, you must point the Arnold environment variable to the folder where the .osl and .mtl (From the <i>Shaders</i> folder) files are located, i.e. ARNOLD_PLUGIN_PATH=C:\solidangle\mtoadeploy\osl. 

Finally, the .mel files (From the <i>Templates</i> folder) must be placed in the maya scripts folder, i.e. C:\Users\Username\Documents\maya\scripts.

For more information on installing OSL shaders refer to the [Arnold User Guide](https://support.solidangle.com/display/A5AFMUG/OSL+Shaders) aswell as the [Maya User Guide on Template Installation](https://knowledge.autodesk.com/support/maya/learn-explore/caas/CloudHelp/cloudhelp/2016/ENU/Maya/files/GUID-592870D2-92E6-44CC-AE54-2F79EC43076A-htm.html) and the [Maya User Guide on Plugin Installation](https://knowledge.autodesk.com/support/maya/learn-explore/caas/CloudHelp/cloudhelp/2016/ENU/Maya/files/GUID-FA51BD26-86F3-4F41-9486-2C3CF52B9E17-htm.html).
