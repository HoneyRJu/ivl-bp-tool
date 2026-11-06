# 第五人格 IVL · BP 工具站

纯静态，双击 index.html 即可使用。

## 页面
- index.html            推荐器（范围 / BO / 地图 / 四类BAN / 选角分布 / 三口径胜率 / 双视角）
- report-quickdown.html 秒倒特征
- report-causal.html    秒倒因果
- report-tempo.html     时间与破译
- report-source.html    数据来源与口径（源库哈希、SQL、审计结果）
- coach-bp.html         教练保平 BP

## 重新生成
python export_bo.py         # 主页
python export_reports.py    # 报告
python patch_nav.py         # 补导航

## 在线地址

https://honeyrju.github.io/ivl-bp-tool/

部署于 GitHub Pages 仓库 `HoneyRJu/ivl-bp-tool`，更新后重新提交即可，链接不变。
