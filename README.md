# APEX Theme Documentation
APEX Plugin to help with component documentation.

This plugin is mostly useful for building themes.

![demo1](/docs/apex-theme-documentation.png)

## Install
- Import `region_type_plugin_apex_theme_documentation.sql` in your application

## Usage
- In Page Designer, add the region plugin to your page
- Select appropriate options for your component (see below)

## Attributes

**Application**
Name | Type | Description
--- | --- | --
`CSS Classes - table` | Text | This class name will be applied to the "table" HTML tag of all documentation components.
`CSS Classes - thead` | Text | This class name will be applied to the "thead" HTML tag of all documentation components.
`CSS Classes - th` | Text | This class name will be applied to the "th" HTML tag of all documentation components.
`CSS Classes - td` | Text | This class name will be applied to the "td" HTML tag of all documentation components.
`CSS Classes - Component Title` | Text | This class name will be applied to the component title of all documentation components.

**Component**
Name | Type | Description
--- | --- | --
`Component Type` | Select List | This indicates what type of component you are documenting (item, region, report, etc.).
`Display Template Options` | Yes/No | This indicates if the component template options will be documented.
`Display Only Associated Template Options` | Yes/No | Select this to limit the number of documented template options only to those that were picked.
`Display All Template Option Group Choices` | Yes/No | Select this to output a concatenated list of available template options (per group)
`Display Grid Attributes` | Yes/No | This indicates if the component grid attributes will be documented.
`Display Custom Attributes` | Yes/No | This indicates if the component custom attributes will be documented.

## Examples
![demo2](/docs/apex-theme-documentation-2.png)

## Changelog
[See changelog](changelog.md).
