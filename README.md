# Ilyass Saadi Portfolio

Static portfolio website for data, BI, analytics, and analytics engineering roles.

## What is included

- One-page recruiter portfolio
- NYC Taxi Intelligence project card
- NYC Taxi Intelligence case study page
- Skills grouped by role relevance
- Experience, education, and contact sections
- Real dashboard screenshots from the NYC Taxi Intelligence project

## Files

```text
portfolio_site/
├── index.html
├── projects/
│   └── nyc-taxi-intelligence.html
├── assets/
│   ├── css/styles.css
│   ├── js/site.js
│   ├── img/
│   └── files/
└── README.md
```

## Personal links to update

The GitHub and email links are included.

Add the LinkedIn URL in `assets/js/site.js`:

```js
const portfolioConfig = {
  linkedin: "https://www.linkedin.com/in/your-profile"
};
```

If the LinkedIn value is empty, the site hides LinkedIn buttons so there are no broken links.

## Publish with GitHub Pages

Recommended: publish this as a separate GitHub user site repository named:

```text
ilyassfcb11-lgtm.github.io
```

That keeps the existing NYC Taxi dashboard at:

```text
https://ilyassfcb11-lgtm.github.io/nyc-taxi-intelligence/
```

and gives the portfolio the clean root URL:

```text
https://ilyassfcb11-lgtm.github.io/
```

This folder already includes a GitHub Pages workflow in `.github/workflows/pages.yml`.
When the folder is used as the root of the portfolio repository, pushes to `main`
will publish the site.
