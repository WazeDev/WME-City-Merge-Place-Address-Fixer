# WME-City-Merge-Place-Address-Fixer
Fixes the address on places missing an address in WME after a city name merge

This runs automatically when a place is selected. If the street ID is invalid, it then attempts get the address currently shown in the app for the place, and then match the street name against a nearby segment. The address in WME for the place is then populated with the updated street/city names and can then be manually reviewed and saved. 
