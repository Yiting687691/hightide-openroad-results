# HighTide · 文献参照

| 设计 | 线长参照 | WNS 参照 | TNS 参照 |
|---|---:|---:|---:|
| CNN | 未核实 | 未核实 | 未核实 |
| Eyeriss | 未核实 | 未核实 | 未核实 |
| NyuziProcessor | 未核实 | 未核实 | 未核实 |

尚未找到可核实的逐例领先结果，不据此认定 RTLMP 最优。

[HighTide 作者仓库](https://github.com/VLSIDA/HighTide)和[数据集论文](https://arxiv.org/html/2606.04126v1)提供流程与设计指标；Fmax 不是布局算法相对收益。CNN、Eyeriss、NyuziProcessor 尚未核实逐设计 WL/WNS/TNS 的外部算法冠军，不能用其他网表版本的同名设计填补。

本仓 CNN 实测基线来自本项目 public_baseline.tcl 的 GP→rtl_macro_placer；这是可追溯的实验分母，不是最佳声明。未对论文布局作同输入/工艺/SDC/RC/后端重测前，不替换现有分母。
