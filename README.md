# Gemini Nano : AI 本地化的新選擇

在這個科技飛速發展的時代，人工智能技術已經滲透到我們生活的方方面面，從手機裡的智能助手到路上的自動駕駛汽車，無一不在悄然改變著我們的日常生活。AI 的普及帶來了無數的便利，但在享受這些高科技帶來的同時，你是否考慮過一個重要的問題——數據安全？

數據安全：便利背後的隱憂
當前，大多數 AI 技術需要通過互聯網來運行，這意味著你的個人數據可能在不知不覺中被傳輸和儲存於雲端。雲端運算提供了強大的計算能力，但在數據傳輸過程中，潛在的安全隱患卻不容忽視。數據洩漏、未經授權的訪問等問題成為每個用戶必須重視的隱患。那么，我們應該如何應對這些挑戰呢？

本地化 AI：通向安全的新路
你有想過本地化 AI 嗎？本地化 AI 的出現徹底改變了這一局面。它允許人工智能在你的設備上直接運行，無需依賴互聯網，這樣做不僅保障了數據的私密性，還提升了運行的效率和穩定性。因為不需要經過網絡傳輸，數據的安全性得到了大幅提升，讓你在享受 AI 便利的同時也能高枕無憂。

更迅速的反應時間
除了安全性，本地化 AI 還帶來了更迅速的反應時間。由於數據處理是在本地進行，這意味著你的設備可以更快地做出反應，而不需要等待與雲端的來回通信。無論是語音識別、影像處理，還是個性化建議，本地化 AI 都可以更迅速地完成。這是否是你一直期待的技術突破呢？

本地化 AI：是否難以實現？
你可能會問，本地化 AI 會不會很困難呢？其實不然！隨著技術的進步，本地化 AI 不僅變得更加可行，甚至可以在瀏覽器中運行，讓使用變得更加簡單和方便。這意味著，你不需要昂貴的硬體設備或複雜的設置，便可以享受本地化 AI 帶來的好處。

探索 Gemini Nano
現在，我將會介紹 Gemini Nano，一款可以在瀏覽器中運行的本地化 AI。它如何能夠改變你的數據處理方式？讓我們一起探討這項創新科技的潛力。

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

如需更詳細資料, 請參閱以下官方連結:
https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/edit?tab=t.0
