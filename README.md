# Bitcoin Flash (比特币快闪)

优雅简洁的比特币入门网站，帮助新人从 0 到 100 建立认知。

## 项目特点

- **极简设计**: 优雅、丝滑、清晰直白。
- **第一性原理**: 从本质解释比特币、交易和存储。
- **响应式布局**: 完美适配手机和桌面端。

## 技术栈

- React
- TypeScript
- Tailwind CSS v4
- Framer Motion (动画)
- Vite

## 开发与部署

### 本地开发

```bash
npm install
npm run dev
```

### 构建

```bash
npm run build
```

构建产物位于 `dist` 目录。

### 部署到 Cloudflare Pages

1. 将代码上传到 GitHub。
2. 登录 Cloudflare Dashboard，进入 Pages。
3. 连接 GitHub 仓库。
4. 构建设置：
   - **Framework preset**: Vite
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`
5. 点击 Deploy。

## 待更新内容

请搜索代码中的 "待更新" 或 `#` 链接，替换为您自己的邀请链接和邀请码：

- `src/components/HowToBuy.tsx`: Binance 和 OKX 的邀请链接/邀请码。
- `src/components/Wallet.tsx`: OneKey 钱包购买链接。
- `src/components/Consultation.tsx`: 联系方式。

## License

MIT
