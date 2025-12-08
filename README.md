# Ocean Bathymetry: Mapping and Measuring

The code and data for the bathymetry measuring exercise.

Given values:

| Code | Latitude            | Longitude          | Depth (m)        | Depth (m)       |
| ---- | ------------------- | ------------------ | ---------------- | --------------- |
| TR   | 00.005°N - 09.937°N | 8.892°W - 14.874°W | 1800 (northwest) | 130 (southeast) |


Calculated values:

- $h \approx 8\ cm$ (distance between top of box and sea surface)
- $s_\text{ocean} = 104375$ (scale factor to convert depth measurements to real depths)

## Tasks

- [x] 1. Create the scales
    - [x] determine $h$
    - [x] determine $s_\text{ocean}$
    - [x] calculate depth from stick length
- [ ] 2. Determine research vessel navigation plan
    - [ ] compute how long it took (assuming speed of 10 kts)
- [x] 3. Take measurements
- [ ] 4. Draw contour map
    - [x] show measurements on a gridded map
    - [x] draw contours on the map to recreate the terrain in the box
    - [x] include contour labels
    - [x] include units
- [ ] 5. Cost
    - [ ] estimate how much it cost, assuming
    - speed of 10 kts
    - 24h work days
    - the ship costs 30,000€ per day to run
    - neglect way between port and research location