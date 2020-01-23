# 基礎知識

* [表頭](#表頭-table-header)
    * [更改欄位 (Columns)](#更改欄位-columns)
    * [排序 (Sorting)](#排序-sorting)
    * [篩選器 (Filters)](#篩選器-filters)
* [工具列](#工具列)
    * [操作鍵/快捷鍵](#操作鍵快捷鍵)
    * [上載列表(Upload CSV)](#上載列表-upload-csv)
    * [下載列表(Download List)](#下載列表-download-list)
    * [清除篩選器(Clear Filters)](#清除篩選器-clear-filters)
* [右鍵功能選單](#右鍵功能選單)
* [頁數控制](#頁數控制)
* [修改記錄](#修改記錄)

本系統以試算表的形式顯示記錄，其操作方法與Excel的試算表十分相似。

![](/images/02.jpg)

## 表頭 (Table header)
列表的表頭隱藏了以下功能，以方便操作員更容易找到所須資料。

#### 更改欄位 (Columns)
可以自訂欄位，顯示最佳工作列表。  

![](/images/03-2.png)

部份欄位是預設隱藏。

#### 排序 (Sorting)
可以直接按下表頭欄位，允許操作員按順序或例序方式排列，

![](/images/03.png)

或表頭旁邊的下箭咀。

![](/images/03-1.png)

所有排序只允許按一個表頭欄位排列，不支持多個表頭欄位排列。

#### 篩選器 (Filters)
可以輸入關鍵字篩選項目。

![](/images/03-3.png)

不同欄位會有不同類別篩選模式。

![](/images/03-4.png)  
（數字篩選模式）

![](/images/03-5.png)  
（分類篩選模式）


> 有關如何清除篩選操作，[按此了解](#清除篩選器-clear-filters) 

---

## 工具列
#### 操作鍵/快捷鍵
會隨著不同的頁面而變化，提供不同的功能。  
相關功能。請參閱該頁面簡介。

![](/images/05-2.png)

#### 上載列表 (Upload CSV)
先準備CSV檔案，你可以在&nbsp;&nbsp;![](/images/06.png)&nbsp;&nbsp;取得它，並修改內容。
> 有關如何下載列表，[按此了解](#下載列表-download-list)  


按下&nbsp;&nbsp;![](/images/05.png) &nbsp;&nbsp;→ &nbsp;&nbsp;![](/images/05-1.png)&nbsp;&nbsp;把已預備好的CSV檔案上傳。

![](/images/09.png) 

如果發現 **Status** 有紅字「Fail」，請按下&nbsp;&nbsp;![](/images/09-2.png)&nbsp;&nbsp;，按照 **Remark** 上的提示修正。

![](/images/10.png)  

修正後，重新按&nbsp;&nbsp;![](/images/05-1.png)&nbsp;&nbsp;把已修正好的CSV檔案上傳。

![](/images/11.png) 

然後按&nbsp;&nbsp;![](/images/12.png)&nbsp;&nbsp;，新的列表列會立即更新。





#### 下載列表 (Download List)
你可以從&nbsp;&nbsp;![](/images/06.png)&nbsp;&nbsp;下載完整列表或可以篩選後下載部份項目的列表。

![](/images/06-1.png)

> 有關如何篩選部份項目的列表操作，[按此了解](#篩選器-filters) 





#### 清除篩選器 (Clear Filters)
要把篩選內容清除，可以按下&nbsp;&nbsp;![](/images/07.png)&nbsp;&nbsp;。  

![](/images/13.png)

已篩選欄位的底線消失。

![](/images/14.png)

清除篩選器不會重設欄位及排序，如要重設，請在瀏覽器按下重新整理

> 有關如何篩選部份項目的列表操作，[按此了解](#篩選器-filters) 

---
## 右鍵功能選單
系統內大部份功能，都由功能選單控制。功能選單會隨著不同的頁面而變化，提供不同的功能。

![](/images/01.jpg)

---
## 頁數控制
各頁面都有頁數控制。

![](/images/15.png)

以下是簡單介紹

| ![](/images/16.png) | ![](/images/17.png) | ![](/images/18.png) | ![](/images/19.png) | ![](/images/20.png) |
|---------------------|---------------------|---------------------|---------------------|---------------------|
| 前往第一頁          | 上一頁          | 輸入數字跳入該頁數          | 下一頁          | 前往最後一頁           |

| ![](/images/21.png) |
|---------------------|
| 重新整理（只會重新載入當前列表結果）          |

> 有關如何清除篩選操作，[按此了解](#清除篩選器-clear-filters)  

| ![](/images/22.png) |
|---------------------|
| 記錄數目          |

---
## 修改記錄
如管理人需要得到某個記錄的修改記錄，可以登入 CMS 查閱，方法如下：

1. 打開隱藏的 ID 欄，記下要查詢的記錄的ID;
![](images/23.jpg)

2. 登入 CMS （注意：CMS使用不同於操作員的戶口登入）：<br>
[http://cpie.dq.hk/admin](http://cpie.dq.hk/admin)
![](courses-management/images/14.jpg)

3. 在工具列選取 Open Object
![](images/24.jpg)

4. 輸入記錄 ID
![](images/25.jpg)

5. 按 versions，查閱修改記錄
![](images/26.jpg)

注意：系統設定保留每項記錄十個版本，如超過10次改動，較舊的版本會被取代。

**重要：不要通過CMS改動系統內的任何記錄，這樣做有可能產生數據衝突而影响系統運作！**