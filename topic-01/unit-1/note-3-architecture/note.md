---
icon:
  type: flat-color-icons:library
---

## Tutors Architecture

A tour of the Tutors Reader source

The Tutors Reader is a [SvelteKit](https://kit.svelte.dev/) web application, packaged as a single source repository:

- <https://github.com/tutors-sdk/tutors>

The top level perspective the application is structure these top level components: 

- Lib: Tutors Components
- Routes: Tutors Applications

![](https://tutors.dev/design/top-level.png)

This is mirrored precisely in the source folder structure:

![](img/repo.png)

The Tutors Lib components consists of two sub systems:

- Services: containing the core tutors models, types and utilities
- Ui: package containing the ui components used by the Tutors Applications

![](https://tutors.dev/design/main-modules.png)

Looking deep

![](https://tutors.dev/design/module-detail.png)

