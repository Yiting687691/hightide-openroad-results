# HighTide · 文献参照

<table>
<thead><tr><th>设⁠计</th><th>线⁠长⁠参⁠照</th><th>W⁠N⁠S⁠ ⁠参⁠照</th><th>T⁠N⁠S⁠ ⁠参⁠照</th></tr></thead>
<tbody>
<tr><td>C⁠N⁠N</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td></tr>
<tr><td>E⁠y⁠e⁠r⁠i⁠s⁠s</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td></tr>
<tr><td>N⁠y⁠u⁠z⁠i⁠P⁠r⁠o⁠c⁠e⁠s⁠s⁠o⁠r</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td><td align="right">H⁠i⁠e⁠r⁠-⁠R⁠T⁠L⁠M⁠P⁠（⁠暂⁠代⁠）</td></tr>
</tbody>
</table>

尚未找到可核实的逐例领先结果，不据此认定 RTLMP 最优。

[HighTide 作者仓库](https://github.com/VLSIDA/HighTide)和[数据集论文](https://arxiv.org/html/2606.04126v1)提供流程与设计指标；Fmax 不是布局算法相对收益。CNN、Eyeriss、NyuziProcessor 尚未核实逐设计 WL/WNS/TNS 的外部算法冠军，不能用其他网表版本的同名设计填补。

本仓 CNN 实测基线来自本项目 public_baseline.tcl 的 GP→rtl_macro_placer；这是可追溯的实验分母，不是最佳声明。未对论文布局作同输入/工艺/SDC/RC/后端重测前，不替换现有分母。

“暂代”是用户指定的待复测参考，不代表已验证作者使用该算法或它最优。


## 本轮补查

[完整方法目录与新增 agent 逐例表](https://github.com/Yiting687691/open-source-openroad-results/blob/main/METHODS.md) · [作者布局工件](https://github.com/Yiting687691/open-source-openroad-results/blob/main/ARTIFACTS.md)。范围包含解析、启发式、RL、扩散、训练及 LLM/多智能体方法；是否具备本地训练或 API 条件不影响文献纳入。
