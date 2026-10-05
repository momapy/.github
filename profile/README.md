This organization gathers momapy, a Python library for working with molecular maps such as SBGN and CellDesigner maps, and tools built around it.

- [momapy](https://github.com/momapy/momapy): a library and CLI for working with molecular maps, supporting SBGN and CellDesigner maps. It represents a map as a model, which describes what is drawn, and a layout, which describes how it is drawn.
- [momapy-kb](https://github.com/momapy/momapy-kb): a library to integrate SBGN and CellDesigner maps into graph databases (Neo4j, FalkorDB) and logic programs (Clingo/ASP). It relies on momapy for handling maps.
- [pd2af](https://github.com/momapy/pd2af): a library and CLI for transforming process description (PD) maps into activity flow (AF) maps. It accepts CellDesigner and SBGN-PD maps as input. It relies on momapy and momapy-kb for handling maps.
