# 📐 Algebra Coach

An AI-powered algebra practice tool built for a solo hackathon project.

A student uploads a photo of a textbook exercise. The app splits it into parts, solves each one privately in the background, and shows the parts one at a time. The student answers by **writing on screen**, **uploading a photo of their handwritten working**, or **typing**. The app reads the handwriting, compares it with the verified solution, finds the **first wrong step**, and explains how to fix it.

A **teacher space** tracks student progress live. Each mistake appears as a cropped picture of the exact step in the student's own handwriting, with an AI diagnosis and a box for the teacher's mentoring note.

## Features
- Photo-to-problems: reads a textbook page and separates parts such as 1(a), 1(b)
- Hidden answer key: problems are solved in the background, not shown to the student
- Handwriting canvas, photo upload of working, or typed answers (with text recognition)
- Step-level feedback: pinpoints where the student went wrong
- Teacher dashboard: per-student accuracy, wrong-step images, notes, reviewed status

## Live demo
https://claude.ai/artifact/KwdtBFakgjoGrVSAWRswEW

(Requires a claude.ai account. The AI and shared-database features run on the Claude artifact platform.)

## Files
- `index.html` — the whole app (HTML, CSS and JavaScript in one file)

## Tech
Plain HTML/CSS/JavaScript, with Claude providing vision (reading photos and handwriting) and reasoning (solving and checking). A shared database stores submissions for the teacher view.

## Known limitations
- Works only inside the Claude artifact environment, not on ordinary web hosting
- The teacher tab is hidden from students but not strictly access-controlled
- Messy handwriting may be misread

## Roadmap
Show teacher notes to students, progress charts over time, weak-topic reports, more subjects beyond algebra, proper accounts and permissions.
