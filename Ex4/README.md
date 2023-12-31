# Assignment4: File Handling in C++ Part2

## Overview
In this assignment we used file handling to read and process triangle data from a file. The implementation is split between two files: `Reader.cpp` and `Writer.cpp`. For this we used the `getline()` function, utilizing `istringstream` for string parsing, creating `Point3D` objects and populating a vector of `Triangle` objects and to read only `vertex` value from .stl file.

## Implementation Steps

1. **Implemented getline() function in getTriangles() in location `Ex4\Updated Sketchers\src\Reader.cpp`**.
2. **Implemented `if condition` logic to read only vertex value from .stl file in location `Ex4\Updated Sketchers\src\Reader.cpp`.**
3. **Used an istringstream to parse the string in location `Ex4\Updated Sketchers\src\Reader.cpp`**.
4. **Taken all values and pass each (x, y, z) values to the point3D class object in location `Ex4\Updated Sketchers\src\Reader.cpp`**.
5. **Added that object in the Triangle class type vector in location `Ex4\Updated Sketchers\src\Reader.cpp`**.
**Used a for each loop to print out the data from each object in write() function in location `Ex4\Updated Sketchers\src\Writer.cpp`**.

