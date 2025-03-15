# TBA4251_Programmering_i_geomatikk
I will use a model-driven approach for 3D roof reconstruction to identify and write 3D models of roofs in Trondheim.

## Input:
    - Segmented roof point clouds
    - Building footprints
## Output: 
    LoD2 building models

I have used two different approaches for this task.
## Method 1:
Found matching roof point clouds and footprint buildings. Combined the building polygon with the z-value, and plottet the 3D results with Matplotlib.

## Method 2:
Extracted plane polygons using planar patch detection. Extruded the roof models to their corresponding footprints to get the 3D building models. Plottet with Open3D.
