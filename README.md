# Node-RED Flow Manager

Node-RED Flow Manager simplifies the management of Node-RED flows by enabling seamless parsing, transformation, and file generation for monolithic and tree-structured flow configurations. Built with the official `@node-red/flow-parser` library, it ensures compatibility and reliability.

## Features

- **Parse Flows**: Convert monolithic Node-RED flow files or objects into structured `flowSet` objects.
- **Generate Tree Structure**: Split flows into organized folders and files (tabs, subflows, and config nodes) in JSON or YAML formats.
- **Reconstruct Flows**: Rebuild monolithic or tree-structured flows from their components.
- **Tab Ordering**: Maintain or modify the order of flow tabs for better organization.

## Installation

```bash
npm install flows-file-manager
```