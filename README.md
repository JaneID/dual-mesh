dual-mesh
=========

A set of MATLAB routines to construct generalised dual meshes given 2-simplex triangulations embedded in R^3.

DUALMESH is a toolbox of mesh processing routines that allow the construction of "dual" meshes based on underlying simplicial triangulations. Support is provided for various planar and surface triangulation types, including non-Delaunay and non-manifold types. 

DUALMESH makes use of a "generalised" dual-mesh that guarantees that dual cells are "star-shaped" w.r.t. their associated generating vertices, even when mesh quality is very low. The generalised dual-mesh is equivalent to the Voronoi diagram when the input is a "well-centred" Delaunay triangulation. 

Dual-meshes are useful for a variety of numerical methods, and are often used as a basis for unstructured finite-volume formulations. 

See DEMODUAL2, MAKEDUAL2 for additional information.
