---
title: "Effective Geospatial codes in OCaml"
---

Supervised by [Michael Dales](https://mynameismwd.org/), [Patrick Ferris](https://patrick.sirref.org/), and [Anil Madhavapeddy](https://anil.recoil.org/)

Original project idea page [here](https://anil.recoil.org/ideas/effective-geospatial-code/)

### 100 word overview:
Geospatial processing is crucial in fields like environmental science but is tricky due to the scale of the data. To help make this processing easier, my project is to create a GDAL wrapper in OCaml which will do common geospatial operations such as:

- Deciding if data sets overlap
- Deciding whether you should rasterize vector layers
- Efficient memory management of large geospatial datasets

While tools like this exist in Imperative languages like Python, this project instead focuses on creating a high-level functional interface. The main tasks will be to create abstractions for the GDAL library in OCaml, and then creating the high-level functional abstractions for geospatial data processing.
