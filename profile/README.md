# PHP Internal

Essential utilities for PHP development workflow optimization and runtime management.

## What We Build

**Core utilities** that solve common PHP development challenges:
- **Dependency & binary management** - Automated tool distribution, version control, and package workflows
- **Memory control** - Detection and analysis of memory leaks, utilites for long-running applications
- **Testing infrastructure** - PHPUnit interceptors and debugging tools

## Current Projects

### [DLoad](https://github.com/php-internal/dload)
Smart binary downloader that automates tool distribution. Download platform-specific binaries like RoadRunner, Temporal, or custom tools with cross-platform compatibility.

### [Promise](https://github.com/php-internal/promise)
A lightweight PHP implementation of CommonJS Promises/A with PHP 8.1+ support, strict type declarations, and enhanced type annotations. This fork of ReactPHP's promise library provides improved rejection handling and better developer experience while maintaining full API compatibility.

## Useful Tools

**[Buggregator Trap](https://github.com/buggregator/trap)** - Local debug server with enhanced Symfony VarDumper integration. Supports multiple protocols (Monolog, Sentry, SMTP, HTTP dumps) and provides rich debugging capabilities for PHP applications.

**[Unpoly](https://github.com/roxblnfk/unpoly)** - Remove unnecessary PHP polyfills based on your PHP version to optimize dependencies and reduce bloat.

Built for teams that value automation, consistency, and efficient development workflows.

> [!NOTE]
> This organization is not affiliated with "PHP Internals".
