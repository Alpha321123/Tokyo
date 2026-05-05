# Tokyo Trip Planner

這是一個簡單的東京旅行規劃網站範本，用於規劃每日行程、交通方式、景點與票券。

## 內容

- `index.html`：倉庫根目錄的首頁，作為第一頁展示項目概述。
- `Tokyo.Web/`：Blazor Server 專案，包含旅遊規劃頁面 `Index.razor`。
- `Tokyo.Web/wwwroot/app.css`：網站樣式。

## 如何本地運行

```bash
cd Tokyo.Web
dotnet run
```

然後在瀏覽器中打開 `https://localhost:5001`。

## 清理說明

`Tokyo.Web/bin/` 和 `Tokyo.Web/obj/` 是編譯輸出，已從工作區刪除，並由 `.gitignore` 忽略。