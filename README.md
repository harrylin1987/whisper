# ProTape - AI Audio Transcription Tool

一個功能強大的 React 應用程式，使用 OpenAI Whisper API 進行音訊轉錄。

## 功能特性

- ✅ **支援多種音訊格式**: MP3, MP4, WAV, M4A, MOV
- ✅ **大檔案自動分割**: 整合 FFmpeg.wasm，自動處理超過 24MB 的檔案
- ✅ **精確時間標記**: 支援 SRT 字幕格式輸出
- ✅ **多語言支援**: 自動偵測或手動選擇語言
- ✅ **隱私保護**: 所有處理完全在瀏覽器內進行
- ✅ **即時進度顯示**: 清晰的進度條和詳細的處理步驟

## 使用方式

### 本地開發

```bash
# 安裝依賴
npm install

# 開發伺服器
npm run dev

# 構建生產版本
npm run build
```

### GitHub Pages 部署

```bash
# 一鍵部署
npm run deploy
```

## 技術棧

- **框架**: React 18
- **構建工具**: Vite
- **樣式**: Tailwind CSS
- **圖示**: Lucide React
- **音訊處理**: FFmpeg.wasm v0.11
- **API**: OpenAI Whisper API

## 需要的 API 金鑰

首次使用需要設定 OpenAI API 金鑰。您可以在 [OpenAI 官網](https://platform.openai.com/api-keys) 取得。

## 隱私聲明

- API 金鑰僅儲存在您的本地瀏覽器 localStorage 中
- 檔案不會上傳至任何第三方伺服器（除了必要的 OpenAI API 呼叫）
- 所有處理完全在您的瀏覽器中進行

## License

MIT
