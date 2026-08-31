# ikhsannur1996.github.io

Personal portfolio site for **Mohamad Ikhsan Nurulloh** — a data professional working across data science, BI, and cloud engineering.

Live at [ikhsannur1996.github.io](https://ikhsannur1996.github.io)

## Pages

| Page | Description |
|------|-------------|
| **index.html** | Main portfolio — projects, experience, certifications, training, and contact |
| **resume.html** | Printable ATS/modern resume with style toggle (`?style=modern` or `?style=ats`) |

## Structure

```
├── index.html          # Portfolio homepage
├── resume.html         # Resume page
├── robots.txt          # SEO
├── sitemap.xml         # Sitemap
├── assets/
│   ├── images/
│   │   ├── company-logos/       # Employer logos for timeline
│   │   ├── portfolio-thumbnails/# Project card thumbnails
│   │   ├── certificate-thumbnails/ # Certification thumbnails
│   │   ├── training-thumbnails/ # Training session images
│   │   ├── education-logos/     # School logos
│   │   ├── award-thumbnails/    # Award images
│   │   └── profile/             # Profile photos
│   ├── documents/
│   │   ├── portfolio/           # Project PDFs (dashboards, models, etc.)
│   │   ├── certifications/      # Certificate PDFs
│   │   ├── training/            # Training materials
│   │   ├── awards/              # Award certificates
│   │   └── general/             # LinkedIn profile exports
│   └── js/                      # JavaScript files
```

## Features

- **Project filter bar** — filter by tag (Data Science, Data Analyst, Cloud, etc.)
- **Resume style toggle** — switch between ATS-friendly and modern layouts
- **Dark mode** on linkedin profile pages
- **Auto-calculated experience** — years of experience updates automatically from timeline data
- **Responsive** — works on desktop, tablet, and mobile
- **Share button** — native share for resume page
- **Download as PDF** — save modern resume as PDF

## Run locally

```bash
# Clone
git clone https://github.com/ikhsannur1996/ikhsannur1996.github.io.git
cd ikhsannur1996.github.io

# Serve (any static server works)
python3 -m http.server 8080
# Open http://localhost:8080
```

No build tools, no frameworks — just plain HTML, CSS, and JavaScript.