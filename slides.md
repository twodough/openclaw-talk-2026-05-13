<section class="hero-slide">
  <div class="hero-sticker">2026/05/13</div>
  <div class="hero-card hero-card-main">
    <p class="eyebrow">OpenClaw Talk</p>
    <h1>從出期末考<br>到紀錄好吃的便當</h1>
  </div>
  <div class="hero-card hero-card-side">
    <span class="mini-label">with</span>
    <strong>Candy Tsai</strong>
    <a href="https://www.threads.com/@stringpiggy" target="_blank" rel="noopener">@stringpiggy</a>
    <a href="https://candys.page" target="_blank" rel="noopener">candys.page</a>
  </div>
  <div class="hero-badge">OpenClaw 龍蝦助理養成日記</div>
</section>

---

## 今天不會講什麼

<div class="highlight-box">
這裡你不會學到怎麼提升 10 倍生產力。
</div>

你會聽到的是：

- 我怎麼把不想做的事情丟給 AI（土豆妹）
- 順便養一隻電子寵物陪玩（Papi）
- 還有中間踩過的一堆坑

---

## 我是 Candy Tsai

- 喜歡小熊維尼的資深工程師
- 臺灣大學資訊系統訓練班講師
- 立志將技術講成人話，讓想學的人聽得懂
- 曾開發過服務百萬人的 Chatbot
- 近期沈迷於 self-hosting 與塔麻可吉

---

## 這場分享會長這樣

- 不想做的事：交給 AI 助理
- 總是忘記的事：讓系統幫忙記
- 電子寵物：把助理養成有互動感的存在
- 真實踩坑：哪些地方聽起來很美，做起來很痛
- 工具選擇：Claude Code？OpenClaw？還是別的？

---

## 💼 不想做的事

把那些「不是不重要，只是真的很煩」的事情交出去。

- Review 程式碼
- 出期末考題
- 生 Podcast 逐字稿

---

## Review 程式碼

<div class="vibe-container">
<div class="vibe-prompt">
<strong>助理適合做什麼？</strong><br>
先抓明顯錯誤、風格不一致、容易忽略的細節，讓人類保留最後判斷權。
</div>
<div class="vibe-code">

```md
你幫我看這個 PR：
1. 有沒有安全風險？
2. 有沒有資料流錯誤？
3. 哪些地方應該請作者補測試？
```

</div>
</div>

---

## 出期末考題

- AI 很適合協助產生初稿
- 但題目正確性、難度、答案仍然需要人工校對
- 重點不是「讓 AI 全自動出完」
- 而是把最耗腦的空白頁階段縮短

---

## 生 Podcast 逐字稿

- 語音轉文字只是第一步
- 真正麻煩的是校對、標註、排版、輸出
- 可以把固定流程包成助理技能
- 每次只改例外，不要每次重做整套流程

---

## 📝 總是忘記的事

人的腦袋很珍貴，不要拿來記「下次要幹嘛」。

- 日文練習
- 紀錄便當好不好吃
- 追蹤身體健康

---

## 日文練習

- 每天固定出一題
- 回答後判斷正誤與語感
- 把答題結果記回資料庫
- 之後針對弱點重新複習

---

## 紀錄好吃的便當

<div class="highlight-box">
不是每件事都要很偉大，生活中的小資料也很值得被記住。
</div>

- 今天吃了什麼？
- 好不好吃？
- 會不會想再買？
- 下次不要踩同一個雷

---

## 追蹤身體健康

- 重點不是醫療診斷
- 而是把零散紀錄整理起來
- 讓未來的自己看得懂發生過什麼
- 需要專業判斷時，再把資料帶去給人類專家

---

## 🐣 電子寵物

當助理不只是工具，而是可以互動的存在。

- 猜拳
- 1A2B 猜數字
- D&D 風格跑團
- 怎麼做出公平的遊戲

---

## 公平的遊戲怎麼做？

