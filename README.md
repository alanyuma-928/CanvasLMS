# 🎓 Canvas LMS Development & Integration

**HTML templates, Python automation scripts, and asset management for Arizona Western College Exercise Science courses.**

![Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-Instructure_Canvas-red)
![Languages](https://img.shields.io/badge/Languages-HTML%20%7C%20CSS%20%7C%20Python-blue)

## 📋 Overview
This repository houses the backend development tools and front-end design assets used to deploy courses (EXW101, EXW150, EXW265) on the Canvas Learning Management System.

The goal of this project is to move beyond standard Canvas formatting to create **immersive, accessible, and mobile-responsive** learning environments.

## 🗂 Repository Structure

```text
CanvasLMS/
├── 📁 assets/              # Banners, buttons, and icons hosted for RCE use
├── 📁 html-templates/      # Code snippets for Canvas Rich Content Editor
│   ├── homepage.html       # Responsive course landing page
│   ├── module-intro.html   # Standardized module headers
│   └── assignment.html     # Rubric and instruction layout
├── 📁 scripts/             # Python scripts using canvasapi
│   ├── date_shifter.py     # Automate due date updates
│   └── rubric_grade.py     # Batch grading assistance
├── 📁 css/                 # Custom CSS overrides (if applicable)
└── README.md
