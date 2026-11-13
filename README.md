# HighTide · 基线与文献参照

[全部方法调研](https://github.com/Yiting687691/open-source-openroad-results/blob/main/METHODS.md) · [作者布局与复测入口](https://github.com/Yiting687691/open-source-openroad-results/blob/main/ARTIFACTS.md)

[配套仓库](https://github.com/Yiting687691/hightide-openroad-optimized-results) · [文献参照](https://github.com/Yiting687691/hightide-openroad-results/blob/main/BEST_REPORTED.md)

## 按指标选择文献参照

<table>
<thead><tr><th>设⁠计</th><th>线⁠长⁠参⁠照</th><th>W⁠N⁠S⁠ ⁠参⁠照</th><th>T⁠N⁠S⁠ ⁠参⁠照</th></tr></thead>
<tbody>
<tr><td>C⁠N⁠N</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td></tr>
<tr><td>E⁠y⁠e⁠r⁠i⁠s⁠s</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td></tr>
<tr><td>N⁠y⁠u⁠z⁠i⁠P⁠r⁠o⁠c⁠e⁠s⁠s⁠o⁠r</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td><td align="right">H⁠（⁠暂⁠代⁠）</td></tr>
</tbody>
</table>

H=Hier-RTLMP。未核实的文献参照按用户约定暂用 H；这是待复测参照，不改变下方 CNN 的已知实际来源，也不表示 H 最优。

## 已有实测基线

线长单位 mm，时序单位 ns；— 为未发布。

<table>
<thead><tr><th>设⁠计</th><th>布⁠局⁠来⁠源</th><th>H⁠P⁠W⁠L⁠ ⁠/⁠ ⁠m⁠m</th><th>R⁠W⁠L⁠ ⁠/⁠ ⁠m⁠m</th><th>W⁠N⁠S</th><th>T⁠N⁠S</th></tr></thead>
<tbody>
<tr><td>⁠<a href="baselines/cnn/">C⁠N⁠N</a>⁠</td><td align="right">O⁠p⁠e⁠n⁠R⁠O⁠A⁠D⁠ ⁠R⁠T⁠L⁠M⁠P⁠¹</td><td align="right">1⁠2⁠,⁠8⁠9⁠7⁠.⁠0⁠4</td><td align="right">1⁠4⁠,⁠7⁠6⁠1⁠.⁠4⁠1</td><td align="right">−⁠2⁠8⁠.⁠3⁠4⁠3⁠2</td><td align="right">−⁠9⁠1⁠6⁠.⁠0⁠7⁠3⁠5</td></tr>
<tr><td>E⁠y⁠e⁠r⁠i⁠s⁠s</td><td align="right">待⁠核⁠验⁠布⁠局⁠来⁠源</td><td align="right">—</td><td align="right">—</td><td align="right">—</td><td align="right">—</td></tr>
<tr><td>N⁠y⁠u⁠z⁠i⁠P⁠r⁠o⁠c⁠e⁠s⁠s⁠o⁠r</td><td align="right">待⁠核⁠验⁠布⁠局⁠来⁠源</td><td align="right">—</td><td align="right">—</td><td align="right">—</td><td align="right">—</td></tr>
</tbody>
</table>

¹ CNN 是本项目 public_baseline.tcl 经 GP→rtl_macro_placer 生成的 v21 历史基线。1 条网回读相差 0.03 µm，严格验收未通过。
