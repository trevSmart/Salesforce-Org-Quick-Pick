# Changelog

All notable changes to this project will be documented in this file.

## [0.2.0]

### Added

- **SFDX command actions in picker**: The picker now mirrors the official Salesforce Org Management extension. It includes the same SFDX commands at the top: Authorize an Org, Authorize a Dev Hub, Create a Default Scratch Org, Authorize an Org using Session ID, and Remove Deleted and Expired Orgs. Each option invokes the corresponding command from the official extension (`sf.org.login.web`, `sf.org.login.web.dev.hub`, etc.).
- **Setting `organizationsFirst`**: When enabled (default), the organization list appears at the top of the picker and SFDX commands are shown at the bottom. When disabled, the layout matches the official extension: SFDX commands first, then a separator, then the org list.

### Changed

- Picker placeholder updated to "Select an org to set as default" to match the official extension.
- Picker now shows even when no orgs are authorized, allowing users to authorize one directly from the list.
