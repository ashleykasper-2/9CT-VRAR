# Menai High School – Stage 5 Computing Technology VR Unit

## Immersive Computing: VR with A-Frame & WebXR

This repository contains the complete self-paced 10-week / 30-lesson VR unit.

### Repository structure

```text
menai-vr-computing-course/
├── index.html
├── README.md
├── assets/
│   └── menai-logo-fallback.svg
├── resources/
│   └── coding-reference.html
└── student-starter/
    ├── index.html
    └── README.md
```

## Main website

`index.html` is the full student course website.

It contains:
- 30 self-paced lessons
- Read and Understand content
- worked examples
- guided practice
- interactive checks
- coding tutorials
- independent challenges
- assessment connections
- saved student responses in browser local storage
- lesson progress tracking
- links to A-Frame and official tutorials
- the VR Escape Room major project sequence


## Interactive practice

Every lesson now includes extra auto-marked practice. Depending on the topic, students will encounter:

- multi-select questions;
- drag-and-order sequencing tasks, with accessible up/down buttons;
- short code-entry questions marked correct/incorrect in the browser;
- the existing multiple-choice knowledge checks;
- guided written responses and independent challenges.

The interactive checking runs entirely in the browser. No student answers are sent to GitHub or an external service.

## Student starter project

`student-starter/index.html` is a simple working A-Frame escape-room starter.

Students can copy the starter into their own project and modify it as they progress through the unit.

## Coding reference

`resources/coding-reference.html` is a standalone quick-reference page for:
- HTML structure
- A-Frame primitives
- position / rotation / scale
- IDs
- JavaScript variables
- events
- if / else
- functions
- animation
- debugging

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload the complete contents of this folder.
3. Make sure `index.html` is in the root of the repository.
4. Open the repository **Settings**.
5. Choose **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)`.
8. Save.
9. GitHub will provide the published website address after deployment.

## Important notes

### A-Frame requires internet access

The course and starter project load A-Frame from the official CDN:

```html
<script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
```

Students therefore require internet access for A-Frame to load.

### Saved responses

Student responses and lesson progress are saved using browser `localStorage`.

This means:
- data is saved on the device/browser being used;
- it is not automatically synced between devices;
- clearing browser storage can delete saved responses;
- GitHub itself does not receive student responses.

### School logo

The website first attempts to load the Menai High School logo from the school-hosted URL. If it cannot load, the local `assets/menai-logo-fallback.svg` graphic is shown so the page layout remains intact.

If you have the official school logo file, place it in `assets/` and update the `<img class="logo">` source in `index.html` to use that local file.

## Recommended student workflow

1. Open the published course website.
2. Work through lessons in order.
3. Use the Student Starter Project when the A-Frame build sequence begins.
4. Keep a separate copy of the student's own project file.
5. Test one code change at a time.
6. Use the Coding Reference and official A-Frame tutorials whenever needed.
7. Develop the final VR Escape Room progressively across the unit.
