# 第 2 课：一手来源包

核对日期：**2026-11-03**。本页选定三篇公开可读的原始研究供训练；它们是**固定教学选文**，不是系统综述、完整检索或截至该日全部最新证据。元数据按正式期刊版核对，方法和结果按原文全文核对；不以搜索摘要代替全文。下文均为必要的中文短转述，不复制论文全文或图表。

本课问题：**临床医生在病例评测任务中使用大模型辅助，与常规资源相比，诊断推理或鉴别诊断表现怎样？** P1、P2直接涉及医生使用 AI；P3用于练习识别相邻问题，三篇不能当作同一种干预合并结论。

<a id="p1"></a>

## P1：Goh 2024——医生使用 GPT-4 的随机试验

Goh E, Gallo R, Hom J, et al. **Large Language Model Influence on Diagnostic Reasoning: A Randomized Clinical Trial.** *JAMA Network Open*. 2024;7(10):e2440969. DOI：[10.1001/jamanetworkopen.2024.40969](https://doi.org/10.1001/jamanetworkopen.2024.40969)。正式期刊论文，在线发表于 2024-10-28；本课不使用早期预印本作为引用版本。

阅读：[PMC 全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/) · [PubMed 元数据与摘要](https://pubmed.ncbi.nlm.nih.gov/39466245/)。

- **场景与单位：**50 名医生参加限时书面病例评测，使用 6 个病例题；不是 50 名患者的临床试验。
- **比较：**医生可用 GPT-4 加常规资源，对比医生仅用常规资源。直接回答本课问题；模型单独作答是另行分析。
- **主要结局：**结构化诊断推理评分的中位数为 76% 对 74%；调整差值 2 个百分点，95% CI −4 至 8，P=.60。它不是患者诊断准确率；未检出显著差异不等于证明等效。
- **范围：**研究在 2023-11-29 至 12-29 开展，使用 ChatGPT Plus（GPT-4）；原文未提供可固定复现的 API 检查点。病例少、使用方式不统一，不能直接推出真实诊疗收益。

**回原文核查：**[Methods → Study Design](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/#H2-3-ZOI241182) 核对分组；[Study Outcomes](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/#H2-5-ZOI241182) 核对评分定义；[Results → Primary Outcome: Diagnostic Performance](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/#H2-7-ZOI241182) 与 [Table 2](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/#zoi241182t2) 核对数值。模型单独作答见 [LLM Alone](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/#H2-10-ZOI241182)，不要替换医生使用 AI 的结果。

<a id="p2"></a>

## P2：McDuff 2025——AMIE 辅助鉴别诊断

McDuff D, Schaekermann M, Tu T, et al. **Towards accurate differential diagnosis with large language models.** *Nature*. 2025;642:451–457. DOI：[10.1038/s41586-025-08869-4](https://doi.org/10.1038/s41586-025-08869-4)。正式期刊论文，在线发表于 2025-04-09；本课使用正式版而非 2023 年预印本。

阅读：[PMC 全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/) · [期刊全文](https://www.nature.com/articles/s41586-025-08869-4) · [PubMed 元数据与摘要](https://pubmed.ncbi.nlm.nih.gov/40205049/)。

- **场景与单位：**20 名内科医生评读 302 篇已发表的 NEJM 临床病理讨论病例；302 是病例报告数，不是医生数或前瞻性入组患者数。
- **比较：**每个病例由两名医生分属不同辅助条件评读；先独立列鉴别诊断，再用 AMIE 加可选常规资源，或仅用搜索等常规资源修订。直接涉及本课问题；另有模型单独表现。
- **主要结果：**AMIE 辅助后的鉴别诊断列表表现优于搜索辅助；不能把模型单独表现当作协作效果。
- **范围：**研究版 AMIE 基于 PaLM 2-L；病例报告覆盖 2013–2023 年，2025 年为发表年。挑战性病例的评读不同于日常接诊，尚不能据此认定临床获益。

**回原文核查：**[Methods → Experimental design](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/#Sec17) 核对先后步骤与分配；[NEJM CPC case reports](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/#Sec11) 核对病例来源；[AMIE as a DDx assistant](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/#Sec3) 与 [Fig. 2](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/#Fig2) 核对协作结果及评价方式；[Limitations](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158753/#Sec8) 核对外推边界。抄录数字时注明指标、评价方式和原文位置，避免混用列表质量分与不同评价方式下的准确率。

<a id="p3"></a>

## P3：Tu 2025——模拟诊断对话的比较

Tu T, Schaekermann M, Palepu A, et al. **Towards conversational diagnostic artificial intelligence.** *Nature*. 2025;642:442–450. DOI：[10.1038/s41586-025-08866-7](https://doi.org/10.1038/s41586-025-08866-7)。正式期刊论文，在线发表于 2025-04-09；本课使用正式版。

阅读：[PMC 全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158756/) · [期刊全文](https://www.nature.com/articles/s41586-025-08866-7) · [PubMed 元数据与摘要](https://pubmed.ncbi.nlm.nih.gov/40205050/)。

- **场景与单位：**20 名基层医生、20 名患者扮演者参与模拟文字问诊，正式版共 159 个场景；不是 159 名真实患者。145 仅为加拿大与印度场景包，另有 14 个英国场景。
- **比较及相关性：**AMIE 与医生分别问诊同一模拟场景，并非医生加 AI 对比常规资源，不能直接回答本课的协作问题。
- **主要结果：**专家评价中 AMIE 的鉴别诊断准确性高于医生；这是模拟对话表现，不是患者结局。
- **范围：**AMIE 为基于 PaLM 2 的研究系统，2025 年发表；结论只适用于文中系统和任务。同步文字问诊与医生日常流程有差异，不能外推为替代医生或真实临床收益。

**回原文核查：**[Methods → Remote OSCE study design](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158756/#Sec34) 明列 159 个场景的来源：印度 75、加拿大 70、英国 14；[Online text-based consultation](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158756/#Sec35) 核对两次独立问诊；[Differential diagnosis accuracy](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158756/#Sec2) 与 [Fig. 3](https://pmc.ncbi.nlm.nih.gov/articles/PMC12158756/#Fig3) 核对结果。补充材料中的 145 个场景包不可替代正式版总数。

## 使用和核查说明

三篇研究使用的模型、任务与评价指标不同；发表年份也不等于模型版本日期。不要用今天同名产品的一次回答复现或否定当时研究，更不要把三篇组成临床应用推荐。

本次核对使用上述 PubMed 元数据及原文全文。PMC 或期刊页面在部分网络环境可能出现验证或跳转；可改用另一公开入口。供进一步核查的 Europe PMC 原文结构化接口：[P1 全文](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC11519755/fullTextXML)、[P2 全文](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC12158753/fullTextXML)、[P3 全文](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC12158756/fullTextXML)。本次已据这些全文核对相关方法和结果。无需运行代码；若原文暂时无法访问，按课内材料完成纸面练习，并在自己的检索日志中记录无法复核的项目，不猜填。

返回：[本课](README.md) · [练习](practice.md) · [参考答案](answer-key.md)
