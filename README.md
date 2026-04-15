# WTK-core-almanac

此仓库记录三国杀官正产品，按系列整理相关资料。

## 仓库说明

这个仓库用于归档和整理三国杀官正产品信息，目录按系列划分。

目前仓库中的 Obsidian 插件采用 Git `submodule` 配置：

- `.obsidian/plugins/paste-image-webp-renamer`

它用于 Obsidian 工作区中的插件管理。如果你只是浏览内容，可以不关心它的具体实现；如果要完整拉取仓库内容，克隆时需要一并初始化子模块。

## 克隆仓库

### 首次克隆

推荐直接使用 `--recurse-submodules`：

```bash
git clone --recurse-submodules https://github.com/WTKAlmanac/WTK-core-almanac.git
```

### 已经克隆过仓库

如果你之前是普通克隆，没有拉取子模块，在仓库根目录执行：

```bash
git submodule update --init --recursive
```

### 后续更新

拉取主仓库最新内容后，建议同步更新子模块：

```bash
git pull --recurse-submodules
git submodule update --init --recursive
```

## 使用建议

- 建议使用支持 Git `submodule` 的客户端进行克隆和更新。
- 如果你使用 Obsidian 打开本仓库，拉取完整子模块后可以获得更完整的工作区配置。
- 如果你只关心资料内容，不使用 Obsidian，也可以忽略 `.obsidian` 相关目录。
