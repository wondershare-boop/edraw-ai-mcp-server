### 什么是 Edraw AI MCP 服务？

**EdrawAIMCP** 是由万兴科技开源的**图表可视化解决方案**，旨在通过**自然语言、图像、文档与代码**四种输入方式，帮助用户**一键生成和智能优化各类可视化图表**。它适用于开发者、产品团队、内容运营人员、教学人员等，能够快速产出高质量的视觉内容，如：

- 流程图  
- 思维导图  
- 时间线  
- 海报  
- PPT 单页  
- 框架图  
- 知识卡片  
- SWOT 分析  
- PEST 分析  
- 精益画布  
- 用户画像  
- 用户故事  

---

### 如何使用 Edraw AI MCP 服务？

平台已经为你部署好了云端的 **Edraw AI MCP 服务**，并且**完全免费使用**。

**自定义配置示例：**

```json
{
  "mcpServers": {
    "edraw-ai-mcp-server": {
      "name": "edraw-ai-mcp-server",
      "type": "streamableHttp",
      "description": "万兴AI文生图示MCP服务",
      "isActive": true,
      "url": "https://api.edrawmax.cn/api/mcp/mcp"
    }
  }
}
```
---

### Edraw AI MCP 服务的关键特性

- ✅ 支持多种输入方式：自然语言、图像、文档、代码
- ✅ 支持多种图表类型生成并返回 URL，包括：
  - 流程图
  - 思维导图
  - PPT 单页
  - 框架图
  - 时间线
  - 海报
  - 知识卡片
  - SWOT、PEST、精益画布、用户画像、用户故事等
- ✅ 提供丰富、专业、全面的图表模板库

![](https://www.edrawsoft.com/images2021/new-edrawsoft/Edrawmax3.png)

---

### 使用案例

| 场景 | 输入内容 | 生成内容 |
|------|-----------|-----------|
| 人力资源与培训 | 培训大纲或政策文本 | 培训流程图、时间线 |
| 跨团队协作与汇报 | 汇报内容 | 图文并茂的 PPT 单页 |
| 营销与品牌推广 | 自然语言描述的品牌故事 | 海报、社交媒体卡片 |
| 产品设计与用户研究 | 产品需求描述 | 用户画像、SWOT 分析图 |
| 项目管理与敏捷开发 | Mermaid 代码 | 流程图 |
| 学术研究与教育 | 研究提纲、文献摘要 | 思维导图、内容框架图 |

---

### 工具列表
| 工具名                   | 工具说明             | 参数说明                                                                                               |
|--------------------------|------------------------|-----------------------------------------------------------------------------------------------------|
| generate_card            | 文本生成知识卡片       | mode 参数可选项：card-loop(循环),card-contrast(对比),card-parallel(平行),card-progressive(递进),card-deduction(总分),card-hierarchical(层级),card-contain(包含) |
| generate_flowchart       | 文本生成流程图         |                                                                                                     |
| generate_info-contrast   | 文本生成对比信息图     |                                                                                                    |
| generate_info-parallel   | 文本生成平行信息图     |                                                                                                     |
| generate_mindmap         | 文本生成脑图           |                                                                                                     |
| generate_ppt             | 文本生成PPT            | mode 参数可选项：ppt-define(自定义), ppt-contrast(对比), ppt-framework(框架), ppt-parallel(并列), ppt-progressive(递进), ppt-loop(循环), ppt-contain(包含), ppt-hierarchical(层级) |
| generate_text-leanCanvas | 文本生成精益画布       |                                                                                                     |
| generate_text-pest       | 文本生成PEST分析图     |                                                                                                    |
| generate_text-swot       | 文本生成SWOT分析图     |                                                                                                     |
| generate_text-userStory  | 文本生成用户故事       |                                                                                                    |
| generate_timeline        | 文本生成时间线         |                                                                                                    |
| generate_user-profile    | 文本生成用户画像       |                                                                                                     |

- 工具中都包含的参数：prompt(主题)、lang(语言)

---

### 常见问题解答

**Q：使用 Edraw AI MCP 服务是否需要付费？**  
A：目前为**限时免费**，用户可免费调用服务。

**Q：如何联系我们？**  
A：如有关于技术问题、服务反馈或 API 调用大量购买需求，欢迎通过邮箱联系：  
📧 **ws-business@wondershare.cn**  
我们将尽快为您解答。
