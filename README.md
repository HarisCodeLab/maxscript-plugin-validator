# MaxScript Plugin Validator

An open-source validation and security toolkit for Autodesk 3ds Max MAXScript plugins.

## Project Status

This project is currently in its initial development stage. The first functional prototype and validation rules are being planned.

## Goal

MaxScript Plugin Validator aims to help developers and users review `.ms`, `.mcr`, and related 3ds Max plugin files before installation.

The planned validator will detect:

- Hard-coded file and installation paths
- Potentially unsafe file operations
- External command execution
- Network and download operations
- Missing referenced files
- Common MAXScript syntax problems
- Installation and packaging issues
- Compatibility risks across 3ds Max 2018–2027

## Planned Features

- Rule-based static script scanner
- Clear severity levels for detected issues
- Human-readable validation reports
- Compatibility recommendations
- Safe and intentionally problematic test samples
- Optional AI-assisted explanations and documentation
- Contributor documentation and validation-rule guidelines

## Six-Month Roadmap

### Month 1
Define the repository structure, validation rules, test samples and documentation.

### Month 2
Implement checks for hard-coded paths, missing files and installation problems.

### Month 3
Add detection for risky file operations, external commands and network access.

### Month 4
Develop compatibility checks for 3ds Max 2018–2027.

### Month 5
Test optional AI-assisted explanations and invite community feedback.

### Month 6
Improve documentation, complete testing and publish the first public release.

## Intended Users

- 3ds Max plugin developers
- MAXScript learners
- Technical artists
- Studios reviewing third-party scripts
- Users who want to inspect plugins before installation

## Contributing

Contribution guidelines will be added as the initial project structure is completed. Suggestions, validation-rule ideas and responsibly prepared test samples will be welcome.

## Licence

An open-source licence will be added before the first public release.

## Maintainer

Created and maintained by HarisCodeLab.
