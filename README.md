<p align="center">
  <img src="https://github.com/kieler/JutilS/assets/10957098/981b567f-11c7-47d2-9dc6-b5af01c3114e" width="200"/>
</p>

# Kieler JutilS \[ˈjuːtɪlz\]
Collection of utilities used by various Kieler tools. The utilities are published in individual npm packages.

## List of utilities


| package | version | Description | 
---|---|---
| [table-webview](https://www.npmjs.com/package/@kieler/table-webview) | [![npm version](https://badge.fury.io/js/@kieler%2Ftable-webview.svg)](https://badge.fury.io/js/@kieler%2Ftable-webview) | Generic table view for use in VS Code extensions. |


## Releasing Packages
The repository houses multiple packages that can be individually released to npm.
To perform a release, make sure the version number in the `package.json` of the package-to-release has been updated to the new version.
The release can then be automatically performed using the `release-package` [workflow](https://github.com/kieler/JutilS/actions/workflows/release-package.yml).
