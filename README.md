# 📐 Algebra Coach

An AI-powered algebra practice tool built for a solo hackathon project.
## Project Description
Ok, consider you are a passionate and driven student practicing your math exercises for the day. You start solving the questions one by one. You solve the problem and check the validity of the solution from the key book to see if your answer was right or wrong. You find that the answer is wrong. While being sure of the methods you used, you spend many long hours trying to find the exact step where you went wrong—browsing the internet for similar solved problem sets, analyzing them, and comparing them to yours. In this whole process, you spend more time finding the problem than actually learning and polishing your math skills.  

This website solves exactly that problem. You upload your exercise picture, and the website generates the problems one by one for you to solve. Then you solve the problem on the screen if you have a stylus, or solve it on paper and upload the picture. The website compares your answer with the solved answer it has generated in the backend (without showing it to the student). If the student has gotten the answer correct, well and good. If not, the website pinpoints exactly which step or steps went wrong and explains in the description box how to correct it.  

Being from a STEM background, I wished for a similar coach available 24/7, especially since my teachers were not available all the time, to help me pinpoint exactly where I went wrong in my solutions so that I could learn efficiently and quickly, rather than spending hours finding my mistakes and eventually reaching my breaking point.
This is how the website I built helps students learn efficiently—spending greater time actually learning rather than wasting long hours analyzing where they went wrong and reaching their breaking point. Let’s make learning fun rather than frustrating.

what this website does: 
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
