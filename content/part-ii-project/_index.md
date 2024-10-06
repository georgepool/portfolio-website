---
title: "Effective geospatial code in OCaml"
---

Supervised by [Michael Dales](https://mynameismwd.org/), [Patrick Ferris](https://patrick.sirref.org/), and [Anil Madhavapeddy](https://anil.recoil.org/)

Original project idea page [here](https://anil.recoil.org/ideas/effective-geospatial-code/)

### 100 word overview:
Geospatial processing is crucial in fields like environmental science but is tricky due to the scale of the data and GDAL’s high level of difficulty. My project will automatically scale out this processing via a declarative embedded DSL that can express geospatial tasks like:

- Deciding if data sets overlap and allowing an intersection / union of these
- Rasterization of vector layers
- Automatic resource management of large geospatial datasets

While tools like this exist in imperative languages like Python, this project instead focuses on creating a high-level functional interface in OCaml, which allows users to interact with data declaratively; success will be evaluated on the performance of this compared to GDAL on an existing geospatial task centered around biodiversity metric calculation. The main tasks will be to create abstractions for the GDAL library for OCaml, and then creating the high-level functional abstractions for geospatial data processing. 
