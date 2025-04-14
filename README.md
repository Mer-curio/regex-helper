# 🎯 Regex Generator

一个简洁美观的正则表达式生成工具，用于筛选机场节点。支持中文、国旗 emoji、英文关键词，以及排除关键词。

[![访问 Regex Generator](https://img.shields.io/badge/在线访问-点击进入-brightgreen)](https://regex-helper-rho.vercel.app/)

![screenshot](./screenshot.png)

---

## ✨ 功能介绍

- ✅ 中文关键词（如：香港、台湾）
- ✅ 旗帜 emoji（如：🇭🇰、🇹🇼）
- ✅ 英文缩写（如：HK、TW、JP）
- ✅ 排除关键词（如：IEPL、IPLC、家宽）
- ✅ 多组关键词组合匹配
- ✅ 一键生成符合标准格式的正则表达式
- ✅ 简洁 UI，纯前端，移动端适配

---

## 🚀 使用方法

1. 打开网页 👉 [https://regex-helper-rho.vercel.app/](https://regex-helper-rho.vercel.app/)
2. 在对应输入框中填写关键词：
   - **输入关键词组**（多个组用英文分号 `;` 分隔，每组内关键词用英文逗号 `,` 分隔）  
     每个组表示一个关键词集合，最终生成的正则会匹配「同时包含每组中任一关键词」的内容。  
     支持自动扩展国家关键词（如输入“香港”自动扩展为 🇭🇰、HK、Hong 等），也可输入任意自定义关键词。  
     示例：  
     ```
     香港,台湾; 普通
     ```
     表示筛选包含“香港或台湾”且包含“普通”的节点。
     
   - **排除关键词**（用英文 `,` 分隔，选填）  
     示例：`IEPL, IPLC, 家宽` 表示排除包含任意一个关键词的节点。

3. 点击【生成正则表达式】
4. 复制结果即可使用于 Clash、Shadowrocket、Loon 等节点筛选

---

## 🛠 应用场景

- 机场节点筛选 / 分类
- Clash / Shadowrocket / Loon 等配置
- 批量处理节点名称中的关键词匹配

---

## 📜 License

MIT License，自由使用，欢迎贡献～

---

👑 项目由 ChatGPT 与 Mer-curio 联合打造，欢迎改进建议或 PR！
