# Web Toolkit

A growing collection of practical browser-based tools, reusable website components, and small web experiments. The goal is to make everyday digital tasks easier with lightweight, accessible tools built with web technologies.

> **Repository rename:** This README uses the new project name, **Web Toolkit**. The GitHub repository URL may still contain `Website-Elements` until the repository itself is renamed in GitHub settings.

## What's inside

- **HTML Tools:** standalone utilities that run in the browser, including metadata inspection/removal and text cleaning.
- **Website Components:** reusable interface patterns such as buttons, cards, navigation, forms, and menus.
- **CSS & Visual Experiments:** animations, gradients, transitions, and visual effects.
- **Future Utilities:** room for formatters, converters, generators, and other small productivity tools.

## Tools

| Tool | Description | Location |
|---|---|---|
| **Advanced Text Cleaner Pro** | Clean and normalize pasted text using configurable cleanup options before copying the result. | [Open tool](./Tools/Advanced-Text-Cleaner-Pro/index.html) |
| **PureMeta Metadata Remover** | Inspect image metadata, review GPS and EXIF details, and export cleaned images. Processing is designed to happen in the browser. | [Open tool](./Tools/PureMeta/index.html) |

Tool features and supported file formats may vary by tool. Check each tool's page for its current capabilities and limitations.

## Project structure

```text
Web-Toolkit/
├── README.md
├── Tools/
│   ├── Advanced-Text-Cleaner-Pro/
│   │   └── index.html
│   └── PureMeta/
│       └── index.html
├── Website-Components/
│   └── component-name/
├── CSS-Experiments/
│   └── experiment-name/
└── Visual-Experiments/
    └── experiment-name/
```

This is a suggested structure, not a strict rule. Keep each substantial tool or experiment in its own folder with descriptive filenames and any assets it needs.

## Running a tool locally

1. Open the tool's `index.html` file in a modern browser.
2. If the tool relies on third-party libraries loaded from a CDN, an internet connection may be required.
3. Use the controls provided by the tool, and review its privacy notes before processing sensitive content.

These are static browser tools, so a build step or package installation is generally not required unless a project-specific README says otherwise.

## Adding a new tool or component

1. Create a descriptive folder under `Tools/`, `Website-Components/`, or the most relevant category.
2. Include an `index.html` entry point and keep related CSS, JavaScript, and assets together.
3. Add a short README when setup, dependencies, limitations, or usage need explanation.
4. Test the tool on desktop and mobile, and check keyboard accessibility.
5. Add a row to the **Tools** table above when publishing a new tool.

## Quality guidelines

- Prefer simple, readable HTML, CSS, and JavaScript.
- Make layouts responsive and controls keyboard accessible.
- Explain what each tool does and what it does not do.
- Do not claim that data stays local unless the implementation has been checked to confirm it.
- Never include passwords, API keys, private data, or assets without permission.
- Pin or document important third-party dependencies where practical.

## Previewing HTML on GitHub

GitHub displays HTML source rather than running it as a webpage. For a quick preview, you can use [HTMLPreview](https://htmlpreview.github.io/) with a raw GitHub file URL. For a more reliable public demo, consider publishing static files with GitHub Pages.

## License

Check the repository's `LICENSE` file before reusing code. If no license is present, do not assume that public visibility grants permission to reuse or redistribute the contents.
