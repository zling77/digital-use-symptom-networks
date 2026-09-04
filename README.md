# Emotional distress predicts change in adolescent problematic digital use and related symptoms

This is a reviewer-facing paper website built with Astro and configured for GitHub Pages under:

```text
https://zling77.github.io/digital-use-symptom-networks/
```

The public page and downloadable manuscript were synchronised with the author-supplied
submission materials on 4 September 2026. The website is public and is not an
anonymous review repository.

The downloadable archives were refreshed from the cleaned submission package on
4 September 2026: the main analysis archive contains 105 files, the external
validation archive contains 21 files, and Supplementary Data 1 contains 23 files.
The archives include analysis code and non-identifiable aggregate results, not
individual-level participant datasets. The external figure helper now uses the
SEARCH CIAS value for problematic digital use, rather than the ACT value.

## Local Development

```bash
npm install
npm run dev
```

Open:

```text
http://localhost:4321/digital-use-symptom-networks/
```

## Build

```bash
npm run build
```

## Deploy

The repository includes `.github/workflows/deploy.yml`. After pushing to `main`, enable GitHub Pages with **Settings -> Pages -> Build and deployment -> GitHub Actions**.

## Content

- Main site content: `src/pages/index.astro`
- Main and supplementary figures: `public/figures/`
- Manuscript: `public/Manuscript.pdf` and `public/Manuscript.docx`
- Supplementary Information: `public/Supplementary_Information.pdf`
- Machine-readable results: `public/Supplementary_Data_1.zip`
- Analysis code: `public/04_Code_Main.zip` and `public/06_External_validation_code_GMP_MCS.zip`

The abstract is reproduced from the current manuscript. Figure summaries follow
the same figure numbering and numerical results. Supplementary Data 1 contains
23 machine-readable result files. Individual-level participant data, cover letters,
reporting-summary drafts and internal submission checklists are not published here.
