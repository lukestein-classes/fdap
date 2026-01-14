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

## 4. Annual Syllabus Update Checklist

This checklist outlines the information and steps required to update the course syllabus for a new academic year.

### 4.1. Information to Request from the User

Before starting the update process, ask the user for the following information:

*   **Academic Year**: The new academic year and semester (e.g., "Spring 2026").
*   **Instructor Information**: Any changes to instructor's name, contact information, or office location.
*   **Class Schedule**:
    *   The number of sections.
    *   The meeting days (e.g., Monday/Wednesday).
    *   The meeting times for each section.
*   **Due Dates**: A list of all graded components and their due dates for the new semester. This should include:
    *   Midterm Group Project (including online submission and presentation dates).
    *   Midterm Exam.
    *   Data/Methods Demonstration (including online submission and presentation dates).
    *   Professional Ethics Module (and its deliverable due date).
    *   Final Group Project (including online submission and presentation dates).
    *   Final Exam.
*   **Technology Updates**: Any new software, tools, or technology policies to be included (e.g., policies on AI/LLM tools).
*   **Course Links**: The updated URL for the course's Canvas page.
*   **Syllabus and Schedule Files**: Confirmation that the `fin6200syllabus.lyx` and `schedule.md` files in the root directory are the correct ones to edit.

### 4.2. Update Process

1.  **Update Syllabus Content**: In the new `fin6200syllabus.lyx` file, perform the following updates:
    *   Update the academic year (e.g., "Spring 2025" to "Spring 2026").
    *   Update all instructor-related information.
    *   Update the class schedule (days and times).
    *   Update the table of deliverables with the new due dates.
    *   Incorporate any changes to the technology section or other policies.
2.  **Check Books and Links**:
    *   Extract all book titles and editions from the syllabus. Use web searches to check for newer editions.
    *   Extract all URLs. Use web fetching tools to check for broken links.
    *   Report any recommended updates to the user.
3.  **Final Questions**: Ask the user any clarifying questions needed to finalize the syllabus (e.g., for TBD dates, or to confirm link updates).