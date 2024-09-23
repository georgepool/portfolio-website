---
title: "Effective Geospatial codes in OCaml"
---

Supervised by [Michael Dales](https://mynameismwd.org/), [Patrick Ferris](https://patrick.sirref.org/), and [Anil Madhavapeddy](https://anil.recoil.org/)

Original project idea page [here](https://anil.recoil.org/ideas/effective-geospatial-code/)

### 100 word overview:
Geospatial processing is crucial in fields like environmental science but is tricky due to the scale of the data and the difficulty with using GDAL. My project will automatically scale out this processing via a declarative embedded DSL that can express geospatial tasks such as:

- Deciding if data sets overlap and allowing an intersection / union of these
- Rasterization of vector layers
- Automatic memory management (balancing memory / disk) of large geospatial datasets

While tools like this exist in Imperative languages like Python, this project instead focuses on creating a high-level functional interface in OCaml, providing a declarative way for users to express what they want to do with the data. The main tasks will be to create abstractions for the GDAL library for OCaml, and then creating the high-level functional abstractions for geospatial data processing.
