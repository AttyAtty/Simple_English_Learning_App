# 英単語学習アプリ / English Vocabulary Learning App

このリポジトリは、HTML・CSS・JavaScript で作成した**ブラウザ上で動く英単語学習アプリ**です。  
ユーザーが単語を登録し、英語 → 日本語、日本語 → 英語の練習モードで学習することができます。  
This repository contains a **browser-based English vocabulary learning app** built with HTML, CSS, and JavaScript.  
Users can register words and practice in two modes: English → Japanese or Japanese → English.

---

## 🔹 機能 / Features

### 単語管理 / Word Management
- 単語を1つずつ登録 / Register words one by one
- 複数単語を一度に登録（カンマ区切りで入力） / Register multiple words at once (comma-separated input)
- 単語一覧を確認 / View the list of registered words
- 単語を削除 / Delete a word
- 単語を全て削除 / Delete all words

### 練習モード / Practice Modes
- 英語 → 日本語（engToJap） / English → Japanese (engToJap)
- 日本語 → 英語（japToEng） / Japanese → English (japToEng)
- 出題する問題数を選択（5問、10問、20問、全部） / Select the number of questions (5, 10, 20, or all)
- 練習中の中止機能 / Cancel practice at any time
- Enterキーでも回答可能 / Answer using the Enter key

### その他 / Others
- 正答・不正解をアラートで表示 / Correct or incorrect answers are displayed via alert
- 練習終了時に正答数を表示 / Shows the number of correct answers when practice ends

---

## 🔹 使い方 / How to Use

1. `index.html` をブラウザで開く / Open `index.html` in a web browser  
2. 単語を登録する / Register words  
   - 「単語を登録」ボタンで1つずつ / Use "Register Word" button to add words one by one
   - 「単語を一気に登録」ボタンで複数まとめて登録 / Use "Register Multiple Words" button to add several words at once
3. 「練習」セクションで問題数を選択 / In the "Practice" section, select the number of questions
4. 英→日 または 日→英 ボタンで練習開始 / Start practice using "Eng → Jap" or "Jap → Eng" buttons
5. 入力欄に答えを入力して「答える」ボタン、または Enter キーで回答 / Enter your answer in the input field and click "Check" or press Enter
6. 練習途中で中止したい場合は「中止する」ボタンをクリック / To cancel practice in the middle, click the "Cancel" button

---

## 🔹 注意事項 / Notes
- 登録した単語データはページを閉じると消えます（ローカルストレージは未使用） / Registered words are **not saved** when the page is closed (local storage is not used)
- ブラウザ上で動作するため、特別な環境は不要です / No special environment is needed as the app runs in a browser
- 単語データが多い場合は、ブラウザやデバイスの動作に注意してください / For large word lists, performance may vary depending on the browser or device

---

## 🔹 今後の拡張案 / Future Enhancements
- 単語データのローカル保存（LocalStorageやIndexedDB利用） / Save word data locally using LocalStorage or IndexedDB
- 正答率の記録・成績表示 / Track correct answer rates and show results
- 音声読み上げ機能の追加 / Add speech synthesis for pronunciation
- デザインの改善（CSSフレームワーク導入など） / Improve design (e.g., using a CSS framework)

---

## 🔹 作成日 / Created on
2025/06/20
