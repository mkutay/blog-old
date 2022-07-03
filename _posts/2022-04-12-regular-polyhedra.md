---
title: "An Investigation On Regular Polyhedra"
tags: english mathematics
key: "regularpolyhedra"
# article_header:
#  type: cover
#  image:
#    src: /screenshot.jpg
---

<style type="text/css">
  .image-left {
    display: block;
    margin-left: auto;
    margin-right: auto;
    float: right;
  }
  .image-center {
    display: block;
    margin-left: auto;
    margin-right: auto;
    float: center;
  }
  .image-right {
    display: block;
    margin-left: auto;
    margin-right: auto;
    float: left;
  }
</style>

### Introduction

Before explaining what regular polyhedra are, it is best to explain the five platonic solids. 
Platonic solids are, by definition, 3-dimensional shapes whose faces are all the same size and shape. 
Another definition is that a platonic solid’s sides, edges, and corners are all the same. 
These are _tetrahedron_, _cube_, _octahedron_, _dodecahedron_, and _icosahedron_. 
Extending the definition of the platonic solids gives the definition of a regular polyhedra, in which, sides, edges, and corners are all the same. 
The difference between regular polyhedra and platonic solids is that the platonic solids are a simplification of regular polyhedra. 
There are not only five regular polyhedra, there are several more, but the reason that it is not shown more is that explaining platonic solids to beginners is much easier.

<!--more-->

### Definitions
A regular polygon is made up of line segments, and each vertex has two edges connected to it. In a regular polygon, it should be possible to move any other edge to any other edge and any other vertex to any other vertex. These qualities are called edge transitivity and vertex transitivity. A regular polyhedron is made up of regular polygons. For instance, a cube is made up of six squares. In addition to the edge and vertex transitivities, regular polyhedrons must have face transitivity. This investigation defines regular polyhedra in 3D Euclidean dimension.

When defining regular polyhedra Schläfli Symbol is used. Schläfli Symbol is used in $$\{p, q, r, ...\}$$ form and a symbol with $$n$$ entries refers to a shape in $$n$$-dimensional space. $$\{p\}$$ refers to a 1-dimensional tiling in which line segments are used and it is a regular polygon with $$p$$ sides. $$\{p, q\}$$ refers to a pattern in which $$q$$ $$\{p\}$$ ‘s meet at each vertex. In simpler terms, $$\{p, q\}$$ is referring to a polyhedra in which $$p$$ is the number of sides each face has and $$q$$ is the number of faces that meet at each vertex. Representations of the platonic solids using Schläfli Symbol are tetrahedron $$\{3, 3\}$$, cube $$\{4, 3\}$$, octahedron $$\{3, 4\}$$, icosahedron $$\{3, 5\}$$, and dodecahedron $$\{5, 3\}$$.

### Regular Polygons

All regular polyhedra is made out of regular polygons. Therefore, it is needed to introduce the types of regular polygons. A finite polygon (or $$n$$-gon) is defined as $$P=[V_1, V_2, .. ., V_n]$$ in a Euclidean space $$E^k$$ as the figure formed by the distinct points (or vertices) $$V_1, .. ., V_n$$ of $$E^k$$, together with the segments (edges) $$[V_i,V_{i+1}]$$ for $$i=1, 2, . .., n-1$$, and $$[V_n,V_1]$$. An infinite polygon is defined as $$P=[.. ., V_{-1}, V_0, V_1, V_2, .. .]$$ which consists of a sequence of distinct points (or vertices) $$V_i$$, and of segments (or edges) $$[V_i, V_{i + 1}]$$, $$i=0, \pm 1, \pm 2, .. ., $$ such that each compact subset of $$E^k$$ meets only finitely many edges. Each edge is said to be incident with each of the two vertices that are its endpoints. If $$P$$ is a polygon, a flag of $$P$$ is a pair consisting of a vertex of $$P$$ and an edge of $$P$$ that is incident with that vertex. Regular polygons are divided into 7 groups.

