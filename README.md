# Elite Explorer

The goal of this is to make finding unexplored systems faster and easier with the help of EDSM.

When loading or entering a new system, we do the following
- Collect the surrounding systems in a 20ly radius
- Order them by distance
- Print that list including the currently known bodies in the system
- Any system with no bodies discovered has potential first discoveries
- Any system not in the EDSM list but in the nearby systems target list is also potentially undiscovered.

It seems to be pretty effective at the moment, and improvments to UI and general logic are appreciated.