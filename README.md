# Weight-Something
自己在挑选手机, 电脑, 平板等产品时, 希望知道他们的重量和屏幕大小的相关信息, 现在网站并不能很好的满足自己的需求, 现尝试自己制作一个可以满足该需求的网站

## UML设计

UML中, 暂时使用"Property: value"来表示数据库属性及其对应值, 该英文表示方式来自CSS, 如果之后发现UML有对应的专属词汇, 以再选择修正为专属词汇.

> Phone

| Property           | Value                         |
| ------------------ | ----------------------------- |
| 型号               | <text>                        |
| 品牌               | <text>(Optional: with <Logo>) |
| 重量               | <number> kg                   |
| 屏幕尺寸           | <number> inch                 |
| 电池容量           | <integer>mAh                  |
| 屏幕材料           | [OLED \| LCD]                 |
| 色彩水平(Optional) | 以某种标准备注                |
| 像素水平(Optional) | 以某种方式标注                |

> Laptop

| Property           | Value                         |
| ------------------ | ----------------------------- |
| 型号               | <text>                        |
| 品牌               | <text>(Optional: with <Logo>) |
| 重量               | <number> kg                   |
| 屏幕尺寸           | <number> inch                 |
| 掀开角(Optional)   | <integer> °                   |
| 电池容量(Optional) | <integer> mAh                 |
| 屏幕材料(Optional) | [OLED \| LCD]                 |
| 色彩水平(Optional) | 以某种标准备注                |
| 像素水平(Optional) | 以某种方式标注                |