**Group 1.** _Convex n-gon_. Symbol is $$\{n\}$$, defined for each $$n \geq 3$$. If $$n$$ were $$2$$ it would be a line segment and not a regular polygon.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/convex-polygons.png){:.border}
</div>

**Group 2.** _Star n-gon_ of density $$d$$. Symbol is $$\{n/d\}$$, defined whenever $$1<d<n/2$$ with $$n$$ and $$d$$ being coprime. Density of a star polygon is a generalization of the concept of winding number from two dimensions to higher dimensions. In other words, the density of a polygon can be found by the sum of the turn angles of all the vertices divided by $$360°$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/star-polygons.png){:.border}
</div>

**Group 3.** _Apeirogon_. A single polygon, with symbol $$\{\infty\}$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/apeirogon.png){:.border}
</div>

**Group 4.** _Zigzag_ with angle $$\alpha$$. Symbol is $$\{\infty^\alpha\}$$, defined for each $$\alpha$$ with $$0 < \alpha < 180$$. Note that $$\{\infty\}$$ can be interpreted as $$\{\infty^{180}\}$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/zigzags.png){:.border}
</div>

**Group 5.** _Antiprismatic n-gon_. Symbol is $$\{n^\alpha/d\}$$, where $$n$$ is even, $$1 \leq d < n/2$$, $$n$$ and $$d$$ are coprime, and $$0<\alpha<(n-2d)180/n$$. The vertices of $$\{n^\alpha/d\}$$ may be obtained from thos of $$\{n\}$$ by alternately raising and lowering them perpendicularly to the plane of $$\{n\}$$. When $$\alpha$$ tends to the upper bound, the polygon $$\{n^\alpha/d\}$$ tend to $$\{n/d\}$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/antirprismatic.png){:.border}
</div>

**Group 6.** _Prismatic n-gon_. Symbol is $$\{2 \times k^\alpha/d\}$$, where $$n=2k$$ is even, $$k$$ and $$2d$$ are coprime, $$1 \leq d < k/2$$, and $$0 < \alpha < (k - 2d)180/k$$. (The vertices coincide with those of a right prism based on $$\{k\}$$.)

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/prismatic.png){:.border}
</div>

**Group 7.** _Helical polygon_. Symbol is $$\{\infty^{\alpha, \beta}\}$$, where $$0 < \alpha < 90$$, $$ 0 < \beta < 90$$, $$\alpha + \beta > 90$$. Vertices $$V_j, j = 0, \pm1, \pm2, …$$ lie on the helix given parametrically by ($$a{ }cos{ } \beta t, a { }sin{ } \beta t, bt$$), where $$V_j$$ results for $$t = j$$, and $$\alpha$$ is the angle between successive edges. Note that if $$ab>0$$ we have a right helix, while $$ab<0$$ is a left helix. Hence each $$\{\infty^{\alpha, \beta}\}$$ comes in two enantiomorphic forms, left and right.
<div style="width:40%; margin:0 auto;" align="center" markdown="1">
[![Image](/assets/posts/regular-polyhedra/helical.png)](){:.border}
</div>

### Regular Polyhedra
A polyhedra $$P$$ is any family of polygons (called faces of $$P$$) that has the following properties:

* Each edge can be interchanged with any other edge.

*  The family of polygons is connected; that is, for any two edges $$E$$ and $$E'$$ of $$P$$ there exists a chain $$E = E_0, P_1, E_1, P_2, E_2, .. ., P_n, E_n = E'$$ of edges and faces of $$P$$, where each $$P_i$$ is incident with $$_{i-1}$$ and with $$E_i$$.

*  Each compact set meets only finitely many faces. 

Each of a polyhedron's faces, as well as each edge and vertex of each of its faces, is said to be incident. A flag of a polyhedron $$P$$ is any triple consisting of a vertex, an edge, and a face of $$P$$, all mutually incidents. The polyhedron $$P$$ is said to be regular if its group of symmetries acts transitively on its flags. 

It is convenient to group some of the regular polyhedra possible in $$E^3$$ into 4 basic classes.

**Class 1.** _Platonic polyhedra_ are the 5 finite regular polyhedra in which faces as well as vertex figures are convex polygons. These polyhedrons are the exact same as the platonic solids which are:

