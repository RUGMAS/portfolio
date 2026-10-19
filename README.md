# Rugma S | Data Analyst Portfolio

A responsive, single-page portfolio website for **Rugma S**, a Data Analyst Intern with an MCA, showcasing skills, dashboard projects, a project presentation, experience and certifications.

**Live site:** `https://rugmas.github.io/<repo-name>/` *(update after enabling GitHub Pages)*

---

## Features

- Dark blue, light blue and white theme with gradient accents
- Sticky navigation with smooth scrolling
- Sections: About, Technical Skills, Dashboard Projects, Presentation, Education & Experience, Certifications
- Fully responsive for mobile, tablet and desktop
- Pure HTML and CSS, with no frameworks or build step
- Respects `prefers-reduced-motion` and uses accessible labels and focus styles

## Tech Stack

| Area | Tools |
|---|---|
| Languages | SQL, Python |
| BI & Visualisation | Power BI, Qlik Sense, Tableau, Looker Studio |
| Data Tools | Excel, Power Query, DAX, Google Analytics, MySQL, PostgreSQL |
| Cloud | AWS (EC2, S3, Lambda), Docker |

## Project Structure

```
.
├── index.html     # The whole site (HTML + CSS in one file)
└── README.md
```

> Rename `portfolio.html` to `index.html` before pushing so GitHub Pages serves it.

## Run Locally

```bash
git clone https://github.com/RUGMAS/<repo-name>.git
cd <repo-name>
# Open index.html in your browser
```

## Deploy with GitHub Pages

1. Push the files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Save, and your site will be live at `https://rugmas.github.io/<repo-name>/` within a minute or two.

## Customise

- **Projects:** edit the three cards in the `#projects` section with your real titles, descriptions and links.
- **Presentation:** update the **View Presentation** and **Download PDF** button links in `#presentation`.
- **Colours:** change the variables in `:root` at the top of the `<style>` block (`--bg`, `--sky`, `--ice` and so on).
- **Photo:** the profile image is embedded in the hero section. Replace the `<img src="...">` inside `.face`.

## Contact

- LinkedIn: [rugma-s](https://www.linkedin.com/in/rugma-s-0130341aa/)
- GitHub: [@RUGMAS](https://github.com/RUGMAS)
- Email: rugmaspta@gmail.com
- Location: Kochi, Kerala, India

---

© Rugma S. All rights reserved.
