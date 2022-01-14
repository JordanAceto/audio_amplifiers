# My various audio amplifier projects are collected here

### Mostly tube guitar amps

---

### The directories for each project roughly follow this structure:

```
├── project_name
│   ├── construction_docs
│   │   ├── project_name_BOM.html
│   │   ├── project_name_schematic.pdf
│   │   └── gerbers
│   │       ├── project_name_gerbers.zip
│   │       └── various gerber files
│   ├── kicad_[/6]_docs
│   │   ├── all KiCad project files needed to open the project in KiCad
│   │   ├── custom_footprints
│   │   │   └── any non-standard footprints used by the project
│   │   └── custom_symbols
│   │       └── any non-standard symbols used by the project
│   ├── pics
│   │   └── images
└── readme.md
```

### The `construction_docs` directory contains everything you need to build the amplifier.
- an interactive HTML BOM
- a pdf copy of the schematic
- gerbers


---

### The `kicad_[/6]_docs` directory contains everything you need to edit the schematic and pcb layout using KiCad.
- KiCad project files
- optional custom symbol libraries
- optional custom footprint libraries

---

### The `pics` directory just contains a few images so you can get an idea of what it looks like.

---

### `Readme` files are sprinkled around liberally
- the project readme files typically indicate whether it is safe to order pcbs or not, and the general state of the project.
- if a project doesn't explicitly say that boards are tested and safe to order, errors are likely.
- additionally, if there are no gerbers in the `construction_docs/gerbers` directory, the project is unlikely to be well tested.

---

### Some amplifier projects were built using entirely point-to-point construction
- these projects have no pcb files, because there is no pcb.
- there may just be a schematic pdf plopped in the root instead of a `construction_docs` directory

---

Some projects have been updated to KiCad 6, but many are still using KiCad 5. If a project is made using KiCad 6, the folder containing the KiCad project will be called `kicad_6_docs`. Projects still using KiCad 5 will have a folder simply called `kicad_docs`. I will probably update projects now and again, but old and well tested projects may not be updated to KiCad 6 anytime soon.

Older projects may not follow the exact directory structure described above, especially regarding custom symbol and footprint libraries. The general idea is pretty consistent across projects though, and there shouldn't be any major surprises.

---