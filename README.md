# YucaMex-MOCS
MOCS: Multiple Object Counting from a Segment (Dataset)

Drive: [MOCS] (https://drive.google.com/drive/folders/1YVGlVsPAl3SQ8JR8c0tZG43__tlkzOqA?usp=sharing)

**The output videos were added using the stabilization method based on characteristic points**

Drive: (https://drive.google.com/drive/folders/13ohu8HSdDd24X9-019nDpvkCYdQmHURK?usp=drive_link)

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

### Cite this work:

If you use YucaMex-MOCS in your research, please use the following entry:
```
Jiménez-Frías, G.A., Hernandez-Lopez, F.J., Batard, T., Forti-Sosa, S., Pérez-Pech, E. (2025). Automatic Counting System in a Region of Interest from Videos Taken by Drones. In: López-Monroy, A.P., Rosales-Pérez, A., Carrasco-Ochoa, J.A., Martínez-Trinidad, J.F., Olvera-López, J.A. (eds) Pattern Recognition. MCPR 2025. Lecture Notes in Computer Science, vol 15715. Springer, Cham. https://doi.org/10.1007/978-3-031-96255-4_18
```
or BibTeX entry:
```
@InProceedings{10.1007/978-3-031-96255-4_18,
author="Jim{\'e}nez-Fr{\'i}as, Guillermo A.
and Hernandez-Lopez, Francisco J.
and Batard, Thomas
and Forti-Sosa, Silvana
and P{\'e}rez-Pech, Eduardo",
editor="L{\'o}pez-Monroy, Adri{\'a}n Pastor
and Rosales-P{\'e}rez, Alejandro
and Carrasco-Ochoa, Jes{\'u}s Ariel
and Mart{\'i}nez-Trinidad, Jos{\'e} Francisco
and Olvera-L{\'o}pez, Jos{\'e} Arturo",
title="Automatic Counting System in a Region of Interest from Videos Taken by Drones",
booktitle="Pattern Recognition",
year="2025",
publisher="Springer Nature Switzerland",
address="Cham",
pages="191--200",
abstract="Implementing road infrastructure projects to improve connectivity and communication in developing countries begins with traffic flow statistics for better planning. This article presents an automatic counting system in videos taken by drones from a segment of interest and a dataset explicitly designed for this task. The input to the system consists of the video and the segment given by the user; the output is a table with the count of eight classes of relevant objects in the Yucatan area: car, truck, bus, combi, motorcycle, bike, mototaxi and pedestrian. The counting system has sequentially integrated modules that perform the tasks of detection, tracking, and counting, respectively. First, the detection module uses a fine-tuned and trained YOLOv4 model. Then, the tracking module uses the Intersection over Union method. Finally, the counting module selects those that have crossed the segment of interest from the tracked objects for the first time. The system reports a weighted average accuracy of {\$}{\$}80.38{\backslash}{\%}{\$}{\$}80.38{\%}.",
isbn="978-3-031-96255-4"
}
```


