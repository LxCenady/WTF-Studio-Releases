# WTF Studio 使用指南 / User Guide

内测版（Beta）。中文在前，English below.

---

## 中文

### 1. 这是什么

WTF (Worldwide Teachers Friend) Studio 是给老师用的出卷、批改和成绩工具：

- 按题型找真题，组卷并导出 PDF（试卷、答案与评分标准）
- 布置作业，导入学生答卷，逐个给分点批改；AI 批卷先出草稿，老师确认后才算正式成绩
- 班级名单、每题得分、薄弱题型，成绩可导出为 Excel 能打开的 CSV
- AI 出题，以及对 AI 题的评价（出题风格）
- Salos：右侧的 AI 助手，能帮你找题、整理练习、查看批改进度；凡是会改动数据的操作都要你先批准

### 2. 需要什么

- Windows 10 或 11
- 联网：登录、AI 功能和下载学科包需要联网
- 一个 WTF 账号（内测账号由我们为你开通）

### 3. 安装

1. 双击 `WTF-Setup.exe`。默认装在你的用户目录 `…\Programs\WTF Studio`，不需要管理员权限。
2. 安装完成后会自动启动，桌面和开始菜单里有"WTF Studio"快捷方式。

### 4. 第一次启动：装学科、提供真题、建题库

SCSA 的真题受版权保护，不随程序分发，需要在你的电脑上导入一次（每门课约 37 MB，约 10 分钟）。

1. **安装学科包**：点"WTF Hub: choose subjects…"，选中科目（例如 Mathematics Methods），点"Install the selected pack"，或直接双击那一行。
2. **2016–2019 年**：程序会自动从 Wayback Machine 存档下载，不用操作。
3. **2020–2025 年**：官网不允许程序直接下载。点"Open next batch"，浏览器会打开 6 个官方 PDF；在每个 PDF 页面按 Ctrl+S 保存到"下载"文件夹（文件名随意），回来点"I've saved them, check Downloads folder"。重复到全部到齐。
   - 如果你已经有这些 PDF（同事给的、U 盘里的），点"Choose folder…"选那个文件夹，一次导入。
4. 全部到齐后会自动建立题库，完成后自动进入 Studio。

### 5. 登录

输入邮箱，点"Send code"，把邮件里的 6 位验证码填进去，点"Sign in"。Studio 只有在账号服务器确认登录后才会打开。

### 6. 日常使用

首页有几块大按钮，顶部任务栏一直都在：

- **Find questions（找题）**：左侧按单元和题型浏览，点开看真题原图与评分标准；可以按年份、分值、关键词搜索。
- **Build a paper（组卷）**：把题加入组卷区，看分值和各部分占比，导出 PDF（试卷和答案评分标准两份）。"Set for a class"可直接布置给班级。
- **Classes & marks（班级与成绩）**：粘贴"学号,姓名"导入名单；查看每题平均分、最常丢的给分点、学生的题型掌握情况；导出成绩 CSV。
- **Mark assignments（批改作业）**：
  1. "New assignment"：选卷子、选班级、填名称日期。
  2. 导入学生答卷 PDF，并对应到学生。
  3. 手动批改：逐个给分点打对错；Enter 记得分、Backspace 记失分，数字键 1–9 连续给多个分。学生缺考用 N/A，不计入平均分。
  4. AI 批卷：在作业里启动后，AI 为每份答卷出草稿；你逐一查看、修改，确认后才进入正式成绩。
- **AI questions（AI 出题）**：选题型出新题，先看答案和给分点再用。每道题右边有评论框和评分矩阵（七项：课程范围、正确可解、表述清楚、背景与配图、难度与分值、给分点、像真题；每项分"好 / 要改 / 不能用"）。评论写多少都行。
- **Question style（出题风格）**：汇总老师对某个题型的评价。内测期间请多写评论，规则草稿和比较功能先不必使用。
- **Teaching materials（资料）**：你自己的 PDF 和讲义。
- **Salos**：点右上角"Salos"打开。可以问"找几道最值问题的真题""帮我看看这份作业还差什么"。它只能看到上方"Salos sees"里列出的科目、作业和你分享给它的班级与文件；布置作业、记分等操作会弹出确认卡片，你点"Approve"才会执行。

### 7. 内测期

- 试用期限和 AI 额度以我们为你开通的设置为准。AI 出题、AI 批卷和 Salos 都从这份额度里扣。
- 最后一周、或 AI 额度用到 80% 时，顶部会提示一次（每天最多一次）。
- **试用结束后**：工作区关闭，但你的班级、成绩和作业仍在你的电脑上。登录界面会显示"Export all my data"，点一下就会在"文档\WTF Studio"里生成一个 zip，里面有每个班的成绩 CSV 和全部数据。续用请联系 hello@wtf-academy.org。

### 8. 反馈问题

- 点顶部的"Feedback"（登录界面上是"Report a problem"）。写下遇到的问题和当时在做什么。
- 可以选择附上诊断日志（发送前能看到全文，学生姓名和学号已替换）和 Studio 窗口的截图。
- 没有网络时，点"Save the diagnostic log to a file"，把文件用邮件发给我们。

### 9. 数据与隐私

- 班级名单、成绩、学生答卷都保存在你的电脑上，WTF 服务器不保存学生资料。
- 使用 AI 功能时（AI 出题、AI 批卷、Salos），请求内容会经过 WTF 的 AI 代理转给模型服务商；代理不保存内容，只记录用量。AI 批卷会发送答卷图片，请确认学校同意后再使用。
- 你主动提交的反馈（文字、你选择附上的日志和截图）会保存在服务器上，只用于改进 Studio。

### 10. 常见问题

