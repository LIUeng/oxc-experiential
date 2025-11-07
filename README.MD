# vite+ 生态体验

## oxc

### oxlint

类似于 eslint

[oxlint](https://oxc.rs/docs/guide/usage/linter.html)

### oxfmt

类比 prettier

[oxfmt](./https://oxc.rs/docs/guide/usage/formatter.html)

## lint-staged

初始化 Git 仓库

> 配置

[介绍](https://github.com/lint-staged/lint-staged?tab=readme-ov-file#configuration)

### 安装 husky

初始化

```shell
# npm
npx husky init
# pnpm
pnpm exec husky init
```

### Git Hooks

> commit-msg

可以使用 commitlint 规范提交信息

> pre-commit

提交前检查
