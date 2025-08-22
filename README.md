
---

## 📊 柱状图 (Mermaid Beta)
Mermaid 新版支持 `chart` 语法，可以画柱状图 / 折线图：  
```markdown
```mermaid
chart
  title: 每月销售额
  type: bar
  xAxis: 月份
  yAxis: 销售额(万元)
  series:
    - title: 产品A
      data: 10,20,30,25,40
    - title: 产品B
      data: 15,25,20,35,30