- AI 不能事後偷改答案
- 人類也不能偷看答案
- 可以用 commitment scheme 先承諾答案
- 揭曉時再驗證雜湊值

---

## 怎麼樣才能精準做事？

<div class="highlight-box">
你以為是 Skills，但其實是 scripts。
</div>

- Skills 決定 AI 什麼時候該做事、怎麼判斷情境
- Scripts 決定任務怎麼被穩定執行、驗證、重跑
- Prompt 會飄，人的記憶會漏，script 才是穩定的執行邊界
- 這也是為什麼 AI 助理最後會長得很像一個小型軟體專案

---

## Skill 不是魔法，是 SOP + 工具箱

<div class="highlight-box">
Skill = 讓 AI 固定執行一套流程
</div>

```txt
SKILL.md
操作手冊 / 何時用 / 怎麼用
        ↓
scripts
真正執行任務的工具
        ↓
output
穩定產出結果
```

<div class="highlight-box">
.md 是神經系統，scripts 是肌肉。
</div>

---

## 錯的 script 會讓 Skill 穩定地錯

<div class="highlight-box">
Skill 的可靠性來自測試，不是來自包裝。
</div>

```txt
AI 寫 script
    ↓
人類 review
    ↓
加測試案例
    ↓
驗證 expected output
    ↓
變成可信 Skill
```

- Skill 不會讓 AI 自動變正確，只是把流程固定下來
- 流程對，就穩定地對；流程錯，就穩定地錯
- Script 就像 Excel 公式：寫錯只會讓你更有效率地算錯

---

## LINE 與 Discord 有什麼不同？

- LINE 最大限制：push message 有額度，不適合大量 alert-based 任務
- Discord / Telegram 比較像事件流，可以自然承載頻繁通知與互動
- LINE 早期 prompt caching 很糟，同樣事情一天可能燒到 120 USD
- 後來修好後，類似使用量可以降到 30–40 USD

---

## LINE：最痛的是 alert-based 任務

如果每次提醒都要消耗 push quota，就很難放心開這些任務：

- inbox / 重要信件提醒
- calendar 會議前提醒、行程異動提醒
- 服務監控、部署失敗、cron job 掛掉
- Notion task 到期、待辦卡住太久
- 學生回答、社群留言、私訊 follow-up
- 天氣、健康、吃藥、喝水這種高頻生活提醒

---

## LINE 成本：prompt caching 的坑

![Prompt caching pricing](assets/prompt-caching-gpt5.5-pricing.png)

---

## LINE push message 限制

![LINE messaging pricing](assets/line-messaging-pricing.png)

---

## LINE vs Discord：更大的差異

- **LINE 是私訊產品**：適合一對一、低頻、強通知感
- **Discord 是工作空間**：適合頻道、thread、多人協作、長期上下文
- **LINE 上下文比較扁平**：訊息容易混在一起，分類靠 bot 自己做
- **Discord 結構比較完整**：channel / forum / thread 本身就是資訊架構
- **LINE 比較像正式敲門**；Discord 比較像助理坐在工作室角落待命

---

## 白痴事件與踩坑

- AI 很會自信地做錯事
- 權限太大會害怕，權限太小會卡死
- 記憶與紀錄不是同一件事
- 自動化不是越多越好

---

## 要選 Claude Code 還是 OpenClaw？

- Claude Code：偏向 coding agent，適合專案內開發
- OpenClaw：偏向長期個人助理，適合跨工具、跨平台、跨生活場景
- 真正的問題不是哪個比較強
- 而是你想養的是「工具」還是「助理」

---

## Takeaway

<div class="highlight-box">
AI 助理不是讓你變成 10 倍速超人，
而是幫你少做一點討厭的事，
多留一點力氣當人。
</div>

---

## Links

- AI 碎碎念：<https://www.threads.com/@stringpiggy>
- 個人網站：<https://candys.page>
