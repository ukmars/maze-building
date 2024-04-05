# Posts and Walls

## Classic Micromouse

## (Scroll down for background and historical details)

## New Wall and Post Design

The current design proposal for classic walls and posts makes used of resin printing technology. Posts can be made in one piece while splitting the walls into a pair of mating halfs makes it possible to print the walls on the smallest of current resin 3D printers. The two half pieces can be permanently bonded with superglue of a small amount of the ame resin used to make them. the STL files for these parts are in this directory:

 - new-classic-post.stl
 - new-classic-wall-half-female.stl
 - new-classic-wall-half-male.stl

the resin to be used should be a white ABS-like resin for maximum toughness. the prototypes used Elegoo ABS-like 3D printer resin:

https://www.amazon.co.uk/ELEGOO-UV-Curing-Precision-Non-Brittle-Photopolymer/dp/B08PFVSLV3/

We welcome samples printed with other, similar resins for compatibility and strength testing.


### Walls

The micromouse classic walls are 12mm thick and 50mm high. The surface is described as white but no details are specified for reflectivity or shininess. Typical contest walls are injection moulded from an unspecified plastic and are reflective to both visible and IR light. For many (most) micromouse sensor designs it is the IR behaviour that is the most critical while also the least easy to observe. The shininess of the surface plays a big part in the response of the sensors. Matt finish walls are not typical in contest mazes and neither are very shiny reflective walls. A reasonable compromise is silk or eggshell finish paint, white melamine laminate or self adhesive semi-gloss finish vinyle sign-making material.

The tops of the walls and posts have historically been painted red. This is likely to be mostly for visual contrast. The only requirement is that the top of the wall be reflective to visible and IR light and provide good contrast with the maze floor. White wall and post tops are likely to be acceptable unless a mouse enters that uses a vision system that epects to have a visible light contrast with the wall surface or which expects to be able to extract the colour information to detect the wall tops.


### Posts

The posts are 12mm square cross section and 50mm high. Like the walls, they are white and tradidionally have a red top. The light reflecting properties should ideally match those of the walls but some variation is to be expected.

Posts are normally located in the maze floor by means of a circular peg or spigot inserted in a suitably sized hole in the floor. Contest mazes around the world vary greatly in the choice of hole size so do not expect posts to fit without checking. In the UK, we now use a nominal peg diameter of 6mm and the hole should be a close sliding fit for that size peg. Normally, this can be achieved with a 6.1mm drill bit.

Note that ordinary twist drills used in soft materials are likely to drill slightly undersize so a 6mm drill bit may produce a hole that is a bit of a tight fit. Machine milling with a 6mm endmill may produce a hole of the correct size. A laser cutter with a 0.1mm kerf may, or may not, need a slight offset to get an appropriate sized hole. If the laser is set to cut exactly 6mm then the resulting hole may be wider by the laser kerf.

### Wall to Post Attachment

Typicaly the posts are slotted on all four sides to accept projecting tabs on the walls so that the walls can be easily slid into place or removed from above. the arrangement needs to positively locate a wall without binding while also being tolerant of slight misalignment of the post holes. Thus, the wall length will be less than the nominal 168mm between posts by an amount that can accomodate post misalignment. For example, if all posts could be guaranteed to me no more than 0.5mm out of place, a siutable maumum wall length might be 166.5mm to allow 0.5mm either end for the posts and an extra 0.5mm to ensure an easy fit. 

The tab and slot mechanism should allow an easy sliding fit with the slots being as deep as can reasonably be managed and the tabs slightly smaller. If the slots are too deep, the post will be weakened and if they are too wide, there may not be enough material left to survive impact from a wayward robot. Again, the specifics vary from country to country. 

### Historical design

In the UK, the posts have been 3D printed with the dimensions similar to those shown in the drawing below. The slots are a little more than 4mm wide to accomodate wall tabs that are generally 3.2-4.0mm wide. Tabs can be made from inserted strips of material such as Acrylic or MDF sheet some some variation in thickness is to be expected. The depth of the slot should be at least 2.5mm and preferably 3.0mm. If the tab on the wall projects by 2mm, a 2.5mm slot only allows a maximum worst case engagement of 1mm or so.

The greatest security and tolerance might be achived with slots that are narrow and deep while running down only 38mm down from the top of the post. Tabs in the walls need only occupy the middle section of the wall 12mm either side of the centre. That way a wall could be inserted either way up and still seat properly.

***Note that the peg size is shown with a diameter of 5.8mm. This is actually a nominal 6mm but depends how your slicer is set up. the layers may include, exclude or average the external dimensions***
![Classic Maze Post 3D Printed](./old-maze-post-classic-3D-print.png)

