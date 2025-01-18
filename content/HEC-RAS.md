---
noteID: 4fdd4ee0-6d08-48f2-bdef-5011dceb864a
---
## [HEC-RAS Basics Part 1 of 8: Download and install HEC-RAS with tips and tricks for getting started - YouTube](https://www.youtube.com/watch?v=BUjF_MGcxYQ)

![](https://www.youtube.com/watch?v=BUjF_MGcxYQ)


Create a file folder structure in the beginning of the project as below
1. Aerial Photos
2. Hydrology
3. Land Use
4. Projection
5. Results
6. Terrain
7. Shape File

[Home -- Spatial Reference](https://spatialreference.org/)

Views

Update per Screen

## [HEC-RAS Basics Part 2 of 8: Creating a 1D geometry file in RAS Mapper - YouTube](https://www.youtube.com/watch?v=xzg0V7RTdok)

![](https://youtu.be/xzg0V7RTdok?si=IQV5PU4PW9ZqJAkY)

**Notes on Creating a 1D Geometry File in RAS Mapper**

1. **River Centerline (U/S to D/S):**
    - Draw the river centerline from upstream (U/S) to downstream (D/S) to represent the flow direction.
    - Ensure it follows the thalweg (deepest part of the river channel).

2. **Chainage (D/S to U/S):**
    - Chainage is measured from downstream (D/S) to upstream (U/S).
    - Stations are marked along the centerline for cross-section placement.

3. **Cross-Sections (5 Lines):**
    - Each cross-section should cross:
        - 2 flow paths (left and right),
        - 2 bank lines (left and right),
        - and the river centerline.
    - This ensures accurate representation of the river geometry and flow area.

These points are essential for setting up a 1D geometry file in HEC-RAS.