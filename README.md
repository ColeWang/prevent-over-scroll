## 禁用IOS橡皮筋效果

```css
/* ios滚动元素添加 */
div {
  -webkit-overflow-scrolling: touch;
}
```

```typescript
  // 启用
  // 初始化自执行一次 将自动判断是否支持WebkitOverflowScrolling属性 无需另外判断ios客户端打开
  enable()
  // 停用
  disable()
  // 当前是否已启用
  isEnabled()
```
