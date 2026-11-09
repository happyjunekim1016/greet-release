# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-11-09

### Added

- `greet()` accepts a `punctuation` argument: `greet("Hee", ".")` was unsupported → now returns `Hello, Hee.` (default `!`).

### Fixed

- `greet()` with a blank or whitespace-only name: returned `Hello, !` → now returns `Hello, world!`.

## [0.1.0] - 2026-11-09

### Added

- `greet()` and command-line greeting: `python greet.py [name]` prints `Hello, <name>!` (default `world`).
