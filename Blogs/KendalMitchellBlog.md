---
title: Template Blog
layout: default
---

## Welcome to Kendal Mitchell's Personal Production Journal

### Week 2
Kendal Mitchell, PPJ 1

Tasks Done: 

This week I worked on testing a variety of solutions to 

* Create our 5x5 hex gridboard
* Allow player movement. 

Initially, I was working with Unity's hexagonal grid and tile palette, 
we eventually shifted over to displaying hexagonal models made with ProBuilder to ease our efforts later down the road for procedurally generating maps.
I researched the A* algorithm for pathfinding and assisted in paired programming for our technical demo. Additionally, I also

* Created a main menu for the game

Overall, I spent about 4 hours researching and 2 in development.

Positive:

We were able to nicely divide our team into roles of designers, programmers, and artists. The team was also eager to coordinate and share ideas with one other.

Negative: 

We ran into some issues getting everyone access to files with SourceTree, but found alternatives with GitHub Desktop and GitKraken.

Upcoming:

We'll be further delegating tasks as we go deeper into development.

### Week 3

Kendal Mitchell, PPJ 2

Tasks Done: 

This week I worked with the others creating our HexMap (grid) and tile scripts. 

* Setup a system to generate Hexagonal grids with adjustable rows, columns, and spacing
* Built public interfaces for the HexMap and Tile GameObjects.
* Designers can now input HexType variants through the Unity Editor rather than through scripts.

Our generated HexMaps utilize an "odd-r" horizontal layout. This orientation isn't set in stone at this point but I ended up learning how to adjust it as I learned how to generate it.

Overall, I spent about 6 to 7 hours in development.

Positive:

Core components! Map creation has been automated and we can now track information not only for the Hex Tiles, but the HexMap itself too. Our artists are pumping out enemy designs and it's exciting to see so much progress over a short amount of time.

Negative: 

I was having some trouble line drawing and calculating distances for hexes but with some research found that Bresenham's algorithm may be a potential solution. It is possible that it may be hampered by our use of offsets, but this is still TBD. If necessary, our HexMap will likely need to change from a square offset tile grid to one using axial coordinates. 

Upcoming:

We're hopefully getting to the point now where we can start integrating pathfinding and player/enemy units types. I also had time to start prepping utility functions for pathfinding as well.

### Week 4

### Week 5

### Week 6

### Week 7

### Week 8

### Week 9

### Week 10

[back](Blogs.html)
