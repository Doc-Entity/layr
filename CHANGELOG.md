# Change Log

All notable changes to the "Layr" extension will be documented in this file.

## [0.0.5] - 2025-11-02

### Added
- Support for **Kimi** (Moonshot AI) provider with models: kimi-k2-0905, moonshot-v1-8k, moonshot-v1-32k, moonshot-v1-128k
- Support for **DeepSeek** provider with models: deepseek-v3.1, deepseek-chat, deepseek-coder
- Support for **Grok** (xAI) provider with models: grok-4, grok-3, grok-2
- Support for **O3** (OpenAI reasoning model) with models: o3, o3-mini
- Separate provider files for better code organization and maintainability
- Individual configuration interfaces for each AI provider

### Changed
- Reorganized provider architecture with dedicated files for each model
- Updated factory pattern to support all 7 AI providers
- Improved TypeScript type safety across all providers
- Enhanced error handling for new providers

### Fixed
- Type casting issues in provider implementations
- Interface ordering for proper TypeScript compilation

## [0.0.4] - Previous Release

### Added
- Initial multi-provider support (Gemini, OpenAI, Claude)
- Basic AI planning functionality
- Template-based fallback system

## [0.0.3] - Earlier Release

### Added
- Core extension functionality
- AI integration
- Project plan generation

## [0.0.2] - Earlier Release

### Added
- Initial release with basic features

## [0.0.1] - Initial Release

### Added
- Project structure
- Basic command setup
