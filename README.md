# react-utility-hooks

A handful of React hooks I keep copy-pasting between projects

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## What it does

- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- Tiny: no dependencies besides React

## Getting started

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```
