# Always Happy

一个充满心形粒子动画的网页项目，展示温馨的“Happy every single day!”消息，带来愉悦的视觉体验。

## 项目特点

- **动态粒子效果**：使用Canvas绘制粉色心形粒子动画
- **优雅字体**：采用Google Fonts的Allura字体呈现优雅文字
- **响应式设计**：自适应不同屏幕尺寸
- **平滑动画**：使用requestAnimationFrame实现流畅的动画效果
---
## 技术栈

- HTML5 Canvas
- JavaScript (ES5)
- CSS3
- Google Fonts
---
## 使用说明

1. 直接打开`index.html`文件即可在浏览器中查看效果
2. 页面加载后会显示渐入的文字动画和持续发射的心形粒子
3. 粒子会从心形图案中发射并逐渐消失，形成连续的动画效果
---
## 自定义选项

您可以通过修改`settings`对象中的参数来自定义动画效果：

```javascript
var settings = {
  particles: {
    length: 500,    // 粒子数量
    duration: 2,    // 粒子持续时间(秒)
    velocity: 100,  // 粒子速度
    effect: -0.75,  // 粒子效果参数
    size: 30,       // 粒子大小
  },
};
```
---
浏览器兼容性
支持所有现代浏览器，包括：

Chrome (推荐)

Firefox

Safari

Edge

