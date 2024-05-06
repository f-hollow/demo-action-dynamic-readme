# Dynamic Readme - **Github Action** Demo

[![.github/workflows/dynamic-template.yml](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml/badge.svg)](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml)

[![.github/workflows/dynamic-template.yml](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml/badge.svg)](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml)

This repo contains some workflows to update README.

- `update-readme.yml` appends data from a file to README and commits it. This is a very simple workflow created as a proof of concept. It needs many improvements to be useful, such as replacing actual markers instead of appending the same data over and over.
- `.github/workflows/dynamic-template.yml` is a third-party solution called [Dynamic Readme](https://github.com/marketplace/actions/dynamic-readme) to make READMEs "dynamic". It works but it seems like the project is not actively maintained. The table below is replaced with a new one from `templates/tables/table.md` on every push.

<!-- START ./tables/table.md -->
| One | Two | Three |
| --- | --- | --- |
| One | Two | Three |

<!-- END ./tables/table.md -->
