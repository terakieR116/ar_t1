# My AR Project (Demo)
這是最小可用的「瀏覽器 3D/AR」展示：

- `index.html` 使用 `<model-viewer>`。
- `model.glb` 是一個可正常顯示的三角形 GLB（Android 可直接 AR）。
- `ios-src` 指向 Apple 的公開 USDZ 範例（鬆餅）。iOS 點擊 AR 會使用 Quick Look 載入該 USDZ。

## 替換成你的模型
- Android / 網頁 3D：把 `model.glb` 換成你的 GLB（檔名同樣為 `model.glb`）。
- iOS AR：把 `index.html` 裡的 `ios-src` 換成你自己的 USDZ 連結或路徑（例如 `model.usdz`）。

## 部署
把整個資料夾上傳到 GitHub，開啟 GitHub Pages 即可分享連結。
