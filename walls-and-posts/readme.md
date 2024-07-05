# Posts and Walls

## Classic Micromouse



### Walls

The micromouse classic walls are 12mm thick and 50mm high. The surface is described as white but no details are specified for reflectivity or shininess. Typical contest walls are injection moulded from an unspecified plastic (robably styrene) and are reflective to both visible and IR light. For many (most) micromouse sensor designs it is the IR behaviour that is the most critical while also the least easy to observe. The shininess of the surface plays a big part in the response of the sensors. Matt finish walls are not typical in contest mazes and neither are very shiny reflective walls. A reasonable compromise is silk or eggshell finish paint, white melamine laminate or self adhesive semi-gloss finish vinyl sign-making material.

The current walls are made from MDF covered with matt white vinyl. 

The nominal distance between posts is 168mm but walls should be manufactured with a nominal length of 167mm to allow for tolerances and ease of insertion/removal.

#### Vinyl Covering
Matt White Ritrama Ri-Mark vinyl:
https://www.dorotape.co.uk/Category/Ritrama-Ri-Mark-Event-Grade-Vinyl
M300 610mm x 50m roll is £63.50 + VAT = £76.20 (about £1.50 per meter)
(M300 is the colour code)
Face thickness with adhesive is 90um (70um without) That is about 3mil without adhesive

305mm wide is easier to handle. A 50m roll should do 625 walls? It is £0.77p + VAT. So, £38.50 + VAT + shipping  = £61.50 from https://www.thevinylcorporation.co.uk/


The tops of the walls and posts have historically been painted red. This is likely to be mostly for visual contrast. The only requirement is that the top of the wall be reflective to visible and IR light and provide good contrast with the maze floor. White wall and post tops are likely to be acceptable unless a mouse enters that uses a vision system that epects to have a visible light contrast with the wall surface or which expects to be able to extract the colour information to detect the wall tops. Paint is messy to apply so a viable alternative is also self-adhesive vinyl materal. Either a matt red version of the same RitRama material or the more readily available TECKWRAP Permanent Adhesive Vinyl 12" x 10ft, Matte Red.

#### Printed Walls

For those with the relevant tools, it is possible to make walls with both resin and FDM 3D printers. Resin printed walls are likely to be brittle and typical ABS-like resins are not very reflective for IR light. These and FDM printed walls can be vinyl covered to make them more compatible with existing walls.

To print walls with an FDM printer, the fastest option is to adjust the slicer settings to give hree bottom layers, two walls (for 0.8mm nozzles), no top layers ans no infill. This produces a hollow structure that is a little flimsy. It is, however, just the right size to take two layers of 5mm foamboard as a filler proucing a stong, light structure. These setting are to be preferred over printing in vase mode so that you can print as many walls as will fit on the bed. On the Bambu P1S with a 0.24mm layer height, each wall takes about 20 minutes.

#### Alternative structures

Foamboard can be sandwiched either side of a laser (or hand) cut 2mm MDF sheet to make light, easily assembled walls requiring no more than a sharp knife. Like the other types, covering with white vinyl improves compatibility.


### Posts

The current design for classic posts makes use of FDM printing technology. The posts can also be made in one piece with a resin printer. FDM printing works best when the post is split diagonally into two parts along the length. The two half pieces need to be glued together into a single post. PLA and ABS are both suitable filament types.

There are concerns that resin printed parts might not be strong enough to survive the rigours of contest use so there are two options for strengthening. One is to create a hole through the peg and into the post body so that a 2mm diameter nail can be glued in for reinforcement. Alternatively, the post can be replaced with a blind rivet. These can be found with a 6mm x 8mm head and a 3.6mm diameter shaft. A modified post would be substantially stronger.

The STL files for all these parts are in this directory:

 - [new-classic-post.stl](./new-classic-post.stl)
 - [new-classic-wall-half-female.stl](./new-classic-wall-half-female.stl)
 - [new-classic-wall-half-male.stl](./new-classic-wall-half-male.stl)

The resin to be used should be a white ABS-like resin for maximum toughness. The prototypes were printed with a layer height of 100microns and used Elegoo ABS-like 3D printer resin:

https://www.amazon.co.uk/ELEGOO-UV-Curing-Precision-Non-Brittle-Photopolymer/dp/B08PFVSLV3/

We welcome samples printed with other, similar resins for compatibility and strength testing.


The posts are 12mm square cross section and 50mm high. Like the walls, they are white and tradidionally have a red top. The light reflecting properties should ideally match those of the walls but some variation is to be expected. Even if posts differ quite alot in their optical properties, it is unlikely to greatly affect the robots.

Posts are normally located in the maze floor by means of a circular peg or spigot inserted in a suitably sized hole in the floor. Contest mazes around the world vary greatly in the choice of hole size so do not expect posts to fit without checking. In the UK, we now use a nominal peg diameter of 6mm and the hole should be a close sliding fit for that size peg. Normally, this can be achieved with a 6.1mm drill bit.

Note that ordinary twist drills used in soft materials are likely to drill slightly undersize so a 6mm drill bit may produce a hole that is a bit of a tight fit. Machine milling with a 4mm endmill may produce a hole of the correct size. A laser cutter with a 0.1mm kerf may, or may not, need a slight offset to get an appropriate sized hole. If the laser is set to cut exactly 6mm then the resulting hole may be wider by the laser kerf.

### Wall to Post Attachment

Typicaly the posts are slotted on all four sides to accept projecting tabs on the walls so that the walls can be easily slid into place or removed from above. the arrangement needs to positively locate a wall without binding while also being tolerant of slight misalignment of the post holes. Thus, the wall length will be less than the nominal 168mm between posts by an amount that can accomodate post misalignment. For example, if all posts could be guaranteed to me no more than 0.5mm out of place, a suitable maxumum wall length might be 166.5mm to allow 0.5mm either end for the posts and an extra 0.5mm to ensure an easy fit. 

The tab and slot mechanism must allow an easy sliding fit with the slots being as deep as can reasonably be managed and the tabs slightly smaller. If the slots are too deep, the post will be weakened and if they are too wide, there may not be enough material left to survive impact from a wayward robot. 

Current UK walls use a tab that is 2mm wide and 2.5mm deep. The slot in the posts is set at 2.5mm wide and 3mm deep to ensure an easy fit in case the tab material is wider than nominal.

