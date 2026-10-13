# EAF Melt Shop KPIs

A single-page website for the EAF Melt Shop: chemistry dispositions by crew, out-of-spec chemistry, furnace and caster operator spec performance, and billet production vs plan.

Open `index.html` in a browser, or view it on GitHub Pages. The data inside is a saved copy of the monthly Chemistry and Billet Excel reports (May–October 2026).

## Adding newer reports

Click **Import Excel** (or drag the files or a whole folder onto the page) and pick the monthly reports:

- `Melt Shop Chemistry Results Report <Month> <Year>.xlsx`
- `VT_STEEL_Production and Shipments_Template <Month> <Year>.xlsx`

The files are read in your browser and never uploaded anywhere. Imported months replace those months on every page and stay in that browser until you click **Remove import**. Files that aren't one of these reports, or that can't be read, are listed and skipped.

To change what everyone sees, click **Download updated site** and replace `index.html` in this repository with the downloaded file.
