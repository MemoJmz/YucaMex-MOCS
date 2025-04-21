# YucaMex-MOCS
MOCS: Multiple Object Counting from a Segment (Dataset)

Drive: [MOCS] (https://drive.google.com/drive/folders/1YVGlVsPAl3SQ8JR8c0tZG43__tlkzOqA?usp=sharing)

## Content:
- [segments] (https://github.com/MemoJmz/YucaMex-MOCS/tree/main/segments)

## Description:

This repository includes a link to nine videos that are part of a new database for multiple object counting with a segment. The videos were captured by a drone positioned between 30 and 70 meters above road intersections in several cities in Yucatan, Mexico. The size of each video is equal to 3840x2160 pixels (width x heigth). All of the above videos were stored at a speed of 29.97 frames/second. We list the videos and their duration in the following table:

| **Name** | **Duration (min:seg)** |
|----------|--------------|
| DJI_0027 |     6:49     |
| DJI_0089 |     5:27     |
| DJI_0362 |     5:27     |
| DJI_0597 |     3:10     |
| DJI_0614 |     4:50     |
| DJI_0674 |     9:41     |
| DJI_0861 |     4:16     |
| DJI_0883 |     4:50     |
| DJI_4040 |     5:28     |
  
The set of classes of interest correspond to *car, truck, bus, combi, motorcycle, bike, mototaxi* and *pedestrian*. It is worth mentioning that there are three particular classes: cars correspond to sedan or hatchback type vehicles; mototaxi are vehicles from the Yucatan region; and trucks represent the class with the most varied vehicles, as they include vans with open cabins, with closed cabins or cargo boxes, tortons, and trailers.

### Contents:

**segments**: Folder with 18 text files. Each contains the segment that defines the test with the name of the text file. The segment contained in each file has the following format:

```
v1
x1 y1
x2 y2
```
where $v_1$ is the number of segments in the file, this value is always one; $x_1$, $y_1$ are the coordinates of one end of the segment; and $x_2$, $y_2$ are those of the other end.