$$\{3, 3\}$$ _tetrahedron_;<br>
$$\{3, 4\}$$ _octahedron_;<br>
$$\{4, 3\}$$ _hexahedron_ or _cube_;<br>
$$\{3, 5\}$$ _icosahedron_;<br>
$$\{5, 3\}$$ _dodecahedron_;<br>

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/platonic.png){:.border}
</div>

**Class 2.** _Planar tessellations_, regular tilings or planar apeirohedra are infinite regular polyhedra in which faces as well as vertex figures are convex polygons. These polyhedra are not closed shape polyhedra but they still fit the definition of regular polyhedra. The three regular tilings are;

$$\{4, 4\}$$ _square tiling_;<br>
$$\{3, 6\}$$ _triangular tiling_;<br>
$$\{6, 3\}$$ _hexagonal tiling_.<br>

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/planar-tesellations.png){:.border}
</div>

**Class 3.** _The Kepler-Poinsot polyhedra_ are the finite regular polyhedra in which the faces are convex polygons and the vertex figures are star polygons, or the other way around. These polyhedra are:

$$\{5, 5/2\}$$ _great dodecahedron_;<br>
$$\{3, 5/2\}$$ _great icosahedron_;<br>
$$\{5/2,5\}$$ _small stellated dodecahedron_;<br>
$$\{5/2, 3\}$$ _great stellated dodecahedron_.<br>
Great dodecahedron is the dual of the dodecahedron, great dodecahedron’s dual is small stellated dodecahedron. Great icosahedron is the dual of the icosahedron, great icosahedron’s dual is great stellated dodecahedron.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/kepler-poinsot.png){:.border}
</div>

**Class 4.** _The Petrie-Coxeter polyhedra_, or _regular skew apeirohedron_ are the infinite regular polyhedra with convex polygons as faces, and antiprismatic polygons as vertex figures. Petrie-Coxeter polyhedra are;

$$\{4, 6^{\pi/3}/1\}$$ _mucube_, a helpful way to think about the mucube is to think of it as being made out of cubes that have two opposite faces missing. By arranging six of these almost-cubes in a cube-like form, you get the basic building block of mucube and can be extended infinitely to get the real thing. <br>
$$\{6, 4^{\alpha^*}/1\}$$ (where $$\alpha^* = arcos 2/3 =48 º 12' $$) _muoctahedron_, its cells are not cubes, but rather truncated octahedra. Trancuation is this process that is like cutting off the corners of a polyhedron. When an octahedron is truncated, its eight triangular faces become hexagons, and its six vertices become squares. This shape isn’t regular, because it has two different types of faces, but it can be used to tile 3D space, and by simply removing all of the squares from this tiling, you get another regular polyhedra.<br>
$$\{6, 6^{\alpha^{**}}\}$$ (where $$\alpha^{**} = arcos 5/6 = 33 º 33'$$ ) _mutetrahedron_.<br>

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/petrie-coxeter.png){:.border}
</div>

#### The Petrials

There’s nothing in the definition of regular polygon that restricts polygons to two dimensions. Let's take a zigzag polygon, instead of putting it in the second dimension let's fold it up into the third dimension, and have it meet back on itself. These polygons rather have big implications. These are called _skew polygons_ (_prismatic_ and _antiprismatic_ polygons).

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/skew-polygon.png){:.border}
</div>

What is the result if a polyhedron was made with skew polygons as its faces? Just like zigzags, it’s not necessary for them to have rigid structures to be regular. They can be moved, and deformed while preserving the defining symmetries. What John Petrie found was that any polyhedra made out of normal flat polygon faces can be converted into another polyhedron made out of skew polygon faces. This is called the Petrie dual or Petrial of the polyhedron. For instance, a cube; rotate the cube so that one vertex is facing the screen, and take the silhouette of it. The silhouette looks like a regular hexagon. Then, draw a hexagon along the edges of the cube. Once you rotate it, it becomes a red outline of a regular skew hexagon, and it’s built into the edges of a cube.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/petrial-of-a-cube.png){:.border}
</div>

