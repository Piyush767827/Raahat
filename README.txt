RAAHAT DELHI — FIRST WEBSITE PROTOTYPE

CONTENTS
- index.html: the complete mobile-friendly website; location data is embedded in the file.

TEST ON YOUR COMPUTER
1. Keep internet connected (Leaflet and map tiles load online).
2. Open index.html in Chrome or Edge.
3. Click All points / Drinking water / Toilets.
4. Click Find nearest to me and allow location access. Browser geolocation usually requires HTTPS or localhost; for reliable testing use the hosted HTTPS website.

PUBLISH FREE WITH GITHUB PAGES
1. Create/sign in to a GitHub account at https://github.com/.
2. Create a new PUBLIC repository named raahat-delhi.
3. Upload index.html from this folder and commit the change.
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for the Pages URL shown in Settings → Pages. Open it on a phone and test location permission.

IMPORTANT DATA NOTE
The source spreadsheet had 1,216 rows. This prototype removes 3 exact duplicate rows, leaving 1,213 records. Records labelled toilets are shown as toilets. drinking_water and water_point are both shown as drinking-water points. If two different source types share coordinates, both records are retained. The spreadsheet has no names, addresses, hours, accessibility, price, or operational-status fields. Therefore all points are clearly marked NOT VERIFIED. Physically verify facilities before promoting them as available.

MAP NOTE
This prototype uses Leaflet and OpenStreetMap tiles. Keep the visible OpenStreetMap attribution. OpenStreetMap's public tile servers are best-effort and have a usage policy; they are suitable for a small pilot, not unlimited high-volume production. Review https://operations.osmfoundation.org/policies/tiles/ before scaling.

NEXT DATA IMPROVEMENT
Add columns for facility name, exact address/landmark, access (public/restricted), hours, water/toilet availability, fee, accessibility, last_verified_date, and verifier_notes.
