# libtmx-parser
Modified for personal use in VS projects.

## Tested Operating Systems
- Windows 10

## Required files
- tmxparser.h/.cpp
- base64.h/cpp
- tinyxml2.h/.cpp

#USAGE
```Cpp
tmxparser::TmxMap map;
tmxparser::TmxReturn error = tmxparser::parseFromFile("example.tmx", &map);
```
