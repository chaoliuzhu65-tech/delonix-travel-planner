# 🏨 德胧商旅出行规划 AI Skill

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-3.0.0-orange.svg)]()
[![德胧集团](https://img.shields.io/badge/%E5%BE%B7%E8%83%A7%E9%9B%86%E5%9B%A2-Delonix%20Group-blue.svg)](https://www.delonix.group/)

> 垂直于德胧酒店集团的智能商旅出行规划能力，百达屋优先推荐 + 12306实时查票 + 高德地图 + HTML报告生成

## ✨ 功能特性

- ⭐ **德胧优先推荐**：百达屋APP首选，万豪备选，OTA备选
- 🔗 **三级预订通道**：百达屋 → 万豪旅享家 → 携程/飞猪
- 🚄 **12306实时查票**：余票/车次/经停/换乘实时数据
- 🗺️ **高德地图集成**：路径规划/POI搜索/天气查询
- 💰 **智能预算计算**：经济/舒适/商务三档标准
- 📱 **HTML报告生成**：德胧品牌色系，响应式设计
- 🧾 **出行清单**：自动生成携带物品/证件清单
- 🤖 **飞书妙搭集成**：一键部署到团队空间

## 🏨 德胧品牌矩阵

| 品牌 | 定位 | 万豪合作 |
|------|------|---------|
| 开元名都·臻品之选 | 豪华国风 | ✅ 双品牌 |
| 开元名都 | 豪华国风 | - |
| 开元名庭 | 中高端 | - |
| 曼居 | 中端时尚 | - |
| 观堂 | 高端文化 | - |
| 方外 | 高端度假 | - |
| 芳草地 | 精品度假 | - |
| 布鲁克林 | 潮流设计 | - |

## 🚀 安装

```bash
git clone https://github.com/chaoliuzhu65-tech/delonix-travel-planner.git
cp -r delonix-travel-planner ~/.workbuddy/skills/
```

### MCP 配置

```json
{
  "mcpServers": {
    "12306-mcp": { "command": "npx", "args": ["-y", "12306-mcp"] },
    "amap-mcp": { "type": "sse", "url": "https://mcp.amap.com/sse?key={AMAP_WEB_KEY}" }
  }
}
```

## 📖 使用示例

```
帮我规划4月23-24日重庆出差，从天津出发，
4月23日下午有直营部会议，预算舒适档。
```

**输出**：德胧酒店推荐 + 交通方案 + 预算明细 + 行程时间线 + HTML报告

## 🔗 链接

- [GitHub Pages](https://chaoliuzhu65-tech.github.io/delonix-travel-planner/)
- [百达屋官网](https://www.betterwood.com/)
- [德胧集团](https://www.delonix.group/)

## 📄 License

MIT License · 德胧酒店集团内部开源
