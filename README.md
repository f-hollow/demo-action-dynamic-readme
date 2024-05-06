# Dynamic Readme - **Github Action** Demo

[![.github/workflows/dynamic-template.yml](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml/badge.svg)](https://github.com/f-hollow/demo-action-dynamic-readme/actions/workflows/dynamic-template.yml)

This repo contains some workflows to update README.

- `update-readme.yml` appends data from a file to README and commits it. This is a very simple workflow created as a proof of concept. It needs many improvements to be useful, such as replacing actual markers instead of appending the same data over and over.
- `.github/workflows/dynamic-template.yml` is a third-party solution called [Dynamic Readme](https://github.com/marketplace/actions/dynamic-readme) to make READMEs "dynamic". It works but it seems like the project is not actively maintained. The table below is replaced with a new one from `templates/tables/table.md` on every push.

<!-- START ./tables/table.md -->
| One | Two | Three |
| --- | --- | --- |
| One | Two | Three |

<!-- END ./tables/table.md -->

Alerts

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
