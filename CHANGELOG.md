# Change Log

## [1.0.2] 2022-06-11
### Improvements

- Built with [Material Kit PRO Generator](https://appseed.us/generator/material-kit-pro/)
  - Timestamp: `2022-06-11 16:08`

## [1.0.1] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.0] 2020-10-02
### Initial Release

- UI: Material Kit PRO - v2.2.0
- [Flask Codebase](https://github.com/app-generator/boilerplate-code-flask/releases) - v1.0.7
  - Dependencies update (all packages)
    - Flask==2.0.1 (latest stable version)
  - Improved Files organization
  - UI Templates moved to home folder
  - Docker Scripts Update
- Added SCSS Compilation scripts  