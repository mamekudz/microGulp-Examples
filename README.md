# microgulp-examples

> **Coming soon — example under development.** This repository is planning scaffolding only. There is no runnable implementation, package, download, install command, test suite or µGulp Ready claim yet.

Practical Gulp examples and reusable building blocks for releases, packaging, documentation and more — with optional µGulp dashboard integration.

Repository: [github.com/mamekudz/microgulp-examples](https://github.com/mamekudz/microgulp-examples)

## Status

Local project scaffolding. The topic folders contain implementation briefs, not runnable examples or released packages. No installation or execution command is claimed until an example has been implemented and tested. Do not treat these folders as a downloadable library.

## Project layout

One repository contains independently runnable example projects. There are no nested Git repositories or submodules. Each completed example will document its own prerequisites, dependency installation, Gulp/CLI commands, expected results and optional µGulp integration.

- [Release management](release-management/README.md) — coming soon
- [Dynamic task names](dynamic-task-names/README.md) — coming soon
- [Build variants](build-variants/README.md) — coming soon
- [Multiple manuals](multi-manuals/README.md) — coming soon
- [Installer pipeline](installer-pipeline/README.md) — coming soon
- [Structured build reports](structured-build-reports/README.md) — coming soon

Within each topic, src/ is reserved for implementation, fixtures/ for synthetic sample inputs, and tests/ for meaningful verification. Root-level task entry points and package manifests are added when implementation begins; there is no fake test command or package version.

## Contribution criteria

- Keep the normal Gulp/CLI path usable without the µGulp application.
- Document tested tool versions, inputs, expected artifacts, a normal run and a meaningful failure case.
- Keep examples independent of private editorial files and author-specific filesystem paths.
- Use original code and synthetic or explicitly licensed fixtures. Preserve third-party notices.
- Add a µGulp Ready badge only after the published requirements have actually been met.
- When an article is published, link it to a tested commit or tag and link the example README back to the article. Do not invent publication URLs.

## Lizenz / License

Original example code and documentation are licensed under the MIT License; see [LICENSE](LICENSE). Third-party dependencies and assets retain their own licenses. This license does not cover the µGulp application or grant permission to copy proprietary company code or other brand assets.

## Deutsch

> **Coming soon — Beispiel in Entwicklung.** Dieses Repository ist derzeit nur ein Planungsgerüst. Es gibt noch keine lauffähige Implementierung, kein Paket, keinen Download, keinen Installationsbefehl, keine Tests und keine Ready-Aussage.

Ein gemeinsames Repository für eigenständig nutzbare Gulp-Beispiele. Aktuell ist nur das lokale Gerüst angelegt; die einzelnen Beispiele sind noch auszuarbeiten. Jedes fertige Beispiel erhält eigene Voraussetzungen, CLI-Aufrufe, erwartete Ergebnisse und Prüfungen. Eine µGulp-Integration ergänzt den normalen Gulp-Ablauf. Artikel werden später mit einem konkreten geprüften Versionsstand verknüpft.
