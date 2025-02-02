# Project Description
Large and ongoing archival project of sorts to zone more or less all available CSGO Skillsurf maps for use with [Surftimer-Official](https://github.com/surftimer/SurfTimer). This is a personal project but I felt it would be worth sharing publically. The ultimate end goal of the project is to have personally touched, and tested, all maps listed and to provide mapper credits wherever possible for archival.

Stripper files are based off of [Kyle3Boi's configs for Demented Gaming](https://github.com/Kyli3Boi/Surftimer-Official-Stripper-Config) and as I learn more about stripper I'll be adding my own configs or any donated.

Provided is a CSV file to compare MD5 hash and filesize against my personal map the zones are based on to confirm they are the same.


## To use:
If using PHPmyadmin or some means of dragging and dropping the two sql files then do that, otherwise add them to your database however you normally would add these.

Files are now availabe 4 ways!
- Safely mergeable files are finally here! **PLEASE** note the differences between versions below. This option will add credits JUST for maps you have in your existing ck_maptier.
	- **Credits Merge (Option 1)** Is intended to support  [Kristián Partl's Web Stats](https://github.com/surftimer/SurfTimer-Web-Stats) which contain a stages and bonus table in ck_maptier.
	- **Credits Merge (Option 2)** Is intended as an upgrade path from the base [SurfTimer release 1.1.2](https://github.com/surftimer/SurfTimer/releases/tag/1.1.2)
- Individual files sorted Alphabetically to pick from.
- Individual files sorted by difficulty Tier to pick from.
- Full wipe files, which DESTRUCTIVELY replace your table with the complete list of maps.

There is an OpenDocument spreadsheet containing just the mapnames, tiers, and mapper credit information, for those looking for that info without needing SQL files/zones.

------------------------------------------------------------------------
## How you can help:

See an incorrect tier? Wrong Maxvelocity? Incorrect mapper credit or one missing altogether? Have you noticed a broken zone while using my tier/zone sql? Let me know!

Workshop maps with no information were tiered based off personal opinion after testing, criticism is always appreciated. If you happen to have a map that works/loads in CSGO that you do not see listed in my zones here, please do a PR or issue report, or contact me on discord @ **Sayt ✿#0621**. 



------------------------------------------------------------------------
Thanks to:

All map creators of course, without which there would be no project to work on. From completed, to abandoned scraps, I think all map projects released should be preserved. All developers and contributers to surftimer and all creators of previous zones and stripper files this collection was built upon.
