# 截图盖章 · Screenshot Stamp

一个纯前端图片水印小工具。用 Codex 制作，图片始终留在你的设备上。

## 使用方法

1. 用浏览器打开 `index.html`。
2. 拖入图片，或点击“选择图片”（手机可从相册选取）。
3. 编辑水印文字，调整字号、透明度、位置和颜色。
4. 点击下载。单张保存为 PNG，多张保存为 ZIP。

无需安装依赖，也不需要构建步骤。页面没有外部脚本或图片上传接口；图片解码、绘制和 ZIP 打包均在浏览器本地完成。浏览器需支持 Canvas、`toBlob` 和 Blob 下载。浏览器对 HEIC 等格式的支持因设备而异。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `screenshot-stamp`。
2. 将本文件夹中的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择 `main` 分支和 `/(root)` 文件夹，点击 **Save**。
6. 等待 Pages 发布完成。网址通常是 `https://你的用户名.github.io/screenshot-stamp/`；也可在 Pages 设置页查看实际网址。

## Privacy

All image processing happens locally in your browser. This page contains no analytics, external scripts, or image upload endpoint.

# Screenshot Stamp

A tiny, browser-only watermarking tool made with Codex. Your images stay on your device.

## How to use

1. Open `index.html` in a browser.
2. Drag in images or tap **Choose images** to pick them from your photo library.
3. Edit the watermark and adjust its size, opacity, position, and color.
4. Download the result. One image is saved as PNG; multiple images are bundled into a ZIP.

There are no dependencies or build steps. Image decoding, rendering, and ZIP creation happen locally in the browser. Support for formats such as HEIC depends on the browser and device.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `screenshot-stamp`.
2. Upload this folder's `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then click **Save**.
6. After deployment, the site is usually at `https://YOUR-USERNAME.github.io/screenshot-stamp/`. The Pages settings show the exact URL.

## Privacy

All processing stays in your browser. The page has no analytics, external scripts, or image upload endpoint.
