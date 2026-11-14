# 摄影模拟器

在雪山湖泊、湖心别墅和霓虹城里取景，练习用光圈、快门和 ISO 拍照。时间、天气和月相可调，也可以拍长曝光、录视频并把作品存入相册。

## 开始玩

- 在线版由本仓库的 GitHub Pages 提供。[点击进入在线试玩](https://jaychiz.github.io/Photo-sim/)。
- 离线版可下载 `index.html`，用浏览器打开。
- 电脑上使用 **WASD** 和鼠标移动视角，按 **U** 举起相机、左键拍摄。按 **T** 换场景，**G** 打开相册，**H** 查看完整帮助。手机或平板可以用屏幕上的控件。

## 从源码构建

下载 [源码压缩包](photo-sim-source.zip) 并解压。在解压后的目录中，用 Node.js 运行以下命令。构建结果是 `index.html`。

```bash
npm ci
node build.mjs
```

`src/` 中的脚本、天空贴图和游戏使用的小型模型一起打包为单个 HTML。

## 作者与素材

作者 Jaychi。第三方代码许可和天空贴图来源见 [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt)。

项目许可证以仓库的 `LICENSE` 为准（如已添加）。第三方依赖和素材按各自的许可或使用条款分发。
