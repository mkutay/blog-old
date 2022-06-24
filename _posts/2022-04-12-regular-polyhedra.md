---
title: "An Investigation On Regular Polyhedra"
tags: english mathematics geometry
key: "regularpolyhedra"
# article_header:
#  type: cover
#  image:
#    src: /screenshot.jpg
---

#### Introduction

Before explaining what regular polyhedra are, it is best to explain the five platonic solids. 
Platonic solids are, by definition, 3-dimensional shapes whose faces are all the same size and shape. 
Another definition is that a platonic solid’s sides, edges, and corners are all the same. 
These are _tetrahedron_, _cube_, _octahedron_, _dodecahedron_, and _icosahedron_. 
Extending the definition of the platonic solids gives the definition of a regular polyhedra, in which, sides, edges, and corners are all the same. 
The difference between regular polyhedra and platonic solids is that the platonic solids are a simplification of regular polyhedra. 
There are not only five regular polyhedra, there are several more, but the reason that it is not shown more is that explaining platonic solids to beginners is much easier.

<!--more-->

#### Definitions
A regular polygon is made up of line segments, and each vertex has two edges connected to it. In a regular polygon, it should be possible to move any other edge to any other edge and any other vertex to any other vertex. These qualities are called edge transitivity and vertex transitivity. A regular polyhedron is made up of regular polygons. For instance, a cube is made up of six squares. In addition to the edge and vertex transitivities, regular polyhedrons must have face transitivity. This investigation defines regular polyhedra in 3D Euclidean dimension.

When defining regular polyhedra Schläfli Symbol is used. Schläfli Symbol is used in $$\{p, q, r, ...\}$$ form and a symbol with $$n$$ entries refers to a shape in $$n$$-dimensional space. $$\{p\}$$ refers to a 1-dimensional tiling in which line segments are used and it is a regular polygon with $$p$$ sides. $$\{p, q\}$$ refers to a pattern in which $$q$$ $$\{p\}$$ ‘s meet at each vertex. In simpler terms, $$\{p, q\}$$ is referring to a polyhedra in which $$p$$ is the number of sides each face has and $$q$$ is the number of faces that meet at each vertex. Representations of the platonic solids using Schläfli Symbol are tetrahedron $$\{3, 3\}$$, cube $$\{4, 3\}$$, octahedron $$\{3, 4\}$$, icosahedron $$\{3, 5\}$$, and dodecahedron $$\{5, 3\}$$.

### Regular Polygons

All regular polyhedra is made out of regular polygons. Therefore, it is needed to introduce the types of regular polygons. A finite polygon (or $$n$$-gon) is defined as $$P=[V_1, V_2, .. ., V_n]$$ in a Euclidean space $$E^k$$ as the figure formed by the distinct points (or vertices) $$V_1, .. ., V_n$$ of $$E^k$$, together with the segments (edges) $$[V_i,V_{i+1}]$$ for $$i=1, 2, . .., n-1$$, and $$[V_n,V_1]$$. An infinite polygon is defined as $$P=[.. ., V_{-1}, V_0, V_1, V_2, .. .]$$ which consists of a sequence of distinct points (or vertices) $$V_i$$, and of segments (or edges) $$[V_i, V_{i + 1}]$$, $$i=0, \pm 1, \pm 2, .. ., $$ such that each compact subset of $$E^k$$ meets only finitely many edges. Each edge is said to be incident with each of the two vertices that are its endpoints. If $$P$$ is a polygon, a flag of $$P$$ is a pair consisting of a vertex of $$P$$ and an edge of $$P$$ that is incident with that vertex. Regular polygons are divided into 7 groups.

**Group 1.** _Convex n-gon_. Symbol is $$\{n\}$$, defined for each $$n \geq 3$$. If $$n$$ were $$2$$ it would be a line segment and not a regular polygon.

![Image](/assets/posts/regular-polyhedra/convex-polygons){:.border}
