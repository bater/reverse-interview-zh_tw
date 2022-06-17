# 反向面試

> 大部分翻譯自：https://github.com/viraptor/reverse-interview ，也包含眾多網友補充。

> 中文譯者另外製作了一份適合臨時抱佛腳的小抄版 LeetCode 題庫與面試題，也歡迎 Star。https://github.com/yifeikong/interview

下面列表裡的問題對於參加技術面試的人來說可能有些用。
列表裡的問題並不一定適用於某個特定的職位或者工作類型，也沒有排序。
最開始的時候這只是我自己的問題列表，但是慢慢地添加了一些我覺得可能讓我對這家公司亮紅燈的問題。
我也注意到被我面試的人提問我的問題太少了，感覺他們挺浪費機會的。

如果你問過的問題沒有被列出來，請提交一個 PR。

各種語系翻譯：

[English](https://github.com/viraptor/reverse-interview)
[Korean](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/blob/master/Reverse_Interview/README.md)
[Portuguese](https://github.com/viraptor/reverse-interview/blob/master/translations/PORTUGUESE.md)
[簡體中文](https://github.com/yifeikong/reverse-interview-zh)

## 如何使用本份文件

- 檢查一下哪些問題你感興趣
- 檢查一下哪些是你可以自己在網上找到答案的
- 找不到的話就向面試官提問

絕對不要想把這個列表裡的每個問題都問一遍。 （請尊重面試官的時間，而且你可以通過搜尋已經公開的答案來顯示你的主動性）

請記住事情總是靈活的，組織的結構調整也會經常發生。擁有一個 bug 追踪系統並不會保證高效處理 bug。
CI/CD （持續集成系統） 也不一定保證交付時間會很短。


# 職責內容

- On-call （電話值班）的計劃或者規定是什麼？值班或者遇到問題加班時候有加班費嗎？
- 我的日常工作是什麼？
- 有給我設定的特定目標嗎？
- 團隊裡面初級和高級工程師的比例是多少？ （有計劃改變嗎？）
- 入職培訓 (onboarding) 會是什麼樣的？
- 每個開發者有多大的自由來做出決定？
- 在你看來，這個工作做到什麼程度算成功？
- 你期望我在最初的一個月 / 三個月能夠完成什麼？
- 試用期結束的時候，你會怎麼樣衡量我的績效？
- 自己單獨的開發活動和按部就班工作的比例大概是怎樣的？
- 一個典型的一天或者一周的工作是怎樣安排的？
- 對我的申請你有什麼疑慮嗎？
- 在這份工作上，我將會和誰緊密合作？
- 我的直接上級他們的上級都是什麼樣的管理風格？ （鉅細彌遺還是著眼宏觀）
- 我在這個位置上應該如何發展？會有哪些機會？
- 每天預期 / 核心工作時間是多少小時？
- 我入職的職位是新增還是接替之前離職的同事？ （是否有技術債需要還）？ (zh)
- 入職之後在哪個專案，是新成立還是現有的？ (zh)

# 技術

- 公司常用的技術棧是什麼？
- 你們怎麼使用源碼控制系統？
- 你們怎麼測試代碼？
- 你們怎麼追踪 bug?
- 你們怎樣監控專案？
- 你們怎麼集成和部署代碼改動？是使用持續集成和持續部署嗎 (CI/CD)？
- 你們的基礎設施搭建在版本管理系統裡嗎？或者是代碼化的嗎？
- 從計劃到完成一項任務的工作流是什麼樣的？
- 你們如何準備故障恢復？
- 有標準的開發環境嗎？是強制的嗎？
- 你們需要花費多長時間來給產品搭建一個本地測試環境？ （分鐘 / 小時 / 天）
- 你們需要花費多長時間來響應代碼或者依賴中的安全問題？
- 所有的開發者都可以使用他們電腦的本地管理員權限嗎？
- 介紹一下你們的技術原則或者展望。
- 你們的程式有開發文件嗎？有沒有單獨的供消費者閱讀的文檔？
- 你們有更高層次的文件嗎？比如說 ER 圖，數據庫範式
- 你們使用靜態代碼分析嗎？
- 你們如何管理內部和外部的數位資產？
- 你們如何管理依賴？
- 公司是否有技術分享交流活動？有的話，多久一次呢？ (zh)
- 你們的數據庫是怎麼進行版本控制的？ (zh)
- 業務需求有沒有文件記錄？是如何記錄的？ (zh)

# 團隊

- 工作是怎麼管理的？
- 團隊內 / 團隊間的交流通常是怎樣的？
- 你們使用什麼工具來做專案管理？你的實際感受是什麼？
- 如果遇到不同的意見怎樣處理？
- 誰來設定優先級 / 計劃？
- 如果團隊沒能趕上預期發布日期怎麼辦？
- 每週都會開什麼類型的會議？
- 會有定期的和上級的一對一談話嗎？
- 產品 / 服務的規劃是什麼樣的？ （n 週一發布 / 持續部署 / 多個發布流 / ...)
- Production 環境發生事故了怎麼辦？是否有不批評人而分析問題的文化？
- 有沒有一些團隊正在經歷還尚待解決的挑戰？
- 你們如何追踪進度？
- 預期和目標是如何設定的？誰來設定？
- Code Review 如何實施？
- 給我介紹下團隊裡一個典型的 sprint
- 你們如何平衡技術和商業目標？
- 你們如何共享知識？
- 團隊有多大？
- 公司技術團隊的架構和人員組成？ (zh)
- 團隊內開發、產品、運營哪一方是需求的主要提出方？哪一方更強勢？ (zh)

# 未來的同事

- 開發者傾向於從哪裡學習？
- 你對在這里工作最滿意的地方是？
- 最不滿意的呢？
- 如果可以的話，你想改變哪裡？
- 團隊最老的成員在這裡多久了？
- 在小團隊中，有沒有出現成員性格互相衝突的情況？最後是如何解決的？

# 公司體質

- 公司為什麼在招人？ （產品發展 / 新產品 / 波動...)
- 有沒有會議 / 旅行預算？使用的規定是什麼？
- 晉升流程是怎樣的？要求 / 預期是怎樣溝通的？
- 績效評估流程是怎樣的？
- 技術和管理兩條職業路徑是分開的嗎？
- 有公司級別的學習資源嗎？比如電子書訂閱或者線上課程？
- 有獲取證書的預算嗎？
- 公司的成熟度如何？ （早期尋找方向 / 有內容的工作 / 維護中 / ...)
- 我可以為開源項目做貢獻嗎？是否需要審批？
- 你認為公司未來五年或者十年會發展成什麼樣子？
- 公司的大多數員工是如何看待Clean Code的？
- 你上次注意到有人成長是什麼時候？他們在哪方面成長了？
- 在這裡成功的定義是什麼？如何衡量成功？
- 有體育活動或者社團麼？
- 有內部的黑客松活動嗎？
- 公司支持開源專案嗎？
- 有競業條款或者保密協議需要簽嗎？
- 你們認為公司文化中的空白是什麼？
- 能夠跟我說一公司處於不良情況，以及如何處理的故事嗎？
- 您在這工作了多久了？您覺得體驗如何？ (zh)
- 大家為什麼會喜歡這裡？ (zh)
- 公司的調薪制度是如何的？ (zh)

