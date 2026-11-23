# WebLearn — CS35302

A responsive, folder-based Web Technology learning platform for B.Tech CSE Semester 5.

## Run locally
1. Install Node.js (LTS).
2. Extract this project.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL shown by Vite.

## Features
- Five unit folders and 71 syllabus topics
- Unit and topic navigation with breadcrumbs
- Search across the syllabus
- Topic completion, bookmarks, recent topics
- Course progress tracking
- Light/dark theme
- Responsive layout
- Topic learning pages with structured sections and exam revision prompts

## Notes on educational content
The project includes syllabus-aligned topic summaries and a consistent learning-page structure. Topic pages currently provide foundational explanatory content and revision prompts. For full lecture-note depth, expand the topic records in `src/data/syllabus.js` and the `buildSections()` content in `src/App.jsx` with instructor-approved notes and topic-specific diagrams/examples.
