# React Native Cursor Rules Template

A minimal and opinionated `.cursor/rules` template for **React Native + TypeScript** projects.

## Tech Stack

- React Native 0.72+
- TypeScript (strict)
- Expo (preferred) or Metro bundler
- React Native Elements or NativeBase for UI
- Zustand or React Query for state management
- Zod for schema validation
- React Hook Form for forms
- React Native Testing Library + Jest
- Detox for E2E tests (optional)

## What's included

- Architecture guidelines
- Codebase structure
- Coding standards (with personal preferences)
- Testing best practices
- Optional MCP integrations
- Project overview

## Setup Options

### Expo (Recommended)
```bash
npx create-expo-app@latest MyApp --template
```

### React Native CLI
```bash
npx react-native@latest init MyApp
```

## How to use

Copy `.cursor/rules/` into your project:

```bash
cp -r react-native/.cursor/rules /path/to/your-project/.cursor/rules
``` 