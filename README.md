# Job Application Tracker

A clean, responsive web app to track your job applications — mark positions as Interview or Rejected, filter by status, and monitor your progress with live counters.

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-3370d1?style=for-the-badge&logo=github)](https://muhatarima.github.io/ass4ph/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Muhatarima/ass4ph)

</div>

---

## Screenshot

<div align="center">
  <img src="https://raw.githubusercontent.com/Muhatarima/ass4ph/main/assets/preview.png" alt="Job Application Tracker Preview" width="700"/>
</div>

---

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI_v4-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## Features

- **Live Counters** — Total, Interview, and Rejected counts update instantly at the top
- **Status Badges** — Each job card shows NOT APPLIED / INTERVIEW / REJECTED status
- **One-click Status Toggle** — Click Interview or Rejected button on any card to update status; click again to undo
- **Filter Tabs** — Filter jobs by All / Interview / Rejected
- **Delete Jobs** — Remove any job permanently with a confirmation prompt
- **Color-coded Cards** — Green left border for Interview, Red left border for Rejected
- **Job Count Label** — Shows how many jobs match the current filter
- **Empty State** — Friendly message when no jobs match the selected filter
- **Fully Responsive** — Works on mobile, tablet, and desktop

---

## Dependencies

All dependencies are loaded via CDN — no installation required.

| Dependency | Version | Purpose |
|---|---|---|
| Tailwind CSS | CDN | Utility-first CSS framework |
| DaisyUI | v4.12.10 | Component library for Tailwind |

---

## Run Locally

**1. Clone the repository**

```bash
# HTTPS
git clone https://github.com/Muhatarima/ass4ph.git

# GitHub CLI
gh repo clone Muhatarima/ass4ph
```

**2. Open the project**

```bash
cd ass4ph
```

**3. Launch in browser**

Open `index.html` directly in your browser, or use the **Live Server** extension in VS Code for best experience.

```
Right click index.html → Open with Live Server
```

---

## Project Structure

```
ass4ph/
├── index.html      # Main application file
├── jobs.png        # Empty state illustration
└── assets/         # Additional assets
```

---

## Author

**Muhatarima** — [GitHub](https://github.com/Muhatarima) · [LinkedIn](https://www.linkedin.com/in/muhatarima-medha/) · [muhatarima@gmail.com](mailto:muhatarima@gmail.com)
