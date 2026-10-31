<div align="center">

# OBADA — Personal Portfolio

**Cybersecurity Student · Developer · IT Enthusiast**

A responsive, English-language personal portfolio presenting selected cybersecurity and software projects, technical skills, education, practical training, and community activities.

[LinkedIn](https://www.linkedin.com/in/obada-khader-08kh/) · [GitHub](https://github.com/obada2008) · [TryHackMe](https://tryhackme.com/p/obadakhader08) · [Email](mailto:obadakhader70@gmail.com)

</div>

## About

I'm **Obada Waleed Khader**, a first-year Cybersecurity student at **Amman Arab University**. Before university, I completed a three-year Information Technology pathway under the British **Pearson BTEC** system, earning **Level 2 and Level 3** qualifications.

My interests include cybersecurity, cryptography, OSINT, digital forensics, web and mobile development, and practical IT troubleshooting. This site highlights hands-on learning and independent technical projects.

## Featured projects

| Project | Description | Demo | Source |
| --- | --- | --- | --- |
| **Wadi Rum Mirage** | Bilingual educational platform for inspecting suspicious URLs and messages and exploring phishing indicators. | [Live demo](https://wadi-rum-mirage.onrender.com/) | [GitHub](https://github.com/obada2008/Wadi-Rum-Mirage) |
| **CRYPTIX** | Interactive browser-based project exploring encryption and cryptography concepts. | [Live demo](https://obada2008.github.io/CRYPTIX/) | [GitHub](https://github.com/obada2008/CRYPTIX) |
| **Hand Gesture Control** | Experimental computer-vision prototype for gesture-based desktop interaction. | Not published | Not published |

> Project descriptions are intentionally scoped to the demonstrated or self-reported work. Wadi Rum Mirage is an educational inspection tool, not a certified real-time threat-detection service.

## Features

- Responsive, dark-blue interface with custom monogram, subtle motion, and accessible navigation
- Project previews and interactive case-study dialogs
- Education, skills, selected certifications, training, and volunteering sections
- Downloadable CV, social links, and direct email contact
- Working front-end submission flow connected to **Formspree**, with success/error feedback
- SEO metadata, favicon, and social-preview asset
- **No build step:** plain HTML, CSS, and JavaScript

## Project structure

```text
.
├── index.html                 # Main portfolio
├── styles.css                 # Responsive styling and animation
├── script.js                  # Navigation, interactions, contact form
├── config.js                  # Public Formspree endpoint
├── 404.html                   # Fallback page
├── robots.txt
├── assets/
│   ├── favicon.svg
│   ├── social-preview.svg
│   └── Obada_Khader_CV.pdf
└── README.md
```

## Run locally

No Node.js, npm, or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a browser.
3. For a local server, use VS Code Live Server or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on GitHub Pages

1. Create a **public GitHub repository** (for example, `obada-portfolio`).
2. Upload **all files and the `assets` folder into the repository root**. Keep `index.html` at the top level, not inside an extra versioned folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Once deployed, visit the Pages URL shown in GitHub settings (typically `https://obada2008.github.io/obada-portfolio/`).
6. Test every project link, the CV download, mobile navigation, and the contact form on the published URL.

The URL above is an **example** until GitHub Pages confirms the actual deployment.

## Contact form

The contact form is configured in `config.js` to submit to:

`https://formspree.io/f/mljjwvbd`

The browser submits via HTTPS and displays loading, success, or error feedback. **Before considering it production-ready**, verify the Formspree account email, send a test submission from the deployed site, and confirm it appears in the Formspree dashboard **and** your inbox. Configure spam/domain restrictions in Formspree if appropriate.

The endpoint is public and is **not a secret API key**. Never commit passwords or private credentials.

## Customize

- **Content:** `index.html`
- **Project case studies and interactivity:** `script.js`
- **Colors, layout, motion:** `styles.css`
- **Contact endpoint:** `config.js`
- **CV:** replace `assets/Obada_Khader_CV.pdf` with your updated PDF (keeping the same filename)

## Privacy and accuracy

The bundled CV is the owner's original document and includes a **phone number and geographic location**, even though the public webpage intentionally omits the location. **Review or redact the CV before making this repository public** if you do not want those details exposed.

The CV's full name and education dates differ slightly from the portfolio's preferred display name and the stated three-year BTEC study period; verify them before publication. The stated TryHackMe **Top 25%** rank is self-reported and may change. Certificates are selected from the supplied CV.

## Status

**Source files are ready to upload.** The JavaScript was syntax-checked during packaging, but public deployment, browser/device QA, and delivery of a real Formspree test message still require verification.

---

Made by **Obada Waleed Khader** · [Get in touch](mailto:obadakhader70@gmail.com)
