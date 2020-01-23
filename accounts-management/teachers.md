# 管理導師

* [新增導師](#新增導師)
    * [界面](#界面)
        * [基本資料（Basic Info）](#基本資料（basic-info）)
        * [簡介（Short Description）](#聯絡資料（short-description）)
        * [詳細介紹（Long Description）](#詳細介紹（long-description）)
        * [薪金分成（Divide）](#薪金分成（divide）)
        * [備注（Remark）](#備注（remark）)
    * [操作](#操作)
        * [新增成功](#新增成功)
        * [新增失敗](#新增失敗)
* [新增代理](#新增代理)
* [篩選捷徑](#篩選捷徑)
* [右鍵功能選單](#右鍵功能選單)
    * [班級記錄](#班級記錄（show-classes）)
    * [課堂記錄](#課堂記錄（show-lessons）)
    * [素材記錄](#素材記錄（show-materials）)
    * [更新導師資料](#更新導師資料（edit-teacher）)
    * [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）)
    * [發送啟動郵件](#發送啟動郵件（send-activation-email）)


## 新增導師
在工具列左上角按下&nbsp;&nbsp;![](/images/202.png)&nbsp;&nbsp;，新增導師視窗會彈出。

![](/images/203.png)




#### 界面
###### 基本資料（Basic Info）

| 欄位           	| 注解         	| 備注                                                                                                                                   	|
|----------------	|--------------	|----------------------------------------------------------------------------------------------------------------------------------------	|
| Username       	| 登入用戶名稱 	| - 以任何英文字母數字或"-"號組成，最多255個字符<br>- 不能重複使用相同用戶名稱                                                           	|
| Profile Pic    	| 導師頭像     	| -                                                                                                                                      	|
| Name           	| 導師名稱     	| - 最多255個字符<br>- 必須填寫                                                                                                          	|
| Phone          	| 電話         	| 必須填寫                                                                                                                               	|
| Email          	| 電郵         	| - 電郵格式<br>- 必須填寫                                                                                                               	|
| First Day      	| 上班首日     	| -                                                                                                                                      	|
| Available Days 	| 上班周期     	| 必須填寫                                                                                                                               	|
| Active Account 	| 啟動帳戶     	| 預設帳戶是未啟動<br>- 導師啟動<br>導師在啟動電郵內，按下啟動連結<br><br>- 手動啟動<br>操作員在該導師註冊後，方可手動剔上               	|
| Type           	| 職位種類     	| 這裡有三種選擇<br>- Self Employment（自僱）<br>按固定分成<br><br>- Agent（代理）<br>按百分比分成<br><br>- Staffs（職員）<br>不適用分成 	|
| Agent List     	| 代理代表     	| 如選擇Agent，必須填寫                                                                                                                  	|

> 有關新增代理（Agent）操作，[按此了解](#新增代理) 

![](/images/204.png)

###### 簡介（Short Description）

| 欄位              	| 注解 	| 備注 	|
|-------------------	|------	|------	|
| Short Description 	| 簡介 	| -    	|

![](/images/205.png)

###### 詳細介紹（Long Description）

| 欄位             	| 注解     	| 備注 	|
|------------------	|----------	|------	|
| Long Description 	| 詳細介紹 	| -    	|

![](/images/206.png)

###### 薪金分成（Divide）

薪金分成允許新增多於一個及Staff（職員）不適用薪金分成。

| 欄位    	| 注解      	| 備注             	|
|---------	|-----------	|------------------	|
| id      	| 號碼      	| 系統自動安排     	|
| Name    	| 分成名稱  	| -                	|
| Subject 	| 學科/科目 	| -                	|
| Unit    	| 計算方法  	| 是取決於職位種類 	|
| Amount  	| 計算值    	| 必須正數         	|

![](/images/207.png)

###### 備注（Remark）

| 欄位   	| 注解 	| 備注 	|
|--------	|------	|------	|
| Remark 	| 備注 	| -    	|

![](/images/208.png)

#### 新增代理

此操作需要後台管理員權限。

1. 在後台 Object → agents 
2. 右鍵 Add object → Teacher → TeacherAgent 
3. 輸入名稱（name） 
4. 按下 Save & Publish

完成後，便會出現新Agent在 Agent List 內。

![](/images/221.png)

若沒有出現，請

1. 重新整理瀏覽器或
2. 退出新增/修改視窗並重新開啟（未儲存資料將會流失）。

#### 篩選捷徑

篩選捷徑位於工具列

![](/images/209.png)

| ![](/images/210.png) 	| ![](/images/211.png) 	| ![](/images/212.png) 	| ![](/images/213.png) 	|
|:--------------------:	|:--------------------:	|:--------------------:	|:--------------------:	|
|   顯示全部導師帳戶   	|    只顯示自僱導師    	|    只顯示代理導師    	|    只顯示職員導師    	|

> 有關其他篩選器操作，[按此了解](basic#篩選器-filters) 

#### 操作
當填妥表格後，可以按&nbsp;&nbsp;![](/images/10.png)&nbsp;&nbsp; 儲存或&nbsp;&nbsp;![](/images/11.png)&nbsp;&nbsp; 取消。

在新增導師過程中，操作員可能會遇上以下問題/提示：
* [新增成功](#新增成功)  
* [新增失敗](#新增失敗) 

###### 新增成功

表格通過後，會彈出發送啟動郵件提示。

> 有關發送啟動郵件，[按此了解](#發送啟動郵件（send-activation-email）) 

###### 新增失敗

若表格欄位有遺漏，系統會彈出提示，根據提示修正。

![](/images/214.png)

> 有關欄位規範，[按此了解](#界面) 

#### 右鍵功能選單

右鍵功能選單會因帳戶啟戶情況不同。

若帳戶已啟動，可操作功能如下：

| 功能                      	| 注解                                                               	|
|---------------------------	|--------------------------------------------------------------------	|
| Show Classes              	| [班級記錄](#班級記錄（show-classes）)                              	|
| Show Lessons              	| [課堂記錄](#課堂記錄（show-lessons）)                              	|
| Show Materials            	| [素材記錄](#素材記錄（show-materials）)                            	|
| Edit Teacher              	| [更新導師資料](#更新導師資料（edit-student）)                      	|
| Send Reset Password Email 	| [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）) 	|

![](/images/215.png)

若帳戶未啟動，可操作功能如下：

| 功能                      	| 注解                                                               	|
|---------------------------	|--------------------------------------------------------------------	|
| Show Classes              	| [班級記錄](#班級記錄（show-classes）)                              	|
| Show Lessons              	| [課堂記錄](#課堂記錄（show-lessons）)                              	|
| Show Materials            	| [素材記錄](#素材記錄（show-materials）)                            	|
| Edit Teacher              	| [更新導師資料](#更新導師資料（edit-student）)                      	|
| Send Activation Email     	| [發送啟動郵件](#發送啟動郵件（send-activation-email）)             	|
| Send Reset Password Email 	| [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）) 	|

![](/images/216.png)

###### 班級記錄（show-classes）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/217.png)&nbsp;&nbsp;，會跳到 Classes 頁面並篩選只有該導師記錄。

> 有關班級操作，[按此了解](courses-management/classes.md#main)

###### 課堂記錄（show-lessons）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/218.png)&nbsp;&nbsp;，會跳到 Lessons 頁面並篩選只有該導師記錄。

> 有關課堂操作，[按此了解](courses-management/lessons.md#main)

###### 素材記錄（show-materials）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/219.png)&nbsp;&nbsp;，會跳到 Materials 頁面並篩選只有該導師記錄。

> 有關素材操作，[按此了解](operations/materials.md#main)

###### 更新導師資料（Edit School）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/220.png)&nbsp;&nbsp;或雙擊導師資料，會彈出修改視窗，操作員可以更新導師資料。

> 有關欄位規範，[按此了解](#界面) 

###### 發送重設密碼郵件（Send Reset Password Email）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/116.png)&nbsp;&nbsp;，系統會詢問要否發送重設密碼郵件。

可參考（學員）發送重設密碼郵件，[按此了解](accounts-management/students#發送重設密碼郵件（send-reset-password-email）) 

> 有關發送重設密碼郵件按鈕消失，[按此了解](#右鍵功能選單)

###### 發送啟動郵件（Send Activation Email）

在導師資料上右鍵並按下&nbsp;&nbsp;![](/images/115.png)&nbsp;&nbsp;，系統會詢問要否發送啟動郵件。

可參考（學員）發送啟動郵件，[按此了解](accounts-management/students#發送啟動郵件（send-activation-email）) 

> 有關發送啟動郵件按鈕消失，[按此了解](#右鍵功能選單) 