# Weight-Something
自己在挑选手机, 电脑, 平板等产品时, 希望知道他们的重量和屏幕大小的相关信息, 现在网站并不能很好的满足自己的需求, 现尝试自己制作一个可以满足该需求的网站

## UML设计

UML中, 暂时使用"Property: value"来表示数据库属性及其对应值, 该英文表示方式来自CSS, 如果之后发现UML有对应的专属词汇, 以再选择修正为专属词汇.

> Phone

| Property               | Value                                                        |
| ---------------------- | ------------------------------------------------------------ |
| 型号                   | <text>                                                       |
| 品牌                   | <text>(Optional: with <Logo>)                                |
| 重量                   | <number> kg                                                  |
| 屏幕尺寸               | <number> inch                                                |
| 屏幕材料               | [OLED \| LCD]                                                |
| 充电接口               | [Type-C \| Lightning]                                        |
| 出厂操作系统           | [iOS \| Harmony \| HyperOS \| MIUI \| EMUI \| MagicOS \| ColorOS \| OriginOS ] |
| 色彩水平(Optional)     | 以某种标准备注                                               |
| 像素水平(Optional)     | 以某种方式标注                                               |
| 最高刷新率(Optional)   | <integer> Hz                                                 |
| 续航时间(Optional)     | 以某种测试方案的续航时间为代表, 也许会节选自bilibili网站上UP主们, 或者某些测试网站的测试时长(需预先取得授权) |
| 有线充电协议(Optional) | [5W \| 15W \| 20W \| 65W \| 66W \| 67W \| 120W \| 150W \| 240W \| ...] |
| 无线充电协议(Optional) | [ 无 \| ... ]                                                |

> Laptop

| Property               | Value                                                        |
| ---------------------- | ------------------------------------------------------------ |
| 型号                   | <text>                                                       |
| 品牌                   | <text>(Optional: with <Logo>)                                |
| 重量                   | <number> kg                                                  |
| 屏幕尺寸               | <number> inch                                                |
| 出厂操作系统           | [MacOS \| Windows]                                           |
| 充电接口               | [Type-C \| ... ]                                             |
| 掀开角(Optional)       | <integer> °                                                  |
| 电池容量(Optional)     | <integer> mAh                                                |
| 屏幕材料(Optional)     | [OLED \| LCD]                                                |
| 色彩水平(Optional)     | 以某种标准备注                                               |
| 像素水平(Optional)     | 以某种方式标注                                               |
| 续航时间(Optional)     | 以某种测试方案的续航时间为代表, 也许会节选自bilibili网站上UP主们, 或者某些测试网站的测试时长(需预先取得授权) |
| 有线充电协议(Optional) | [5W \| 15W \| 20W \| 65W \| 66W \| 67W \| 120W \| 150W \| 240W \| ...] |

> Pad

| Property               | Value                                                        |
| ---------------------- | ------------------------------------------------------------ |
| 型号                   | <text>                                                       |
| 品牌                   | <text>(Optional: with <Logo>)                                |
| 重量                   | <number> kg                                                  |
| 屏幕尺寸               | <number> inch                                                |
| 屏幕材料               | [OLED \| LCD]                                                |
| 充电接口               | [Type-C \| Lightning]                                        |
| 出厂操作系统           | [iPadOS \| Harmony \| HyperOS \| MIUI \| EMUI \| MagicOS \| ColorOS \| OriginOS \| ZUI] |
| 色彩水平(Optional)     | 以某种标准备注                                               |
| 像素水平(Optional)     | 以某种方式标注                                               |
| 最高刷新率(Optional)   | <integer> Hz                                                 |
| 续航时间(Optional)     | 以某种测试方案的续航时间为代表, 也许会节选自bilibili网站上UP主们, 或者某些测试网站的测试时长(需预先取得授权) |
| 有线充电协议(Optional) | [5W \| 15W \| 20W \| 65W \| 66W \| 67W \| 120W \| 150W \| 240W \| ...] |

## 备注

1. 或许续航时长可以用新的网页表示, 因为计算机的续航跟电池容量, 软硬件调教以及使用方式有关, 所以无法在一个表格中客观给出, 所以应该要显示来自第三方的测试数据, 如果是这样, 感觉可以单独分出来一页, 罗列第三方的测试数据, 或者直接给出第三方链接供用户参考, 因为罗列第三方数据应该需要支付授权费, 除非对方愿意免费给出.
