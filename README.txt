RAAHAT DELHI — SIMPLE MOBILE REDESIGN (V2)

FILES TO UPLOAD TO GITHUB
- index.html: bilingual, high-contrast mobile-first website
- data.json: 1,213 de-duplicated pilot location records

DATA SUMMARY
Original spreadsheet: 1,216 rows. Three exact duplicate rows removed.
- 956 toilet records
- 257 water records (235 drinking_water + 22 water_point)
Total: 1,213 unique records.
The spreadsheet has coordinates and type only; no names, addresses, hours, access, fee, or live condition. Every point is therefore labelled not verified.

OPTIONAL EXTRA DATA
The website has a button to fetch additional community-mapped drinking-water and toilet points from OpenStreetMap via Overpass. This happens only when a visitor taps the button; it may fail due to network/rate limits. OSM points are attributed and labelled unverified. OSM data is ODbL; attribution is included in the site. Review https://www.openstreetmap.org/copyright before redistributing extracts.

GITHUB PAGES DEPLOYMENT (EXISTING REPOSITORY)
1. Open https://github.com/Piyush767827/Raahat
2. Click Add file → Upload files.
3. Drag BOTH index.html and data.json from this folder into the upload area. (Do not upload the ZIP.)
4. If GitHub asks whether to replace index.html, choose replace/overwrite.
5. Scroll down to Commit changes. Keep branch main and click Commit changes.
6. Open Settings → Pages. Confirm Deploy from a branch, branch main, folder /(root). Do not change if already selected.
7. Wait 1–3 minutes, then open https://piyush767827.github.io/Raahat/ on your phone. Refresh the page.
8. Test Hindi/English, Drinking water/Public toilet, then FIND NEAR ME and allow location. Location works only on HTTPS and when browser permission is allowed.

IMPORTANT
- Both files must be in the repository root (same level), not inside a subfolder.
- The website needs internet for map links and optional OpenStreetMap data. The core saved list loads from data.json.
- Test on mobile data as well as Wi-Fi. If an older version appears, refresh or clear that site's cached data.
- The OSM live add-on is community data, not official municipal verification. Do not describe any pin as operational until someone checks it on the ground.
