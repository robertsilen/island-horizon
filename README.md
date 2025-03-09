# island-horizon
**Summary:** Explore archipelagos by plotting surrounding islands on a horizon chart.

**Experimenting:** Create using only Gen AI with prompts without touching code manually. 

## Use case for user
Use to visualize and identify islands easier when e.g. boating in the archipelago or looking at a view from a lookout spot. 

## Features
- Set location coordinates and direction manually or from presets, or update automatically from device as it moves. Set parameters through URL to easily share settings. 
- Fetches island data and lists name in Swedish and Finnish, Wikidata Q-code, distance to island and span in degrees on horizon. 
- Plot islands' span as lines on a horizon, with distance to island visualized by line's distance from horizon.
- Give option for user to show horizon chart in full screen.
- Easily access equivalent spot in Google Maps or OpenStreetMap.
- Cache data for less API requests. 

## Implementation
[island-horizon-js.html](island-horizon-js.html): Proof of concept. Uses javascript, fetches data from openstreetmap API. No cache (yet). Created purely in Cursor by prompting Claude AI. 
