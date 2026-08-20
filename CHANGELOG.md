# nf-gadi changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v1.0.0 - 2024.09.27

Initial release of nf-gadi plugin, created with the [nf-hello](https://github.com/nextflow-io/nf-hello) template.


## v1.0.1 - 2025.02.26

### `Added`
- Added queue node name: Now included in relevant outputs.
- New method to get cached process information: Resolves known issues with process tracking.

### `Fixed`
- Improved stability


## v1.1.0 - 2025.12.11

- Migrated to the new [Nextflow plugin template](https://github.com/nextflow-io/nf-plugin-template) requiring Nextflow >=25.04 and supporting the [Nextflow Plugin Registry](https://registry.nextflow.io/plugins/nf-gadi).


## v1.2.0 - 2026.01.21

### `Fixed`
- Fixed keyword matching for the new Gadi job log format.


## v1.3.0 - 2026.07.23

### `Added`
- Added a function to publish usage report to an external location.


## v1.3.1 - 2026.07.27

### `Fixed`
- Updated the publish function to support closure definitions.


## v1.4.0 - 2026.08.20

### `Fixed`
- Fixed an issue where GPU memory usage was incorrectly reported as CPU memory usage. 