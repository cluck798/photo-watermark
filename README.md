# 照片水印 · 时间 / 天气 / 定位

一个纯前端、可离线使用的照片水印工具，按“水印相机”风格为照片添加时间、日期、天气与定位信息。

**在线使用：** <https://cluck798.github.io/photo-watermark/>

## 功能

- 点击上传、拖拽或 Ctrl+V 粘贴照片，画布实时预览
- 自定义时间、日期、星期天气与两行定位
- 一键同步当前时间
- 大号时间使用内嵌 D-DIN Condensed 字体，日期与天气为 D-DIN + 系统细字重中文
- 可调水印大小、左下 / 右下位置、强调色与文字阴影
- 导出原始分辨率 JPG，全部处理在浏览器本地完成，照片不会上传

## 使用

打开在线页面，或直接双击本地的 `照片水印.html`。页面为单文件，字体已内嵌，无需安装依赖或联网运行。

天气与定位为手动填写，静态页面不请求天气或位置接口。

## 字体与许可

- D-DIN / D-DIN Condensed © Datto, Inc.，SIL Open Font License 1.1
- 中文使用系统细字重字体：PingFang SC / Microsoft YaHei Light

## 部署

GitHub Pages 静态发布，发布分支 `gh-pages`；默认分支 `main` 保存源码。
