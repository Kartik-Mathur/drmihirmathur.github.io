# Dr. Mihir Mathur — Medical Portfolio

A responsive portfolio built with plain HTML, CSS and JavaScript. The design uses white backgrounds, navy text, blue accents and bold sans-serif headings. Main text is 18px on desktop and 17px on mobile, with larger labels and strong contrast throughout. Clinical experience appears directly after the introduction, followed by community health, education, honours, skills, additional training and leadership.

## Preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Files

- `index.html` — portfolio content, navigation and contact links.
- `styles.css` — typography, colours, layout and responsive styles.
- `script.js` — mobile navigation, active section highlighting and the footer year.
- `assets/dr-mihir-mathur.png` — the supplied portrait.
- `assets/tianjin-medical-university-logo.png` — the university emblem shown beside the graduating institution in the education section.
- `assets/bhai-parmanand-vidya-mandir-logo.png` and `assets/st-johns-academy-logo.png` — school emblems shown beside the Class XII and Class X results.
- `assets/st-stephens-hospital-logo.png` and `assets/tianjin-general-hospital-logo.png` — smaller hospital emblems shown beside the clinical experience headings.
- `assets/honours-award.svg` — a medal icon above the heading in the separate blue honours and awards panel.
- `assets/Mihir_Mathur_Resume.docx` — the supplied résumé, available to download from the introduction, experience section and contact section.

The portrait and résumé are served locally. Inter loads from Google Fonts with Arial and Helvetica as fallbacks. Text uses medium or heavier weights, with a minimum size of 14px for supporting labels. The portfolio also works without JavaScript, including navigation and résumé downloads.

## Content

Experience, dates, education, awards, clinical skills, courses and leadership follow the supplied résumé, reviewed on 16 November 2026. Permanent medical registration is stated as **applied for; approval awaited**. The AI in Healthcare Specialization is attributed to Stanford University via Coursera.

Certificate links are taken from the hyperlinks embedded in the original résumé: the Tianjin clinical internship, three academic awards, the Coursera specialization and the cricket tournament. They open in a new tab. The Python course has no certificate link in the supplied résumé.

The site describes clinical training and does not add patient counts, independent practice claims or qualifications absent from the résumé.

The university emblem is stored locally and displayed without recolouring. Image source: [Tianjin Medical University logo collection](https://www.urongda.com/logos/4112010062), [original image](https://cdn.urongda.com/images/normal/medium/tianjin-medical-university-logo-1024px.png).

School logos are stored locally in their original colours. Sources: [Bhai Parmanand Vidya Mandir](https://www.bvmschool.in/wp-content/uploads/2021/12/flogo.png) and [St. John’s Academy, Delhi](https://www.sanjohn.org/webroot/front/assets/images/sanjohn_logo_png.png).

Hospital logos are sourced from the hospitals’ own websites: [St. Stephen’s Hospital](https://ststephenshospital.org/wp-content/uploads/2026/04/cropped-Favicon-1-192x192.png) and [Tianjin Medical University General Hospital](https://www.tjmugh.com.cn/images/logo.png). The Tianjin header image is displayed with CSS cropping to show its emblem, preserving the original file. Hospital emblems are 56px on desktop and 48px on mobile.

## Publishing

Serve `index.html`, `styles.css`, `script.js` and the entire `assets/` folder together on any static host, including GitHub Pages. No build step or dependencies are required.
