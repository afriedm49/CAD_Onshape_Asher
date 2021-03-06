# CAD-Engineering3

## Table of Contents
* [Table of Contents](#TableOfContents)
* [Skateboard](#Skateboard)
* [Duck](#Duck)

## Skateboard
The Skateboard is designed on Onshape by combining a deck, trucks, wheels, and bearings. It is then assembled all together.

[Link to Onshape Document](https://cvilleschools.onshape.com/documents/43ac334ecc19ff8ab6669fec/w/b0ce2447437d1404e49dbab2/e/44c58274e30f4a2979bdd1af)

### Deck

#### Description
The Deck is designed by a rectangle and circles, and is extruded. Holes are poked in the deck symmetrically for screws; it was then named, assigned the material Hard Maple, and colored blue.

#### Images

<img src="Images/Skate_Deck.png" alt="SkateDeck" width="400" height="200"/>

#### Reflection
* The instructions for the deck taught me to use the hole tool, which can be used to easily cut holes with different settings of diameter on each part of the hole. It simplifies doing a remove extrude, and the hole can be placed overtop a single point.
* I learned the usefulness of the rectangle shape to outline spaces for other features. This was useful in designing where the screw holes would be, so that the corners of the rectangle mark a symmetrical spot for holes to be placed.
* A helpful hotkey for creating a new sketch is Shift+S.

### Trucks

#### Description
The Trucks are made from 3 different parts combined: The baseplate, the hanger, and the bushing. The baseplate is a flat structure with holes and extensions that connects directly to the deck, and lends support to the axle. It has a pin sticking out of it which the bushing and the hanger are connected to. 
The Hanger is the main axle which the wheels go onto.
The Bushing is a polyurethane ring to provide a shock support and bend to the board.
The Truck hanger and baseplate are made of stainless steel.

#### Images
<img src="Images/Skate_Truck.png" alt="SkateTruck" width="400" height="200"/>

#### Reflection
* I learned how to add extrusions from different parts from the original sketch. If trying to create an added extrusion onto another, it is sometimes helpful to extrude from a separate part, and then change the scope so that it adds to the correct part. This can be useful in order to use similar geometry from one part to the next.
* The assembly was difficult, because of weird sketch problems, so I learned the importance of checking each step carefully before continuing, and to make sure everything is constrained before completing the sketch.

### Wheels_and_Bearings

#### Description
The wheels and bearings were both created by first designing a section view sketch, and using a revolve feature to make it circular. The bearing is extruded as a separate part from the wheel.

#### Images
<img src="Images/Skate_Wheel.png" alt="SkateWheel" width="300" height="250"/>

#### Reflection
* This one was pretty simple, because of how easy the revolve tool is to use. Instead of extruding in one direction, the tool helps to make a rotated surface.
* The bearing was created using the geometry of the wheel, and was created as an extrusion (New) from the inside of the wheel. It was simple in that way, because I did not have to create any new sketch.

### Assembly

#### Description
The assembly consisted of using mate connectors to put all the different parts together. Most connections were via fastened mates, besides the one between the axle and the bearings. Combined, 8 bearings were imported, 4 wheels, 2 trucks, 1 deck, 8 small screws, 8 small nuts, as well as 4 other nuts for the wheels and 2 for the king pin of the trucks.

#### Images
<img src="Images/Skate_Assembly.png" alt="SkateAssembly" width="700" height="350"/>

#### Reflection
* At first, it was difficult to figure out the mate connectors again. The revolve connector allows rotation of the wheels like a real board, so it made sense to use it there, and the rest were fastened mates, allowing no movement.
* The k hotkey was helpful to clear the view (it hides all mate connectors).

## Duck

#### Description 
I took 4 different configurations of 6 total blocks and assembled it into a Duck. The design is shown in the images below.

#### Images
<img src="Images/Duck_Assembly.png" alt="DuckAssembly" width="450" height="350"/>

#### Reflection
* The process was simple after figuring out how to snap different pieces together. Remember that the mate connectors sometimes take a while to line up correctly, so it is helpful to zoom in, to get a closer look of where it connects. 
* The design originally uses Yellow and Red, but I created a new color on the list called "Duck_Green", by messing around with the RGB values. This was to make it look more realistic, because the red didn't look like a duck. 
* The center of mass was confusing at first, because I didn't see the purpose for it. It makes sense now, because the center of the object's mass is where the x values balance out on both sides, and the y values balance, for volume. This is helpful in showing where it could handle the most weight.

## Multi-Tool

#### Description
I made a base sketch of a multi-tool to measure cm, inches, angles, and use as a #4-40 wrench. This was extruded, and then formatted as a DXF drawing file. After labeling Cm, Inches, and my name, I laser cut it on acrylic.

#### Images
<img src="Images/Multi-tool.jpg" alt="SkateDeck" width="300" height="350"/> <img src="Images/Multi-tool_Drawing.png" alt="SkateDeck" width="300" height="300"/>

#### Reflection
* Dxf files cannot be opened on window computers without the laser cutting program installed.
* Linear patterns for quickly copying holes were helpful, but it is important that you have a sketch for ONLY the part that you want to pattern. It doesn't work to patter a part of a sketch.
* The easiest way to create a sketch is to draw the basic outline, then add relations, and then add dimensions.
