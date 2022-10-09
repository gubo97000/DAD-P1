# DAD - Project 1
## Quiz Time

### Deployment Link: [Here](https://gubo97000.github.io/DAD-P1/$FLUTTER_BASE_HREF#/)

### Description
The app has the same functionality as requested in the handout. 
All the required functionalities for merits were implemented. 

Providers, Screens and api Services have each a file. Routing is done by go router, riverpod takes care of the counter and futures variable are managed by the future builder. If layouts sometimes look inconsistent (e.g. the counter in the appbar only in the menu) is mostly caused by flutter technical limitations that I didn't have the time to overcome both in a visual and functional way.

### Key Challenges
1. Updating the counters inside a future builder. (Solved by not doing it)
2. Clamping the width of the entire application for bigger screens. While avoiding reloads of the widget etc... 
