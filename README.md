# MultiStage Builder

A Docker project demonstrating multi-stage builds by separating:

- Dependency installation
- Application compilation
- Testing
- Production runtime

## Architecture

Dependencies
     ↓
Build
     ↓
Test
     ↓
Runtime

## Technologies

- Docker
- Docker Multi-Stage Builds
- Node.js
- Bash

## Features

- Separate build stages
- Minimal production image
- Automated build commands
- Stage-specific builds
- Single-stage vs multi-stage comparison

## Usage

./multistage build
