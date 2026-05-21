# AIB 2026 Personal Planner

一个基于 AIB 2026 conference program 制作的静态网页工具，支持：

- 按日期、track、房间、时间、session 类型筛选
- 勾选 session
- 勾选 paper，并显示所属 session
- 高亮已选 paper 所在 session
- 自动检测时间冲突
- 导出个人日程为 Excel 和打印版 PDF

## Files

- `index.html`: GitHub Pages 入口页
- `conference-planner.html`: 主应用页面
- `planner-data.js`: 解析后的会议数据

## Notes

- 当前选择结果保存在每位用户自己的浏览器本地，不会自动同步给其他人。
- 这是一个纯静态网站，适合通过 GitHub Pages 部署。