This shape is called the _cube’s Petrie polygon_. If this process is done for half of the cube’s eight vertices, a shape that looks exactly like a cube is made. However, it is made out of four hexagons instead of six squares. The Schläfli Symbol of the petrial cube is $$\{6^{\pi/2}/1, 3\}$$. By this observation, it can be concluded that 15 of the regular polyhedra which are gone through have their respective petrials.

Another observation that can be made is that the petrial of a petrial is the shape at the start. The property of being a petrial is always mutual: the cube and the petrial cube are in fact petrials of each other. To understand the concept of petrial of something, some of the regular polyhedra’s petrials are given below.

<img align="left" class="image image--lg" src="/assets/posts/regular-polyhedra/petrial-icosahedron.png"/>
<img align="center" class="image image--lg" src="/assets/posts/regular-polyhedra/petrial-hexagonal-tiling.png"/>
<img align="center" class="image image--lg" src="/assets/posts/regular-polyhedra/petrial-great-icosahedron.png"/>

&emsp;**petrial iccosahedron** &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
**petrial hexagonal tiling**&emsp;&emsp;&emsp;&emsp;&emsp;
**petrial great icosahedron**

#### The Blended Apeirohedra

There are 12 regular polyhedra in this family, these regular polyhedra can be made out of six planar apeirohedra: 
square tiling, hexagonal tiling, triangular tiling, petrial square tiling, petrial hexagonal tiling, petrial triangular tiling. 
By using a process called _blending_, each planar apeirohedron can be blended with a _segment_ or with an _apeirogon_. 
To explain how this process is done, let's consider each of the blending types separately.

**Blending with segments**. In basic words, this process is making a planar apeirohedron spiky, by lifting some vertices. 
This is just like how an apeirogon can be turned into a zigzag in 2D and have it still be a regular polygon. 
Making each of these tilings spikier doesn’t stop them from being regular polyhedra. These regular polyhedra also have their petrial. 
Regular polyhedra blended with segments have the following Schläfli Symbols:

$$\{\infty^\alpha, 4\}$$, for $$0<\alpha\leq \pi/2$$ _square tiling blended with a segment_;<br>
$$\{\infty^\alpha, 3\}$$, for $$0<\alpha\leq 2\pi/3$$ _triangular tiling blended with a segment_;<br>
$$\{\infty^\alpha, 6\}$$, for $$0<\alpha\leq \pi/3$$ _hexagonal tiling blended with a segment_.<br>

<img align="left" class="image image--lg" src="/assets/posts/regular-polyhedra/hexagonal-tiling-segment.png"/>
<img align="center" class="image image--lg" src="/assets/posts/regular-polyhedra/square-tiling-segment.png"/>

&emsp;&emsp;&emsp;**hexagonal and square tiling blended with a segment** &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

**Blended with apeirogon**. These regular polyhedra are made out of helical regular polygons. To create the other blended apeirohedra, replace the faces of one of the flat tilings with helices. Once again there are petrials of these regular polyhedra too.

<img align="left" class="image image--lg" src="/assets/posts/regular-polyhedra/hexagonal-tiling-apeirogon.png"/>
<img align="center" class="image image--lg" src="/assets/posts/regular-polyhedra/square-tiling-apeirogon.png"/>

&emsp;&emsp;&emsp;**hexagonal and square tiling blended with a apeirogon** &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

#### The Pure Grünbaum-Dress Polyhedra

In this category there are 6 regular polyhedra, and these are derived from the Petrie-Coxeter polyhedra. Let’s start with the mucube, you can half the mucube. To do this start with a mucube, and then draw a line across the diagonal of each of the square faces, after doing so at each vertex there would be six lines meeting. 

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/halved-mucube.png){:.border}
</div>

<div style="width:70%; margin:0 auto;" align="center" markdown="1">
**halved mucube**
</div>

The Schläfli symbol of it is $$\{6,6\}_4$$. There is no real name for this regular polyhedra. However, halved mucube is a good candidate for the name of it. There is the petrial of this regular polyhedra which can be called petrial halved mucube.

