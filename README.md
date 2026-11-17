# HTML Pricing Comparison Table

A single, unstyled, semantic HTML5 page that compares three subscription plans (Free, Pro and Business) side by side using an accessible table.

This project was developed as part of the HTML Fundamentals learning path on [roadmap.sh](https://roadmap.sh/projects/pricing-comparison-table), with a focus on displaying structured data in HTML using a real table, proper headers, a caption, row scopes and the semantic markup around it.

## Live Demo

[View the Live Webpage](https://7amarah.github.io/html-pricing-comparison-table/)

## Project Overview

The objective of this project is to build a small pricing comparison page where the table structure does the work. The page is deliberately left unstyled: styling is covered in a later project, so the focus here is on correct, accessible markup that screen readers can announce in context.

The page compares three plans across storage, number of projects and support level:

| Plan | Storage | Projects | Support |
| --- | --- | --- | --- |
| Free | 5 GB | 3 | Email |
| Pro | 100 GB | 25 | Priority Email |
| Business | 1 TB | Unlimited | 24/7 Phone |

## Features

- Semantic page structure using `<header>`, `<main>` and `<footer>`.
- A real `<table>` with `<thead>` and `<tbody>` separating header rows from data rows.
- A `<caption>` as the first child of the table, naming what is being compared.
- Header scopes: `scope="col"` on column headers and `scope="row"` on the plan-name cells.
- A merged cell using `colspan` in the table footer, spanning every column for a note that applies to all plans.
- Head metadata: `<title>`, `<meta charset>` and `<meta viewport>`.
- SEO metadata, Open Graph and Twitter card tags for link previews.
- Favicons and a web app manifest.
- No CSS and no JavaScript, by design.

## Requirements Checklist

| Requirement | Where it is met |
| --- | --- |
| Semantic page structure | `<header>`, `<main>` and `<footer>` wrap the page content |
| Table with `<caption>`, `<thead>` and `<tbody>` | "Plan Comparison" caption, one header row and three data rows |
| `scope="col"` and `scope="row"` | Column headers use `col`; Free, Pro and Business use `row` |
| At least one merged cell | `colspan="4"` footer cell: "All plans include SSL and daily backups." |
| Page metadata in the head | `<title>`, `<meta charset>` and `<meta viewport>`, plus SEO and Open Graph tags |

## Technologies Used

- HTML5
- Semantic HTML
- Accessible table markup
- SEO metadata
- Open Graph metadata

## Project Structure

```text
html-pricing-comparison-table/
├── index.html
├── README.md
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── favicon-transparent-512x512.png
├── site.webmanifest
└── og-image.png
```

*Note: Some assets are optional and should only be included if they are present in the repository and referenced by the HTML document.*

## Getting Started

### Prerequisites

You only need:

- A web browser.
- A code editor (such as Visual Studio Code).
- Git (optional, for cloning the repository).

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/7amarah/html-pricing-comparison-table.git
   ```

2. Navigate into the project directory:

   ```bash
   cd html-pricing-comparison-table
   ```

3. Open `index.html` directly in your browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension to preview the page.

No package installation, build process, or development server is required.

## Deployment

The project is hosted using GitHub Pages.

To deploy:

1. Push the project files to the `main` branch of the public GitHub repository.
2. Navigate to the repository's **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` and `/ (root)` as the deployment source.
5. Save the configuration.

GitHub Pages will publish the page.

## Learning Objectives

This project demonstrates an understanding of:

- Structuring a page with semantic elements (`<header>`, `<main>`, `<footer>`).
- Building an accessible data table with `<caption>`, `<thead>`, `<tbody>` and `<tfoot>`.
- Using `scope="col"` and `scope="row"` so screen readers announce cells in context.
- Merging cells with `colspan` for a real reason.
- Setting page metadata correctly in the head.
- Adding SEO and Open Graph metadata for search engines and social sharing.
- Static website hosting using GitHub Pages.

## Author

**Tamarabrakaemi Waritimi**

- GitHub: [@7amarah](https://github.com/7amarah)
- LinkedIn: [Tamarah Waritimi](https://www.linkedin.com/in/tamarah-waritimi-4850bb111)