# PyXploreUI

This repository provides the open-source user interface for **PyXplore**, a Python toolkit designed for whole-pattern expectation maximization (WPEM). It supports X-ray diffraction (XRD) simulation, analysis, and AI-driven structure refinement.

The official WPEM/PyXplore repository is available here:
[https://github.com/Bin-Cao/PyWPEM](https://github.com/Bin-Cao/PyWPEM)

## Components

### RefineUI.html
A locally runnable, single-file HTML interface (English) for the core PyXplore/WPEM pipeline. No installation or backend required — open directly in any modern browser.

**Features:**
- **Background Processing** — configure and generate a complete `WPEM.BackgroundFit` Python script with parameters `lowAngleRange`, `poly_n`, `bac_split`, and `bac_num`; robust file validation with 2θ range checks and a live data preview
- **Lattice Constant Refinement** — step-by-step panels for CIF preprocessing (`WPEM.CIFpreprocess`), X-ray source wavelength selection (Cu/Mo/Co Kα presets or custom), crystal-system-aware lattice parameter constraints, and full `WPEM.XRDfit` parameter configuration
- One-click generation of a complete, copy-pasteable Python script covering the full pipeline: `BackgroundFit → CIFpreprocess → XRDfit`

### RefineUI_CN.html
Identical to `RefineUI.html` in functionality, with all user-facing text, parameter descriptions, tooltips, validation messages, and generated Python code comments fully localized into **Simplified Chinese (简体中文)**. All Python API identifiers, HTML element IDs, and JavaScript logic remain unchanged.

**适用场景：** 适合中文用户直接使用，无需任何安装，在浏览器中本地运行即可操作完整的 XRD 背底处理与晶格常数精修流程。

---

* **...** *(under development)*

## Contribution

Developed by [Bin Cao](https://bin-cao.github.io/).
Contributions are welcome, and I warmly invite collaborators to participate in further development.
