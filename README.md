# NS-Adam Portfolio

A high-signal, single-page personal portfolio site designed for the Network School Core Team application.

## Overview
- **Stack**: HTML5, Tailwind CSS (CDN), LaTeX (for assets).
- **Design**: Network School / Linear.app aesthetic (Dark mode, Emerald accents).
- **Purpose**: Demonstrate "Execution over Accreditation" and serve as a LinkedIn replacement.

## Project Structure
- `index.html`: Main portfolio page.
- `resume.pdf`: Compiled resume (generated from `resume.tex`).
- `proposal.pdf`: Compiled proposal (generated from `proposal.tex`).

## Deployment (Vercel)
This project is ready for immediate deployment on Vercel.

1.  **Push to GitHub**:
    - Initialize a git repo (if not already done).
    - Commit `index.html`, `resume.pdf`, and `proposal.pdf`.
    - Push to GitHub.

2.  **Import to Vercel**:
    - Go to [vercel.com/new](https://vercel.com/new).
    - Import your GitHub repository.
    - Vercel will automatically detect the static site.
    - Click **Deploy**.

## Local Development
To test locally:
```bash
python3 -m http.server 8080
```
Open [http://localhost:8080](http://localhost:8080).
