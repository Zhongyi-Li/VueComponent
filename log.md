1. npm init -y pnpm install vue typescript
2. 新建.npmrc 文件 写入 shamefully-hoist = true (将 vue 核心模块从 pnpm 暴露出来) / 再次执行 ppm install
3. pnpm tsc --init (初始化 ts 配置文件)
4. 新建文件夹 并一一创建 package.json 文件 修改 name 字段
5. 再根目录下的 package.json 文件下手动添加依赖名 执行 pnpm install xxx -w
6. 根目录执行 pnpm create vite play --template vue-ts / 删除冗余文件 / 新建 typing.ts 文件 / 修改根目录 package.json 的 dev 命令
