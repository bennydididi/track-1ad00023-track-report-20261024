# SERP 最终判定（2026-10-24）

本文件与 serp.json 的 final_decisions、report.md 使用同一最终表。旧年龄标签仅保存在 evidence/serp-original.* 与 legacy_verdict，禁止作为难度结论。

| 用户任务组 | 已有证据与限制 | 排名页/替代方案观察 | 最终判断 | 公开入口 |
|---|---|---|---|---|
| 报价制作 | 8个核心词均已补查意图；32个英语市场×核心词组合的指定Google前十未找到 | LawnPilot、QuoteNovo等可比窄工具公开提供报价功能；公开付费客户/留存未找到 | 有任务；收费待验证；SEO低优先级，先做付费实验 | [官网](https://getlawnpilot.com/pricing) |
| 报价模板与范围说明 | US estimate template=70、quote template=70、proposal template=50；不能直接相加 | Jobber免费模板覆盖排除项；scope/specifications补查偏公共采购文本 | 模板可获客；只生成PDF的差异不足，验证频次+排除项联动 | [官网](https://www.getjobber.com/free-tools/estimate-template/lawn-care/) |
| 同业宽词与本地询价 | US lawn care quote样本8条；estimating样本8条；FR exemple devis paysagiste样本8条 | estimating样本含2个近18个月域名，实际提供软件；其他宽词混有服务商/资讯 | 仅竞争线索，不贡献主需求量与主评分；不能据年龄判新手友好 | [官网](https://gusapp.io/) |

原始3300行；追加未查询53行。当前各语言36词，与原每语言300词快照不同。搜索量来源：[PXAny](https://api.pxany.com/v1/keyword-volumes)，鉴权接口；原始Google搜索结果仅6–9条。核心8词已通用web检索，32个英语市场×核心词组合仍缺指定Google前十；不伪装已完成。完整国家×关键词状态见 evidence/keyword-audit.csv。

| 市场 | 词 | 月量 | 状态 | 样本 | 年龄线索 | 最终判定 |
|---|---|---|---|---|---|---|
| US | lawn care software | 390 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care app | 720 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care management | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care CRM | 140 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| US | lawn care system | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| US | lawn service software | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service app | 210 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn service CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping software | 1600 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping app | 1900 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | landscaping management software | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping CRM | 260 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping management system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping platform | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape management system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape management platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf management software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf management app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf management system | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf maintenance software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardening business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardening business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardener CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardener management software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing app | 590 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn mowing CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | mowing business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | mowing business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn business software | 260 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care estimating | 210 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| US | lawn care estimating software | 20 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care estimating app | 140 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care quote software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care pricing software | 20 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care billing software | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care invoicing software | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care invoice app | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care scheduling software | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care scheduling app | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care routing software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care dispatch software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care booking software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care booking app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care contract software | 20 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn care customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn service proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn service invoicing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service routing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service billing software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn service customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping estimating software | 320 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 混合意图/相邻需求 |
| US | landscaping estimating app | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping quote software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping proposal app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping bid software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping invoicing software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping billing software | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping scheduling software | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping contract software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping job management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping business software | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | landscaping work order software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping crew management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping takeoff software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape estimating software | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| US | landscape quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape bidding software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | landscape maintenance scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | grounds maintenance scheduling software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance contract software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardening quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardening invoice software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardener scheduling app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | gardener quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn mowing quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn mowing invoice app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing scheduling app | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing route planner | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate | 210 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| US | lawn care quote | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 混合意图/相邻需求 |
| US | lawn care proposal | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care bid | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate template | 70 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care quote template | 70 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care proposal template | 50 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care bid template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care quote form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care proposal example | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate example | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate calculator | 20 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care price calculator | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care cost calculator | 260 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | lawn care quote calculator | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care service agreement | 50 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn care service contract | 480 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care contract template | 1000 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 范围说明辅助词，条件承接 |
| US | lawn care agreement template | 1000 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care contract example | 1000 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care contract form | 1000 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn care scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn care service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn care service description | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care service checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care service packages | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care service list | 320 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn maintenance service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance quote | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance contract | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance agreement | 260 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance contract template | 1000 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn maintenance estimate template | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance checklist | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance schedule | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance pricing | 390 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance service description | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn maintenance bid template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping estimate | 480 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | landscaping quote | 880 | 返回正数 | 7/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | landscaping proposal | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping bid | 260 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping estimate template | 390 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping quote template | 210 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping proposal template | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping bid template | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping estimate calculator | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping cost calculator | 1600 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | landscaping quote calculator | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping contract template | 880 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | landscaping service agreement | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscaping scope of work | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance contract | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance contract template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance checklist | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | landscape maintenance bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance contract | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance tender | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | grounds maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance service agreement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden maintenance checklist | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing estimate | 40 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| US | lawn mowing quote | 260 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 混合意图/相邻需求 |
| US | lawn mowing proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing estimate template | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing quote template | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing contract template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing contract | 260 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn mowing service agreement | 260 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn mowing cost calculator | 1000 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | lawn mowing price calculator | 1000 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| US | lawn mowing quote calculator | 20 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn mowing bid calculator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn care proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | commercial lawn care contract | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | commercial lawn mowing bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | residential lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | residential lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | residential lawn care contract | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | residential lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | HOA lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | HOA landscaping proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | apartment lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | school grounds maintenance tender | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | sports turf maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | municipal mowing contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | cemetery mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | property maintenance quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care pricing | 2900 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| US | lawn care price list | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care rates | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 历史扩展词，不纳入主评分 |
| US | lawn care hourly rate | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care monthly cost | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care annual contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care subscription software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | recurring lawn care billing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | weekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | biweekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | monthly lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | annual lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing per acre | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing per hour | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing per visit | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn mowing minimum charge | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn aeration estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn aeration quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn aeration pricing | 1300 | 返回正数 | 7/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | lawn dethatching quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn dethatching estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn scarifying quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn fertilization estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn fertilization quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn treatment quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn treatment contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn overseeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn overseeding quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn renovation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn renovation quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn edging quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn trimming quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn weed control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn pest control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn topdressing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn seeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | sod installation estimate | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | sod installation quote | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | turf laying quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn clippings removal cost | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | leaf removal estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | yard cleanup estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | spring cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | fall cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | garden waste removal quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn area measurement app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn measurement software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn area calculator | 1300 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| US | mowing time calculator | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care job costing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care work orders | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care service report | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care digital signature | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care quote approval | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care recurring invoices | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care payment app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care crew scheduling | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care time tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care job tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care CRM software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | free lawn care software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | best lawn care software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | online lawn care quotes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | instant lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | mobile lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | small lawn business software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care scope of work template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care statement of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care app | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care management | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| UK | lawn care system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| UK | lawn service software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping software | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping app | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping management software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping CRM | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping management system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping platform | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape management system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape management platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf management software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf management app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf management system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf maintenance software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardening business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardening business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardener CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardener management software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing app | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | mowing business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | mowing business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn business software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimating | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn care estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care estimating app | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care invoice app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care routing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care dispatch software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care booking software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care booking app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn service proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn service invoicing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service routing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn service customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | landscaping estimating app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping proposal app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping bid software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping job management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping business software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping work order software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping crew management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping takeoff software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | landscape quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape bidding software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | landscape maintenance scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance billing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | grounds maintenance scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance contract software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardening quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardening invoice software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardener scheduling app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | gardener quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn mowing quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn mowing invoice app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing route planner | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn care quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn care proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate form | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care quote form | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care proposal example | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate example | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care price calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care cost calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care service agreement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care service contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care contract template | 70 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care agreement template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care contract example | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care contract form | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care service description | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care service checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care service packages | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care service list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn maintenance service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance contract template | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance proposal template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn maintenance estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance quote template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance schedule | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance pricing | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance service description | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn maintenance bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping estimate | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote template | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping bid template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping cost calculator | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscaping scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | landscape maintenance bid template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance contract | 210 | 返回正数 | 6/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance tender | 140 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | grounds maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance quote | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance contract | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance service agreement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn mowing quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn mowing proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing estimate template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing quote template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing cost calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing price calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| UK | lawn mowing quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn mowing bid calculator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn care proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | commercial lawn care contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | commercial lawn mowing bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | residential lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | residential lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | residential lawn care contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | residential lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | HOA lawn maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | HOA landscaping proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | apartment lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | school grounds maintenance tender | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | sports turf maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | municipal mowing contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | cemetery mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | property maintenance quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care pricing | 210 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 混合意图/相邻需求 |
| UK | lawn care price list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care rates | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care hourly rate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care monthly cost | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care annual contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care subscription software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | recurring lawn care billing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | weekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | biweekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | monthly lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | annual lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing per acre | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing per hour | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing per visit | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn mowing minimum charge | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn aeration estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn aeration quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn aeration pricing | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn dethatching quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn dethatching estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn scarifying quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn fertilization estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn fertilization quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn treatment quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn treatment contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn overseeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn overseeding quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn renovation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn renovation quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn edging quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn trimming quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn weed control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn pest control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn topdressing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn seeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | sod installation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | sod installation quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | turf laying quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn clippings removal cost | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | leaf removal estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | yard cleanup estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | spring cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | fall cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | garden waste removal quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn area measurement app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn measurement software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn area calculator | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | mowing time calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care job costing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care work orders | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care service report | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care digital signature | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care quote approval | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care recurring invoices | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care payment app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care crew scheduling | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care time tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care job tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care CRM software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | free lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | best lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | online lawn care quotes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | instant lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | mobile lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | small lawn business software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care scope of work template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| UK | lawn care statement of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care app | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care management | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| CA | lawn care system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| CA | lawn service software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping software | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping app | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping management software | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping CRM | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping management system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping platform | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape management system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape management platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf management software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf management app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf management system | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf maintenance software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardening business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardening business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardener CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardener management software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing app | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | mowing business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | mowing business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimating | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | lawn care estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care estimating app | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care quote software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care invoice app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care routing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care dispatch software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care booking software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care booking app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn service proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn service invoicing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service routing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn service customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping estimating software | 20 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | landscaping estimating app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping proposal app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping bid software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping billing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping job management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping business software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping work order software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping crew management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping takeoff software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape estimating software | 20 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | landscape quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape bidding software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | landscape maintenance scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance billing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | grounds maintenance scheduling software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance contract software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardening quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardening invoice software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardener scheduling app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | gardener quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn mowing quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn mowing invoice app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing route planner | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | lawn care quote | 20 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | lawn care proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate form | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care quote form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care proposal example | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate example | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care price calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care cost calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care service contract | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care contract template | 50 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care agreement template | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care contract example | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care contract form | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care service description | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care service checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care service packages | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care service list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn maintenance service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance contract template | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn maintenance estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance schedule | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance pricing | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance service description | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn maintenance bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping estimate | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote | 140 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote template | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping cost calculator | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping contract template | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscaping scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | landscape maintenance bid template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance tender | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | grounds maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance quote template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance service agreement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | lawn mowing quote | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| CA | lawn mowing proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing cost calculator | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing price calculator | 50 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| CA | lawn mowing quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn mowing bid calculator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn care proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | commercial lawn care contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | commercial lawn mowing bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | residential lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | residential lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | residential lawn care contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | residential lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | HOA lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | HOA landscaping proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | apartment lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | school grounds maintenance tender | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | sports turf maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | municipal mowing contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | cemetery mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | property maintenance quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care pricing | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| CA | lawn care price list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care rates | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care hourly rate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care monthly cost | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care annual contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care subscription software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | recurring lawn care billing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | weekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | biweekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | monthly lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | annual lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing per acre | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing per hour | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing per visit | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn mowing minimum charge | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn aeration estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn aeration quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn aeration pricing | 140 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn dethatching quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn dethatching estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn scarifying quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn fertilization estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn fertilization quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn treatment quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn treatment contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn overseeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn overseeding quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn renovation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn renovation quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn edging quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn trimming quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn weed control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn pest control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn topdressing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn seeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | sod installation estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | sod installation quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | turf laying quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn clippings removal cost | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | leaf removal estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | yard cleanup estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | spring cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | fall cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | garden waste removal quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn area measurement app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn measurement software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn area calculator | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | mowing time calculator | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care job costing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care work orders | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care service report | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care digital signature | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care quote approval | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care recurring invoices | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care payment app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care crew scheduling | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care time tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care job tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care CRM software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | free lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | best lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | online lawn care quotes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | instant lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | mobile lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | small lawn business software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care scope of work template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| CA | lawn care statement of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care app | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care management | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| AU | lawn care system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| AU | lawn service software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping software | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping app | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping management software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping management system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping platform | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape management system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape management platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance system | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf management software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf management app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf management system | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf maintenance software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf maintenance app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardening business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardening business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardener CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardener management software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing app | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing CRM | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | mowing business software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | mowing business app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn business software | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimating | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn care estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care estimating app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care pricing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care billing software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care invoice app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care scheduling software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care routing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care dispatch software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care booking software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care booking app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn service proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn service invoicing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service routing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service billing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn service customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping estimating software | 20 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | landscaping estimating app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping proposal software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping proposal app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping pricing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping bid software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping invoicing software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping billing software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping scheduling software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping contract software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping customer management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping client portal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping job management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping business software | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping work order software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping crew management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping takeoff software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape estimating software | 20 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | landscape quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape proposal software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape bidding software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape contract management | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance estimating software | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | landscape maintenance scheduling software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance billing software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | grounds maintenance scheduling software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance contract software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardening quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardening invoice software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardener scheduling app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | gardener quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing estimating software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn mowing quote app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn mowing invoice app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing scheduling app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing route planner | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn care quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn care proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care quote form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care proposal example | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate example | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care price calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care cost calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care service contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care agreement template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care contract example | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care contract form | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care service description | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care service checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care service packages | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care service list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn maintenance service specifications | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance contract | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance agreement | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance proposal template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn maintenance estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance schedule | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance pricing | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance service description | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn maintenance bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| AU | landscaping proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote template | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping bid template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping estimate calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping cost calculator | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping estimate generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping quote generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping proposal generator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping contract template | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping service agreement | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscaping scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance scope of work | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance proposal template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | landscape maintenance bid template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance scope of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance specifications | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance tender | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | grounds maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance proposal | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance service agreement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden maintenance checklist | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing estimate | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn mowing quote | 90 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn mowing proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing bid | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing estimate template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing quote template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing contract template | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing contract | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing service agreement | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing cost calculator | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing price calculator | 30 | 返回正数 | 0/10 | 年龄未找到 | 混合意图/相邻需求 |
| AU | lawn mowing quote calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn mowing bid calculator | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn care proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | commercial lawn care contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn maintenance contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | commercial lawn mowing bid | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | residential lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | residential lawn care estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | residential lawn care contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | residential lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | HOA lawn maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | HOA landscaping proposal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | apartment lawn care quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | school grounds maintenance tender | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | sports turf maintenance contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | municipal mowing contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | cemetery mowing contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | property maintenance quote software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care pricing | 320 | 返回正数 | 9/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| AU | lawn care price list | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care rates | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care hourly rate | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care monthly cost | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care annual contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care subscription software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | recurring lawn care billing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | weekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | biweekly lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | monthly lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | annual lawn maintenance quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing per acre | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing per hour | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing per visit | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn mowing minimum charge | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn aeration estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn aeration quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn aeration pricing | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn dethatching quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn dethatching estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn scarifying quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn fertilization estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn fertilization quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn treatment quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn treatment contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn overseeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn overseeding quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn renovation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn renovation quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn edging quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn trimming quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn weed control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn pest control quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn topdressing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn seeding estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | sod installation estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | sod installation quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | turf laying quote | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn clippings removal cost | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | leaf removal estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | yard cleanup estimate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | spring cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | fall cleanup quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | garden waste removal quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn area measurement app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn measurement software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn area calculator | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | mowing time calculator | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care job costing | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care work orders | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care service report | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care digital signature | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care quote approval | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care recurring invoices | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care payment app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care crew scheduling | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care time tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care job tracking | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care CRM software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | free lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | best lawn care software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | online lawn care quotes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | instant lawn mowing quote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | mobile lawn care software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | small lawn business software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care scope of work template | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| AU | lawn care statement of work | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege App | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Verwaltungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Rasenpflege CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Rasenpflege System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Gartenpflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege App | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Verwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Verwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Software | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau App | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Verwaltungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Software | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Verwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice Verwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenservice Plattform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Software | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner App | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Verwaltungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Bürosoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Branchensoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Verwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenmanagement Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenmanagement App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenmanagement System | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mähservice Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mähservice App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Verwaltungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Planung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftspflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftspflege App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Planungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Vertragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Rasenpflege Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Gartenpflege Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Gartenpflege Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Planungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Vertragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Gartenpflege Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| DE | Grünflächenpflege Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Grünflächenpflege Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Grünflächenpflege Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Planungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Vertragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | GaLaBau Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | GaLaBau Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Planungssoftware | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Vertragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Planungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Auftragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Angebotssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Kalkulationssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Rechnungssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Vertragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Auftragsverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Landschaftsbau Kundenverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Grünflächenpflege Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Angebote erstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebots App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Angebots App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | GaLaBau Angebots App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Rechnungs App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Aufmaß App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Leistungsnachweis App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Einsatzplanung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Einsatzplanung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Zeiterfassung App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Zeiterfassung App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Tourenplanung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Tourenplanung App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Pflegeplanung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Pflegeplanung App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Nachkalkulation Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Ausschreibung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | GaLaBau Leistungsverzeichnis Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Gartenpflege Leistungsverzeichnis Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | GaLaBau Aufmaß Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Aufmaß Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenkataster Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenkataster App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Dokumentation App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Abrechnung Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Kalkulation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Angebot Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Angebot Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Kostenvoranschlag Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Leistungsumfang | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Leistungskatalog | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Leistungsverzeichnis Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Leistungsbeschreibung Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Pflegevertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Vertrag Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Vertrag Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Rasenpflege Jahresvertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Pflegeplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Checkliste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Maßnahmenplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Leistungsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Arbeitsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Abnahmeprotokoll | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Dokumentation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebot | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Kalkulation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebot Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Angebot Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Gartenpflege Kostenvoranschlag Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Gartenpflege Leistungsumfang | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungskatalog | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungsverzeichnis Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Gartenpflege Leistungsverzeichnis Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Pflegevertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Vertrag Vorlage | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Vertrag Muster | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Jahresvertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Pflegeplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Checkliste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Leistungsnachweis Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Arbeitsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Abnahmeprotokoll | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Tätigkeitsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Kalkulation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Angebot Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Angebot Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Ausschreibung | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Leistungsverzeichnis | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Grünflächenpflege Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Grünflächenpflege Leistungsumfang | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Leistungskatalog | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Leistungsverzeichnis Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Leistungsbeschreibung Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Pflegevertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Vertrag Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Vertrag Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Jahresvertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Pflegeplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Leistungsnachweis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Pflegevertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Kalkulation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünpflege Ausschreibung | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Angebot Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Angebot Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Kalkulation | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Angebot Muster | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Mäharbeiten Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| DE | Mäharbeiten Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Ausschreibung | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Rahmenvertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Angebot | 1000 | 返回正数 | 9/10 | 年龄未找到 | 排除：意图不匹配 |
| DE | Rasenmähen Kostenvoranschlag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Angebot Vorlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Vertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Preise | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Preisliste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Kosten | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Kosten berechnen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Kostenrechner | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Quadratmeterpreis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Stundenlohn | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Monatspauschale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Jahreskosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Pauschalangebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Preise | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Preisliste | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Kostenrechner | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Stundenlohn | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Monatspauschale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Jahrespauschale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Quadratmeterpreis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Kostenrechner | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Preise | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Kosten | 210 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Quadratmeterpreis | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Stundenlohn | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenmähen Kostenrechner | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Mäharbeiten Preisberechnung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Hausverwaltung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Wohnanlage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Gewerbe | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Privatgarten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Sportplatz | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Friedhof | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Wohnanlage Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Hausverwaltung Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Gewerbe Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Jahresangebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünflächenpflege Kommune Ausschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Sportplatzpflege Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Sportplatzpflege Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Sportplatzpflege Vertrag | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Sportplatzpflege Software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Sportplatzpflege App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Jahresplanung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Saisonplanung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen vertikutieren Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen vertikutieren Kosten | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen lüften Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen aerifizieren Kosten | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen düngen Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen düngen Kosten | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen nachsäen Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen nachsäen Kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasensanierung Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasensanierung Kosten | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasensanierung Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenrenovation Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenkanten schneiden Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenkanten schneiden Kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen mähen Leistungsbeschreibung | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenschnitt entsorgen Kosten | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Grünschnitt entsorgen Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Laub entfernen Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Unkrautbekämpfung Rasen Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Unkrautbekämpfung Rasen Kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen besanden Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen besanden Kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasen bewässern Kosten | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Zusatzleistungen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rollrasen verlegen Angebot | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rollrasen verlegen Kosten | 720 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| DE | Rasenneuanlage Angebot | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenneuanlage Leistungsverzeichnis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Pflegeintervalle | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Arbeitsumfang | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Vertragsleistungen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Zusatzarbeiten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Anfahrtspauschale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Entsorgungskosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Materialkosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Arbeitszeit berechnen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Software Vergleich | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau Software kostenlos | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gärtner Software kostenlos | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Software Vergleich | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Software Kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenpflege Software online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege digitale Angebote | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | GaLaBau digitale Unterschrift | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege wiederkehrende Rechnungen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Gartenpflege Aufträge verwalten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenflächen messen App | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| DE | Rasenfläche berechnen App | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application entretien pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application entretien gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel paysagiste | 260 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | application paysagiste | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion entreprise paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CRM paysagiste | 10 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| FR | système gestion paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| FR | plateforme paysagiste | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel jardinier | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application jardinier | 260 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | gestion entreprise jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CRM jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | système gestion jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | plateforme jardinage | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel espaces verts | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion espaces verts | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CRM espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel entretien jardins | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application entretien jardins | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion entretien jardins | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | appli jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | appli paysagiste | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel devis paysagiste | 30 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | application devis jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | application devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application devis tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel facturation paysagiste | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel facturation jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel facturation jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel facturation espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application facturation paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application facturation jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel planning paysagiste | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel planning jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel planning jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel planning espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application planning paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application planning jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion paysagiste | 20 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| FR | logiciel gestion jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion jardinage | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| FR | logiciel contrats entretien | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application contrats entretien | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion contrats espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion contrats jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion clients paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion clients jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion clients jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion commerciale paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion interventions paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion interventions jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion interventions espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application interventions paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application interventions jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel interventions jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel chiffrage paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel chiffrage jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel chiffrage espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel métrés paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel métrés espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application métrés jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel devis entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel devis entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | application devis entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application devis espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | application devis tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | logiciel planning entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel planning tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel gestion entretien jardins | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel tournées jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel tournées paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application tournées jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel suivi chantier paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel suivi entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application suivi entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application rapport intervention jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel rapport intervention jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel facturation entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel contrat entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | logiciel abonnement entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel devis paysagiste gratuit | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel paysagiste gratuit | 320 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | logiciel jardinier gratuit | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application jardinier gratuite | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | comparatif logiciel paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | logiciel paysagiste en ligne | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien espaces verts | 30 | 返回正数 | 0/10 | 年龄未找到 | 混合意图待确认 |
| FR | devis tonte pelouse | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis tonte gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis jardinage | 320 | 返回正数 | 8/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis paysagiste | 590 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 排除：意图不匹配 |
| FR | devis jardinier | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin annuel | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin mensuel | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis tonte régulier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle devis paysagiste | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle devis jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle devis entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | modèle devis entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | modèle devis tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | exemple devis jardinage | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | exemple devis paysagiste | 320 | 返回正数 | 8/10 | 样本中有年轻域名入榜，值得继续查 | 混合意图/相邻需求 |
| FR | exemple devis entretien jardin | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | exemple devis tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | exemple devis entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin détaillé | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul devis entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul prix tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul coût entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calculateur entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | simulateur devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | simulateur devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | simulateur entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | simulateur tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | générateur devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | générateur devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| FR | générateur devis entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis jardinage en ligne | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis paysagiste en ligne | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis tonte en ligne | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis pelouse en ligne | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis gazon en ligne | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat entretien pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | contrat entretien gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | contrat entretien jardin | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat entretien espaces verts | 30 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | contrat tonte pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat tonte gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle contrat entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | modèle contrat entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle contrat entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | modèle contrat tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat annuel entretien jardin | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat annuel espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat mensuel jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat jardinage particulier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat entretien jardin entreprise | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat tonte copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat entretien jardin copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat maintenance espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | cahier des charges pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | cahier des charges gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | cahier des charges jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | cahier des charges espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | cahier des charges tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CCTP entretien espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | CCTP entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | CCTP entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CCTP tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CCTP entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | CCTP entretien terrains sportifs | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | DCE entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | DPGF entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | BPU entretien espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | bordereau prix espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | descriptif entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | descriptif entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | descriptif entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prestations entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prestations entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prestations entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prestations entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | liste prestations jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche prestation tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche intervention jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche intervention espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche intervention tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | rapport entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | rapport intervention jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | compte rendu entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | planning entretien pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | planning entretien gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | planning entretien jardin | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | planning tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | planning annuel espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calendrier entretien gazon | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | plan entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | plan entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | plan entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche entretien gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fiche suivi espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien pelouse | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien jardin | 210 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | prix entretien espaces verts | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tarif tonte pelouse | 480 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | tarif tonte gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tarif jardinier | 480 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | tarif jardinage | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tarif paysagiste | 390 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | tarif horaire jardinier | 480 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | tarif horaire tonte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tarif tonte au m2 | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix tonte au m2 | 390 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | prix entretien pelouse m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien gazon m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien jardin annuel | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix entretien jardin mensuel | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | forfait entretien jardin | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | forfait tonte pelouse | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | forfait entretien pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | forfait entretien gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | abonnement entretien jardin | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | abonnement tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | abonnement entretien pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien pelouse copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien gazon copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien jardin copropriété | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien espaces verts entreprise | 590 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| FR | entretien pelouse entreprise | 30 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien pelouse particulier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien jardin résidence | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | entretien espaces verts collectivité | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tonte pelouse copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis tonte copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin copropriété | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien jardin entreprise | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | appel d’offres espaces verts | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | marché entretien espaces verts | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | marché tonte pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | consultation entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis entretien terrain sportif | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | contrat entretien terrain sportif | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis scarification pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis scarification gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix scarification pelouse | 140 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix scarification gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis aération pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis aération gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix aération pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis fertilisation pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis fertilisation gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix fertilisation gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis désherbage pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis désherbage gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix désherbage pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis traitement gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis traitement pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis regarnissage gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix regarnissage gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis rénovation pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix rénovation pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis rénovation gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis semis gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis réfection pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis pose gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis gazon rouleau | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prix pose gazon | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis sablage gazon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis terreautage pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis arrosage pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | devis découpe bordures | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tonte avec ramassage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | tonte sans ramassage | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | évacuation déchets verts devis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | ramassage feuilles devis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | nettoyage jardin devis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | remise en état jardin devis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fréquence tonte pelouse | 70 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | fréquence entretien espaces verts | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | prestations jardinage supplémentaires | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | limites prestations jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | avenant contrat jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | reconduction contrat entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | résiliation contrat entretien jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul surface pelouse | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application mesure pelouse | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | application mesure jardin | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | calcul rentabilité jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | suivi heures jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | gestion équipes paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | signature devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | validation devis jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | facturation récurrente jardinage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | portail client paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | relance devis paysagiste | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| FR | suivi devis jardinier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | CRM de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| ES | plataforma de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software para jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app para jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación para jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | CRM para jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software espacios verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app espacios verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión espacios verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software paisajismo | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app paisajismo | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aplicación paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software empresas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa empresas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | app presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | programa presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | aplicación presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | sistema presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | plataforma presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | software presupuestos jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | app presupuestos jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | programa presupuestos jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software presupuestos paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app presupuestos paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa presupuestos paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software cotizaciones jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | app cotizaciones jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | programa cotizaciones jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | sistema cotizaciones jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | software cotizaciones paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app cotizaciones paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software facturación jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app facturación jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa facturación jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software facturas jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app facturas jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software facturación paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software gestión jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| ES | app gestión jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa gestión jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software gestión jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app gestión jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa gestión jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software planificación jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app planificación jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software agenda jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app agenda jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software rutas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app rutas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software contratos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | app contratos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión contratos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | gestión clientes jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión clientes jardineros | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión clientes paisajismo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software partes jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app partes jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | partes trabajo jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión servicios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión equipos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | planificación mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programación mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | control mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | seguimiento mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | gestión operarios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | registro visitas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software jardinería gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | app jardinería gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software jardineros gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software jardinería precios | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | comparativa software jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | software jardinería online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| ES | presupuesto mantenimiento jardines | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto mantenimiento jardín | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| ES | presupuesto corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto de jardinería | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto de jardinero | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto de paisajismo | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto espacios verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| ES | cotización mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| ES | cotización servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla presupuesto jardinería | 10 | 返回正数 | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | modelo presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | ejemplo presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | formato presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla presupuesto jardinero | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo presupuesto jardinero | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla presupuesto césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo presupuesto césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | ejemplo presupuesto césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla presupuesto jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo presupuesto jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | ejemplo presupuesto jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla cotización jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo cotización jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | ejemplo cotización jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | formato cotización jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | plantilla cotización césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | formato cotización jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | generador presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | generador cotizaciones jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | calculadora presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | calculadora mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calculadora corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | calculadora corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calcular presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calcular presupuesto césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calcular precio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calcular costo césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | crear presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | hacer presupuesto jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardinería online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización jardinería online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto césped online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización césped online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardines online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardinería gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | contrato mantenimiento jardines | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | contrato corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo contrato jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | plantilla contrato jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | formato contrato jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | ejemplo contrato jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo contrato césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo contrato jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato anual jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mensual jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato anual jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mensual césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mantenimiento zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mantenimiento áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | alcance servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | alcance mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | alcance mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | alcance trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | alcance corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | descripción servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | descripción mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | descripción mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | especificaciones mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | especificaciones mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | pliego mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | pliego mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| ES | pliego técnico jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | pliego técnico zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | memoria técnica jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | memoria mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | propuesta mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | propuesta mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | propuesta servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | modelo propuesta jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plantilla propuesta jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | catálogo servicios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | lista servicios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | ficha servicio jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plan mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plan mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | plan mantenimiento zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | programa mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calendario mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calendario mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cronograma mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cronograma mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | informe mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | informe mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | informe trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | lista tareas jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | lista tareas césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | control trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | orden trabajo jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | órdenes trabajo jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | registro trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio mantenimiento jardines | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo corte pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | tarifas de jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | tarifas de jardinero | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | lista precios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio jardinero hora | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio corte césped m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio mantenimiento jardín m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo corte pasto m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio jardinería mensual | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costo jardinería mensual | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento césped residencial | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento césped comercial | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento jardines comunidades | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento jardines condominios | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento jardines empresas | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento áreas verdes empresas | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardines comunidades | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardines condominios | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto jardines empresas | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización jardines condominios | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización áreas verdes empresas | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | licitación mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | licitación mantenimiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | licitación áreas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | licitación zonas verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | concurso mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento campos deportivos | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | contrato mantenimiento campo deportivo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto escarificado césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio escarificado césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto aireación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio aireación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto fertilización césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio fertilización césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto abonado césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio abonado césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto deshierbe césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio deshierbe césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto resiembra césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio resiembra césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto renovación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio renovación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto recuperación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto tratamiento césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto riego césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto siega césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto bordes césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio perfilado césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | retiro residuos verdes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto recogida hojas | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto limpieza jardín | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto desbroce jardín | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización poda de césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización corte zacate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización corte grama | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio corte zacate | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio corte grama | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | cotización mantenimiento pasto | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto césped natural | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto instalación césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto colocación tepes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio colocación tepes | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | presupuesto siembra césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | precio siembra césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | medir césped app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | medir jardín app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | calculadora superficie césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | medición jardines software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | rentabilidad servicios jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | costes trabajos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | firma presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | seguimiento presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | aprobación presupuestos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | facturación recurrente jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | portal clientes jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | renovación contratos jardinería | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | frecuencia corte césped | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | frecuencia mantenimiento jardines | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | servicios jardinería incluidos | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | servicios jardinería adicionales | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento jardines por visita | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| ES | mantenimiento césped mensual | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | CRM giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | sistema gestione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piattaforma giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software giardinaggio | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app giardinaggio | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | CRM giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | sistema gestione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piattaforma giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| IT | CRM manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| IT | sistema manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| IT | piattaforma manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | sistema manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piattaforma manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software cura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app cura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software tappeti erbosi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app tappeti erbosi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione tappeti erbosi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software sfalcio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app sfalcio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software imprese giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale imprese giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app imprese giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | CRM imprese giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software aziende giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale aziende giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | programma preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | gestionale preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software preventivi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software preventivi manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software preventivi manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software preventivi taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | app preventivi taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | programma preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | generatore preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | generatore preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolatore preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software fatturazione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app fatturazione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | programma fatturazione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software fatturazione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app fatturazione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale fatture giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software gestione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software gestione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software gestione manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software gestione manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app gestione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app gestione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software interventi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app interventi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione interventi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione interventi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione clienti giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione clienti giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software contratti giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | gestione contratti giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione contratti manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | software programmazione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app appuntamenti giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software pianificazione giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app pianificazione giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software squadre giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione squadre giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app rapportini giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software rapportini giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | rapportini manutenzione verde app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software consuntivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione commesse giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software commesse giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software costi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app ore giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestione sopralluoghi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software capitolati manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software computi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software computo manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software preventivi giardinieri gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software giardinieri gratuito | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale giardinieri gratuito | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app giardinieri gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software giardinaggio prezzi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | confronto software giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale giardinieri online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | software giardinieri cloud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gestionale manutenzione verde online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| IT | preventivo manutenzione giardino | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione verde | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图待确认 |
| IT | preventivo taglio erba | 10 | 返回正数 | 0/10 | 年龄未找到 | 混合意图待确认 |
| IT | preventivo taglio prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo cura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo tappeto erboso | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo sfalcio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardinaggio | 50 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardiniere | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo aree verdi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello preventivo giardinaggio | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello preventivo giardiniere | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | esempio preventivo giardinaggio | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | esempio preventivo giardiniere | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | fac simile preventivo giardiniere | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modulo preventivo giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello preventivo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | modello preventivo manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello preventivo manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | modello preventivo taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | esempio preventivo manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | esempio preventivo taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | preventivo manutenzione prato online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione giardino online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardinaggio online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardiniere online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolo preventivo giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolo preventivo manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolo costo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolo costo taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolatore taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolatore manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | creare preventivi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | fare preventivo giardiniere | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | contratto manutenzione giardino | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione giardini | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione verde | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto cura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello contratto giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | modello contratto manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | modello contratto manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | fac simile contratto giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto annuale giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto annuale manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione verde condominiale | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto giardinaggio condominio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione giardino privato | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione parco | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione aree verdi | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | accordo manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | capitolato manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato manutenzione verde | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | capitolato taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato manutenzione aree verdi | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato tecnico giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato verde condominiale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | capitolato manutenzione tappeto erboso | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | disciplinare manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | disciplinare manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | specifiche manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | descrizione lavori giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | descrizione manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | descrizione servizio giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | descrizione lavori manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | elenco lavori giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | elenco servizi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | computo metrico giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | computo metrico manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | computo metrico taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | computo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | computo manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | elenco prezzi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | elenco prezzi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | elenco prezzi taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | analisi prezzi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | analisi prezzi taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | stima costi manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | stima costi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piano manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piano manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piano manutenzione verde | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | piano manutenzione tappeto erboso | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | programma manutenzione prato | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | programma manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calendario manutenzione prato | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calendario manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | scheda manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | scheda manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | scheda intervento giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | scheda controllo aree verdi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | rapportino lavori giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | rapportino manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | verbale sopralluogo giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | relazione manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | relazione tecnica giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | registro interventi giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo taglio erba | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo taglio prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo sfalcio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo manutenzione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo manutenzione giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo manutenzione giardino annuale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo manutenzione giardino mensile | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo taglio prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo taglio erba mq | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | prezzo manutenzione prato mq | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | tariffa oraria giardiniere | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | listino prezzi giardinieri | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | listino prezzi giardinaggio | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | tariffe manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione prato condominiale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione giardini condominiali | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione verde aziendale | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione giardini privati | 320 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| IT | manutenzione verde pubblico | 210 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| IT | manutenzione campi sportivi | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardinaggio condominio | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo verde condominiale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo giardino privato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione verde aziendale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo manutenzione campo sportivo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | contratto manutenzione campo sportivo | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | appalto manutenzione verde | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gara manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | gara sfalcio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | offerta manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | offerta taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | offerta manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo arieggiatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo arieggiatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo scarificatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo scarificatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo concimazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo concimazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo diserbo prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo diserbo prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo disinfestazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo trattamento prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo trasemina prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo trasemina prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo rigenerazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo rigenerazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo rifacimento prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo rifacimento prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo sabbiatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo sabbiatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo semina prato | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo semina prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo prato rotoli | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo posa prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo posa prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo irrigazione prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo bordatura prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo rifinitura bordi prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo raccolta foglie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo smaltimento sfalci | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo smaltimento erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | preventivo pulizia giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | sfalcio con raccolta | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | sfalcio senza raccolta | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | taglio erba periodico | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | taglio erba settimanale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione prato annuale | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | manutenzione prato mensile | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | frequenza taglio erba | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | frequenza manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | servizi giardinaggio inclusi | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | lavori giardinaggio extra | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | variante contratto giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | rinnovo contratto manutenzione verde | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app misurare prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | app misurare giardino | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | calcolo superficie prato | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | costo orario giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | redditività commesse giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | pianificazione squadre giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | firma preventivo giardiniere | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | approvazione preventivo giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | invio preventivi giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | fatturazione ricorrente giardinaggio | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | portale clienti giardinieri | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| IT | scadenzario manutenzione giardini | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | software voor hoveniers | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | app voor hoveniers | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers administratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | CRM voor hoveniers | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | systeem voor hoveniers | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | platform voor hoveniers | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| NL | hoveniers app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| NL | hoveniers bedrijfssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud app | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenvoorziening software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenvoorziening app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gras maaien app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf administratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf systeem | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniersbedrijf platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenbeheer software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenbeheer app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenbeheer systeem | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenbeheer platform | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | terreinonderhoud software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | terreinonderhoud app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers offertesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | hoveniers calculatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | hoveniers calculatieprogramma | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | hoveniers facturatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers factuur app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers planningssoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers planning app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers werkbon app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers werkbonnen software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers urenregistratie app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers urenregistratie software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers klantbeheer software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers projectadministratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers contractbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers onderhoudsplanning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers calculatie app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers nacalculatie software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers projectbeheer software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers personeelsplanning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers opdrachtbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers werkplanning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers routeplanning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers digitaal offreren | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers digitale werkbon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers online factureren | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud offertesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | tuinonderhoud offerte app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | tuinonderhoud calculatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | tuinonderhoud facturatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud planning software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud werkbon app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud contractbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| NL | tuinonderhoud klantbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud abonnement software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud afspraken app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud routeplanning software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud urenregistratie app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud offertesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | groenonderhoud offerte app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud calculatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | groenonderhoud facturatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud planning software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud werkbon app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud contractbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| NL | groenonderhoud klantbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud urenregistratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud opdrachtbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud onderhoudsplanning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud rapportage app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud offertesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud offerte app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud calculatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud facturatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud planning software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud contractbeheer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| NL | maaiwerk calculatiesoftware | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | maaiwerk offerte app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | maaiwerk planning software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk registratie app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maairoutes plannen app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk rapportage app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware vergelijken | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers app gratis | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenierssoftware cloud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| NL | gazononderhoud prijsopgave | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud kostenraming | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud calculatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud offerte voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud offerte maken | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud offerte | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud prijsopgave | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud kostenraming | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud calculatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud offerte voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | tuinonderhoud offerte maken | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud prijsopgave | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud kostenraming | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud calculatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud offerte voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud offerte maken | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenier offerte | 140 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenier offerte voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenier offerte maken | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gras maaien offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien prijsopgave | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk calculatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk kostenraming | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | voorbeeld offerte gazononderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | voorbeeld offerte tuinonderhoud | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | voorbeeld offerte groenonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte sjabloon tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte sjabloon groenonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte sjabloon gazononderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerteformulier tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerteformulier gazononderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte opstellen hovenier | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte berekenen tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte berekenen gazononderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offertegenerator hoveniers | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | offertegenerator tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | kostencalculator tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | kostencalculator gazononderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | kostencalculator grasmaaien | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | offerte tuinonderhoud online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte gazononderhoud online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte grasmaaien online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte groenonderhoud online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte hovenier online | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte tuinonderhoud aanvragen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte gazononderhoud aanvragen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud onderhoudscontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | gazononderhoud overeenkomst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud contract voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | gazononderhoud jaarcontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud abonnement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud contract | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud onderhoudscontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud overeenkomst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud contract voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud jaarcontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud abonnement | 90 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud onderhoudscontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud overeenkomst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud contract voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud jaarcontract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud abonnement | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudscontract tuin voorbeeld | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudscontract gazon voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudscontract groenvoorziening voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | contract grasmaaien voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | overeenkomst tuinonderhoud voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | modelovereenkomst tuinonderhoud | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud werkomschrijving | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | gazononderhoud werkzaamheden | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud bestek | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | gazononderhoud werkprogramma | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud onderhoudsplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud onderhoudsschema | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud werkomschrijving | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud werkzaamheden | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud bestek | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud werkprogramma | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud onderhoudsplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud onderhoudsschema | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud werkomschrijving | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud werkzaamheden | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud bestek | 10 | 返回正数 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | groenonderhoud werkprogramma | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud onderhoudsplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud onderhoudsschema | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaibestek voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | maaibestek opstellen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk werkomschrijving | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | maaiwerk bestek | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk planning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk onderhoudsplan | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | bestek groenonderhoud voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | werkomschrijving tuinonderhoud voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| NL | werkomschrijving gazononderhoud voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudsplan gazon voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudsplan tuin voorbeeld | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoudsplan groen voorbeeld | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud checklist | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud werkbon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud werkbon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud werkbon | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud rapportage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud rapportage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud rapportage | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk registratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud kwaliteitscontrole | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud opleverrapport | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud prijzen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud tarieven | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud prijslijst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud kosten berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud prijs m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud kosten | 40 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud prijzen | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud tarieven | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud prijslijst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud maandprijs | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud uurprijs | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien prijzen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien tarieven | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gras maaien uurprijs | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gras maaien prijs m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk prijs hectare | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenier uurtarief | 170 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hovenier tarievenlijst | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud prijs m2 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud kosten berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud maandkosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud jaarkosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud bedrijven | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud particulieren | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud VvE | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud VvE | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud bedrijventerrein | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud woningcorporatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | onderhoud bedrijfstuin offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud VvE offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud VvE contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | groenonderhoud aanbesteding | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaiwerk aanbesteding | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud aanbesteding | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud contract | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud bestek | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud software | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | sportveldonderhoud planning | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon verticuteren offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon verticuteren kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon beluchten offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon beluchten kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon bemesten offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon bemesten kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon doorzaaien offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon doorzaaien kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazonrenovatie offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazonrenovatie kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon herstellen offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon bezanden kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon onkruidbestrijding offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon mosbestrijding kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazonkanten steken offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazonkanten knippen kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasafval afvoeren kosten | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | bladruimen offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | voorjaarsbeurt tuin offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | najaarsbeurt tuin offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinafval afvoeren offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon aanleggen offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | graszoden leggen offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gras zaaien offerte | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien met afvoer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | grasmaaien zonder afvoer | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud frequentie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud extra werkzaamheden | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazononderhoud meerwerk | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud contract verlengen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon meten app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuin meten app | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | gazon oppervlakte berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | maaitijd berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers kostprijs berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers winst berekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | offerte hovenier digitaal ondertekenen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers offertes opvolgen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | tuinonderhoud terugkerende facturen | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers klantenportaal | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers automatische facturatie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| NL | hoveniers mobiele administratie | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| JP | 芝生管理 クラウド | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 プラットフォーム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| JP | 芝生管理 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 管理システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 予約システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り マッチングアプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り ソフト | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り アプリ | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 管理システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 予約システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り マッチングアプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 管理システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 CRM | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| JP | 造園業 クラウド | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 プラットフォーム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 ソフト | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 アプリ | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 顧客管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 業務システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 管理ツール | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 クラウド | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 プラットフォーム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 クラウド | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 プラットフォーム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 顧客管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 クラウド | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 業務管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 積算ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 積算システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 造園 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 積算ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 造園 積算アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積作成ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積作成アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 積算ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 費用計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝刈り 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝刈り 見積システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 草刈り 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 草刈り 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 積算ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 植栽管理 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 植栽管理 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 積算ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 緑地管理 見積アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 見積ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 請求ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 請求書アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 請求管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 契約管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| JP | 造園業 顧客管理システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 原価管理ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 工程管理ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 現場管理アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 施工管理アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 日報アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 作業管理アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 受発注システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 スケジュール管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 作業員管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 勤怠管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 営業管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 案件管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 入金管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業記録アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 スケジュールアプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 作業記録アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り スケジュールアプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 作業管理アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 日報アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 作業計画ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 作業報告アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 作業報告アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 写真管理アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 電子契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 電子見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 ソフト 比較 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 ソフト 無料 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積ソフト 無料 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積アプリ 無料 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 積算ソフト 比較 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 クラウド 料金 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 混合意图待确认 |
| JP | 芝生管理 見積書 テンプレート | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積書 書き方 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積例 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 積算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 料金 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 単価表 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 料金表 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 費用 相場 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 平米単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 年間費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 月額 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 定期契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 年間契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務委託 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 契約書 雛形 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 委託契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 特記仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 作業範囲 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 作業内容 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 サービス内容 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務内容 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業項目 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業一覧 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 仕様書 雛形 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 仕様書 例 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 計画書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 年間計画 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業計画書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 チェックリスト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業報告書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 報告書 雛形 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業日報 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業記録 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 点検表 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 管理台帳 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積書 テンプレート | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝刈り 見積書 例 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 料金 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 料金表 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 平米単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 時間単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 費用計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積 自動計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 見積 オンライン | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 定期契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 年間契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 作業範囲 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 作業報告書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積 | 210 | 返回正数 | 8/10 | 已知年龄样本未见近18个月域名 | 排除：意图不匹配 |
| JP | 草刈り 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積書 テンプレート | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積書 書き方 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積書 例 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 料金表 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 平米単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 時間単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 見積 オンライン | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 年間契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 定期契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 契約書 雛形 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 業務仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 作業範囲 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 作業報告書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積書 テンプレート | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積書 書き方 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積書 例 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積 自動作成 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 積算 単価 | 20 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 見積書 テンプレート | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 年間見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 緑地管理 特記仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 緑地管理 年間計画 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 見積書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 作業範囲 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭園管理 年間契約 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 提案書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 企画提案書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務内訳書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 数量計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 設計書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 歩掛 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 入札 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 委託業者 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業者 比較 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業者 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 業者 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 業者 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | マンション 芝生管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | マンション 芝刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | マンション 植栽管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | マンション 植栽管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 企業 芝生管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 工場 緑地管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 公園 芝生管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 公園 芝刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 学校 芝生管理 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 校庭 芝生管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 競技場 芝生管理 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | サッカー場 芝生管理 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | ゴルフ場 芝生管理 システム | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | ゴルフ場 コース管理 ソフト | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | ゴルフ場 芝生管理 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 墓地 芝刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 個人宅 芝生管理 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 庭 芝刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 エアレーション 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 エアレーション 費用 | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 サッチ除去 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 サッチ除去 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 施肥 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 施肥 単価 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 除草 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 除草 費用 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 除草剤散布 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 薬剤散布 単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 病害虫防除 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 防除 仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 目土 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 目土 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 更新作業 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 補修 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 張り替え 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 張り替え 費用 | 210 | 返回正数 | 9/10 | 已知年龄样本未见近18个月域名 | 历史扩展词，不纳入主评分 |
| JP | 芝張り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝張り 平米単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 種まき 見積 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 水やり 代行 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 散水管理 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 刈り込み 単価 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 キワ刈り 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 刈草回収 費用 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 処分費 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 集草 単価 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 草刈り 刈草処分 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 落ち葉清掃 見積 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 追加作業 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 追加料金 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業頻度 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 雨天対応 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 契約更新 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 作業回数 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 面積測定 アプリ | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生 面積計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝刈り 作業時間 計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園 見積 原価計算 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 定期請求 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 顧客台帳 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積承認 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積比較 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 造園業 見積履歴 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 作業写真 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 完了報告 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 植栽管理 業務範囲 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 サービス仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務委託仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| JP | 芝生管理 維持管理仕様書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 見積依頼 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 管理項目 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| JP | 芝生管理 業務委託契約書 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 소프트웨어 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 플랫폼 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 솔루션 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 플랫폼 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 솔루션 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업체 관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업체 관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업체 관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업체 CRM | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 조경업체 업무관리 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경업 CRM | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 고객관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 조경 고객관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 영업관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 플랫폼 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 플랫폼 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 유지관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 유지관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 작업관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 작업관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 작업관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 예약 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 예약 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 예약 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 견적 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 소프트웨어 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 견적 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 관리 견적 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 관리 견적 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 깎기 견적 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 견적 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 유지관리 견적 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 유지관리 견적 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 정원 관리 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 예초 견적 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 제초 견적 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 견적 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적서 작성 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 견적서 작성 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 내역서 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 조경 적산 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 적산 소프트웨어 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 원가계산 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 단가산출 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 공사비 산출 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 물량산출 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 계약관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 계약관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 조경 유지관리 계약관리 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 정기청구 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 작업일지 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 작업일보 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 현장관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 현장관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 일정관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 일정관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 작업일지 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 작업기록 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 작업계획 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 작업일정 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리이력 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 작업배정 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 인력관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 근태관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 장비관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 사진관리 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 작업보고 앱 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 프로그램 비교 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 프로그램 가격 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 프로그램 무료 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 앱 무료 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 클라우드 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 통합관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 混合意图待确认 |
| KR | 잔디 관리 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 관리 견적서 예시 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 견적 비교 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 비용 산출 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 견적 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 견적서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 내역서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 유지관리 단가 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 용역 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 깎기 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 가격표 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 견적서 예시 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 단가산출 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 비용 계산 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 비용 계산 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 용역 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 견적 | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 견적 비교 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 대행 비용 | 110 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 비용 계산 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 관리 계약 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 견적 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 견적서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 견적서 양식 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 조경 유지관리 견적서 예시 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적서 예시 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적서 작성 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적서 자동작성 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 자동계산 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 비교 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 견적서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 녹지 관리 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 공원 관리 견적서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 관리 업무범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 서비스 내용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업내역 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 유지관리 시방서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 유지관리 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 깎기 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 작업범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 특기시방서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 시방서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 조경 유지관리 업무범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 작업범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 용역 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 특기시방서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 내역서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 산출내역서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 조경 관리 설계내역서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 물량내역서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 단가산출서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 서비스 범위 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 작업범위 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 용역 내역서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 과업지시서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 계약서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 계약서 양식 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 잔디 관리 용역계약서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 연간계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 정기계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 위탁계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 계약서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 정기계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 용역계약서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 용역계약서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 벌초 대행 계약서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 계약서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 계약서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 계약서 양식 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 조경 유지관리 용역계약서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 연간계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 위탁계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 계약조건 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 제안서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 계획서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 연간계획 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업계획서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 일정표 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 점검표 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 체크리스트 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업일지 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업일보 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 보고서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 완료보고서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업확인서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 제안서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 계획서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 연간계획서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 작업계획서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 작업일지 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 완료보고서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 비용 | 10 | 返回正数 | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 가격 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 단가표 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 평당 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 연간 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 월 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 평당 가격 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 면적당 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 인건비 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 시간당 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 평당 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 면적당 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 비용 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 단가표 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 월 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 연간 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 관리 월 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 정기서비스 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 아파트 잔디 관리 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 아파트 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 아파트 조경 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 아파트 조경 유지관리 시방서 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 공장 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 기업 조경 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 학교 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 학교 잔디 관리 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 운동장 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 축구장 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 공원 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 공원 잔디 관리 시방서 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 골프장 잔디 관리 프로그램 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 골프장 코스 관리 시스템 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 골프장 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 묘지 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 전원주택 잔디 관리 견적 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 정원 잔디 관리 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 용역 입찰 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 용역 공고 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 관리 용역 입찰 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 유지관리 업체 선정 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 용역 입찰 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 제초 용역 입찰 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 통기작업 견적 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 통기작업 비용 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 에어레이션 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 시비 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 시비 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 비료 살포 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 배토 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 배토 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 갱신작업 견적 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 보수 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 보식 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 보식 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 파종 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 파종 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 식재 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 식재 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 교체 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 교체 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 제초 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 제초제 살포 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 병충해 방제 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 약제 살포 단가 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관수 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 예지물 처리 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 부산물 수거 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 예초 폐기물 처리 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 낙엽 수거 견적 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 가장자리 정리 비용 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 추가작업 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 추가비용 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 깎기 작업주기 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 작업횟수 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 관리 계약갱신 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 면적 측정 앱 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 잔디 면적 계산 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 원가관리 프로그램 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 견적 승인 | 0 | 供应商返回0（旧脚本记录；未获原始响应复核） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 전자계약 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 고객관리 시스템 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| KR | 조경 정기작업 관리 | 未找到 | 未返回（旧记录未找到；无批次报错） | 0/10 | 年龄未找到 | 历史扩展词，不纳入主评分 |
| US | lawn care proposal app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care bid software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn care contract app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| US | lawn care management software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| US | lawn care management system | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| US | lawn service quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn maintenance estimating software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| US | lawn mowing quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care proposal app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care bid software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn care contract app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| UK | lawn care management software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| UK | lawn care management system | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| UK | lawn service quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn maintenance estimating software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| UK | lawn mowing quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care proposal app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care bid software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn care contract app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| CA | lawn care management software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| CA | lawn care management system | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| CA | lawn service quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn maintenance estimating software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| CA | lawn mowing quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care proposal app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care bid software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn care contract app | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| AU | lawn care management software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| AU | lawn care management system | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| AU | lawn service quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn maintenance estimating software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| AU | lawn mowing quote software | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| DE | Rasenpflege Managementsystem | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| FR | logiciel contrats paysagiste | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| FR | plateforme devis paysagiste | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | software presupuestos mantenimiento césped | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| ES | app presupuestos mantenimiento césped | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software computi manutenzione verde | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| IT | software capitolati giardinaggio | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| IT | piattaforma preventivi giardinaggio | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud offerte programma | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | hoveniers offerteplatform | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | hoveniers offertesysteem | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| NL | gazononderhoud offerte sjabloon | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 芝生管理 見積計算ツール | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| JP | 造園業 見積管理システム | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 천연잔디 관리 프로그램 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 천연잔디 관리 소프트웨어 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 천연잔디 관리 시스템 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 잔디 유지관리 플랫폼 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 相邻：经营管理 |
| KR | 조경 견적관리 프로그램 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 报价制作候选词 |
| KR | 잔디 관리 서비스 범위 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
| KR | 천연잔디 유지관리 용역계약서 | 未找到 | 未查询 | 0/10 | 年龄未找到 | 范围说明辅助词，条件承接 |