# 社會價值觀

- 你們關於多元化招聘什麼看法？
- 你們對於性小眾有什麼看法？（同志 / 跨性別 / ...）
- 公司對於同性婚姻與異性戀婚姻的政策相同嗎？
- 你們的公司文化如何？你認為有什麼不足之處？
- 這裡的工作生活平衡如何？
- 公司對氣候變化有什麼觀點或政策嗎？

# 如何面對衝突

- 不同的意見如何處理？
- 如果被退回了會怎樣？ （“這個在預計的時間內做不完”）
- 當團隊有壓力並且在超負荷工作的時候怎麼處理？
- 如果有人注意到了在流程或者技術等其他方面又改進的地方，怎麼辦？
- 當管理層的預期和工程師的績效之間有差距的時候如何處理？
- 能給我講一個公司深處有毒環境以及如何處理的故事嗎？
- 如果在公司內你的同事因涉嫌性侵犯他人而被調查，請問你會如何處理？
- 假設我自己很不幸是在公司內被性侵的受害者，在公司內部有沒有爭取合法權益的管道？

# 商業模式

- 你們如何盈利？
- 你們現在盈利嗎？
- 如果沒有的話，還需要多久？
- 什麼阻止了你們賺更多的錢？
- 公司的資金來源是什麼？誰影響或者制定高層計劃或方向？
- 公司未來一年的增長計劃怎樣？五年呢？
- 你們認為什麼是你們的競爭優勢？
- 你們的競爭優勢是什麼？
- 公司未來的商業規劃是怎樣的？有上市的計劃嗎？ (zh)

# 遠距工作

- 遠距工作和辦公室工作的比例是多少？
- 公司提供硬體嗎？更新計劃如何？
- 使用自己的硬體工作可以嗎？現在有政策嗎？
- 額外的附件和家具可以通過公司購買嗎？這方面是否有預算？
- 有共享辦公或者上網的預算嗎？
- 多久需要去一次辦公室？
- 公司的會議室是否一直是支援視頻會議的？

# 辦公室設施與環境

- 辦公室的佈局如何？ （開放的 / 小隔間 / 獨立辦公室）
- 有沒有其他需要大量打電話的團隊或部門在我的團隊旁邊辦公？

# 終極問題

- 該職位為何會空缺？
- 公司如何保證人才不流失？
- 這份工作 / 團隊 / 公司最好和最壞的方面是？
- 你最開始為什麼選擇了這家公司？
- 你為什麼留在這家公司？

# 待遇

- 如果有獎金計劃的話，獎金如何分配？
- 如果有獎金計劃的話，過去的幾年裡通常會發百分之多少的獎金？
- 有退休養老金等福利嗎？
- 有額外商業保險嗎？例如人壽保險和額外的養老/醫療保險？
- 更換工作地點，公司付費嗎？

# 休假

- 帶薪休假時間有多久？
- 病假和事假是分開的還是一起算？
- 我可以提前使用假期時間嗎？也就是說應休假期是負的？
- 假期的更新策略是什麼樣的？也就是說未休的假期能否遞延入下一周期
- 照顧小孩的政策如何？
- 育嬰假、陪產假的規定如何呢？
- 無薪休假政策是什麼樣的？
- 學術性休假政策是怎麼樣的？

# 其他資源

更多有啟發性的參考來源：

  - [The Joel Test: 12 Steps to Better Code](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/) by Joel Spolsky
  - [Questions I'm asking in interviews](https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/) by Julia Evans

# License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
