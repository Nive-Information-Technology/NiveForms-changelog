# Changelog

[25.6.3]
Date: 19.6.2025

Bugfixes
- Fixed an issue with M-Files cloud environments cookies not being returned correctly, causing user unauthentication after login.

[25.6.2]
Date: 18.6.2025

Minor Features
- Improved translation handling for better support of multiple languages.
- Improved overall frontend project structure for better maintainability.
- Added public changelog
- Implemented form field order management in the form editor interface.
- Implemented form submissions validation to ensure data integrity in M-Files.

Changed
- Migrated frontend code to typescript for better type safety and maintainability.

Bugfixes
- Fixed form descriptions displayed in columns instead of rows.
- Merged heartbeat check and form submission API calls to reduce the number of requests and fix service unavailable errors.
**NOTE:** This change introduces a breaking dependency on the vault application. The required version of the vault application is now `25.6.0` or higher.
- Fixed accessibility issues with slider input component.'

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