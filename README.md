# My React Template

一个现代化的 React 项目模板，集成了最新的开发工具和最佳实践。

## 🚀 特性

- ⚡️ **Vite** - 极速的构建工具
- ⚛️ **React 19** - 最新版本的 React
- 🎯 **TypeScript** - 类型安全的 JavaScript
- 🎨 **Tailwind CSS** - 实用优先的 CSS 框架
- 📁 **路径别名** - 支持 `@/` 别名导入
- 🔧 **ESLint** - 代码质量检查
- 📦 **现代化依赖** - 使用最新稳定版本

## 📋 技术栈

- **前端框架**: React 19.1.1
- **构建工具**: Vite 7.1.2
- **语言**: TypeScript 5.8.3
- **样式**: Tailwind CSS 4.1.12
- **代码检查**: ESLint 9.33.0
- **包管理**: npm

## 🛠️ 快速开始

### 1. 克隆模板

```bash
git clone https://github.com/ruanxianxiang/my-react-template.git my-project
cd my-project
```

### 2. 安装依赖

```bash
npm install
```

### 3. 启动开发服务器

```bash
npm run dev
```

### 4. 构建生产版本

```bash
npm run build
```

### 5. 预览生产版本

```bash
npm run preview
```

## 📁 项目结构

```
my-react-template/
├── public/                 # 静态资源
├── src/                   # 源代码
│   ├── assets/           # 资源文件
│   ├── components/       # 组件目录
│   ├── App.tsx          # 主应用组件
│   ├── main.tsx         # 应用入口
│   ├── index.css        # 全局样式
│   └── vite-env.d.ts    # Vite 类型声明
├── eslint.config.js      # ESLint 配置
├── index.html           # HTML 模板
├── package.json         # 项目配置
├── tsconfig.json        # TypeScript 配置
├── tsconfig.app.json    # 应用 TypeScript 配置
├── tsconfig.node.json   # Node.js TypeScript 配置
└── vite.config.ts       # Vite 配置
```

## 🎯 路径别名

项目已配置 `@` 别名指向 `src` 目录，可以使用绝对路径导入：

```typescript
// 使用别名导入
import App from '@/App'
import Component from '@/components/Component'

// 而不是相对路径
import App from '../App'
import Component from '../../components/Component'
```

## 🎨 样式系统

使用 Tailwind CSS 4.x 版本，支持：

- 实用优先的 CSS 类
- 响应式设计
- 深色模式支持
- 自定义主题配置

## 📝 可用脚本

- `npm run dev` - 启动开发服务器
- `npm run build` - 构建生产版本
- `npm run preview` - 预览生产版本
- `npm run lint` - 运行 ESLint 检查

## 🔧 配置说明

### Vite 配置

- 配置了 `@` 路径别名
- 集成 React 和 Tailwind CSS 插件
- 优化了构建配置

### TypeScript 配置

- 严格模式启用
- 支持 JSX
- 配置了路径映射
- 分离了应用和 Node.js 配置

### ESLint 配置

- React Hooks 规则
- React Refresh 支持
- TypeScript 集成

## 🚀 部署

构建后的文件在 `dist` 目录中，可以部署到任何静态文件服务器：

- Vercel
- Netlify
- GitHub Pages
- 或任何 CDN

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

**享受编码！** 🎉
