# 管理學校

* [新增學校](#新增學校)
    * [界面](#界面)
        * [基本資料（Basic Info）](#基本資料（basic-info）)
        * [聯絡資料（Contact Info）](#聯絡資料（contact-info）)
        * [備注（Remark）](#備注（remark）)
    * [操作](#操作)
        * [新增成功](#新增成功)
        * [新增失敗](#新增失敗)
* [篩選捷徑](#篩選捷徑)
* [右鍵功能選單](#右鍵功能選單)
    * [課程報名（New Enrollment）](#課程報名（new-enrollment）)
    * [報名記錄（Show Enrollment）](#報名記錄（show-enrollment）)
    * [更新學校資料（Edit School）](#更新學校資料（edit-school）)
    * [發送重設密碼郵件（Send Reset Password Email）](#發送重設密碼郵件（send-reset-password-email）)
    * [發送啟動郵件（Send Activation Email）](#發送啟動郵件（send-activation-email）)

## 新增學校
在工具列左上角按下&nbsp;&nbsp;![](/images/101-1.png)&nbsp;&nbsp;，新增學校視窗會彈出。

![](/images/102.png)

#### 界面
###### 基本資料（Basic Info）

| 欄位           	| 注解         	| 備注                                                                                                                                   	|
|----------------	|--------------	|----------------------------------------------------------------------------------------------------------------------------------------	|
| Username       	| 登入用戶名稱 	| - 以任何英文字母數字或"-"號組成，最多255個字符<br>- 不能重複使用相同用戶名稱                                                           	|
| School         	| 學校         	| 必須填寫                                                                                                                               	|
| Address        	| 地址         	| 必須填寫                                                                                                                               	|
| Active Account 	| 啟動帳戶     	| 預設帳戶是未啟動，可在以下途徑啟動<br>- 學校啟動<br>學校在啟動電郵內，按下啟動連結<br><br>- 手動啟動<br>操作員在該學校註冊後，方可手動剔上 	|

![](/images/101.png)

###### 聯絡資料（Contact Info）

| 欄位  	| 注解 	| 備注                          	|
|-------	|------	|-------------------------------	|
| Title 	| 稱呼 	| 必須填寫                      	|
| Name  	| 姓名 	| - 最多255個字符<br>- 必須填寫 	|
| Phone 	| 電話 	| 必須填寫                      	|
| Email 	| 電郵 	| 必須填寫                      	|
| Fax   	| 傳真 	| -                             	|

![](/images/103.png)

###### 備注（Remark）

| 欄位   	| 注解 	| 備注 	|
|--------	|------	|------	|
| Remark 	| 備注 	| -    	|

![](/images/104.png)


#### 篩選捷徑

篩選捷徑位於工具列

![](/images/105.png)

|   ![](/images/106.png)   	| ![](/images/107.png) 	| ![](/images/108.png) 	|
|:------------------------:	|:--------------------:	|:--------------------:	|
| 顯示全部啟動或未啟動帳戶 	|    只顯示啟動帳戶    	|   只顯示未啟動帳戶   	|

> 有關其他篩選器操作，[按此了解](basic#篩選器-filters) 

#### 操作
當填妥表格後，可以按&nbsp;&nbsp;![](/images/10.png)&nbsp;&nbsp; 儲存或&nbsp;&nbsp;![](/images/11.png)&nbsp;&nbsp; 取消。

在新增學校過程中，操作員可能會遇上以下問題/提示：
* [新增成功](#新增成功)  
* [新增失敗](#新增失敗) 

###### 新增成功

表格通過後，會彈出發送啟動郵件提示。

> 有關發送啟動郵件，[按此了解](#發送啟動郵件（send-activation-email）) 

###### 新增失敗

若表格欄位有遺漏，系統會彈出提示，根據提示修正。

![](/images/109.png)

> 有關欄位規範，[按此了解](#界面) 

#### 右鍵功能選單

右鍵功能選單會因帳戶啟戶情況不同。

若帳戶已啟動，可操作功能如下：

| 功能                      	| 注解                                                               	|
|---------------------------	|--------------------------------------------------------------------	|
| New Enrollment            	| [課程報名](#課程報名（new-enrollment）)                            	|
| Show Enrollments          	| [報名記錄](#報名記錄（show-enrollments）)                          	|
| Edit School               	| [更新學校資料](#更新學校資料（edit-school）)                       	|
| Send Reset Password Email 	| [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）) 	|

![](/images/110.png)

若帳戶未啟動，可操作功能如下：

| 功能                      	| 注解                                                               	|
|---------------------------	|--------------------------------------------------------------------	|
| Show Enrollments          	| [報名記錄](#報名記錄（show-enrollments）)                          	|
| Edit School               	| [更新學校資料](#更新學校資料（edit-school）)                       	|
| Send Activation Email     	| [發送啟動郵件](#發送啟動郵件（send-activation-email）)]            	|
| Send Reset Password Email 	| [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）) 	|

![](/images/111.png)

###### 課程報名（New Enrollment）

在學校資料上右鍵並按下&nbsp;&nbsp;![](/images/112.png)&nbsp;&nbsp;，會彈出課堂列表。

可參考學員報名，[按此了解](accounts-management/students#課程報名（new-enrollment）) 

> 有關課程報名按鈕消失，[按此了解](#右鍵功能選單) 

###### 報名記錄（Show Enrollment）

在學校資料上右鍵並按下&nbsp;&nbsp;![](/images/113.png)&nbsp;&nbsp;，會顯示該學校的報名記錄。

###### 更新學校資料（Edit School）

在學校資料上右鍵並按下&nbsp;&nbsp;![](/images/114.png)&nbsp;&nbsp;或雙擊學校資料，會彈出修改視窗，操作員可以更新學校資料。

> 有關欄位規範，[按此了解](#界面) 

###### 發送重設密碼郵件（Send Reset Password Email）

在學校資料上右鍵並按下&nbsp;&nbsp;![](/images/116.png)&nbsp;&nbsp;，系統會詢問要否發送重設密碼郵件。

可參考（學員）發送重設密碼郵件，[按此了解](accounts-management/students#發送重設密碼郵件（send-reset-password-email）) 

> 有關發送重設密碼郵件按鈕消失，[按此了解](#右鍵功能選單)

###### 發送啟動郵件（Send Activation Email）

在學校資料上右鍵並按下&nbsp;&nbsp;![](/images/115.png)&nbsp;&nbsp;，系統會詢問要否發送啟動郵件。

可參考（學員）發送啟動郵件，[按此了解](accounts-management/students#發送啟動郵件（send-activation-email）) 

> 有關發送啟動郵件按鈕消失，[按此了解](#右鍵功能選單) 