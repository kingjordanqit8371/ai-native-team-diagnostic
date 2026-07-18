# AI-Native Team Diagnostic v2026 - team assessment tool 2026

> **AI-Native Team Diagnostic is a browser-based team assessment experience that blends interactive scoring, real-time feedback, and diagnostic reporting so teams can judge readiness and refine their operating model.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kingjordanqit8371/ai-native-team-diagnostic?style=flat-square)](https://github.com/kingjordanqit8371/ai-native-team-diagnostic)

---

<p align="center">
  <a href="https://kingjordanqit8371.github.io/ai-native-team-diagnostic/">
    <img src="https://img.shields.io/badge/Download-AI--Native%20Team%20Diagnostic%20Latest-brightgreen?style=for-the-badge" alt="Download AI-Native Team Diagnostic">
  </a>
</p>

> **[Direct Download - AI-Native Team Diagnostic v2026](https://kingjordanqit8371.github.io/ai-native-team-diagnostic/)**

---

[Download Latest Build](https://kingjordanqit8371.github.io/ai-native-team-diagnostic/)

---

## What AI-Native Team Diagnostic Does

AI-Native Team Diagnostic gives teams a structured way to review their current state, compare answers as the session unfolds, and translate the outcome into a clear diagnostic. The tool is centered on team readiness and operating model clarity, which makes it a fit for product teams, leadership groups, and cross-functional organizations that need a common picture of where they are today.

The application combines a browser frontend with an Express API and PostgreSQL-backed persistence. It can be deployed through GitHub Pages, Render, and Neon. The workflow is intentionally interactive: results can be inspected in the browser, preserved between sessions in newer versions, and printed when a workshop output or formal handoff is required.

---

## Core Capabilities

- Interactive self-scoring assessment flow
- Live score readout as responses are entered
- Diagnosis report generation from assessment results
- 90-day plan output for next-step planning
- Browser-local autosave support in v2
- Shared team persistence support in v3
- Print-to-PDF using the browser's print dialog
- Frontend built for GitHub Pages with an Express and PostgreSQL backend

---

## Installation

Clone the repository and open the project folder locally:

```bash
git clone https://github.com/kingjordanqit8371/ai-native-team-diagnostic.git
cd ai-native-diagnostic
```

For local development, start the frontend and API according to your environment setup. If you are using the full stack, launch the Express service and connect it to PostgreSQL or Neon before opening the app in a browser.

---

## How to Use It

1. Open the web app in a supported browser.
2. Work through the assessment and enter team responses.
3. Review the live score as the form updates.
4. Generate the diagnosis report and 90-day plan.
5. Use the browser print dialog if you want a PDF copy.

If you are running the backend, point the frontend to the active API endpoint before starting the assessment session.

---

## Configuration

Configuration is usually divided between the frontend and backend layers.

Example environment setup:

```bash
DATABASE_URL=postgresql://user:password@host:5432/database
PORT=3000
```

For hosted setups, connect the database to Neon or another PostgreSQL provider and configure the Express API deployment on Render or a similar platform.

---

## Requirements

- Modern web browser
- Node.js for the Express backend
- PostgreSQL-compatible database
- Optional Neon database service
- Optional deployment target such as Render
- GitHub Pages for frontend hosting

---

## FAQ

**How do I update the project?**  
Pull the newest commits from the repository, then redeploy whichever frontend or backend pieces changed.

**Where do I make configuration changes?**  
Static app settings live in the frontend layer, while API and database values are normally supplied through environment variables.

**What if scores are not saving?**  
First confirm whether you are using a browser-local build or a shared team deployment, then check the backend, database, and API connection settings.

**Can I print the results?**  
Yes. Open the browser print dialog to export the report as a PDF.

**Where should I get support?**  
Check the repository, deployment configuration, and any environment-specific logs for the frontend, Express API, or database connection.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
