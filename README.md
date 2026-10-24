# Web Toolkit

A growing collection of practical browser-based tools, reusable website components, and small web experiments. The goal is to make everyday digital tasks easier with lightweight tools built with HTML, CSS, and JavaScript.

> **Repository name:** This project is being organized as **Web Toolkit**. The repository URL may still contain `Website-Elements` until the repository name is changed in GitHub settings.

## What's inside

- **Browser tools:** standalone utilities for text cleanup, image metadata reduction, and other everyday tasks.
- **Website components:** reusable interface patterns such as buttons, cards, navigation, forms, and menus.
- **CSS and visual experiments:** animations, gradients, transitions, and visual effects.
- **Future utilities:** room for formatters, converters, generators, and other small productivity tools.

## Tools

| Tool | What it does | Link |
|---|---|---|
| **Advanced Text Cleaner Pro** | Cleans pasted text with options for whitespace, blank lines, zero-width characters, curly quotes, dash normalization, and removing a chosen phrase. Includes copy and TXT download. | [Open tool](./Tools/Advanced-Text-Cleaner-Pro/index.html) |
| **PureMeta** | Re-encodes JPG, PNG, and WebP images in the browser to create copies that generally omit embedded metadata. Includes basic file information and individual downloads. | [Open tool](./Tools/PureMeta/index.html) |

### Important notes about PureMeta

- This version supports JPG, PNG, and WebP images.
- It shows basic browser-visible file properties, not a complete EXIF/IPTC/XMP tag inspector.
- Re-encoding can change image quality, especially for JPEGs.
- Verify the output file before sharing it. Do not treat this tool as a forensic metadata audit.

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

This is a flexible structure, not a strict requirement. Keep each substantial tool or experiment in its own folder with descriptive filenames and any assets it needs.

## Running a tool locally

1. Open its `index.html` file in a modern browser.
2. If a tool uses third-party libraries from a CDN, an internet connection may be required.
3. Review each tool's privacy notes before processing sensitive content.

These tools are static browser pages, so no build step or package installation is generally required.

## Adding a new tool or component

1. Create a descriptive folder under `Tools/`, `Website-Components/`, or the most relevant category.
2. Add an `index.html` entry point and keep related CSS, JavaScript, and assets together.
3. Add a short project-specific README when setup, dependencies, limitations, or usage need explanation.
4. Test on desktop and mobile, and check keyboard accessibility.
5. Add the tool to the table above when publishing it.

## Quality and privacy guidelines

- Prefer simple, readable HTML, CSS, and JavaScript.
- Make layouts responsive and controls keyboard accessible.
- Explain supported formats, dependencies, and limitations accurately.
- Only claim that data stays local when the implementation has been checked to confirm it.
- Never include passwords, API keys, private data, or assets you do not have permission to share.
- Document third-party libraries and important dependencies where practical.

## Previewing HTML on GitHub

GitHub displays HTML source rather than running it as a webpage. For a quick preview, use [HTMLPreview](https://htmlpreview.github.io/) with a raw GitHub file URL. For a more reliable public demo, consider publishing static files with GitHub Pages.

## License

Check the repository's `LICENSE` file before reusing code. If no license is present, do not assume that public visibility grants permission to reuse or redistribute the contents.
