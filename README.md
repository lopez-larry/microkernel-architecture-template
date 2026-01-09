# Microkernel Architecture Template

This repository demonstrates a microkernel (plug-in) architecture.

A small core system provides the base capabilities, and plugins extend or customize behavior. This pattern is common in IDEs, rule engines, and platforms that must support many variants.

## Folder Structure

core/
  api/      - public contracts the plugins must implement or call
  service/  - core services and shared logic

plugins/
  plugin-a/ - example plugin implementation
  plugin-b/ - example plugin implementation

tests/      - tests for core and plugins

docs/
  architecture.md
  decisions.md
