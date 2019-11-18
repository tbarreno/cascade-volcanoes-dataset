# Cascade volcanoes dataset

A simple dataset for maps plot training.

This dataset contains data about the 82
[Cascade Volcanoes](https://en.wikipedia.org/wiki/List_of_Cascade_volcanoes),
formed as a result of subduction along the
[Cascadia subduction zone](https://en.wikipedia.org/wiki/List_of_Cascade_volcanoes)
in the Pacific Northwest of North America.

It's intended for data science training (for example, as topographic
representation with [Leaflet](https://leafletjs.com/) or a similiar
library).

## The dataset

The data is presented in a *comma-separated values* file with a header row and
UNIX-style newline characters.

The columns present in the dataset are:

Order | Column header | Description
----- | ------------- | -------------
1     | `id` | A sequential row ID
2     | `Country` | USA or Canada
3     | `State` | State (USA) or province (Canada) name
4     | `Name` | Volcano's name
5     | `Type` | Type of volcano or structure
6     | `ElevationMeters` | Elevation (meters)
7     | `ElevationFeets` | Elevation (feets)
8     | `LastEruptionDate` | Last eruption's date or period
9     | `LastEruptionVEI` | Last eruption's explosivity index
10    | `Latitude` | Latitude
11    | `Longitude` | Longitude

