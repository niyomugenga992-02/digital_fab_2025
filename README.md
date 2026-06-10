# UR-ACEIoT Student Documentation: CO3 Nameplate Project
## Niyomugenga Grace - Modeling & Fabrication Course

**Live Site:** https://niyomugenga992-02.github.io/digital_fab_2025/

**Repository:** https://github.com/niyomugenga992-02/digital_fab_2025

**Author:** Niyomugenga Grace  
**Program:** MSc in IoT Embedded Computing Systems (ECS)  
**Institution:** University of Rwanda - ACEIoT  
**Course:** Modeling & Fabrication (9-Day Intensive)  
**Project Status:** COMPLETE

---

## 📋 Project Overview

This repository documents **Niyomugenga Grace's** comprehensive digital fabrication journey creating the **CO3 Nameplate** - a professional walnut hardwood nameplate with carved lettering, showcasing the complete design-to-fabrication workflow.

### Final Product Specifications

| Specification | Value |
|---------------|-------|
| **Material** | American Black Walnut Hardwood |
| **Dimensions** | 150mm (W) × 90mm (H) × 10mm (T) |
| **Letter Depth** | 4mm carved pockets |
| **Design** | Oval base with vertically-stacked "CO3" letters |
| **Surface Finish** | Satin polyurethane (3 coats) |
| **Grain Enhancement** | Dark walnut oil stain |
| **Manufacturing Process** | CAD → Laser Template → 3D Prototype → CNC Milling → Hand Finishing |
| **Total Project Cost** | $34.42 USD |
| **Active Work Time** | ~15 hours |
| **Total Timeline** | 9 days (including drying/curing) |

### Technologies & Tools Used

**Design & Modeling:**
- FreeCAD (parametric 3D CAD)
- Fusion 360 (CAM programming)
- STEP, STL, DXF file formats

**Fabrication Methods:**
- Laser cutting (CO₂ laser, cardboard validation template)
- 3D printing (FDM/Ultimaker, PLA prototype)
- CNC routing (3-axis subtractive manufacturing, walnut final)
- Hand finishing (sanding, staining, sealing)

**Digital Tools:**
- Git & GitHub (version control)
- GitHub Actions (CI/CD automation)
- MkDocs (documentation)

---

## 🎯 Key Achievements

**Day 1:** Concept development and project planning  
**Day 2:** Production-ready CAD model with tolerances  
**Day 3:** Technical drawings & quality control documentation  
**Day 4:** Material selection & testing (walnut chosen)  
**Day 5:** Laser-cut cardboard validation template  
**Day 6:** FDM-printed PLA prototype for depth testing  
**Day 7:** CNC-milled walnut nameplate (42 minutes, ±0.1mm tolerance)  
**Day 8:** Professional finishing (sanded, stained, sealed)  
**Day 9:** Complete project documentation & presentation  

---

## 🌐 Website Features