- **装学科时看不到"安装"按钮**：把 WTF Hub 窗口拉大或最大化，或直接双击要装的那一行。
- **真题检查不到**：确认存的是 PDF 而不是网页（官网有时先显示验证页面，等 PDF 显示出来再保存），或用"Choose downloaded files…"直接选中这些文件。
- **打不开、提示需要联网登录**：检查网络后点"Try again"。
- **一直没收到验证码**：看看垃圾邮件；仍然没有，请联系 hello@wtf-academy.org。

---

## English

### 1. What it is

WTF (Worldwide Teachers Friend) Studio is a teacher's tool for papers, marking and marks:

- Find past questions by question type, build a paper and export it as PDF (paper, answers and marking key)
- Set assignments, import students' scripts and mark them point by point; AI marking writes drafts, and only what you confirm becomes a formal mark
- Class lists, marks per question and weak question types; marks export as CSV for Excel
- AI-written questions, and your reviews of them (Question style)
- Salos: the AI assistant on the right that finds questions, drafts worksheets and checks marking progress; anything that changes your data waits for your approval

### 2. What you need

- Windows 10 or 11
- An internet connection: sign-in, AI features and subject packs need it
- A WTF account (we set up your beta account)

### 3. Install

1. Double-click `WTF-Setup.exe`. It installs into your user folder, `…\Programs\WTF Studio`, with no administrator rights.
2. It starts by itself when done; "WTF Studio" shortcuts are on the desktop and in the Start menu.

### 4. First start: a subject, its past papers, the question bank

SCSA past papers are copyright and not shipped with the app; you import them once on your computer (about 37 MB and 10 minutes per subject).

1. **Install a subject pack**: click "WTF Hub: choose subjects…", select a subject (e.g. Mathematics Methods) and click "Install the selected pack", or double-click its row.
2. **2016–2019**: downloaded automatically from the Wayback Machine archive; nothing to do.
3. **2020–2025**: the official website does not allow program downloads. Click "Open next batch": your browser opens 6 official PDFs. On each, press Ctrl+S and save to Downloads (any file name), then click "I've saved them, check Downloads folder". Repeat until none are missing.
   - Already have the PDFs (from a colleague, on a USB stick)? Click "Choose folder…" and pick that folder to import them in one go.
4. When everything is in, the question bank is built and Studio opens.

### 5. Sign in

Enter your e-mail, click "Send code", type the 6-digit code from the e-mail and click "Sign in". Studio opens only after the account server confirms your sign-in.

### 6. Everyday use

The home page has large tiles; the task bar along the top is always there:

- **Find questions**: browse by unit and question type on the left; open a question to see the original paper and its marking key. Search by year, marks or words.
- **Build a paper**: add questions, watch the marks and section balance, export the PDFs (paper; answers and marking key). "Set for a class" sets it as an assignment directly.
- **Classes & marks**: import a class by pasting `student number,name` lines; see each question's mean, the most often lost marking points and each student's mastery by question type; export marks as CSV.
- **Mark assignments**:
  1. "New assignment": choose the paper and the class, give it a name and date.
  2. Import the students' answer PDFs and match them to students.
  3. Mark by hand, point by point: Enter for earned, Backspace for lost, number keys 1–9 for several points at once. Use N/A for an absent student; it never counts towards a mean.
  4. AI marking: start it in the assignment; it drafts each script, you review and adjust, and only confirmed drafts become formal marks.
- **AI questions**: write new questions for a question type; read the answer and marking points before using one. Beside each question is a comment box and a review matrix (seven rows: curriculum, correct, clear wording, setting & figures, difficulty & marks, marking key, like past questions; each Good / Needs edits / Unusable). Write as much as you like.
- **Question style**: your reviews of a question type, collected. During the beta, comments help most; rule drafts and comparisons can wait.
- **Teaching materials**: your own PDFs and notes.
- **Salos**: click "Salos" at the top right. Ask things like "find some past questions on optimisation" or "what is left on this assignment?". It sees only what "Salos sees" lists (the subject, the open assignment, and the classes and files you share with it). Setting assignments or recording marks shows an approval card; nothing happens until you click "Approve".

### 7. During the beta

- Your trial's length and AI allowance are as we set them up for you. AI questions, AI marking and Salos all draw on that allowance.
- In the last week, or once 80 % of the AI allowance is used, a note appears at the top (at most once a day).
- **When the trial ends**, the workspace closes, but your classes, marks and assignments stay on your computer. The sign-in screen offers "Export all my data": one zip in Documents\WTF Studio with each class's marks as CSV and all your data. To continue, write to hello@wtf-academy.org.

### 8. Reporting a problem

- Click "Feedback" at the top ("Report a problem" on the sign-in screen). Say what went wrong and what you were doing.
- You can attach the diagnostic log (you see all of it before sending; students' names and numbers are replaced) and a screenshot of the Studio window.
- Offline? Click "Save the diagnostic log to a file" and e-mail us the file.

### 9. Data and privacy

- Class lists, marks and students' scripts stay on your computer; the WTF server keeps no student records.
- AI features (AI questions, AI marking, Salos) send their requests through WTF's AI proxy to the model provider; the proxy keeps no content, only usage numbers. AI marking sends images of scripts: please make sure your school agrees before using it.
- Feedback you choose to send (your text, and the log and screenshot if you attach them) is kept on our server and used only to improve Studio.

### 10. Questions

- **No "Install" button in WTF Hub**: enlarge or maximise the WTF Hub window, or double-click the subject's row.
- **Papers not found**: make sure you saved a PDF and not a web page (the website sometimes shows a check page first: wait for the PDF), or use "Choose downloaded files…" to pick them directly.
- **"Sign in online to use WTF Studio"**: check the connection and click "Try again".
- **No sign-in code**: check your spam folder; if it still has not arrived, write to hello@wtf-academy.org.
