# HighTide · 基线结果

[数据来源](https://github.com/VLSIDA/HighTide) · [配套候选](https://github.com/Yiting687691/hightide-openroad-optimized-results)。单位：线长 µm，时序 ns；— 为待补结果。

## 结果

| 设计 | 小循环 HPWL | 小循环 WNS / TNS | OpenROAD RWL | OpenROAD WNS / TNS | 状态 |
|---|---:|---:|---:|---:|---|
| [CNN](baselines/cnn/) | 12,897,036.322 | 未测 | 14,761,406.165 | −28.343180 / −916.073547 | v21 历史基线；回读差异待核实 |
| Eyeriss | — | — | — | — | 待补当前版本结果 |
| NyuziProcessor | — | — | — | — | 待补当前版本结果 |

仅采用同输入、同后端配置的配对结果；宏位置/朝向可变，标准单元由 OpenROAD 重摆。完整布线后报告 WNS/TNS、线长收益及 DRC；不把预布局改善当作布线收益。

CNN 保留已发布的完整历史归档；1 条网回读相差 0.03 µm，严格验收未通过，不作为新算法已完成对照。
