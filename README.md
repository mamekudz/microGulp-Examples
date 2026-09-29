# microGulp-Examples

Public collection of independent µGulp™ example repositories.

Each example is its **own public Git repository**. This collection indexes them as Git submodules so you can clone everything at once, or clone any single example directly.

## Clone all examples

```bash
git clone --recurse-submodules https://github.com/mamekudz/microGulp-Examples.git
cd microGulp-Examples
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Individual repositories

| Example | Repository | Status |
| --- | --- | --- |
| Release management | [microGulp-example-release-management](https://github.com/mamekudz/microGulp-example-release-management) | runnable |
| npm statistics | [microGulp-example-npm-statistics](https://github.com/mamekudz/microGulp-example-npm-statistics) | runnable |
| Dynamic task names | [microGulp-example-dynamic-task-names](https://github.com/mamekudz/microGulp-example-dynamic-task-names) | scaffold |
| Build variants | [microGulp-example-build-variants](https://github.com/mamekudz/microGulp-example-build-variants) | scaffold |
| Multiple manuals | [microGulp-example-multi-manuals](https://github.com/mamekudz/microGulp-example-multi-manuals) | scaffold |

Clone one example only:

```bash
git clone https://github.com/mamekudz/microGulp-example-npm-statistics.git
```

## Pending topics

The folders `installer-pipeline/` and `structured-build-reports/` remain planning scaffolds in this collection. They are **not** independent public child repositories yet.

## Articles

Related µGulp™ articles are published on [microgulp.dev](https://microgulp.dev) when available. Example READMEs link to public article URLs only after publication.

## License

Original collection documentation is under the MIT License; see [LICENSE](LICENSE). Each child repository carries its own license. This does not cover the proprietary µGulp™ application.
