# Collectathon System
## What You'll need
### For the tracker:
- A Counter Module for keeping track of collected items
- A Relay Module for the universal OnCollect
- A Global Message Module for possible collection message (optional)
### For the collectibles (per collectible):
- Either a button or an another item with similar functionality.
- An object to represent the collectible (if the interactable part is invisible)
- A relay Module for organization purposes (optional)
### For the resetter:
- A Relay To All Module
- A Button
## Construction
### Layout
Place the objects listed above into the condo:
![Overview](images/Collectathon_Overview.png)
You can use a pre-existing Global Message module, since those have zero variables
### The Tracker
The Tracker consists of the counter and relay in the center
![Tracker](images/Collectathon_Tracker.png)