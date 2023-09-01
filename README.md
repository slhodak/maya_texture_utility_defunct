# Purpose
Create a basic texture shader setup faster.

Creates nodes for Base Color/Albedo, Roughness, and Normal, and connects them to an aiStandardSurfaceShader. The roughness map goes through a remapValue node in case you want to scale the values in it for more/less reflectivity. aiImage is used for the normal map solely because aiNormalMap is also used.

# Usage
Basic: Copy this into your MEL editor, select a node graph window, and execute it.
Advanced: Not sure actually. Will get back to you on that.
