# Computer Graphics (CG) 2023/2024

This repository contains the Computer Graphics coursework for the 2023/2024 academic year. The work is split across a set of mini-projects (tp1–tp5) and a final Project. Each subfolder contains an independent web-based scene/application built using WebGL and the course CGF framework.

## Quick links
- [tp1](tp1/README.md)
- [tp2](tp2/README.md)
- [tp3](tp3/README.md)
- [tp4](tp4/README.md)
- [tp5](tp5/README.md)
- [Project](project/README.md)

## Overview
This workspace demonstrates various fundamental aspects of WebGL and computer graphics using an educational framework (CGF). Each TP (theory/practical task) represents a separate assignment focusing on topics like primitives and transformations, camera control and texturing, and more advanced shading and scene composition.

### Key features
- WebGL scenes with interactive cameras and GUI controls
- Multiple scene files under `tp*` and `project/` directories
- Custom shapes (triangles, quads, cylinders, prisms, etc.) implemented as individual JS classes
- Basic shader examples (vertex/fragment) in `shaders/`
- A final project showing scene composition (eg. garden with bees, hive etc.)

## How to run (Quick Start)
This repository uses plain HTML/JS and a simple local HTTP server is required to serve contents (browsers block local file requests for many assets otherwise).

Option 1 — Python 3 (quick):
```
cd <repo-root>
python -m http.server 8000
# Open http://localhost:8000 (then navigate to any folder like /tp1 or /project)
```

Option 2 — Node (serve):
```
npm install -g serve
serve -s . -l 8000
# Open http://localhost:8000
```

Option 3 — VS Code Live Server extension: Install Live Server and right-click any `index.html` file and choose "Open with Live Server".

Open any folder (eg. `tp1/index.html` or `project/index.html`) to view the examples or the final project.

## Folder structure (high level)
- `lib/` — CGF helper library and shaders
- `project/` — Final Project implementation (garden/bee/hive scene)
- `tp1/` to `tp5/` — Assignments and their own `index.html`, `main.js`, and supporting shapes
- `README.md` — This file

## Notable files and folders
- `lib/CGF.js` — core helper framework for the course
- `lib/dat.gui.module.min.js` — GUI helper
- `lib/CGF/shaders/` — shader examples for shading techniques used in the tasks
- `project/` — final Scene and assets (images, subcomponents)

## Contributing
If you want to make small fixes or improvements (typos, screenshots, documentation), feel free to open a PR. For content updates related to coursework or source files, maintainers should be the original authors.

## Screenshots and Resources
Screenshots for assignments are under each `tp*/screenshots/` and in `project/screenshots/` where available. The `textures/` and `images/` folders contain the project's assets.

## License
Please check `LICENSE` if present. If not present, please contact the authors for permission before reusing code.
