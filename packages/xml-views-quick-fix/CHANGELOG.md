# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.0.3](https://github.com/sap/ui5-language-assistant/compare/@ui5-language-assistant/xml-views-quick-fix@2.0.2...@ui5-language-assistant/xml-views-quick-fix@2.0.3) (2021-01-03)

**Note:** Version bump only for package @ui5-language-assistant/xml-views-quick-fix

## [2.0.2](https://github.com/sap/ui5-language-assistant/compare/@ui5-language-assistant/xml-views-quick-fix@2.0.1...@ui5-language-assistant/xml-views-quick-fix@2.0.2) (2020-12-30)

**Note:** Version bump only for package @ui5-language-assistant/xml-views-quick-fix

## [2.0.1](https://github.com/sap/ui5-language-assistant/compare/@ui5-language-assistant/xml-views-quick-fix@2.0.0...@ui5-language-assistant/xml-views-quick-fix@2.0.1) (2020-08-27)

**Note:** Version bump only for package @ui5-language-assistant/xml-views-quick-fix

# 2.0.0 (2020-08-12)

### Features

- non stable id quick fix ([#266](https://github.com/sap/ui5-language-assistant/issues/266)) ([c564db4](https://github.com/sap/ui5-language-assistant/commit/c564db4ed7a5ec9e026be0f10a72c734a366c3f7))
- quick fix stable id for entire file ([#283](https://github.com/sap/ui5-language-assistant/issues/283)) ([b3945da](https://github.com/sap/ui5-language-assistant/commit/b3945da286479d0cca1955dba092cba44f4359fa))

### BREAKING CHANGES

- - computeQuickFixStableIdInfo function signature has changed.

* validateXMLView no longer accepts `flexEnabled` optional argument and always requires passing a `UI5ValidatorsConfig`
