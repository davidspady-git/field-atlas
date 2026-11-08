# Field Atlas

A spinning-globe naming drill — countries, mountain ranges, and lakes. Drag to
rotate, scroll or pinch to zoom, then double-click (double-tap on a phone) what
you're asked for. Misses come back around more often; progress is saved in the
browser.

Two more modes:
- **Pinpoint** -- the globe shows land and sea only, no borders. Drop a pin
  (double-click / double-tap) where the named country is. 100 points on or
  inside it, one point less per 10 miles from its nearest border, 0 past
  1,000 miles; the reveal draws the line from your pin to the nearest edge.
- **Neighbors** -- no map. The named country's real neighbours plus the
  nearest other countries, 20 names in all; tap every one that shares a land
  border, then Check -- the map comes back, turned and zoomed to the country, with
  your hits, misses and wrong picks coloured and named (Show list flips back).
  Score = right picks / (real borders + wrong picks).
  Borders come from the shared edges in the map data, plus Botswana-Zambia
  and Spain-Morocco (Ceuta, Melilla), too short for its resolution.

Single static page. Map data: Natural Earth (public domain). Uses d3 v7 (ISC).
Installable as an app and playable offline.
