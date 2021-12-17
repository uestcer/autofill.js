# 中国大学 MOOC 互评脚本

* 进入互评界面；
* 按 <kbd>F12</kbd> 并切换到 `console` 面板；
* 输入以下脚本：

```js
document.querySelectorAll(".s").forEach((item) => { item.lastElementChild.click(); });
document.querySelectorAll(".j-textarea").forEach((item) => { item.value="牛逼！"; });
```

* 按回车；
* 点击底部 <kbd>提交</kbd> 按钮。

