# INTERACT CCI Research Methods Bank

An open web platform for sharing child-computer interaction (CCI) research methods developed by the [INTERACT Research Unit](https://interact.oulu.fi) at the University of Oulu, Faculty of Information Technology and Electrical Engineering (ITEE).

## What is this?

The INTERACT CCI Research Methods Bank makes research-backed methods for child-centred technology design freely accessible to teachers, researchers, social workers, and other practitioners. Materials come from multiple INTERACT research projects — starting with the MAD project (2020–2023) and the Takeover project (ongoing).

## Current Status

This repository contains a **UI prototype** built during a summer traineeship (June–August 2026). The prototype demonstrates the full visual design and user interface of the platform across 6 pages — it is not yet connected to a backend database.

| Page | File | Status |
|------|------|--------|
| Home | index.html | ✅ Complete |
| Browse Materials (with filters) | materials.html | ✅ Complete |
| Material Detail (with download modal) | detail.html | ✅ Complete |
| Projects | projects.html | ✅ Complete |
| About | about.html | ✅ Complete |
| Admin panel prototype | admin.html | ✅ Complete |
| Shared stylesheet | style.css | ✅ Complete |

## How to Open the Prototype

No installation needed. Just:

1. Download or clone this repository
2. Open the `interact-cci-bank` folder
3. Double-click `index.html` — it opens in your browser
4. Navigate between all pages using the top navigation bar

## Pages Overview

### Public pages
- **Home** — Introduction, featured method cards, project overview
- **Browse Materials** — Full filter panel (8 filter groups) with real-time filtering and multi-select download
- **Material Detail** — Full method description, metadata sidebar, file download with voluntary tracking form
- **Projects** — MAD and Takeover project cards with stats
- **About** — Simplified about page with contributor list and link to INTERACT website

### Admin panel
- **Login page** — Email and password login (prototype only — no real authentication yet)
- **Dashboard** — Stats, metadata field guide (Required vs Optional), Add New Material form, materials table with Edit/Delete, download records

## Tech Stack (Current Prototype)

| Component | Technology |
|-----------|-----------|
| Frontend | HTML5, CSS3, JavaScript (vanilla) |
| Styling | Single shared stylesheet (style.css) |
| Filtering | Client-side JavaScript (no backend) |
| Hosting | Local file system / GitHub Pages |
| Backend | ❌ Not yet implemented |
| Database | ❌ Not yet implemented |

## What Needs to Be Built Next (Backend)

The next development phase requires a student or developer with the following skills:

- **PHP and MySQL** — for server-side logic and database
- **File upload handling** — so INTERACT researchers can upload PDF, image, and video files
- **User authentication** — restricted admin login for INTERACT researchers only
- **Bolt CMS integration** — potentially using INTERACT's existing Bolt CMS (v5.1.20) at interact.oulu.fi
- **CRUD operations** — Create, Read, Update, Delete for materials in the database
- **Download tracking** — recording user details and file names when materials are downloaded

See the scholarship student description in the project documentation for full details.

## Metadata Structure

Each material has 19 metadata fields — 12 Required and 7 Optional:

**Required:** Material title, Source project, Process, Phase number, Phase name, Target user group, Time required, Material type, Language, Description, Contributor/Author, File upload

**Optional:** Age group, Topic/Theme, Difficulty for children, Classroom setting, Related publications (DOI), Photo/image, Step-by-step instructions

## Project Background

- **Trainee:** Ritu Basak (MSc student, Software Engineering and Information Systems, University of Oulu)
- **Supervisors:** Prof. Tonja Molin-Juustila and Prof. Netta Iivari (INTERACT Research Unit)
- **Period:** June–August 2026
- **Licence:** MIT

## Links

- [INTERACT Research Unit](https://interact.oulu.fi)
- [MAD Project materials](https://interact.oulu.fi/mad-materials)
- [Figma wireframes](https://www.figma.com/design/JnPsg74CKynHtCq8vt2e5g/INTERACT)
# INTERACT CCI Research Methods Bank

An open web platform for sharing child-computer interaction (CCI) research methods developed by the [INTERACT Research Unit](https://interact.oulu.fi) at the University of Oulu, Faculty of Information Technology and Electrical Engineering (ITEE).

## What is this?

The INTERACT CCI Research Methods Bank makes research-backed methods for child-centred technology design freely accessible to teachers, researchers, social workers, and other practitioners. Materials come from multiple INTERACT research projects — starting with the MAD project (2020–2023) and the Takeover project (ongoing).

## Current Status

This repository contains a **UI prototype** built during a summer traineeship (June–August 2026). The prototype demonstrates the full visual design and user interface of the platform across 6 pages — it is not yet connected to a backend database.

| Page | File | Status |
|------|------|--------|
| Home | index.html | ✅ Complete |
| Browse Materials (with filters) | materials.html | ✅ Complete |
| Material Detail (with download modal) | detail.html | ✅ Complete |
| Projects | projects.html | ✅ Complete |
| About | about.html | ✅ Complete |
| Admin panel prototype | admin.html | ✅ Complete |
| Shared stylesheet | style.css | ✅ Complete |

## How to Open the Prototype

No installation needed. Just:

1. Download or clone this repository
2. Open the `interact-cci-bank` folder
3. Double-click `index.html` — it opens in your browser
4. Navigate between all pages using the top navigation bar

## Pages Overview

### Public pages
- **Home** — Introduction, featured method cards, project overview
- **Browse Materials** — Full filter panel (8 filter groups) with real-time filtering and multi-select download
- **Material Detail** — Full method description, metadata sidebar, file download with voluntary tracking form
- **Projects** — MAD and Takeover project cards with stats
- **About** — Simplified about page with contributor list and link to INTERACT website

### Admin panel
- **Login page** — Email and password login (prototype only — no real authentication yet)
- **Dashboard** — Stats, metadata field guide (Required vs Optional), Add New Material form, materials table with Edit/Delete, download records

## Tech Stack (Current Prototype)

| Component | Technology |
|-----------|-----------|
| Frontend | HTML5, CSS3, JavaScript (vanilla) |
| Styling | Single shared stylesheet (style.css) |
| Filtering | Client-side JavaScript (no backend) |
| Hosting | Local file system / GitHub Pages |
| Backend | ❌ Not yet implemented |
| Database | ❌ Not yet implemented |

## What Needs to Be Built Next (Backend)

The next development phase requires a developer with the following skills:

- **PHP and MySQL** — for server-side logic and database
- **File upload handling** — so INTERACT researchers can upload PDF, image, and video files
- **User authentication** — restricted admin login for INTERACT researchers only
- **Bolt CMS integration** — potentially using INTERACT's existing Bolt CMS (v5.1.20) at interact.oulu.fi
- **CRUD operations** — Create, Read, Update, Delete for materials in the database
- **Download tracking** — recording user details and file names when materials are downloaded

## Metadata Structure

Each material has 19 metadata fields — 12 Required and 7 Optional:

**Required:** Material title, Source project, Process, Phase number, Phase name, Target user group, Time required, Material type, Language, Description, Contributor/Author, File upload

**Optional:** Age group, Topic/Theme, Difficulty for children, Classroom setting, Related publications (DOI), Photo/image, Step-by-step instructions

## Project Background

- **Trainee:** Ritu Basak (MSc student, Software Engineering and Information Systems, University of Oulu)
- **Supervisors:** Prof. Tonja Molin-Juustila and Prof. Netta Iivari (INTERACT Research Unit)
- **Period:** June–August 2026
- **Licence:** MIT

## Links

- [INTERACT Research Unit](https://interact.oulu.fi)
- [MAD Project materials](https://interact.oulu.fi/mad-materials)
- [Figma wireframes](https://www.figma.com/design/JnPsg74CKynHtCq8vt2e5g/INTERACT)
