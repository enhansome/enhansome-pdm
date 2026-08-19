# Awesome PDM with stars

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![PDM](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fpdm-project%2F.github%2Fbadge.json\&style=flat-square)](https://pdm-project.org)

> A curated list of awesome PDM plugins and resources

## Plugins

* [pdm-packer](https://github.com/frostming/pdm-packer) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - A PDM plugin that packs your packages into a zipapp
* [pdm-bump](https://github.com/carstencodes/pdm-bump) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2026-08-18 - A PDM plugin that behaves like [bump2version](https://github.com/c4urself/bump2version) ⭐ 1,115 | 🐛 115 | 🌐 Python | 📅 2025-02-20 relying on PEP440 compliant versions
* [pdm-plugin-torch](https://github.com/EmbarkStudios/pdm-plugin-torch) ⚠️ Archived - A utility tool for selecting torch backend and version
* [pdm-conda](https://github.com/macro128/pdm-conda) ⚠️ Archived - A PDM plugin to install project dependencies with [Conda](https://docs.conda.io/projects/conda/en/latest/index.html)
* [sync-pre-commit-lock](https://github.com/GabDug/sync-pre-commit-lock) ⭐ 29 | 🐛 5 | 🌐 Python | 📅 2026-08-15 - A PDM plugin to ease your life with `pre-commit` (automatic install, sync)
* [pdm-vscode](https://github.com/frostming/pdm-vscode) ⚠️ Archived - A PDM plugin that autogenerates workspace vscode settings for you
* [pdm-dockerize](https://github.com/noirbizarre/pdm-dockerize) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2026-08-01 - A PDM plugin to help generating docker images from PDM projects
* [pdm-shear](https://github.com/pdm-project/pdm-shear) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2025-04-05 - Detect and remove unused dependencies for Python projects
* [pdm-download](https://github.com/pdm-project/pdm-download) ⭐ 16 | 🐛 4 | 🌐 Python | 📅 2024-07-18 - A PDM plugin to download all packages in a lockfile for offline use
* [pdm-autoexport](https://github.com/frostming/pdm-autoexport) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-09-06 - A PDM plugin to sync the exported files with the project file
* [pdm-dotenv](https://github.com/znd4/pdm-dotenv) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2026-04-27 - A PDM plugin that loads `.env` files
* [pdm-shell](https://github.com/abersheeran/pdm-shell) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-11-24 - Use `pdm shell` set PATH and PYTHONPATH in the current shell
* [pdm-sbom](https://github.com/carstencodes/pdm-sbom) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-02-02 - A PDM plugin that generates Software Bill of Materials as [SPDX](https://spdx.org), [CycloneDX](https://cyclonedx.org) and [JFrog build info](https://buildinfo.org) from `pdm.lock`.
* [pdm-wheel](https://github.com/GabDug/pdm-wheel) ⭐ 9 | 🐛 5 | 🌐 Python | 📅 2026-08-17 - A PDM plugin to export your dependencies wheels, mainly for CI and deployments
* [pdm-version](https://github.com/abersheeran/pdm-version) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-11-27 - Make `pdm version` like `poetry version`
* [pdm-multirun](https://github.com/pawamoy/pdm-multirun) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-07-02 - A PDM plugin to run a command on multiple Python versions
* [pdm-build-locked](https://github.com/sigma67/pdm-build-locked) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-11-30 - A PDM plugin to add locked packages as additional optional dependency groups to the distribution metadata on build
* [pdm-readiness](https://github.com/andriykohut/pdm-readiness) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-08-14 - A PDM plugin to check if your project dependencies support specified Python version
* [pdm-django](https://github.com/neutron-sync/pdm-django/) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2023-04-10 - `pdm manage` and `pdm django-admin` shortcuts for Django commands
* [pdm-audit](https://github.com/carstencodes/pdm-audit) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-08-18 - A PDM plugin that hooks into the installation end executes [pip-audit](https://github.com/pypa/pip-audit) ⭐ 1,347 | 🐛 69 | 🌐 Python | 📅 2026-08-12 right after installation or manually
* [pdm-pip-index-url](https://github.com/theredfoxlee/pdm-pip-index-url) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2023-06-18 - A PDM plugin that automatically converts `PIP_*INDEX_URL` to `PDM_PYPI_*` envs

## Eco-system

* [setup-pdm](https://github.com/pdm-project/setup-pdm) ⭐ 96 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-13 - A GitHub Action that installs pdm properly for all Python versions
* [copier-pdm](https://github.com/pawamoy/copier-pdm) ⭐ 92 | 🐛 1 | 🌐 Jinja | 📅 2024-12-04 - Another Copier template for Python projects managed by PDM
* [copier-pdm](https://github.com/pdm-project/copier-pdm) ⭐ 31 | 🐛 1 | 🌐 Jinja | 📅 2024-02-20 - A Copier template for PDM projects
* [tox-pdm](https://github.com/pdm-project/tox-pdm) ⭐ 26 | 🐛 7 | 🌐 Python | 📅 2026-08-17 - A plugin for tox that utilizes PDM as the package manager and installer
* [Mina](https://github.com/GreyElaina/Mina) ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2024-10-11 - a monorepo-like implementation, which act as a hacking agent of `pdm-pep517`
* [pdm-ci](https://github.com/Seven45/pdm-ci) ⭐ 10 | 🐛 1 | 🌐 Dockerfile | 📅 2026-08-18 - A docker image for usage in multistage builds or gitlab-ci
* [sync\_with\_pdm](https://github.com/floatingpurr/sync_with_pdm) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-08-17 - a `pre-commit` hook to keep PDM-managed packages and pre-commit hooks in sync
* [cookiecutter-pdm-pypackage](https://github.com/Aviksaikat/cookiecutter-pdm-pypackage) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-05-31 - A cookiecutter pdm pypackage template with ruff, mkdocs, precommit-hooks, github actions and more
* [VSCode PDM Task Provider](https://marketplace.visualstudio.com/items?itemName=knowsuchagency.pdm-task-provider) - VSCode Task provider for PDM
* [update-deps-action](https://github.com/marketplace/actions/pdm-update-dependencies) - A GitHub Action to update the pdm lockfile

## Articles

* [PDM: A smarter way to manage Python packages](https://www.infoworld.com/article/3654196/pdm-a-smarter-way-to-manage-python-packages.html) - Info World - 2022/03
* [A Review: Pipenv vs. Poetry vs. PDM](https://frostming.com/2021/03-26/pm-review-2021/) - Frost Ming - 2021/03
* [You don't really need a virtualenv](https://frostming.com/2021/01-22/introducing-pdm/) - Frost Ming - 2021/01
* [PDM - 一款新的 Python 包管理器](https://frostming.com/2020/02-28/pdm-introduction/) (Chinese) - Frost Ming - 2020/02

## Videos

* [How To Use PDM...](https://youtu.be/qOIWNSTYfcc) - Ian Wootten - 2022/03

## Gists

* [Automatic dependency updates with PDM](https://gist.github.com/carstencodes/bdf6c1664f49f387b6994a02965e787c) - Carsten Igel (@carstencodes) - 2022/02

## Slides & Talks

* [基于 PEP 582 的包管理器](https://slides.fming.dev/pep582/) (Chinese) - Frost Ming - 2020/05

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
