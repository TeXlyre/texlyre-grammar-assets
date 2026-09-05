# Third-party grammar sources

The release generator follows the source set used by TeXlyre v0.11.0.

| Bundle | Upstream | License declared by TeXlyre downloader |
|---|---|---|
| SILE | `sile-typesetter/vscode-sile` | MIT |
| Org | `vscode-org-mode/vscode-org-mode` | AGPL-3.0 |
| PreTeXt | `PreTeXtBook/pretext-tools` | MIT |
| ConTeXt | `pgundlach/context.tmbundle` | CC0-1.0 |
| AsciiDoc | `asciidoctor/asciidoctor-vscode` | MIT |
| Quarto, DOT, Mermaid | `quarto-dev/quarto` | MIT |
| XML, Lua, Julia, Markdown, R, CSS, HTML, Java, JavaScript, JSON, Python, Shell, SQL, YAML | `microsoft/vscode` | MIT |
| TeX | `jlelong/vscode-latex-basics` | MIT |
| LilyPond (optional) | `jeandeaual/vscode-lilypond-syntax` | CC BY-NC 3.0 |

The default release does **not** include LilyPond. It is only generated when `--include-optional` / `npm run build:optional` is explicitly used.

The generated bundle includes upstream license files alongside grammar assets according to TeXlyre's downloader behavior. Review the individual license files before redistributing the generated bundle.
