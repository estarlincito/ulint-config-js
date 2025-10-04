# ulint-config-js ⚡

[![NPM version](https://img.shields.io/npm/v/ulint-config-js.svg?style=flat)](https://npmjs.org/package/ulint-config-js)
[![ESM-only](https://img.shields.io/badge/ESM-only-brightgreen?style=flat)](https://nodejs.org/)

> _“JavaScript linting made easy — recommended and strict rules for modern projects.”_

---

## Features ✨

- 📌 **Preconfigured ESLint rules for JavaScript** projects.
- ⚡ Includes **recommended rules** from `@eslint/js`.
- 🛠️ Fully compatible with **ulint** and ESLint CLI.

---

## Installation 📲

```bash
npm install --save-dev ulint ulint-config-js
# or
pnpm add --save-dev ulint ulint-config-js
# or
yarn add --dev ulint ulint-config-js
```

---

## Usage 🎉

Create a `ulint.config.mjs`:

```javaScript
// ulint.config.mjs
import { defineConfig } from 'ulint';
import jsConfig from 'ulint-config-js';

export default defineConfig(jsConfig);
```

Then lint your JavaScript project:

```bash
ulint "src/**/*.js"
```

---

## License 📄

MIT License – see [LICENSE](LICENSE) for details.
**Author:** Estarlin R ([estarlincito.com](https://estarlincito.com))
