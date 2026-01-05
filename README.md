# Networks Grade Calculator (Winter 2026)

A specialized grade calculator for the multidisciplinary **Networks** course (ECON 2040 / INFO 2040 / SOC 2090 / CS 2850) at Cornell University, tailored for the Winter 2026 session.

## Overview

This calculator helps students track their progress and estimate their final course grade based on the official syllabus grading formula. It features real-time updates, local storage persistence, and a "Target Score" calculator for the final exam.

## Grading Logic

The calculator implements the exact formula from the Winter 2026 syllabus:

| Category | Weight | Details |
| :--- | :--- | :--- |
| **Short Homeworks** | 40% | 9 assignments, capped at a maximum of 40 points total. |
| **Long Assignments** | 20% | HW4 (10%) and HW9 (10%). |
| **Class Engagement** | 20% | Attendance (10%) and Participation (10%) for 12 sessions. |
| **Final Exam** | 20% | Take-home final exam score (out of 50). |
| **Course Evaluation**| +1% | Extra credit for completion. |

### Letter Grade Scale
- **A+**: 98–101%
- **A**: 93–97%
- **A-**: 90–92%
- **B+**: 88–89%
- **B**: 83–87%
- **B-**: 80–82%
- **C+**: 78–79%
- **C**: 73–77%
- **C-**: 70–72%
- **D**: 60–69%
- **F**: Below 60%

*Note: Grades are rounded to the nearest integer (e.g., 92.50 becomes 93, 92.49 becomes 92).*

## Features

- **Persistent State**: Your grades are saved automatically in your browser's local storage.
- **Dynamic Target Calculator**: Automatically calculates exactly what you need on the final exam to reach specific letter grades (A, A-, B+, etc.).
- **Mobile Optimized**: Clean, responsive UI for checking grades on the go.
- **Syllabus-Compliant**: Handles the "Short HW" cap and specific weights for HW4/HW9 correctly.

## Technologies Used

- **HTML5** & **Semantic Elements**
- **Tailwind CSS** (via CDN for rapid styling)
- **Vanilla JavaScript** (State management, local storage, and calculation logic)
- **Lucide Icons**

## Usage

Simply open `index.html` in any modern web browser. 

---
*Disclaimer: This is a student-built tool. Always cross-reference with official Canvas grades and the syllabus.*
