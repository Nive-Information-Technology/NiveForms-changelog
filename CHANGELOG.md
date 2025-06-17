# Version Compatibility
| Nive Forms | Vault Application                            |
|-|-|
| 25.6.0 [unreleased]   | 25.6.0 [unreleased]|              |
| 25.5.0                | 25.4.0                            |


# Changelog
[Unreleased]
Date: 

Minor Features
- Improved translation handling for better support of multiple languages.
- Improved overall frontend project structure for better maintainability.
- Added public changelog
- Implemented form field order management in the form editor interface.

Changed
- Migrated frontend code to typescript for better type safety and maintainability.

Bugfixes
- Fixed form descriptions displayed in columns instead of rows.
- Merged heartbeat check and form submission API calls to reduce the number of requests and fix service unavailable errors.
**NOTE:** This change introduces a breaking dependency on the vault application. The required version of the vault application is now `25.6.0` or higher.

---

[25.5.0]
Date: 28.4.2025

Minor Features
- Added logging for most backend operations
- Filter out most built-in M-Files properties from the field property mapping to show only valid properties
- Filter out all built-in M-Files properties from suomi.fi authentication property mapping settings

Bugfixes
- Fixed not being able to disable suomi.fi authentication for forms
- Added fallback language for untranslated valuelist items