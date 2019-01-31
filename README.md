目前已知将网页生成图片保存实现方案。

- 方案一：将DOM改写为canvas（即直接在画布上进行绘制文字、图片等），然后利用canvas的toDataURL()实现将DOM输出为包含图片展示的data URI。
- 方案二：使用html2canvas.js实现。
- 方案三：使用rasterizeHTML.js实现。

该demo采用方案二。
