# 課程管理

* [建立課程](#建立課程)
* [右鍵功能選單](#右鍵功能選單)
    * [顯示班級 (Show Classes)](#顯示班級-show-classes)
    * [建立班級 (Create Class)](#建立班級-create-class)
    * [更新課程 (Edit Course)](#更新課程-edit-course)
    * [複製課程 (Duplicate Course)](#複製課程-duplicate-course)
    * [移除課程 (Remove Course)](#移除課程-remove-course)

## 建立課程
在工具列按 "New Course"
![](images/02.jpg)

#### 當 "New Course" 視窗打開，請輸入以下資料：

**基本資料 (Basic)**

| 欄位 | 注解 | 備注 |
| --- | --- | --- |
| Course Code| 以任何英文字母數字或"-"號組成，最多255個字符||
| Course Name| 任何字符，最多50個字符||
| Options | |
| - Allow Waiting|  此課程可接受後補名單| |
| - Trial Course | 此課程為「試堂」，課堂費用將自動設定為0 | |
| - Private Course| 此課程不會在EdFun網站上顯示 | |
| Type| 課程種類，這是課程的頂層分類 | |
| Subject| 課程主題，這是課程種類的子類別 | |
| Target| 課程對像 | |
| Grade| 級別，這是課程對像的子類別 | |
| Tags| 標籤，用於特別分類 | |
| Quota| 一班可以報名的最多人數 | |

![](images/03.jpg)

課程資料在EdFun網站出現的位置：
![](images/08.jpg)

**Prerequisite:**<br>
如課程有「入讀要求」，可在此輸入。內容會在EdFun網站的課程介紹頁顯示。
![](images/04.jpg)

**Course Descriptions:**<br>
- Short Description: 課程的簡短描述；
- Highlight Description: 課程的重點描述，內容會在EdFun網站的課程介紹頁顯示；
- Detail Page: 顯示課程是否已經有課程介紹頁；<br>
如果未有課程介紹頁，請看「[如何建立及連結課程介紹頁](/courses-management/course-detail-page.md)」<br>

![](images/05.jpg)

Short Description 內容會在EdFun網站的課程索引頁顯示。（如下圖）
![](images/09.jpg)

**Course Image:**<br>
上載課程圖片，會在EdFun網站的課程索引頁顯示。
![](images/06.jpg)

**Related Courses:**<br>
加入相關課程，此內容會在課程介紹頁的㡳部顯示。<br>
選擇課程種類(Type)，課程主題(Subject)，最後選取相關課程。<br>
相關課程可選多於一個，基於版面的美觀需要，提議最好選取3個。<br>

![](images/07.jpg)

**Save:**<br>
當所有欄位成功輪入，操作員可以按 "Save" 建立及儲存此課程。<br>
**注意：課程必須要有可報名的班級，才會前台網站顯示。[請看此如何建立班級](#建立班級-create-class)。**<br>
如系統發現有欄位有問題，會在有問題的欄位上(i)示圖，及顯示問題原因。<br>
操作員必須改正所有欄位，課程才能成功建立及儲存。

![](images/10.jpg)

---

## 右鍵功能選單
在表單上按右鍵可打開功能選單。
![](images/17.jpg)

#### 顯示班級 (Show Classes)
按右鍵選取 Show Classee，打開此課程所擁有的班級。
![](images/18.jpg)

#### 建立班級 (Create Class)
按右鍵選取 Create Classee，建立班級及課堂。當 Create Class 視窗打開，請輸入以下資料：

**Basic**
- Quota: 此班級可接收的人數上限；
- No. of lesson: 此班級的總堂數；
- Lesson Fee: 每堂費用；
- Start Date: 第一堂的日期；
- Days: 每逢星期幾上堂，可選一或多天；
- Start Time: 課堂開始時間；
- End Time: 課堂結束時間；
- Room: 選用班房（系統會基於人數上限，排除不合適的班房）；

![](images/19.jpg)

**Detail**
- Teacher: 選取導師，只有與課程主題(subject)相關的導師才會顯示；（如何加入/更新導師的課程主題，[請看此](accounts-management/teachers/#divide)）
- Divide: 選取分成；（如何加入/更新導師的分成，[請看此](accounts-management/teachers/#divide)）
- Enrollment Start: 開始報名時間（系統默認為今天）。前台網站只會在報名時間開始後，才顯示班級與同學報名；
- Enrollment Deadline: 結束報名時間；
- Payment Deadline: 最後交費日期；
- Payment Days: 同學必須報名後多少天內完成付款；

![](images/20.jpg)

**Discount**
- Discount Name: 如有需要，可選取折扣
- Start Date: 折扣的開始時間
- End Date: 折扣的結束時間

折扣可在 Settins > Discount Rules 內設定

![](images/21.jpg)

**預覽及確認建立班級**<br>
系統會顯示將會建立的班級及課堂。<br>
如建立的課堂時間有衝突，系統以紅線顯示，及自動跳到下一個有空缺的時間建立課堂。<br>
如操作員同意，按 Save Class 便會建立班級及課堂，否則可按 Cancel 回到前頁更改謝定。

![](images/22.jpg)

**成功建立班級及課堂**<br>
系統成功建立班級及課堂後，會打開 Class 頁及顯示剛剛建立的課堂。
![](images/23.jpg)

#### 更新課程 (Edit Course)
按右鍵選取 Edit Course，以更改課程設定。操作與[建立課程](#建立課程)相同。
![](images/24.jpg)

#### 複製課程 (Duplicate Course)
按右鍵選取 Duplicate Course，以此課程為藍本建立新的課程。系統會複製課程的內容，操作員必須填入不同的 course code，也可更改其他欄位，以建立新的課程。
![](images/25.jpg)

#### 移除課程 (Remove Course)
按右鍵選取 Remove Course，來移除此課程。移除時，如果課程下還有班級，課程將不能移除。操作員必須先移除所有課程下的班級。