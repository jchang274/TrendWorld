# Multi-Indicator in ONE

**This indicator can show 3 things.**

1. SPX Market Breadth (SPXMB)
2. Draw SPX Market Breadth Line (SPXMBL)
3. Bias (BIAS)
4. Waiting for your advice...

---

* 把 **市场宽度（SPXMB）**，**市场宽度画线（SPXMBL）**，**乖离率（BIAS）** 三个指标融合到一起，后续按需添加。
* 附件**视频操作演示 Demo.wmv**。
* 也可点击[网址](https://cn.tradingview.com/script/a2cyWUM9/)，添加到常用脚本。
* https://cn.tradingview.com/script/a2cyWUM9/
* 除去1个主图指标，还可以同时添加2个相同的副图，任意组合，参考图Combine1,2。
* **不是程序员，代码不免冗余啰嗦，只为实现功能，也不会用这个github，请见谅。**

- ===========(\__/) ||
  ===========(•ㅅ•) ||
  ===========/ 　 づ Fat Go Away !

---

**Bug Fix：**

- 解决了小周期显示错误的问题（英语我编不出来了）
- 之前大家传的市场宽度，都是用的这个参数time.period，这个用法好像不太对，引用的Above 20 Index本身就是日线级别的，所以直接用“1D”比较好，time.period会随切换周期而变动，切换小周期时候显示感叹号！Study Resolution。