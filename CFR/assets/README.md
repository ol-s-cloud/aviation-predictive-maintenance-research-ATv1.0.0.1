# Assets

This folder contains all visual assets used in the Commercial Feasibility Report including images, diagrams, charts, and logos.

---

## Folder Structure

```
assets/
├── README.md (this file)
├── diagrams/        # System diagrams, flowcharts, frameworks
├── charts/          # Data visualizations, graphs, charts  
└── logos/           # Company and partner logos
```

---

## File Naming Convention

Use descriptive, lowercase names with hyphens:

**Good examples:**
- `07-competitor-swot-analysis.png`
- `trl-framework-diagram.png`
- `market-size-projection-chart.png`
- `business-model-canvas.png`

**Avoid:**
- `IMG_1234.png`
- `Untitled.png`
- `diagram final FINAL v2.png`

---

## Supported Formats

- **Images:** PNG, JPG, JPEG (PNG preferred for diagrams)
- **Vector graphics:** SVG (recommended for scalable diagrams)
- **Charts:** PNG, SVG

---

## How to Use Assets in Markdown

### Basic Image
```markdown
![Alt text description](../assets/diagrams/filename.png)
```

### Image with Caption
```markdown
![TRL Framework](../assets/diagrams/trl-framework.png)
*Figure 1: Technology Readiness Level Framework*
```

### From Sections Folder
```markdown
![Market Analysis](../assets/charts/market-size.png)
```

### From CFR-Master.md
```markdown
![Business Model](./assets/diagrams/business-model.png)
```

---

## Image Guidelines

**Resolution:**
- Minimum: 1200px width for full-width images
- Charts/diagrams: 800-1200px width
- Logos: Original resolution

**File Size:**
- Keep under 2MB per image
- Optimize images before uploading
- Use compression tools if needed

**Accessibility:**
- Always include descriptive alt text
- Ensure text in images is readable
- Use high contrast for clarity

**Style:**
- Maintain consistent style across all visuals
- Use professional, clean designs
- Ensure brand consistency

---

## Recommended Tools

**Creating Diagrams:**
- [Draw.io](https://draw.io) / [diagrams.net](https://diagrams.net)
- [Lucidchart](https://lucidchart.com)
- [Miro](https://miro.com)
- [Figma](https://figma.com)

**Creating Charts:**
- Excel/Google Sheets
- [Chart.js](https://chartjs.org)
- [Plotly](https://plotly.com)
- Python (matplotlib, seaborn)
- R (ggplot2)

**Image Optimization:**
- [TinyPNG](https://tinypng.com)
- [ImageOptim](https://imageoptim.com)
- [Squoosh](https://squoosh.app)

---

## Asset Checklist

Before adding an asset, ensure:

- [ ] File has descriptive name
- [ ] Image is properly sized and optimized
- [ ] File is in correct subfolder
- [ ] You have rights to use the image
- [ ] Image is referenced in a section file
- [ ] Alt text is descriptive and meaningful

---

*Add subfolders as needed for better organization (e.g., /screenshots, /mockups, /presentations)*