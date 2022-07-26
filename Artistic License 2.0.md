# Artistic License 2.0 (Artisitc 2.0)

Artistic 2.0 原文內容[請點這裡瀏覽](https://www.opensource.org/licenses/artistic-license-2.0)。

##　一、概覽

Artistic 2.0 是 the Artistic Licnese (Artistic) 的升級版本。由於 Artisitc 條款的規定有許多模糊不清的地方，並且不相容於應用普遍的 GPL，因此 Perl 基金會 (The Perl Foundation, TPF) 決定改版，並且於 2006 年正式發布 Artistic 2.0。

Artistic 2.0 由 Roberta Cairney 與 Allison Randal 共同執筆撰寫完成，內容除了遵循自由軟體的精神之外，並且承襲前一個版本，將「藝術控制 (artistic control)」作為實踐的理想目的。由於具有這樣的混合目的，因此 Artistic 2.0 並不像 GPL、LGPL 等授權條款會嚴格拘束被授權人利用軟體的方式，但是卻也不會如同 BSD、MIT 等條款的規定幾乎無拘無束，而是有著獨樹一格的權利義務規定。關於「藝術控制 (artistic control)」與相關的 Artistic 2.0 重要規定，可以參考「獨樹一格的藝術條款：Artistic License 2.0」。

##　二、目前運用狀況

與前一個版本一樣，Artistic 2.0 主要是應用在 Perl 程式語言、CPAN 與 Parrot 等軟體上，其中 Perl 自第 6 版開始採用 Artistic 2.0，而之前的版本則是採用舊版 Artistic 跟 GPL 的雙重授權方式。

##　三、權利義務

根據 Artistic 2.0，被授權人被授予特定的著作權與大範圍的專利權，而在享有這些權利的同時，被授權人也必須遵守相關的義務規定。

在了解 Artistic 2.0 所規定的權利義務之前，必須要先了解這份條款中所定義的「標準版本 (Standard Version)」與「修改版本 (Modified Version)」這兩個相對的概念。「標準版本 (Standard Version)」是指著作權人所認定的標準版本，所以著作權人自己所發布的軟體與後續改版，都是屬於標準版本，此外，只要是依照著作權人明確指示而修改出來的版本，即使不是著作權人自己所發布，一樣是屬於標準版本。至於其他因為修改了標準版本而產生出來的，就都是「修改版本 (Modified Version)」。透過這樣的分別機制，原 Artistic 2.0 軟體的著作權人可以確保標準版本依照自己堅持的寫作規則與方向來發展，同時他人也藉由「標準版本」這個名詞，可以辨識出哪一個版本是著作權人心中所認可的理想後續版本。

###　（一）權利

1. 被授權人有權利執行、修改、重製與散布標準版本與修改版本。不過在散布的時候，必須要遵守一些義務規定，這些義務規定請見下面（二）的說明。
2. 散布標準版本的時候，被授權人可以不收取任何費用，但是也可以選擇收取散布費用 (Distributor Fee)，散布費用可以是因為散布行為而產生的費用，或者是提供支援的服務費用。
3. 被授權人在特定範圍之內，可以為修改版本選擇 Artistic 2.0 以外的條款來授權。詳細選擇方式請見下面（二）義務規定說明的第 3 點。
4. 被授權人可以利用軟體中由著作權人合法授權的專利技術，這些利用行為包括製造、代工、使用、販賣、為了販賣而提供給他人、進口以及運輸軟體等行為。而這些合法授權的專利技術是指，著作權人自己擁有的專利技術，或者是著作權人從他人取得、可以再次授權出去的專利技術，由於在這兩種情況下，著作權人擁有全部的專利權或者是取得可以再授權的權利，因此著作權人可以透過 Artistic 2.0 將這些技術的專利權授權出去，讓被授權人在利用軟體的範圍內，可以一併利用這些已經申請、受到專利權保護的技術。

### （二）義務

1. 散布標準版本原始碼的時候，被授權人：
   1. 必須散布所有完整的原始碼；
   2. 必須重製一切的著作權標示與相關聲明，讓後手可以閱讀到這些文字；
   3. 可以自行決定是否與編譯過的形式一起散布。
2. 若是要散布修改版本原始碼的話，被授權人必須要詳實記錄修改版本中所有的修改之處，包括與標準版本有哪些不同的功能、可執行檔案或者是任何經過變動的模組資訊等等，以便利原軟體開發團隊能了解修改內容，並在認同修改內容的情況下，將這些修改處順暢地納入後續版本的開發，以達到原軟體專案開發者能持續參與軟體修改與更新除錯的目的。
3. 若是要散布修改版本原始碼的話，被授權人必須在下列三種方式中選擇一項，來為修改版本選定授權條款與散布方式：
   1. 選擇 Artistic 2.0 作為修改版本的授權條款，並且主動地讓著作權人可以取得修改版本的程式碼，以方便著作權人將修改內容納入到標準版本中。若是被授權人想要將自己的修改內容回饋給原軟體開發社群，就可以利用這項規定。
   2. 選擇其他具有授權拘束性的自由軟體授權條款來授權修改版本，這類條款包括 GPL、LGPL 與 MPL 等，不過並不僅止於這些條款，只要是符合下面三項要件的授權條款，被授權人也都可以採用：(a) 允許他人可以自由重製、修改與再散布修改版本；(b) 他人可以自由取得修改版本與由此再衍生出來程式的原始碼；(c) 散布修改版本與再衍生出來程式的時候，禁止收取授權金，不過可以收取散布費用。關於服務費用請參考上面（一）權利規定說明的第 2 點。若是修改版本必須與 GPL、LGPL 或 MPL 授權的軟體結合成為另一個更大的軟體專案時，就可以利用這項規定，讓原本是 Artistic 2.0 授權的程式碼，順利地與採用這類具有授權拘束性條款的軟體結合在一起。
   3. 在符合特定的條件下，被授權人可以選擇任何一份符合自身需求的條款來授權修改版本，例如 BSD、MIT，甚至是不提供原始碼的傳統商業軟體授權條款。而這裡所謂的特定條件有二：一方面修改版本的名稱不可以與標準版本相混淆，必須要讓他人能夠清楚辨識兩者的差異，另外一方面，修改版本的安裝不會影響到標準版本的安裝或執行，也就是說，其他的使用者可以用標準版本來置換修改版本，而整個軟體仍然可以正常運作。若是被授權人預計不採用 Artistic 2.0 或其他具有授權拘束性的條款來授權修改版本的話，就可以利用這項彈性規定，將修改版本與相關的程式碼調整到符合規定的狀態，被授權人就可以為修改版本選擇前兩項以外的條款來授權。   
4. 被授權人可以散布標準版本的編譯後形式，不過必須要附上一份完整的說明文件，告知他人如何取得原始碼。而從開始散布標準版本的時候起，這份說明文件的內容就必須是有效的，若說明文件的內容在散布的期間失效的話，被授權人必須要在知悉這樣的狀況起 30 天內，提供新的說明文件或者是取消之前發布的說明文件，否則將會喪失 Artistic 2.0 條款所給予的權利。
5. 被授權人可以散布修改版本的編譯後形式，而散布條件依照修改版本授權條款的規定。而修改版本所採用的授權條款，請被授權人依照上述義務規定說明第 3 點來進行選擇。

##　四、專有特色

1. Artistic 2.0 在 2007 年經過開放源碼促進會 (Open Source Initiative, OSI) 審核通過，是一份經過 OSI 核可認證的開放源碼授權條款，此外，自由軟體基金會 (Free Software Foundation, FSF) 也認定這是一份符合四大自由的自由軟體授權條款。
2. Artistic 2.0 規定有專利報復條款，若是被授權人對任何人提出專利訴訟，並且訴訟內容主張這個 Artistic 2.0 軟體侵害他人專利權的話，那麼從提出訴訟之日開始，Artistic 2.0 授予這位被授權人的權利將全部終止。
