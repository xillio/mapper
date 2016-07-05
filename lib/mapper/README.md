# Mapper library - Read Me

version 1.0.1

## Purpose

- Provide a standardized way to do type and field level mapping in projects.
- Make connectors independent of mapping.
- Simplify mapping effort and improve maintainability by providing inheritance in mapping templates.
- Make mapping templates self-contained by having them provide the source types that they apply to.
- Automate generation of a mapping robot that is checked at compile time and simplifies debugging.

## Usage

1. Set up your project using the xill project convention (https://xillio.atlassian.net/wiki/x/FwAuAg) 
2. Copy the lib/mapper folder into your project's lib folder.
3. Add mapping templates (xill robots that map system documents to udm or vice versa).
4. Run Build.xill manually or by calling it from a robot. 