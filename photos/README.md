# 📸 照片文件夹

将你想要在圣诞树场景中显示的照片放在这个文件夹中。

## 支持的图片格式
- JPG/JPEG
- PNG
- GIF
- WEBP
- BMP
- SVG

## 使用方法

### 方法1：自动配置（推荐）
1. 将照片复制到此文件夹
2. 运行脚本：`python generate_photo_config.py`
3. 脚本会自动扫描此文件夹并更新 圣诞树.html 的配置

### 方法2：手动配置
1. 将照片复制到此文件夹
2. 打开 圣诞树.html
3. 找到 `presetPhotos` 配置区域
4. 手动添加照片文件名：
```javascript
presetPhotos: [
    'photo1.jpg',
    'photo2.jpg',
    'photo3.png',
],
```

## 注意事项
- 建议使用适中大小的照片（宽度1000-2000px），太大会影响加载速度
- 照片文件名不要包含特殊字符或中文（虽然支持，但为了兼容性最好避免）
- 如果要部署到网站，确保整个文件夹结构保持不变

## 文件夹结构示例
```
shengdan/
├── 圣诞树.html
├── generate_photo_config.py
├── photos/
│   ├── family1.jpg
│   ├── vacation2.png
│   └── memories3.jpg
└── README.md
```
