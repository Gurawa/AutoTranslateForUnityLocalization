# Auto Translate for Unity Localization

## Release 0.5.0 - Mar 2026

Getting Started:

- Overview
- Installation
- Quick Start
- Requirements
- Warnings

## Overview

This guide provides a basic overview of the main features and setup flow for Auto Translate for Unity Localization.

## Installation

You can install the package through Unity Package Manager using this Git URL:

`https://github.com/Gurawa/AutoTranslateForUnityLocalization.git?path=/Assets`

If you are using a `.unitypackage`, import it through `Assets -> Import Package -> Custom Package...`, verify the included files, and then confirm the import.

## Quick Start

Use `Auto Localization/Auto Translate for String Tables` to open the main translation window.

Other available menu entries include:

- `Auto Localization/Search Text in Scene or Prefab`
- `Auto Localization/Search Text in Scenes`
- `Auto Localization/Search Text in Prefabs`
- `Auto Localization/Search Audio`
- `Auto Localization/Search Texture`
- `Auto Localization/Clean up Localization in Scenes`
- `Auto Localization/Clean up Localization in Prefabs`

## Requirements

This package expects Unity Localization and Addressables to be available in the project.

Current package dependencies:

- Localization `1.4.5`
- Addressables `1.21.21`
- TextMeshPro `3.0.6`

Recommended Unity version:

- Unity `2023.2` or newer in the current package configuration.

## Warnings

The package still has some known limitations:

- Disabled objects are not included in text search results.
- Some checklist selection workflows may still behave inconsistently.
- Translation or search results may not be saved if the project is closed before the operation finishes.
