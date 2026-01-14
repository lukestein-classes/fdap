# Agentic Workflow Documentation

This document outlines the conventions and procedures for using AI agents to assist with the maintenance and development of the course materials for **FIN 6200: Financial Data Analysis and Practice**.

## 1. Project Overview

This repository is the private workspace for the course instructor. While the content is publicly available via GitHub Pages, this repository is where the instructor and their AI agents perform maintenance and updates. The agentic workflow described here is for the instructor's benefit and is separate from any policies regarding student use of AI tools.

- **Purpose**: To maintain, update, and improve public course materials, including the syllabus, schedule, datasets, and code templates.
- **Technology Stack**:
    - **Content**: Markdown (`.md`), LyX (`.lyx`), and LaTeX (`.tex`) files.
    - **Website Generation**: GitHub Pages (likely using Jekyll).
    - **Data & Code**: Python, Jupyter Notebooks (`.ipynb`), and various data files (`.csv`).
    - **Course Tooling**: The curriculum is centered around Python for data science (pandas, NumPy, Seaborn), VS Code, and specialized financial data services like Bloomberg, WRDS, and CRSP.

## 2. Repository Structure

- **/`**: The root contains the current course schedule (`schedule.md`), configuration files, and the main `README.md`.
- **`syllabus/`**: Contains the current course syllabus (`fin6200syllabus.lyx`) and its derivatives.
- **`data/`**: Stores sample datasets (`.csv` files) used in assignments and demonstrations.
- **`templates/`**: Holds template Jupyter Notebooks (`.ipynb`) that provide starting points for students.
- **`cheatsheets/`**: Contains PDF reference guides for common Python libraries.

## 3. Agent Tasks & Workflows

### 3.1. File Versioning Convention

- **Current Year (Working Files)**: Files with "undated" names (e.g., `schedule.md`, `fin6200syllabus.lyx`) are the active versions for the current or upcoming semester (e.g., 2026). **These are the primary files to be edited.**
- **Archives**: Files with years in their names (e.g., `schedule_2025.md`, `fin6200syllabus_2025.lyx`) are historical archives. **Do not edit these files.** They serve as a record of past semesters.

### 3.2. Common Task: Updating Course Materials for a New Semester

The main task is updating the course materials for the upcoming semester by modifying the "undated" working files.

**Workflow:**

1.  **Identify Working Files**: Target the undated files (e.g., `schedule.md`, `syllabus/fin6200syllabus.lyx`) for edits. The user has already prepared these files by copying the content from the previous year.
2.  **Update Content**: Modify the contents of the working files based on instructor requests.
    - **Schedules**: Update dates, topics, holidays, and deliverables. Dates must be calculated accurately for the new academic year.
    - **Syllabi**: Revise policies, dates, and course details as instructed.
3.  **Compilation**: The source file for the syllabus is `fin6200syllabus.lyx`.
    - The instructor may handle compilation of `.lyx` and `.tex` files to `.pdf` manually using desktop software.
    - Agents may be asked to investigate or perform command-line compilation if possible.
4.  **Verification**: After any change, the agent should review the modified source files to ensure accuracy and proper formatting.

### 3.3. Other Conventions

- **Source vs. Generated Files**: For the syllabus, `.lyx` is the primary source. Only edit this file unless specifically instructed otherwise. The `.tex` and `.pdf` files are generated from it.
- **Private vs. Public Content**: This repository is for public materials only. Do not add or reference non-public information such as student data, homework solutions, or internal lecture notes.

### 3.4. Citing Agent Contributions

When an agent makes a significant contribution to a file, a note should be added in the commit message to acknowledge the agent's role.
