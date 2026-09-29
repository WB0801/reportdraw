# Report Draw

一个适合课堂投影使用的报告顺序抽签网页。

## 功能

- 可输入 2–20 组
- 自动生成 1–N 的抽签号码
- 每个号码只会出现一次
- 使用浏览器 `crypto.getRandomValues()` 进行随机抽取
- 实时显示剩余号码与抽签记录
- 抽完后自动整理最终报告顺序
- 支持全屏
- 单一 `index.html`，无外部依赖，也可下载后离线使用

## 使用

直接打开 `index.html`，输入今天的组数后开始抽签即可。

如果启用 GitHub Pages，也可以直接通过网页链接使用。

## Acknowledgement

Fair-randomness approach inspired by [`ttomohisa/htmlapps-random-picker`](https://github.com/ttomohisa/htmlapps-random-picker), released under the MIT License.
