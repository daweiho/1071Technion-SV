
## 20181119#5: Communicating Social Ventures I

### [Preview materials]

**→ Customer Discovry:**

- [Get out of the building (by S. Blank)](https://youtu.be/a-J_SwmMJyo)
- [There is a wrong way to get out of the building (by C. Lema)](https://chrislema.com/wrong-ways-get-out-of-the-building/)
- [How to write Agile User Stories?](https://gorillalogic.com/blog/how-to-write-agile-user-stories/)
- [From Personas to User Stories](http://www.romanpichler.com/blog/personas-epics-user-stories/)***
- [10 Tips to write User Stories](https://www.romanpichler.com/blog/10-tips-writing-good-user-stories/)***

**→ Gamification:**

- [Gamification: What is it?](https://youtu.be/-N-jMSymzBM)***
- [Gamification Guide: in the workplace](https://youtu.be/vInCVUIiq6g)*
- [Gaming can make a better world (by J. McGonagal)](https://www.ted.com/talks/jane_mcgonigal_gaming_can_make_a_better_world?language=en)
- [Case: The Fun Theory - Piano Stairs](https://youtu.be/2lXh2n0aPyw)



### [Suggestion readings]

- [設計大舌頭：如何打造對專案有效益的人物誌 ？](https://designtongue.me/persona-for-project/)***
- [設計大舌頭：體驗地圖與使用者體驗旅程](https://designtongue.me/體驗地圖-使用者體驗旅程/)
- [打造人們需要的產品(二)－人物誌Persona](https://medium.com/@Nathan_Lee/打造人們需要的產品-二-人物誌persona-2c309225a69b)*
- [遊戲化 Gamification 入門篇](https://vide.tw/2414)*
- [解析產品令人上癮的秘訣——遊戲化理論架構 Ocatalysis 介紹（上）](https://tw.alphacamp.co/blog/2015-09-21-gamification-framework-octalysis-1)***
- [原文完整版：Octalysis – the complete Gamification framework](https://yukaichou.com/gamification-examples/octalysis-complete-gamification-framework/?fbclid=IwAR0lC-z9BANebEVbVBqQZykLCgFqTpPgRbVTrRHcCYKAt_PcTmfI3sRgpJ8#.Vft6DiCqqko)
- [《遊戲化實戰全書》八角化理論打造讓人上癮的產品服務【閱讀筆記】](https://medium.com/@corik826/遊戲化實戰全書-八角化架構理論打造讓人上癮的產品服務-1790922e559e)*




### [Notes]＊

#### 1. 人物誌

**人物誌是什麼？**

人物誌是一種由研究結果轉畫出來的虛擬人物，常用來幫助我們瞭解不同類型的使用者之間在使用產品，生活態度與行為模式上的差異，近進而開發出更精準對應不同類型使用者的產品或服務，一位人物誌就代表「一群具有相似行為模式及目標的使用者」。要注意的是，人物誌與一般行銷所說的目標族群與市場區隔是截然不同的兩種內涵，行銷上的市場區隔往往是以年齡、性別、職業或收入來區隔（demography），
而人物誌則是以「行為、相似性」進行分類，幫助我們專注在客觀的行為需求，規劃符合真正人們需要而非我們自己認為很好的服務與產品。 

Personas offer a great way to capture the users and the customers with their needs. They are fictional characters that have a name and picture; relevant characteristics such as a role, activities, behaviours, and attitudes; and a goal, which is the problem that has to be addressed or the benefit that should be provided.

**面對人物誌，你該注意的是...**

- 人物誌的年齡、收入、職業或家庭背景都只是為了幫助我們沈浸故事，不具有意義
- 請專注在行為、目標與價值觀的描述，而非糾結於枝微末節的故事情節上
- 人物誌可在開發中的任何階段利用人物誌，檢視服務與產品是否偏離既定目標



#### 2. 使用者故事

- User stories are a powerful technique to capture the product functionality from the perspective of a user or customer. User stories want to tell a story about the users using the product. 

使用者故事（User Story） 是敏捷社群用來描述需求的practice。 它非常容易上手， 但是也容易犯下錯誤， 以下便是常見的問題：

**（1）都是使用者**

User story 有個範本： As a <role>， I want to <action> because of <business value>. 大家可以根據這個來撰寫使用者故事。可是很多人在寫的時候都會變成這個樣子：身為一個「使用者」，我想要「可以根據關鍵字查詢書籍」，因為「大多數時候我只記得一些關鍵字，這樣對我比較方便」

也就是說，大家都不區分你的使用者是誰，都把它泛稱使用者。可是這會讓你損失很多了解系統的機會。因為不同角色的人會有不同的考量和需求，並且也會有不同的優先順序，混為一談，只是讓你迷失在一大包功能列表中，而無法掌握重點一刀斃命。

 **（2）不是從客戶角度出發**
本來應該要從不同角色的角度出來，來思考他想要的需求是什麼？可是總是會有些是技術債，或者是product owner自己想要的東西。這些東西不是不能寫，而是要寫的時候，還是要站在客戶的角度，想想客戶會希望你這個東西做成什麼樣子。例如，有些debug log 資訊不完整的技術債，開發人員一開始可能會寫成：「身為開發人員，我要能產生一些debug logs，這樣好讓我再出錯時可以方便除錯。」如果你若是能再進一步從使用這個機制的客戶來思考，他可能要的會是像這樣：「身為開發人員，我要能產生一些可以分層且方便下載的debug logs，這樣好讓我再出錯時可以方便除錯，並且不用看太多訊息，或是收集太大的debug log。」

因為有時候產生debug log不是問題，問題是產生太多，短短時間內就產生了幾G大小的檔案，在某些環境下，你要使用者如何把這玩意下載交付到你手上。所以你如果能換位思考，同一個功能，你做出來會更貼心。

 **（3）沒有商業價值**
另外一個問題，就是沒有撰寫商業價值的部分。當我們沒有這部分的資訊，我們就無法判斷他到底有多急，或者是在該做到多少才足夠。例如：身為系統管理人員，我需要產生日報表。如果只是這樣就呆呆地去實踐日報表的功能，通常出來的都不會是客戶要的。你需要知道這報表出來是要給誰看的，是要那它來做什麼，大多時候我們都是一廂情願的給很多資料，可是你有想過上百頁的報表他會看嗎？或者是有時候客戶也不見得確定他想看什麼資料，或是想交付什麼資料給老闆看，這時候一份固定格式的報表，對他來說效益不大。所以我們需要有商業價值的部分，並且那只是起始點，我們還需要根據這個起始點，來和客戶好好溝通，他們內心真的在想什麼。

 **（4）沒有驗收條件**
寫過使用者故事的都知道，user story只是很簡單的一兩句話，他希望的就是你要去跟利害關係人討論，要去了解他們著遇到什麼問題，要這個功能的動機是什麼。此外還有一件重要的事情，就是要列出驗收條件，也就是定出要做的功能的範圍，如果沒有這個框框，在大家認知不同的狀況下，便會有不同的產出。

 例如：身為一個「使用者」，我想要「可以根據關鍵字查詢書籍」，因為「大多數時候我只記得一些關鍵字，這樣對我比較方便。」

是只針對書籍名稱找尋，還是對作者或是書籍簡介也搜尋？此外找出的書目，是根據出版時間，還是根據書籍名稱的字母順序排列？雖然這些功能不見得難做，可是一開始沒有做對，等到事後才來修改，不僅浪費工程師的時間，也讓使用者覺得很不貼心。為什麼不一開始就把驗收條件確認好呢？



#### 3. 遊戲化

##### 什麼是遊戲化？

遊戲化（Gamification）是 2002 年由英國工程師 Nick Pelling 提出，我們看一下[這篇文章](https://journals.tdl.org/absel/index.php/absel/article/viewFile/2137/2106)：

1. Gamification is the use of game design elements in non-game contexts
   遊戲化是將遊戲的元素放到非遊戲的內容之中
2. Gamification is the process of game-thinking and game mechanics to engage users and solve problems
   遊戲化是利用遊戲的思考與遊戲的機制讓使用者更容易解決問題

- 簡單來說，「遊戲化」是一種以「人性為中心的設計」（Human-Focused Design），根據人們為什麼做或不做某件事，找到能夠強化人們的感覺、動機和投入程度的誘因去做設計；反之，以功能為中心的設計（Function-Focused Design），則關注在如何提升產品效能、工作效率等，像是自動化或流線化系統，讓整個供應鏈可以更快速的運行。常見的累積點數、蒐集印章、成為「專家」，其實都是「遊戲化」的一種。不過行銷活動遊戲化也不是將積分遊戲（points）、獎勵制度（rewards）、計分板（leader board）等這些元素置入這麼簡單，最重要的是遊戲化的內容可以讓你的主要目標客群買帳，那麼才可稱作是一個成功的行銷遊戲化活動。

##### **周郁凱遊戲化的八角理論**

1. 重大使命與呼召（Epic meaning & calling）：意義是會讓人想要付出自己的時間與技能非常重要的一個因素，舉個例子，[Teach for Taiwan的劉安婷](http://www.teach4taiwan.org/)，她是一位放棄美國高薪回台灣推動偏鄉教育的夢想家，為了偏鄉的教育。Teach for Taiwan的偏鄉師資計畫每一位老師需要到偏鄉進行為期2年的教學。大家可能覺得奇怪，現在不是很多流浪教師嗎？為什麼偏鄉還是沒有老師？因為大多數的人還是會想要留在大城市，所以還是需要這樣有理想的組織，去補足偏鄉教育這個區塊。
   - 當一個玩家認為他在做一件很偉大的事情，或他被「選中」做某些事情。典型會出現的情形是，玩家投入很多時間在維持論壇或幫助整個社群的運作，像是維基百科、PTT、Reddit。而當玩家有著「新手玩家的好運」（Beginner’s Luck）時，也會啟動這個機制，人們相信比起其他的玩家，他更有天賦，或是相信他們很幸運就在遊戲的一開始抓到訣竅，是命中註定要來破關的玩家。
2. 進度與成就（ Development & Accomplishment）：點數、徽章與排行榜，這在大部份的網路遊戲，或是實體店家都會嘗試使用的方式，也因為大家被商人行銷的手段教育的很好，也習慣了這樣的方式，就看你有沒有想要參與這樣的集點。
   - 這是人們想要更進步、精進技能以及達成挑戰的內在驅力。在這個驅力的狀態下，「挑戰」的設計非常重要，如果挑戰沒有獲得相對應的獎勵就毫無意義。這也是最容易設計和執行的核心驅力，也是大部份PBL系統：積分（points）、徽章（badge）、排行榜（leader board）著重之處。
3. 賦予創造力與回饋（Empowerment of Creativity & Feedback）：提供一個園地可以讓玩家展現創意，例如小時候在玩超級瑪莉的時候，可以得到一個無敵星星，就可以全力衝刺把所有敵人都殺光。
4. 所有權與佔有慾（Ownership & Possession）：從玩家覺得他們擁有一些東西，他們就會自然而然地想要讓他們擁有的這些東西更好（像是裝備的升級），或是去追求更多的東西（獲得更多寶物、打敗更多的敵人、累積更多虛擬貨幣等）。此外，如果玩家花了很多時間在客製化他的人物角色、圖像，他也更容易覺得他「擁有」這個角色。集點換贈品、不同景點的印章蒐集就是利用這個概念。
5. 社會影響與關聯（ Social Influence & Relatedness）：所有與人相關的社會元素，包括：師徒關係、認同、友誼、競爭、敵對等。當你看到你的朋友有一個很厲害的技巧，或是擁有某個很特別的東西，你會不由自主地也會想要像他一樣。這個驅力也包括我們必須會想靠近和我們有關的人、地方、或是活動。比方說，行銷業者透過故事的包裝，讓你在看到商品的時候回想起你的小時候，這樣的懷舊的情節可能會增加你的購物慾望，就是利用這個驅力。
6. 稀缺性與迫切（Scarcity & Impatience）：當你很想要某個東西但你又不能馬上擁有的時候。很多遊戲都有延遲的機制，像是2個小時後你可以獲得在這場戰役裡面的獎勵－但人們其實很想要「馬上」就得到即時的回饋，可是因為無法獲得立即性的報償，讓他們把這件事情掛在心上。Facebook剛推出的時候就是運用這個概念，只開放給哈佛大學的學生使用，接著才開放給其他長春藤的名校，然後到所有的大學。因此當Facebook不再限制註冊者的身份時，人們便一湧而入地註冊，因為在那之前他們早就磨刀霍霍了！
7. 不確定性與好奇心（Unpredictability & Curiosity）：扭蛋就是一種不確定性與好奇心的展示，因為每次投錢之後，掉出來的扭蛋不一定是原先預期的。知名的心理學史金納箱（Skinner Box）實驗，因為出自於不確定性和好奇心，小白鼠沒辦法預測獎賞，所以會更頻繁地按壓槓桿。雖然很多人會錯誤地認為積點、記分板、徽章的獎勵機制是歸類在這個驅力之下。
8. 損失與避免（Loss & Avoidance）：與第二個（發展與成就感）相反，玩家參與遊戲是為了避免不好的事情發生，或是避免先前的努力功虧一簣。此外，當人們認為不趕快行動的時候，他們可能會永遠失去行動的機會，也是誘使行動的主要因素。例如：喝水App如果不喝水的話，App裡面的植物就會枯萎，引導人們養成正確的習慣。

##### 延伸閱讀

- [HackMD 共筆：遊戲化（Gamification）](https://hackmd.io/s/rJUvcQvee)
- [遊戲化 (Gamification) 與產品設計實踐：完整案例分析](https://medium.com/yahoo-apac-design/遊戲化-gamification-與產品設計實踐-b6899b0d9931)*
- [Gamification: Wharton Lifelong Learning Tour](https://www.youtube.com/watch?v=-jfgxt4AZIc) by Kevin Werbach
- [Octalysis: Complete Gamification Framework](http://www.yukaichou.com/gamification-examples/octalysis-complete-gamification-framework/#.Vjd4I7crKUn) by 台灣遊戲化大師周郁凱
- [Gamification to improve our world: Yu-kai Chou at TED x Lausanne](https://www.youtube.com/watch?v=v5Qjuegtiyc)
- [遊戲化(Gamification)行銷怎麼做？8角分析(Octalysis)教你誘客戶上鉤](https://transbiz.com.tw/gamification-遊戲化行銷-octalysis/)*
