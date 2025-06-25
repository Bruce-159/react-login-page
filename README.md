
## 📸 預覽畫面

![image](https://github.com/user-attachments/assets/cfb3a794-573d-4bc3-9682-4b76c11ef445)


# React CSS 練習專案

這是一個 React 練習專案，目的是為了熟悉並實作不同的 CSS 技術，包括：

- ✅ Tailwind CSS
- ✅ 原生 CSS（Vanilla CSS）
- ✅ CSS Modules

透過這個專案，我練習了如何在不同情境下使用這三種技術來達成樣式設計。

## 🎯 目標

- 熟悉各式 CSS 技術的語法與使用情境
- 理解各種 CSS 寫法對元件作用範圍（scoping）的差異
- 練習元件化思維與表單處理

## 🚀 功能特色

- ✨ 使用者可以輸入 Email 與密碼
- ✅ 表單輸入驗證：Email 格式與密碼長度（最少 6 字）
- 🧩 組件化設計：Input、Button、Header 等皆為獨立元件
- 🚫 不具實際登入功能，但可依輸入是否符合條件來套用不同樣式（錯誤提示、邊框變色等）

## 🧪 技術使用

- **React**：核心框架
- **Tailwind CSS**：工具化原子樣式設計
- **Vanilla CSS**：直接使用 `index.css` 或單一檔案撰寫樣式
- **CSS Modules**：模組化的樣式設計，解決樣式衝突問題
- **Vite**：開發伺服器與建構工具

## 📁 專案結構簡介

src/
├── components/
│ ├── Header.jsx # 使用 Tailwind
│ ├── AuthInputs.jsx # 搭配 Tailwind / Input 元件練習
│ ├── Button.jsx # 客製化按鈕樣式
│ ├── Input.jsx # 利用 props 控制樣式
│ └── SomeVanillaComponent.jsx # 練習 Vanilla CSS
├── App.jsx
├── index.css # Vanilla CSS
├── main.jsx
├── styles/
│ └── Form.module.css # CSS Modules
