[Unreleased]
Date: 

Minor Features
- Improved translation handling for better support of multiple languages.
- Improved overall frontend project structure for better maintainability.
- Added public changelog

Changed
- Migrated frontend code to typescript for better type safety and maintainability.

Bugfixes
- Fixed form descriptions displayed in columns instead of rows.

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