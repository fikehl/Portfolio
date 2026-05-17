# Filip Kehl - E-portfolio

## About me
I'm a 20 year old student from Germany, currently studying IT at KTH (Kungliga Tekniska högskolan) in Stockholm, Sweden. I have a big passion for technology and I'm always looking for new challenges. In my free time I enjoy learning new things, play football, and spending time with my friends. Beyond my technical skills, my diverse background—ranging from data annotation and strategic marketing in Berlin to high-paced restaurant service, has shaped me into an analytical, stress-resilient, and collaborative team player. Furthermore, I thrive in dynamic environments, utilizing my fluency in Swedish, German, and English to communicate effectively and adapt to new challenges.

## Contact
Email: filipkehl@gmail.com  
GitHub: https://github.com/fikehl 
LinkedIn: https://www.linkedin.com/in/filip-kehl-912272264/

## Projects
### SkinMatch
A skincare website that helps users determine if products are safe for their specific skin type, allergies, and physical conditions based on barcode scans and ingredient analysis.

Github repository: https://gits-15.sys.kth.se/iprog-students/carln8-fkehl-jimmieki-liyuns-HT25-Project

### Pong (VGA)
A classic Pong game built for a VGA graphical display using C. It features X/Y ball movement, Y-axis paddle control, natural bounce physics on paddles and walls, and win state detection.

The repository for this project is private because it contains course-related material. 

### Sortrace
Web application for housing associations (BRF) to monitor waste sorting quality, identify mis-sorting patterns, and reduce unnecessary costs. Built in collaboration with Sortrace.

## Features

- **Dashboard** — KPI cards (mis-sorted bins, mis-sorting rate, total collections, estimated cost), pie chart by material type, trend chart, and cost-over-time chart. Includes a percentile badge showing how the association ranks against others.
- **Sorting Guide** — Per-material sorting instructions tailored to the association's 30-day data, with AI-generated cost impact explanations.
- **Reports** — Generate and download PDF reports with KPI summaries, material distribution, cost forecasts, and action suggestions. Supports Swedish and English.
- **Evidence** — Browse image and video evidence linked to mis-sorting incidents, with card and table views.
- **Settings** — Language (Swedish / English) and theme (light / dark / system) preferences.
- **AI Chat** — Assistant that answers questions about the association's waste statistics.

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 16, React 19, TypeScript |
| UI | Tailwind CSS, Base UI, Radix UI, Recharts |
| Auth | JWT in HTTP-only cookies (jose), bcrypt, Prisma |
| PDF | @react-pdf/renderer |
| AI | Google Gemini via REST API (`generativelanguage.googleapis.com`) |
| Database | PostgreSQL, Prisma |
| Testing | Vitest |
| Hosting | Railway (optional) |

The repository for this project is private and is not owned by me since it was an external project. 
