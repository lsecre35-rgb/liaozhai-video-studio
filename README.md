# 《促織》20 秒水彩動畫工作室

這個專案提供《促織》短片的五段分鏡與可複製動作提示，設計給 iPhone Safari 使用。

## 免費動態生成器
本專案使用 [NiftyVid](https://igorcsis.github.io/nifty-vid/) 作為 Wan 2.2 image-to-video 公開 GPU 前端。單段影片約 3.5–4.5 秒，免費共享 GPU 可能排隊、冷啟動或暫時不可用。這不是本 Repository 自己提供 GPU。

## 使用方式
1. 開啟 GitHub Pages 網頁。
2. 每段上傳對應的原始水彩場景圖。
3. 複製該段動作提示到 NiftyVid，生成 MP4。
4. 五段完成後再合併成約 20 秒，加入旁白、蟋蟀聲、配樂與字幕。

## 重要限制
目前此專案先建立分鏡工作台；它不會在 GitHub Actions 裡執行 Wan 2.2，也不會假裝 CPU runner 能生成 AI 動畫。若免費 Hugging Face GPU Space 停機或排隊，需稍後重試。