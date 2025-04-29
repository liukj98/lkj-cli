# 学习搭建cli脚手架

## 安装
### 全局安装

```bash
npm install -g lkj-cli

# or yarn
yarn global add lkj-cli
```

### 借助npx

**创建模版**

```bash
npx create lkj-cli <name> [-t|--template]
```

**示例**

```bash
npx create lkj-cli hello-cli -template dumi2-demo
```

## 使用

**创建模版**

```bash
lkj-cli create <name> [-t|--template]
```

**示例**
```bash
lkj-cli create hello-cli -t dumi2-demo
```
