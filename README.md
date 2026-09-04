# texlyre-grammar-assets

Generated TextMate grammar assets for TeXlyre.

## Build

```sh
npm install
npm run build
```

Generated assets are written to `dist/grammars`.

To include optional grammars(e.g., lilypond):

```sh
npm run build:optional
```

## Release

Bump the version in `package.json`, then run the **Release** workflow from GitHub Actions. It creates the matching `v<version>` tag and GitHub release.

## License

TeXlyre grammar assets are licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). AGPL-3.0-or-later. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

 
 