# uv-dist-cust
Repository to track the GU customizations made to the Universal Viewer distribution.

**Note: Universal Viewer is a community-developed open source IIIF viewer available at the following GitHub repo: https://github.com/universalviewer/universalviewer. This repository is for tracking the Georgetown University customizations made to v2.0.2 of the UV distribution files.**

## Customizations
#### Config
Top-level config directory contains the following files:
* **config.json** - Provides alternative default display configurations for instances of UV embedded in DSpace
* **config.no-download.json** - Provides no-download viewer configuration for certain collections in DSpace

### Available fields to customize
* https://github.com/UniversalViewer/universalviewer/blob/master/src/extensions/uv-seadragon-extension/config/en-GB.json

### Themes
The following customizations live under the themes directory:
* **uv-seadragon-extension/theme.css** - Simple change to improve the default sizing for mobile browsing of DSpace-embedded UV
