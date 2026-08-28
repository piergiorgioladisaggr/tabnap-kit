# tabnap-kit

Chrome extension that tracks reading time per tab

## What it does

- Manifest V3, service worker based
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   └── usage.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## License

MIT - see [LICENSE](LICENSE).