- **Responsive Design:** Mobile-friendly documentation site
- **Dark Theme:** Dark header/footer (#021736) with Material Design
- **Interactive Navigation:** Tab-based navigation with expandable sections
- **Image Gallery:** Glightbox image lightbox for project photos
- **Auto-Deployment:** GitHub Actions builds and deploys on every push
- **Search Functionality:** Full-text search across all documentation
- **Git Integration:** Last revision dates automatically tracked
- **Custom Styling:** Dark professional theme with enhanced readability

---

## 🚀 Getting Started

### Prerequisites
* **Python 3.11+** - Required for MkDocs
* **Git** - For version control and cloning the repository
* **Optional:** Node.js (for advanced customization)

### Quick Setup (Local Development)

1. **Clone the repository**
   ```bash
   git clone https://github.com/niyomugenga992-02/digital_fab_2025.git
   cd digital_fab_2025
   ```

2. **Create and activate virtual environment**
   ```bash
   # Windows
   python -m venv .venv
   .venv\Scripts\activate
   
   # Mac/Linux
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**readme
   ```bash
   pip install -r requirements.txt
   ```

4. **Run development server**
   ```bash
   mkdocs serve
   ```
   The site will be available at: `http://127.0.0.1:8000/`

5. **Make edits and preview live**
   - Edit markdown files in `docs/Daily-Activity/`
   - Changes appear instantly in your browser (hot reload)
   - No rebuild necessary!

### Deploy to GitHub Pages

The site automatically deploys via GitHub Actions. To publish your changes:

```bash
# Make your edits
git add .
git commit -m "Update documentation"
git push origin main

# GitHub Actions automatically builds and deploys
# Site is live within 2-3 minutes at:
# https://niyomugenga992-02.github.io/digital_fab_2025/
```

---

## 📚 Documentation Structure

### Day-by-Day Learning Path

| Day | Topic | Key Skills | Output |
|-----|-------|-----------|--------|
| **Day 1** | Foundations & CO3 Concept | Design thinking, sketching, iteration | Concept sketches, project brief |
| **Day 2** | Digital Modeling (FreeCAD) | CAD, parametric constraints, DFM | STEP/STL/DXF files, 3D model |
| **Day 3** | Technical Documentation | Engineering drawings, QC, BOM | Technical drawings, inspection plan |
| **Day 4** | Materials & Fabrication | Material science, CNC parameters | Material selection report |
| **Day 5** | Laser Cutting | File preparation, laser safety | Cardboard validation template |
| **Day 6** | 3D Printing (FDM) | Slicing, print settings, post-processing | PLA prototype (validation) |
| **Day 7** | CNC Milling | CAM, toolpaths, feeds/speeds | Final walnut nameplate (raw) |
| **Day 8** | Finishing Techniques | Sanding, staining, sealing | Finished walnut nameplate |
| **Day 9** | Final Presentation | Documentation, reflection, portfolio | Complete project package |

### Project Files Organization

```
Niyomugenga-URACEIoT/
├── .github/
│   └── workflows/
│       ├── ci.yml              # CI/CD pipeline
│       └── mkdocs.yml          # Auto-deployment to GitHub Pages
├── docs/
│   ├── index.md                # Homepage with bio
│   ├── Daily-Activity/
│   │   ├── index.md            # Daily activities overview
│   │   ├── day_1.md - day_9.md # 9-day detailed documentation
│   ├── images/
│   │   ├── day_1/ through day_9/  # Project photos by day
│   │   ├── home/               # Homepage images
│   │   └── all images/         # Complete photo archive
│   └── stylesheets/
│       └── extra.css           # Custom dark theme styling
├── site/                       # Auto-generated static site (git ignored)
├── .venv/                      # Python virtual environment (git ignored)
├── mkdocs.yml                  # Site configuration & navigation
├── requirements.txt            # Python dependencies
├── .gitignore                  # Excluded files
└── README.md                   # This file
```

---

## 🎨 Customization & Features

### Features

* **Automatic Publishing** - GitHub Actions builds and deploys on every commit
* **Live Editing** - MkDocs serve provides instant preview with hot reload
* **Professional Theme** - Material for MkDocs with custom dark color scheme
* **Responsive Design** - Mobile-optimized documentation site
* **Image Gallery** - Glightbox lightbox for project photos
* **Search** - Full-text search across all pages
* **Navigation** - Tab-based UI with expandable sections
* **Git Integration** - Auto-tracked revision history

### Customizing the Site

#### Change Theme Colors
Edit `mkdocs.yml`:
```bash
# Make your edits
git add .
git commit -m "Update documentation"
git push origin main

# GitHub Actions automatically builds and deploys
# Site is live within 2-3 minutes at:
# https://niyomugenga992-02.github.io/digital_fab_2025/
```
- Typography and spacing
- Responsive breakpoints
- Animation effects

#### Update Navigation
Edit `mkdocs.yml` nav section:
```yaml
nav:
  - Home: index.md
  - New Page: new-page.md
  - Section:
    - Subsection: path/to/page.md
```

#### Add New Documentation Pages
1. Create markdown file: `docs/my-page.md`
2. Add to navigation in `mkdocs.yml`
3. Push to GitHub - auto-deployment handles the rest!

### Current Color Scheme

- **Header Background:** Dark Navy (#021736)
- **Footer Background:** Dark Navy (#021736)
- **Text (Header):** White (#FFFFFF)
- **Active Link:** Light (#FFFFFF)
- **Primary Accent:** Blue
- **Secondary Accent:** Light Blue

---

## 🛠 Troubleshooting

### MkDocs Build Errors
```bash
# Clean and rebuild
rm -r site/
mkdocs build

# Check dependencies
pip install -r requirements.txt --upgrade
```

### Plugin Issues
```bash
# Ensure all plugins installed
pip install mkdocs-material mkdocs-glightbox mkdocs-git-revision-date-plugin
```

### GitHub Pages Not Updating
1. Check GitHub Actions tab for build errors
2. Verify branch is set to `main`
3. Ensure `.github/workflows/mkdocs.yml` exists
4. Wait 2-3 minutes for deployment

---

## 📊 Project Specifications & Metrics

### CO3 Nameplate Final Dimensions

| Feature | Target | Achieved | Tolerance | Status |
|---------|--------|----------|-----------|--------|
| Overall Length | 150.0 mm | 150.1 mm | ±0.1 mm |  Pass |
| Overall Width | 90.0 mm | 89.9 mm | ±0.1 mm |  Pass |
| Thickness | 10.0 mm | 10.0 mm | 0.0 mm |  Pass |
| Letter "C" Depth | 4.0 mm | 4.0 mm | 0.0 mm |  Pass |
| Letter "O" Depth | 4.0 mm | 3.9 mm | ±0.1 mm |  Pass |
| Letter "3" Depth | 4.0 mm | 4.0 mm | 0.0 mm |  Pass |

### Materials Used

- **Primary:** American Black Walnut (160×100×12mm blank, $20)
- **Finish:** Dark walnut stain + satin polyurethane ($12)
- **Prototypes:** Cardboard ($0.50) + PLA filament ($1.92)
- **Total Cost:** $34.42

### Manufacturing Time Breakdown

- **CAD Modeling:** 3 hours
- **Fabrication Planning:** 1.5 hours
- **Laser Cutting:** 2 minutes (cardboard)
- **3D Printing:** 2h 47 minutes (PLA)
- **CNC Milling:** 42 minutes (walnut)
- **Hand Finishing:** 1 hour active + 30 hours curing
- **Documentation:** 2 hours
- **Total:** 47.7 hours (15 hours active)

---

## 📖 Resources & References

**Documentation Platforms:**
- [MkDocs Official Docs](https://www.mkdocs.org)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

**Digital Fabrication:**
- [UR-ACEIoT Home](https://fablabrwanda.github.io/UR-ACEIoT/)
- [Kigali FabLab](https://instagram.com/fablab_rwanda)

**Learning Resources:**
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Actions Docs](https://docs.github.com/en/actions)
- [FreeCAD Manual](https://wiki.freecadweb.org/Manual)

---

## 📞 Contact & Social

**Student:** Niyomugenga Grace  
**Email:** Available upon request  
**Social Media:**
- Instagram: [@fablab_rwanda](https://instagram.com/fablab_rwanda)
- Facebook: [KigaliFabLab](https://facebook.com/KigaliFabLab)
- Twitter: [@fablabrw](https://twitter.com/fablabrw)

---

## 📄 License & Attribution

This project documentation is created for educational purposes as part of the **UR-ACEIoT Modeling & Fabrication Course**.

**License:** Creative Commons Attribution Non-commercial (CC BY-NC)  
**Author:** Niyomugenga Grace  
**Year:** 2026  
**Institution:** University of Rwanda - ACEIoT

---

##  Verification Checklist

- [x] Project completed on schedule (9 days)
- [x] All deliverables documented with photos
- [x] Technical specifications verified (±0.1mm achieved)
- [x] Final product within specifications
- [x] Documentation site live and functional
- [x] GitHub Actions CI/CD working
- [x] Custom dark theme applied
- [x] All 9 days documented in detail
- [x] README comprehensive and complete
- [x] Project ready for portfolio/showcase

---

**Last Updated:** January 31, 2026  
**Status:** COMPLETE AND DEPLOYED

🎉 **The CO3 Nameplate Project is LIVE!**  
Visit https://niyomugenga992-02.github.io/digital_fab_2025/ to explore the full documentation.
