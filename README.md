# Tauri + React + TypeScript + Shadcn UI Template

This is a desktop application template built with Tauri, React, TypeScript and Shadcn UI, based on Vite build tool.

[中文文档](./README.zh-CN.md)

## Features

- 🦀 **Tauri** - Lightweight, secure desktop application framework built with Rust
- ⚛️ **React 19** - Latest version of React framework for the frontend
- 📘 **TypeScript** - Type-safe JavaScript superset
- 🎨 **Shadcn UI** - High-quality component library based on Radix UI
- 🌬️ **Tailwind CSS 4** - Utility-first CSS framework
- 📦 **PNPM** - Efficient package manager

## Development Environment Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (18+ recommended)
- [PNPM](https://pnpm.io/)
- [Rust](https://www.rust-lang.org/)

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/ni00/tauri-react-shadui-template.git
   cd tauri-react-shadui-template
   ```

2. Install dependencies
   ```bash
   pnpm install
   ```

3. Start development server
   ```bash
   pnpm tauri dev
   ```

4. Build for production
   ```bash
   pnpm tauri build
   ```

## Project Structure

- `/src` - React frontend code
- `/src-tauri` - Rust backend code
- `/public` - Static assets
- `/src/components/ui` - Shadcn UI components

## Configuration

Application configuration is located in `src-tauri/tauri.conf.json`. You can modify application name, window size, and other settings in this file.

## Learning Resources

- [Tauri Official Documentation](https://tauri.app/docs/getting-started/introduction)
- [React Documentation](https://react.dev/)
- [Shadcn UI Documentation](https://ui.shadcn.com/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## License

MIT
