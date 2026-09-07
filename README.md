# hooksmith

A handful of React hooks I keep copy-pasting between projects

Side project, maintained when I have time.

## Features

- Tiny: no dependencies besides React
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization

## Getting started

```bash
npm install
npm test
```

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
