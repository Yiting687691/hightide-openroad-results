# HighTide · 基线与文献参照

[配套仓库](https://github.com/Yiting687691/hightide-openroad-optimized-results) · [文献参照](https://github.com/Yiting687691/hightide-openroad-results/blob/main/BEST_REPORTED.md)

## 按指标选择文献参照

| 设计 | 线长参照 | WNS 参照 | TNS 参照 |
|---|---:|---:|---:|
| CNN | 未核实 | 未核实 | 未核实 |
| Eyeriss | 未核实 | 未核实 | 未核实 |
| NyuziProcessor | 未核实 | 未核实 | 未核实 |

尚未找到可核实的逐例领先结果，不据此认定 RTLMP 最优。

## 已有实测基线

线长单位 mm，时序单位 ns；— 为未发布。

| 设计 | 布局来源 | HPWL / mm | RWL / mm | WNS | TNS |
|---|---:|---:|---:|---:|---:|
| [CNN](baselines/cnn/) | OpenROAD RTLMP¹ | 12,897.04 | 14,761.41 | −28.3432 | −916.0735 |
| Eyeriss | 待核验布局来源 | — | — | — | — |
| NyuziProcessor | 待核验布局来源 | — | — | — | — |

¹ CNN 是本项目 public_baseline.tcl 经 GP→rtl_macro_placer 生成的 v21 历史基线。1 条网回读相差 0.03 µm，严格验收未通过。