Another regular polyhedra can be derived from the petrial halved mucube. 
This can be done by getting the dual of the petrial halved mucube. 
Name for this regular polyhedra is _skewed petrial muoctahedron_. The Schläfli symbol of this regular polyhedra is $$\{6, 4\}_6$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/skewed-petrial-muoctahedron.png){:.border}
</div>

<div style="width:70%; margin:0 auto;" align="center" markdown="1">
**skewed petrial muoctahedron**
</div>

Using the petrial of petrial mutuality, taking the petrial of a _skewed petrial muoctahedron_ gives a _skewed muoctahedron_. 

Another method to get a _skewed muoctahedron_ is by starting with a _muoctahedron_. 
Each of the hexagonal faces can be turned into a triangle by removing half of the vertices.
By looking at the right angle each triangle is part of an infinite tower of triangles. 
Finally, turning that infinite tower into a helix, the result is a _skewed muoctahedron_. The Schläfli symbol is $$\{\infty, 4, \}_{,*3}$$.

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/skewed-muoctahedron.png){:.border}
</div>

<div style="width:70%; margin:0 auto;" align="center" markdown="1">
**skewed muoctahedron**
</div>

Start with some square helices. Arrange the square helices like the one down below. 

<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/top-down-square-helices.png){:.border}
</div>

<div style="width:70%; margin:0 auto;" align="center" markdown="1">
**Top down and the side view of the square helices**
</div>

Considering the side view again, if they are put in the exact location, they can be seen in this pattern. In which, the squares can be noticed, if helices are built from those squares they’ll be identical to the first one that was built.


<img align="left" class="image image--lg" src="/assets/posts/regular-polyhedra/side-square-helices.png"/>
&emsp;&emsp;
&emsp;&emsp;
&emsp;&emsp;
<img align="center" class="image image--lg" src="/assets/posts/regular-polyhedra/square-helices-built-side.png"/>

**Another side view of the square helices** &emsp;&emsp; **Side view when square helices are built**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

After doing these steps a new regular polyhedra is made. The name of this polyhedra can be considered as the facetted halved mucube (this name can be given as it is possible to derive it from halved mucube) or trihelical square tiling. This regular polyhedra also has its petrial. The symbol for facetted halved mucube is $$\{\infty, 3\}^{(a)}$$.


<div style="width:50%; margin:0 auto;" align="center" markdown="1">
![Image](/assets/posts/regular-polyhedra/facetted-halved-mucube.png){:.border}
</div>

<div style="width:70%; margin:0 auto;" align="center" markdown="1">
**facetted halved mucube**
</div>

### Conclusion

There are 48 regular polyhedra, in which 18 of them are finite. The rest 30 regular polyhedra are infinitely large. Six of the regular apeirohedra are flat tilings. All six flat tilings can be blended with either segments or with apeirogon. 12 regular polyhedra left are mucube, muoctahedron, mutetrahedron, halved mucube, skewed muoctahedron, facetted halved mucube and their petrials. 

In this investigation the definition of regular had some assumptions, for instance, regular polyhedra can’t have two faces, two edges, or two vertices at the same place. Another assumption is that faces of a regular polyhedron must all be connected, or even it was assumed that a regular polyhedra must fit in 3D Euclidean space. It is possible that removing any of these assumptions changes the answer to how many regular polyhedra there are. 

#### References

Coxeter, H. S. M. _Regular Polytopes_, Methuen,1948.

McMullen, P., Schulte, E. _Regular Polytopes in Ordinary Space_. Discrete Comput Geom 17, 449–478 (1997). https://doi.org/10.1007/PL00009304.

Grünbaum, B. _Regular polyhedra—old and new_. Aeq. Math. 16, 1–20 (1977). https://doi.org/10.1007/BF01836414.

Smithers888. _Regular Polyhedra_. cpjsmith, 2020. https://cpjsmith.uk/regularpolyhedra. Date of access: 12.04.2022.

Misali, Jan. _there are 48 regular polyhedra_. YouTube. 2 August 2020. youtu.be/_hjRvZYkAgA. Date of access: 12.04.2022.


