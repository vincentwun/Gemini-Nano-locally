AI 本地化：安全與便捷的新選擇

現今，人工智能技術已經深入到我們生活的方方面面，從智能助手到自動駕駛，無一不在改變著我們的日常。然而，在享受這些高科技帶來的便利時，你有沒有考慮過一個重要的問題——數據安全？

當前的 AI 技術多半需要通過互聯網來運行，這意味著你的個人數據很可能在不知不覺中被傳輸和儲存。而這樣的過程中，數據安全問題便成為了每個用戶不得不重視的隱患。

那麼，你有想過本地化 AI 嗎？本地化 AI 不僅可以讓人工智能在你的設備上直接運行，還能有效地保護你的個人數據不被外洩。因為不需要經過網絡傳輸，數據的安全性得到了大幅提升，讓你在享受 AI 便利的同時也能高枕無憂。

你可能會問，本地化 AI 會不會很困難呢？其實不然！隨著技術的進步，本地化 AI 不僅變得更加可行，甚至可以在瀏覽器中運行，讓使用變得更加簡單和方便。

現在我將會介紹 Gemini Nano, 一款可以在瀏覽器中運化的本地化AI。

## 設置步驟：

1. 前往 [Google Chrome 開發者工具](https://www.google.com/chrome/dev/) 下載 Chrome 開發者版本。確認您的版本等於或高於 128.0.6545.0。

2. 在地址欄輸入 `chrome://flags`，搜尋 `prompt-api-for-gemini-nano`，並將其設置為**啟用**。

3. 同樣地，在 `chrome://flags` 中搜尋 `optimization-guide-on-device-model`，並將其設置為**啟用 BypassPerfRequirement**。

   ![Chrome 標誌](images/chrome_flags.jpg)

4. 重新啟動 Chrome。

5. 前往 `chrome://components` 並檢查 `Optimization Guide On Device Model` 的版本是否大於或等於 `2024.5.21.1031`。

   ![Chrome 組件](images/chrome_components.jpg)

6. 按 **F12** 打開開發者工具，並在控制台中輸入以下命令：

   (await ai.assistant.capabilities()).available;

   如果返回 **"readily"**，則表示您已完成設置。

7. 將 `Gemini_Nano_test.html` 下載到您的電腦。使用 Chrome 開發者版本打開它，並輸入您的提示。

   ![測試圖片](images/test.jpg)

好的, 現在您可以在本地運行 Gemini Nano 了！（甚至無需網路連接～）
