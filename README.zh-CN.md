# Tauri + React + TypeScript + Shadcn UI 模板

这是一个使用Tauri、React、TypeScript和Shadcn UI构建的桌面应用程序模板，基于Vite构建工具。

[English Documentation](./README.md)

## 项目特性

- 🦀 **Tauri** - 使用Rust构建的轻量级、安全的桌面应用框架
- ⚛️ **React 19** - 前端使用最新版的React框架
- 📘 **TypeScript** - 类型安全的JavaScript超集
- 🎨 **Shadcn UI** - 基于Radix UI的高质量组件库
- 🌬️ **Tailwind CSS 4** - 实用优先的CSS框架
- 📦 **PNPM** - 高效的包管理工具

## 开发环境设置

### 前提条件

- [Node.js](https://nodejs.org/) (推荐18+)
- [PNPM](https://pnpm.io/) 
- [Rust](https://www.rust-lang.org/)

### 推荐的IDE设置

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## 开始使用

1. 克隆此仓库
   ```bash
   git clone https://github.com/ni00/tauri-react-shadui-template.git
   cd tauri-react-shadui-template
   ```

2. 安装依赖
   ```bash
   pnpm install
   ```

3. 启动开发服务器
   ```bash
   pnpm tauri dev
   ```

4. 构建生产版本
   ```bash
   pnpm tauri build
   ```

## 项目结构

- `/src` - React前端代码
- `/src-tauri` - Rust后端代码
- `/public` - 静态资源
- `/src/components/ui` - Shadcn UI组件

## 配置

应用配置位于 `src-tauri/tauri.conf.json` 文件中。您可以在此文件中修改应用名称、窗口大小等设置。

## 学习资源

- [Tauri 官方文档](https://tauri.app/docs/getting-started/introduction)
- [React 文档](https://react.dev/)
- [Shadcn UI 文档](https://ui.shadcn.com/)
- [Tailwind CSS 文档](https://tailwindcss.com/docs)

## 许可证

MIT