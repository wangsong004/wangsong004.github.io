---
title: Boosting SLS 3D Printing with Advanced Nesting Techniques
summary: Nesting is a crucial technique in Powder Bed Fusion technologies like Selective Laser Sintering (SLS) 3D printing.
tags:
  - Nest
date: 2022-01-01
# external_link: http://github.com
---
Nesting is a crucial technique in Powder Bed Fusion technologies like Selective Laser Sintering (SLS) 3D printing, which enables the production of large builds containing hundreds of items.

Efficient nesting maximizes cost-effectiveness by densely packing parts within a single build, reducing material waste and production time. By optimizing the placement of parts on the printing bed, nesting allows for the highest number of parts per printing volume in a single run—enhancing both efficiency and material savings.

## 1.Accelerate the Nesting Process
Providing quick and accurate nesting results is essential for users, who manage large quantities of parts daily. VDA empowers by its GPU acceleration to expedite the nesting process. With a single click, parts are automatically nested in an optimal way and can be distributed across multiple platforms.

## 2.Different Nesting Methods for Different User Scenarios 
### a.Reduce the Height of the Build
Limit the maximum build height to save the build time. When calculating the cost of an SLS 3D printing order, the XYZ dimensions of the part are used to determine the bounding box volume. By reducing the Z-height of the batch, the build time will be saved. This is because 3D printers typically print faster in the X and Y directions than in the Z (height) direction. 

![reduce height](images/reduce_height.png "reduce height")

