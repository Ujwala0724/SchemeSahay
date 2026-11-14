# SchemeSahay – Government Schemes Made Simple

SchemeSahay is a civic-tech website that brings information about Central Government schemes into one clear starting point, so people can explore what a programme does, where to check details, and what to ask next.

It was developed as part of our **Community Service Project (CSP)**.

> **Disclaimer:** SchemeSahay is an informational student project. It is **not** an official government website, and the eligibility checker is only a preliminary guide, not official eligibility verification. Always confirm details on the official government portal.

---

## Project details

| | |
|---|---|
| **Project title** | Awareness of Central Government Schemes and the Level of Participation |
| **Location** | Chevuturu, Andhra Pradesh, India |
| **Duration** | 13 May 2026 – 22 June 2026 |
| **Faculty guide** | Dr. G. Sambi Reddy, Associate Professor, Department of CSE |

### Team members
1. Chittela Bala Krishna Teja
2. Chitturi Prasanthi
3. Dandugula Nithin Kumar
4. Dasari Suguna Tejaswi
5. Dasari Ujwala

---

## Survey findings

Findings from our project survey (not national statistics).

**Awareness levels:** Fully aware 30% · Partially aware 38% · Not aware 32%

**Major barriers:** Lack of information 62% · Lack of documents 55% · Lack of digital knowledge 54%

---

## Features

- **Home** – hero section, survey statistics, featured schemes, platform features, community impact
- **Explore Schemes** – searchable directory, category filters, scheme detail pop-ups (benefits, eligibility overview, how to apply, official link)
- **Eligibility Checker** – form with validation; shows schemes that may be relevant, with a reason for each
- **Document Checklist** – common document categories, progress indicator, reset button
- **Our CSP Journey** – objectives, survey charts, challenges, proposed solutions, team, faculty guide, conclusion, photo gallery
- **About** – why SchemeSahay exists, the awareness gap, how the platform helps, proposed improvements
- Responsive layout with a mobile menu, consistent footer and empty-state messages

### Schemes covered
Pradhan Mantri Jan Dhan Yojana (PMJDY) · Pradhan Mantri Awas Yojana (PMAY) · Pradhan Mantri Ujjwala Yojana · Swachh Bharat Mission · Digital India · Beti Bachao Beti Padhao · Ayushman Bharat · Pradhan Mantri Mudra Yojana · Pradhan Mantri Kaushal Vikas Yojana (PMKVY)

### Proposed solutions (recommendations only)
Local-language pamphlets · Digital literacy workshops · Document assistance · WhatsApp information groups · Panchayat facilitation support · Digital kiosks

These are presented as recommendations, not completed activities.

---

## Tech stack

**Web version**
- HTML, CSS and JavaScript (no framework, no build step)
- Manrope font (Google Fonts)

**Flutter version**
- Flutter (Material 3) with Dart
- Packages: `google_fonts`, `url_launcher`

---

## Folder structure

### Web version
```
schemesahay-web/
├── index.html
├── style.css
├── script.js
└── images/
```
A single-file build (`index.html` only, with CSS, JS and images built in) is also available.

### Flutter version
```
schemesahay/
├── lib/
│   ├── main.dart     # app theme and navigation
│   ├── data.dart     # schemes, statistics, documents, team
│   └── pages.dart    # all six pages and shared widgets
├── assets/images/    # hero and survey photos
├── web/              # Flutter web template
└── pubspec.yaml
```

---

## Run locally

**Web version:** open `index.html` in a browser.

**Flutter version:**
```bash
flutter pub get
flutter run -d chrome
```

## Build for the web (Flutter)
```bash
flutter build web --release
```
The finished site is created in `build/web`.

## Deploy on Netlify
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the site folder onto the page (for Flutter, drag the `build/web` folder).
3. Make sure `index.html` is directly inside the folder you upload.
4. Netlify gives you a live link.

---

## Notes

- Scheme details are concise summaries. Eligibility, benefits, application rules and document requirements can change, so users are asked to verify them on the official portal for each scheme.
- Photographs are from our survey visit in Chevuturu on 13 May 2026.
- No beneficiary numbers or completed outreach activities are claimed on the website.

---

## Acknowledgements

Thanks to the residents of Chevuturu who took part in our survey, and to our faculty guide, Dr. G. Sambi Reddy, for his guidance.
