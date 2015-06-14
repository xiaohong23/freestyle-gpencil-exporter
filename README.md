Freestyle to GPencil 
====================

<p align="center"><img src ="https://rawgit.com/folkertdev/freestyle-gpencil-exporter/master/images/header.png" /></p>

A tool for converting the Freestyle view map (i.e. Freestyle strokes) to Grease Pencil strokes. This may be useful for inspecting how Freestyle lines are generated, or to further manipulate Freestyle strokes with Blender's excellent (and recently improved) GPencil tools. 

Conversion from GPencil to a curve object is possible, but generates an unexpected result. This is because GPencil -> Curve doesn't respect splines (all points are put in one spline), so there are extra curve segments connecting what should be lose stroke segmenst. 