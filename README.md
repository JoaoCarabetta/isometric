# isometric
Easily calculate walking distances catchment area in a city from one or more specific points.


![example](https://github.com/JoaoCarabetta/isometric/blob/master/Screen%20Shot%202018-09-20%20at%2000.45.30.png)

The code is based on two main packages:
- **Osmnx** is a Python package that lets you download spatial geometries and construct, project, visualize, and analyze street networks from OpenStreetMap's APIs. It allows to download and construct walkable, drivable, or bikable urban networks with a single line of Python code.
- **Networkx** is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

The walking distance catchment area is obtained considering OpenStreetMap data for the city analyzed. The code can be runned for any city in the world but final results depends on the quality of data available in OpenStreetMap. The output of the code is a csv file with polygons reperesenting catchment at the one or more walking distances defined from one of more points.

To run the code you have to input the coordinates of points using WGS 84 EPSG: 4326 with the maximum decimal digits possible to increase the accuracy of the result. The output in csv will be generated in WGS 84 / UTM in the respective zone of the city analyzed.

Final output under the name ”polygons.cvs” can be downloaded from yours google drive root.

You can run it [here](https://colab.research.google.com/drive/1xpzFkH7MPwmtFiIfBP2Lg2yqtvzhiF23#scrollTo=0tgOV0U2mN0x). Just add the **points and distances** that the code does the rest.
