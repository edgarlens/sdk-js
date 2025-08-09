# Edgar Lens JavaScript SDK

Official JavaScript/TypeScript SDK for the Edgar Lens API.

## Features
- Strongly typed models (TypeScript)
- Pagination & retries
- Works in Node.js and modern browsers

## Installation
```bash
npm install @edgarlens/sdk
# or
yarn add @edgarlens/sdk
# or
pnpm add @edgarlens/sdk
```

## Quick Start
```ts
import { EdgarLens } from '@edgarlens/sdk';

const client = new EdgarLens({ apiKey: process.env.EDGARLENS_API_KEY! });

const diffs = await client.diffs.get({ ticker: 'AAPL' });
console.log(diffs);
```

## Examples
See `/examples` for usage patterns (Node, browser, Next.js).

## Versioning
Follows the API's semantic versioning. Breaking API changes bump the major version.

## License
MIT — see [LICENSE](LICENSE).
