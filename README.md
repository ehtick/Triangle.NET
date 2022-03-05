# Triangle.NET

Triangle.NET generates 2D (constrained) Delaunay triangulations and high-quality meshes of point sets or planar straight line graphs. The code is based on Jonathan Richard Shewchuk's [Triangle](https://www.cs.cmu.edu/~quake/triangle.html) project, see references below.

## Features

* Constrained Delaunay triangulation of planar straight line graphs
* Incremental, sweepline and divide & conquer Delaunay triangulation algorithms
* High-quality triangular meshes with minimum/maximum angle constraints
* Mesh refinement
* Mesh smoothing using centroidal Voronoi tessellation (CVT)
* Node renumbering (Cuthill-McKee)
* Read and write Triangle format files (.node, .poly, .ele)

Until the wiki is setup, please refer to the [Examples](https://github.com/wo80/Triangle.NET/tree/master/src/Triangle.Examples) project to get started.

## License

The original C code published by Jonathan Shewchuk comes with a proprietary license (see [Triangle README](https://github.com/wo80/Triangle/blob/master/src/Triangle/README)) which, unfortunately, isn't very clear about how a derived work like Triangle.NET should be handled. Though Triangle.NET was published on Codeplex (https://triangle.codeplex.com, no longer available) under the MIT license in 2012, I recommend not using this code in a commercial context. Due to the unclear licensing situation, there will also be no Nuget package release.

For further discussion, please refer to the open issue [License Confusion](https://github.com/wo80/Triangle.NET/issues/6).

## References

If you want to learn about the algorithms used in Triangle.NET, I recommend taking a look at the following papers:
* Jonathan Richard Shewchuk, *Triangle: Engineering a 2D Quality Mesh Generator and Delaunay Triangulator* ([free PDF](https://duckduckgo.com/?t=ffsb&q=Triangle+Engineering+a+2D+Quality+Mesh+Generator+and+Delaunay+Triangulator&ia=web))
* Jonathan Richard Shewchuk, *Delaunay Refinement Algorithms for Triangular Mesh Generation* ([free PDF](https://duckduckgo.com/?q=Delaunay+Refinement+Algorithms+for+Triangular+Mesh+Generation&t=ffsb&ia=web))
* Hale Erten & Alper Üngör, *Triangulations with Locally Optimal Steiner Points* ([free PDF](https://duckduckgo.com/?t=ffsb&q=Triangulations+with+Locally+Optimal+Steiner+Points&ia=web))
