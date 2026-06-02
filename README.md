[![Docs][docs-src]][docs-href]
[![Release][release-src]][release-href]
[![npm version][npm-version-src]][npm-version-href]
[![License][license-src]][license-href]

My preferred commitlint config.

It matches the [`@commitlint/config-conventional`](https://www.npmjs.com/package/@commitlint/config-conventional) config pretty closely, except the types are extracted straight from my semantic release config [`@alanscodelog/semantic-release-config`](https://github.com/AlansCodeLog/semantic-release-config) (which should be installed as a peer dependency) and the max header length is set to 100 (and that is only set to warn).


# Install
```bash
pnpm add -D @alanscodelog/commitlint-config @alanscodelog/semantic-release-config
```

```json
// package.json
{
	"commitlint": { "extends": [ "@alanscodelog/commitlint-config" ] },
	// OR
	"commitlint": { "extends": [ "@alanscodelog" ] },
}
```

<!-- Badges -->
[docs-src]: https://github.com/alanscodelog/commitlint-config/actions/workflows/docs.yml/badge.svg
[docs-href]: https://github.com/alanscodelog/commitlint-config/actions/workflows/docs.yml
[release-src]: https://github.com/alanscodelog/commitlint-config/actions/workflows/release.yml/badge.svg
[release-href]: https://github.com/alanscodelog/commitlint-config/actions/workflows/release.yml
[npm-version-src]: https://img.shields.io/npm/v/@alanscodelog/commitlint-config/latest
[npm-version-href]: https://www.npmjs.com/package/@alanscodelog/commitlint-config/v/latest
[license-src]: https://img.shields.io/npm/l/@alanscodelog/commitlint-config.svg?style=flat&colorA=020420&colorB=00DC82
[license-href]: https://npmjs.com/package/@alanscodelog/commitlint-config
