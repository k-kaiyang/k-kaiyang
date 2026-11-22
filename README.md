# Hi, I'm Kai Yang

Computer Science student in Interactive Media and Game Development at the Singapore Institute of Technology and DigiPen Institute of Technology Singapore. I mostly work in C++, building engine systems such as state machines, pathfinding and audio.

[Portfolio](https://k-kaiyang.github.io/k-kaiyang/)

[LinkedIn](https://www.linkedin.com/in/koh-ky)

[kohkaiyang@gmail.com](mailto:kohkaiyang@gmail.com)

## Currently working on

**AnytimeReno** (GAM300, ongoing school group project, private repo): an interior design web app with 2D and 3D room editors, drag-and-drop furniture and first-person walkthroughs.

What I've built so far:
- **Floor plan image import:** bring a floor plan image from the web page into the Unity scene, then crop it (including when rotated), rotate, move and scale it
- **Automatic wall detection:** computer vision with OpenCV.js traces the walls in the image, merges duplicate lines and closes door and window gaps only where the image shows a frame, then turns them into editable walls
- **Scale calibration:** click both ends of a known measurement and type its real length, and the plan rescales so every wall comes out in real millimetres
- **Undo and redo:** snapshot-based history of up to 100 steps (Ctrl+Z / Ctrl+Y) for floor plan edits, later extended to furniture

[Click here to take a look at AnytimeReno!](https://team35.dp-ext8.com/)

## Projects

| Project | What it is | My role |
|---|---|---|
| [Umapyoi Engine](https://github.com/Siestasies/GAM200-250_UmapyoiEngine) | C++20/OpenGL 2D engine, editor and elemental action game | Finite state machine system running 40 Lua scripts, A* pathfinding, FMOD audio, enemy AI scripts |
| [Parry Everything](https://github.com/Siestasies/GAM150_PARRY_EVERYTHING) | 2D roguelite built on timing-based parries | Flow-field pathfinding, sound manager, particle system |

### Earlier projects (Nanyang Polytechnic)

| Project | What it is | My role |
|---|---|---|
| Final Year Project (private repo, Dec 2021 – Jan 2022) | Unity game in C# with player accounts and items stored on PlayFab | Login, registration and password reset through PlayFab; PlayFab-backed inventory with item-type filters and consume and delete panels; player movement and camera. 32 of the project's 37 commits |
| Independent Work Project (private repo, May – Aug 2021) | Unity game in C# with cards, platforms, enemies and power-ups | Built it alone: time-based card spawning, toggleable tiles, power-ups, shooting enemies and object pooling |
| [Android game](https://github.com/ri3n/MGP_Assignment) (Nov 2020 – Feb 2021) | Mobile game in Java with its own entity and state system | Trap entity, combo system, high-score storage, a Facebook page screen, and a fix for a crash when resuming from pause |
| [Studio Project 2](https://github.com/sp2team/ourstudioproject) (Feb – Mar 2020) | Team car game in C++ | Car selection, skins and textures, acceleration and camera controls |
| [Studio Project 1](https://github.com/hanyemi09/SP1-Framework) (Aug 2019) | Team game in C++ | Level splash screens, per-level spawn points, map code and main menu sound |

## What's in this repository

This repo holds the source for my [portfolio site](https://k-kaiyang.github.io/k-kaiyang/), served by GitHub Pages. It is plain HTML and CSS with no build step.

| File or folder | What it is |
|---|---|
| `index.html` | Home page: intro, case-study cards, AnytimeReno, About and Contact |
| `umapyoi-state-machine.html` | Case study: the C++ state machine system and enemy AI in Umapyoi Engine |
| `astar-pathfinding.html` | Case study: A* pathfinding with staggered re-paths and a search cap |
| `flow-field.html` | Case study: flow-field pathfinding in Parry Everything |
| `style.css` | Dark theme, with one accent colour per case study |
| `assets/` | Gameplay videos and screenshots used on the pages |
| `KohKaiYang_Resume.docx` | My resume, linked from the site's Download resume button |
| `README.md` | This file, which also appears on my GitHub profile |

To view the site locally, download the repo and open `index.html` in a browser.
