# AGENTS.md - uuidManager_repo 模组说明

## 文件结构（当前仓库）
```text
uuidManager_repo/
|-- .github/
|   \-- workflows/
|       \-- release.yml
|-- bundles/
|   |-- bundle.properties
|   \-- bundle_zh_CN.properties
|-- gradle/
|   \-- wrapper/
|       |-- gradle-wrapper.jar
|       \-- gradle-wrapper.properties
|-- scripts/
|   \-- main.js
|-- tools/
|   \-- uid_bruteforce_fast.py
|-- .gitignore
|-- AGENTS.md
|-- build.gradle
|-- gradlew
|-- gradlew.bat
|-- LICENSE
|-- mod.hjson
|-- README.md
|-- README_en.md
\-- settings.gradle
```

## 维护约束
- 保持 Java 8 兼容（如本项目包含 Java 源码）。
- 变更优先聚焦性能与可读性，不做无关重构。
- 用户可见文案优先走 bundle/资源文件，不硬编码。

命令操作请使用 PowerShell 7（`pwsh`）。
