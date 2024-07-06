# 語音轉文字應用程式

這是一個語音轉文字應用程式，使用 OpenAI 和 Google 翻譯 API。

## 功能

- 語音轉文字
- 文本潤飾
- 生成摘要
- 提取重點
- 文字翻譯

## 安裝與運行

### 前提條件

- Node.js（推薦版本 14.x 或更高）

-  cd 你的倉庫

2. 安裝依賴項：

    ```sh
    npm install
    cd backend
    npm install
    cd ..
    ```
3. 配置 API 密鑰：

    打開 `backend/config.js` 文件，並將 `your-google-api-key` 和 `your-openai-api-key` 替換為你自己的 API 密鑰。

    ```javascript
    // config.js
    export const apiKeyGoogle = 'your-google-api-key';
    export const openAIKey = 'your-openai-api-key';

    //srever.js

    app.get('/config', (req, res) => {
    res.json({ apiKeyGoogle: 'YOUR_GOOGLE_API_KEY' });
替換為自己的API密鑰

4. 運行應用程式：

    ```sh
    npm start
    ```

    前端將運行在 `http://localhost:8080`，後端將運行在 `http://localhost:3000`。

## 注意事項

- 如果你遇到任何問題，請檢查你的 API 密鑰是否正確配置。
- 請確保你使用的是最新版本的 Node.js。


    
