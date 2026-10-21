# 健康与长寿 · 立项说明与总纲

立项日期：2026-10-20。本类是「领域学习谱系」五类中的第二类，按《分类总纲》定版的推进顺序，紧接量化交易之后开工。理由写在总纲里：这一类直接对应 Ezra 本人「活到 150 岁」的长期目标，个人动机最强；药品医药窗口已有长寿前沿的供料基础，材料来源现成。本文件定本类的总纲：收什么、不收什么、按什么顺序学、证据怎么标、经典材料有哪些。


支持与更多：[GitHub Sponsors](https://github.com/sponsors/Ezra-Zhao) · [Gumroad — 我在用的模板与工作簿](https://ezraflow28.gumroad.com) · [Ko-fi](https://ko-fi.com/ezra777zhao)

## 一、先把这个领域的特殊性说清楚

健康与长寿是五个领域里离「带货与神药」最近的一个，也是离他的个人实践最近的一个。总纲定的标准是五类里最严的：**宁可慢，不许把传闻写成结论。**具体化为三条红线，写在最前面，长期有效：

1. **只做教育整理，不给健康建议。**本谱系讲「衰老这门科学在研究什么、工具怎么用、证据怎么分级」，不写具体诊疗建议、不写用药指导、不推荐任何保健品与干预方案。任何人读完想采取行动，行动的前提是咨询自己的医生——这句话不是免责套话，是本类的立场。
2. **健康主张一律标证据等级**（Ezra 2026-10-01 定的规矩，全线沿用）：**A**＝有荟萃分析、大型队列或随机对照试验（RCT），且有具体数字可查；**B**＝有研究支持，但样本小、数字不确切或只有观察性证据；**C**＝经验之谈、专家观点或动物实验外推。A 级只说明数字可核，不保证因果。
3. **不写任何「照做能长寿」式承诺。**目前人类科学能拿出的最强结论，是某些生活方式因素与更低的死亡风险相关（多为 B 级观察性证据）、少数干预在 RCT 里改变了生物年龄的替代指标（如 CALERIE 试验，A 级，见经典清单）。「活到 150 岁」是 Ezra 的目标与愿景，不是现有科学的结论——本谱系的任务是把通向这个目标的真实知识地形画出来，包括哪里是路、哪里还是雾。

## 二、本类总纲

### 收录范围（照《分类总纲》第五类执行）

1. **衰老生物学**：衰老标志（hallmarks of aging）框架、细胞衰老、表观遗传重编程等机制研究的经典论文与开放材料。
2. **长寿科研的里程碑与试验**：大型队列、随机对照试验、标志性研究项目（如 CALERIE、Blue Zones、百岁老人队列），只报道设计与结果，并标证据等级。
3. **健康监测与量化自我的开源工具**：可穿戴数据、活动与睡眠记录、运动与营养追踪——前提是开源、自托管或数据自主，数据主权在使用者手里。
4. **生物年龄与生物标志物的计算工具**：表观遗传时钟、表型年龄、器官年龄等已发表算法的官方或代表性开源实现。
5. **开放数据与数据库**：NHANES 这类公开人群健康数据、HAGR/Open Genes/Aging Atlas 这类衰老研究数据库。
6. **生活方式医学的开放教材与课程**：大学与研究机构的公开课，只列名目出处，不搬运付费内容。

### 不收

- 具体疾病的诊疗建议、用药指导（包括「某药抗衰老该怎么吃」式的超说明书用法指导）——已有临床证据的药物干预只作研究进展报道，写清「试验进行中／仅动物数据」等状态。
- 保健品带货、长寿诊所与付费检测服务的软文式收录。
- 未经证实的「抗衰神药」宣传、名人个案外推（「某富豪的方案」类内容只在批判性语境下提及）。
- 需要湿实验资质的病原与基因编辑操作细节（与生物学类的排除口径一致）。

### 学习路线（草案，随批次细化为正式路线图）

- 阶段 0 概念地基：先分清寿命（lifespan）与健康寿命（healthspan）、实际年龄与生物年龄、相关与因果、替代指标与硬终点（死亡率）——这个领域的九成忽悠死在这四个概念的混淆上。
- 阶段 1 衰老生物学：衰老标志框架（2013 九条 → 2023 十二条），知道细胞层面「老」指的是什么。
- 阶段 2 先量自己：监测层工具上手——可穿戴数据拿回自己手里、运动与营养记录跑起来、活动与睡眠有连续数据。先有自己的数据，再谈指标。
- 阶段 3 看懂指标：生物标志物清单与常规体检面板逐项学——每一项测的是什么、正常范围怎么定的、单项异常说明什么与不说明什么。
- 阶段 4 生物年龄计算：用 BioAge 在 NHANES 公开数据上亲手跑一遍表型年龄与 KDM，再读表观遗传时钟的原理（Horvath 时钟、DunedinPACE），理解「生物年龄」是模型输出、不是体检真理。
- 阶段 5 证据分级读干预：拿 CALERIE 做样本，把一项干预从动物实验、观察性研究、RCT 到荟萃分析的证据链走一遍；此后任何「新突破」都用同一把尺子量。

### 与既有线的关系

- **给他的长寿目标供料**：本谱系是「活到 150 岁」这个目标的知识底座——目标归目标，谱系只负责把地形画准，不负责把愿景说成科学。
- **与药品医药窗口双向供料**：那个窗口管当下情报（观察清单、并购雷达、长寿前沿动态），本谱系管底层知识体系（长效教育）。窗口里的 GLP-1、二甲双胍、雷帕霉素等话题，在谱系里对应到「代谢与衰老通路」这类知识节点，只讲研究状态与证据等级，不讲用法。
- **与飞轮医疗线衔接**：飞轮的医疗/长寿内容若引用本谱系材料，证据等级标注随材料一起走，不许在转述中升级。

## 三、经典学习材料清单（只列名目与出处，逐个核实存在；导读随后续批次展开）

### 书籍

- David A. Sinclair & Matthew D. LaPlante, *Lifespan: Why We Age—and Why We Don't Have To*（Atria Books, 2019）——把「衰老是一种可干预的信息丢失」讲给大众听的现象级科普，作者是哈佛医学院遗传学教授。读法提醒：书中的机制框架（表观遗传信息理论）是**一家之说**，NMN、白藜芦醇等具体主张的人类证据至今未定，按 B/C 级读，不当结论读。
- Nir Barzilai & Toni Robino, *Age Later: Health Span, Life Span, Lifestyle, and the New Science of Longevity*（St. Martin's Press, 2020-06-16，本次已核实出版信息）——爱因斯坦医学院衰老研究所所长写自己的研究：百岁老人（SuperAgers）队列告诉我们什么、为什么他要推动 TAME 试验（用二甲双胍验证「衰老本身可以被当作干预靶点」；该试验至今尚未启动，见下文 TAME 条，无结果可引）。队列部分是 B 级观察性证据，展望部分是 C 级，按这个口径读。
- Peter Attia & Bill Gifford, *Outlive: The Science and Art of Longevity*（Harmony Books, 2023）——临床医生写的「医学 3.0」框架书：运动、睡眠、营养、情绪四根支柱 + 代谢健康。它的生活方式部分与主流指南共识重合度较高；涉及药物的部分属临床判断范畴，本谱系不展开、不复述用法。
- Dan Buettner, *The Blue Zones: Lessons for Living Longer from the People Who've Lived the Longest*（National Geographic, 2008）——「蓝区」概念的源头读物（冲绳、撒丁岛、洛马林达等长寿人群的生活方式观察）。证据等级 B：观察性与人口学材料，无对照；且蓝区的百岁认定近年有方法学争议（出生记录质量问题），只作生活方式的观察样本读，不作处方读。
- Aubrey de Grey & Michael Rae, *Ending Aging*（St. Martin's Press, 2007）——SENS 路线（把衰老看作七类可修复的损伤）的宣言书，了解长寿领域「工程派」思想源头的一本；具体技术路线多数仍停留在研究早期，按思想史读。

### 里程碑论文与试验

- López-Otín, Blasco, Partridge, Serrano & Kroemer, "The Hallmarks of Aging", *Cell* 153(6), 2013；及 López-Otín 等, "Hallmarks of Aging: An Expanding Universe", *Cell* 186(2), 2023——衰老标志框架：2013 年九条（基因组不稳定、端粒损耗、表观遗传改变、蛋白稳态丧失、营养感应失调、线粒体功能障碍、细胞衰老、干细胞耗竭、细胞间通讯改变），2023 年扩为十二条（新增巨自噬失能、慢性炎症、肠道菌群失调）。这是整个领域的坐标系，本谱系阶段 1 的地基文献。
- Horvath, "DNA methylation age of human tissues and cell types", *Genome Biology* 14, 2013——第一个泛组织的表观遗传时钟（353 个 CpG 位点），「生物年龄可以被算出来」这件事的起点。
- Levine et al., "An epigenetic biomarker of aging for lifespan and healthspan", *Aging* 10(4), 2018——PhenoAge（表型年龄）：先用临床血液指标算表型年龄、再映射到甲基化，第一批导读里 BioAge 与 PC-Clocks 都与它直接相关。大型队列验证，A 级方法学文献。
- Lu et al., "DNA methylation GrimAge strongly predicts lifespan and healthspan", *Aging* 11(2), 2019——GrimAge：以血浆蛋白替代物 + 吸烟包年构建的甲基化时钟，对死亡时间的预测力是第二代时钟的标杆。
- Belsky et al., "DunedinPACE, a DNA methylation biomarker of the pace of aging", *eLife*, 2022——换思路的一篇：不算「你有多老」，算「你正老得多快」，源自新西兰 Dunedin 出生队列的纵向数据。它是下一篇 CALERIE 分析的主角指标。
- **CALERIE 试验**（Comprehensive Assessment of Long-term Effects of Reducing Intake of Energy，美国国家衰老研究所资助）：设计见 Ravussin et al., *Journals of Gerontology A*, 2015；代谢结果见 Redman et al., *Cell Metabolism*, 2018；关键分析 Waziry et al., "Effect of long-term caloric restriction on DNA methylation measures of biological aging in healthy adults from the CALERIE trial", *Nature Aging* 3, 2023（本次已核实原文数字）：220 名健康非肥胖成年人随机分组，两年热量限制（目标 25%，实际平均达成约 11.9%），DunedinPACE 测得的衰老速度减慢 2–3%（效应量 d≈−0.29／−0.25），而 PhenoAge 与 GrimAge 两个时钟**没有**测出干预效应。证据等级：干预效应本身 **A**（随机对照试验，数字可查）；论文提到的「2–3% 减速约相当于 10–15% 死亡风险降低」是从其他队列的关联换算来的，属 **B**，引用时必须分开标。这篇是本谱系的标本：一个真实、有限、被如实报告的结果，长什么样。
- Kennedy et al., "Geroscience: Linking Aging to Chronic Disease", *Cell* 159(4), 2014——老年科学（geroscience）假说的纲领：衰老是慢性病的共同上游，干预衰老机制可能同时推迟多种疾病。这个假说指导了整个领域的研究议程，但「假说」二字要读准。
- Poulain et al., "Identification of a geographic area characterized by extreme longevity in the Sardinia island: the AKEA study", *Experimental Gerontology* 39(9), 2004——蓝区研究的人口学源头论文（撒丁岛长寿区考证），与 Buettner 的书对读。
- TAME 试验（Targeting Aging with Metformin，Barzilai 主导）：状态如实标注——**尚未启动，无任何结果**：方案设计与和 FDA 的复合终点协商早已完成，但资金始终未到位，AFAR 至今仍在公开为「启动这项试验」募款，截至 2026 年尚未入组一名受试者（Barzilai 2025 年 8 月受访时亦称资金只落实约三分之一；2026-10-20 复核）。它的重要性在监管路径（让 FDA 接受「衰老相关复合终点」），不在二甲双胍本身；任何「二甲双胍已被证实抗衰老」的说法都早于证据——连检验它的那项 RCT 都还不存在，人类抗衰适应症的证据等级目前为 C。

### 开放课程与公开讲座

- **Why Do We Age? The Molecular Mechanisms of Ageing**（FutureLearn，格罗宁根大学／欧洲衰老生物学研究所 ERIBA）——免费 MOOC，从分子与细胞机制讲衰老理论与模式生物，本次已核实在营。它是清单里最对口「衰老生物学入门」的一门。
- **Fundamentals of Longevity Science**（哈佛 T.H. Chan 公共卫生学院）——八个模块的长寿科学基础课，含「如何评估科学主张」一整个模块，与本谱系的证据纪律高度对口。状态如实标注：官方页面显示**开发中、尚未开放报名**（2026-10-20 核实），先列入观察，开课后再补导读。
- **Approaching the Second Half of Life with Health and Vitality**（斯坦福大学 Anne Brunet 教授公开讲座，Class Central 收录）——遗传学视角的长寿研究概览（干细胞、胰岛素通路、重编程），是一场讲座而非完整课程，当「领域地图讲座」用正合适。
- 斯坦福长寿中心（Stanford Center on Longevity）与哈佛 Paul F. Glenn 衰老生物学中心的公开材料，作为机构公开课与报告的持续来源列入观察，不逐项展开。

### 开放数据库与数据资源

- **NHANES**（美国国家健康与营养检查调查，CDC）——完全公开的人群健康数据，生物年龄算法（PhenoAge、KDM）的训练与验证主战场，第一批的 BioAge 就跑在它上面。是本谱系「动手算」环节的数据源。
- **HAGR**（Human Ageing Genomic Resources，genomics.senescence.info）——衰老基因组学资源集：GenAge（衰老相关基因）、CellAge（细胞衰老基因）、DrugAge（影响寿命的化合物），学术界维护多年的老牌数据库。
- **Open Genes**（open-genes.com）——长寿相关基因的开放数据库，人工策展 + 文献出处，查「某个基因与长寿什么关系」时的第一站。
- **Aging Atlas**（agingatlas.org）——多组学衰老数据库（转录组、表观组等），2021 年发表于 *Nucleic Acids Research*。
- **UK Biobank**——50 万人队列，长寿与衰老研究的高频数据源；获取方式如实标注：**申请制**，不是公开下载，个人学习者走 NHANES 这类完全开放的数据即可。

## 四、批次规划

- 第一批（已完成）：监测与计算两端取样 12 仓，见 `第一批-导读.md`——活动与时间记录（ActivityWatch）、运动营养追踪（wger）、可穿戴数据自主（Gadgetbridge、Open Wearables）、营养数据库（Open Food Facts）、个人数据聚合（QS Ledger）、两份索引（Awesome Quantified Self、Awesome Biomarkers）、生物年龄计算四件（BioAge、pyaging、FaceAge、PC-Clocks）。
- 第二批（候）：时钟与衰老组学工具专题——methylCIPHER（PC 时钟的现行维护仓）、ComputAge、organage（器官年龄）、dnaMethyAge 等；及睡眠与节律分析工具。
- 第三批（候）：开放数据库导读——HAGR、Open Genes、Aging Atlas 的逐个用法 + NHANES 数据结构与下载实操，为学习路线图阶段 4 的动手环节备料。
- 选品口径说明（本批取舍留痕）：Nightscout 与 OpenAPS（糖尿病 DIY 闭环生态）未收——它们是疾病自我管理的执行设备，落在总纲「不收诊疗执行」的边界之外，且 OpenAPS 主仓已自标 deprecated；大量「人脸变老／变年轻」的图像处理仓（人脸年龄变换类）未收——那是计算机视觉，不是生物年龄科学；2025 年底新建的若干「AI 健康数据」仓（如 thetahealth/mirobody，建仓未满一年）先入观察名单，待存活与留存验证后再议。
