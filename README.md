```markdown
# crypto-webui

示例 DEX 前后端骨架（TypeScript + Next.js + Tailwind + Prisma(SQLite) + wagmi + rainbowkit）

快速开始：
1. 安装依赖：`pnpm install` 或 `npm install`
2. 生成 Prisma 客户端并迁移（dev）：
   - `npx prisma migrate dev --name init`
   - `npx prisma db seed`（如果实现了 seed 脚本）
3. 启动开发：`pnpm dev` 或 `npm run dev`

注意：
- SQLite 适合本地开发，生产请使用 Postgres 并调整 prisma/schema.prisma datasource。
- 钱包交互使用 ethers + wagmi + rainbowkit。
```
