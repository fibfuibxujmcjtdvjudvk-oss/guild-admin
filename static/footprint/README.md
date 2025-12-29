# 足迹页面图片资源

## 需要添加的图片

### 1. world-map.png
- **用途**: 世界地图背景
- **推荐尺寸**: 1200x600 像素
- **格式**: PNG
- **要求**: 
  - 简化的世界地图轮廓
  - 建议使用浅灰色或淡蓝色
  - 透明背景或白色背景
  - 清晰可辨的大洲轮廓

**在线资源推荐**:
- https://www.flaticon.com (搜索 "world map outline")
- https://www.freepik.com (搜索 "world map vector")
- https://unsplash.com (搜索 "world map")

**或者使用纯色占位**:
可以暂时使用一张纯色图片占位，等后续替换为真实地图。

---

## 临时解决方案

如果暂时没有世界地图图片，可以：

1. **使用在线地图API** (推荐)
   - 百度地图 API
   - 高德地图 API
   - 腾讯地图 API

2. **使用占位图**
   在页面中添加提示文字："地图加载中..." 或 "点击下方按钮记录位置"

3. **使用纯色渐变背景**
   修改 CSS 使用渐变色替代图片

```css
.simple-map {
  background: linear-gradient(135deg, #E8F7FF 0%, #61DCF2 100%);
}
```

