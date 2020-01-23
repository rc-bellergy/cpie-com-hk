# 學員管理


* [新增學員](#新增學員)
    * [界面](#界面)
        * [基本資料（Basic Info）](#基本資料（basic-info）)
        * [更多資料（More Info）](#更多資料（more-info）)
        * [家屬聯絡人資料（Parent's Info） ](#家屬聯絡人資料（parent39s-info）)
        * [備注（Remark） ](#備注（remark）)
    * [操作](#操作)
        * [新增成功](#新增成功)
        * [新增失敗](#新增失敗)
* [篩選捷徑](#篩選捷徑)
* [右鍵功能選單](#右鍵功能選單)
    * [出席記錄（Show Attendances）](#出席記錄（show-attendances）)
    * [報名記錄（Show Enrollments）](#報名記錄（show-enrollments）)
    * [更新學員資料（Edit Student）](#更新學員資料（edit-student）)
    * [發送啟動郵件（Send Activation Email）](#發送啟動郵件（send-activation-email）)
    * [課程報名（New Enrollment）](#課程報名（new-enrollment）)
    * [發送重設密碼郵件（Send Reset Password）](#發送重設密碼郵件（send-reset-password-email）)




## 新增學員

學員戶口可在EdFun前台網站由學員自行登記及產生。 操作員亦可在本系統為學員產生，方法如下：

在工具列左上角按下&nbsp;&nbsp;![](/images/02.png)&nbsp;&nbsp;，新增學員視窗會彈出。

![](/images/06-1.png)

#### 界面 
###### 基本資料（Basic Info） 

| 欄位           	| 注解                 	| 備注                                                                                                                         	|
|----------------	|----------------------	|------------------------------------------------------------------------------------------------------------------------------	|
| Username       	| 登入用戶名稱         	| - 以任何英文字母數字或"-"號組成，最多255個字符<br>- 不能重複使用相同用戶名稱                                                 	|
| Name           	| 學員名稱             	| - 最多255個字符<br>- 必須填寫                                                                                                	|
| Chinese Name   	| 學員中文名稱（如有） 	| 最多255個字符                                                                                                                	|
| Email          	| 電郵                 	| - 電郵格式<br>- 必須填寫                                                                                                     	|
| Phone          	| 電話                 	| 必須填寫                                                                                                                     	|
| Gender         	| 性別                 	| 必須填寫                                                                                                                     	|
| DOB            	| 出生日期             	| 必須填寫                                                                                                                     	|
| Active Account 	| 啟動帳戶             	| 預設帳戶是未啟動，可在以下途徑啟動<br>- 學員啟動<br>學員在啟動電郵內，按下啟動連結<br><br>- 手動啟動<br>操作員在該學員註冊後，方可手動剔上 	|

![](/images/06.png)

###### 更多資料（More Info） 

| 欄位         	| 注解               	| 備注                     	|
|--------------	|--------------------	|--------------------------	|
| Grade        	| 組別               	| 必須填寫                 	|
| School       	| 學校               	| -                        	|
| How To Know  	| 什麼途徑知道本中心 	| -                        	|
| Input others 	| 其他               	| 必須填寫（選擇"Others"） 	|
| Address      	| 地址               	| -                        	|

![](/images/07.png)


###### 家屬聯絡人資料（Parent's Info） 

只適用於學員在18歲以下

| 欄位         	| 注解 	| 備注     	|
|--------------	|------	|----------	|
| Parent Title 	| 稱呼 	| 必須填寫 	|
| Parent Name  	| 姓名 	| 必須填寫 	|
| Parent Phone 	| 電話 	| 必須填寫 	|
| Parent Email 	| 電郵 	| -        	|

![](/images/08.png)


###### 備注（Remark） 

| 欄位   	| 注解 	| 備注 	|
|--------	|------	|------	|
| Remark 	| 備注 	| -    	|

![](/images/09.png)


#### 操作
當填妥表格後，可以按&nbsp;&nbsp;![](/images/10.png)&nbsp;&nbsp; 儲存或&nbsp;&nbsp;![](/images/11.png)&nbsp;&nbsp; 取消。

在新增學員過程中，操作員可能會遇上以下問題/提示：
* [新增成功](#新增成功)  
* [新增失敗](#新增失敗) 

###### 新增成功 

表格通過後，會彈出發送啟動郵件提示。

> 有關發送啟動郵件，[按此了解](#發送啟動郵件（send-activation-email）) 

###### 新增失敗 

若表格欄位有遺漏，系統會彈出提示，根據提示修正。

![](/images/12.png)

> 有關欄位規範，[按此了解](#界面) 

## 篩選捷徑

篩選捷徑位於工具列

![](/images/13.png)

|    ![](/images/03.png)   | ![](/images/04.png) | ![](/images/05.png) |
|:------------------------:|:-------------------:|:-------------------:|
| 顯示全部啟動或未啟動帳戶 |    只顯示啟動帳戶   |   只顯示未啟動帳戶  |

> 有關其他篩選器操作，[按此了解](basic#篩選器-filters) 

## 右鍵功能選單

右鍵功能選單會因帳戶啟戶情況不同。

若帳戶已啟動，可操作功能如下：

| 功能                      	| 注解                                                               	|
|---------------------------	|--------------------------------------------------------------------	|
| Show Attendances          	| [出席記錄](#出席記錄（show-attendances）)                          	|
| Show Enrollments          	| [報名記錄](#報名記錄（show-enrollments）)                          	|
| New Enrollment            	| [課程報名](#課程報名（new-enrollment）)                            	|
| Edit Student              	| [更新學員資料](#更新學員資料（edit-student）)                      	|
| Send Reset Password Email 	| [發送重設密碼郵件](#發送重設密碼郵件（send-reset-password-email）) 	|

![](/images/14.png)

若帳戶未啟動，可操作功能如下：

| 功能                  	| 注解                                                       	|
|-----------------------	|------------------------------------------------------------	|
| Show Attendances      	| [出席記錄](#出席記錄（show-attendances）)                  	|
| Show Enrollments      	| [報名記錄](#報名記錄（show-enrollments）)                  	|
| Edit Student          	| [更新學員資料](#更新學員資料（edit-student）)              	|
| Send Activation Email 	| [發送啟動郵件](#發送啟動郵件（send-reset-password-email）) 	|

![](/images/15.png)


####  出席記錄（Show Attendances）

在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/16.png)&nbsp;&nbsp;，會顯示該學員的出席記錄。

> 有關出席記錄操作，[按此了解](attendances#main) 

####  報名記錄（Show Enrollments）

在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/17.png)&nbsp;&nbsp;，會顯示該學員的報名記錄。

> 有關課堂記錄操作，[按此了解](enrollment#main) 

####  更新學員資料（Edit Student）

學員資料可在EdFun前台網站由學員自行更改。 操作員亦可在本系統為學員更改，方法如下：<br>
在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/19.png)&nbsp;&nbsp;或雙擊學員資料，會彈出修改視窗，操作員可以更新學員資料。

> 有關欄位規範，[按此了解](#界面) 

####  發送啟動郵件（Send Activation Email）

在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/21.png)&nbsp;&nbsp;或在成功新增學員後，系統會詢問要否發送啟動郵件。啟動郵件會發送到學員登記的電郵地址，學員必須按下啟動連結以啟動戶口。

![](/images/22.png)

按下&nbsp;&nbsp;![](/images/23.png)&nbsp;&nbsp;發送啟動郵件。

按下&nbsp;&nbsp;![](/images/24.png)&nbsp;&nbsp;以取消當前操作。

> 有關發送啟動郵件按鈕消失，[按此了解](#右鍵功能選單) 

#### 課程報名（New Enrollment）

學員可在EdFun前台網站瀏覽課程，並完成報名。操作員亦可在本系統為學員報讀課程，方法如下：<br>
在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/18.png)&nbsp;&nbsp;，會彈出課堂列表。

![](/images/25.png)

在列表裡，系統提供三款搜尋關鍵範圍/字及只能使用一款

1. [Type ＋ Subject](#type-＋-subject)
2. [Course](#course)
3. [Class Code](#class-code)

然後[報名](#報名)。

> 有關課程報名按鈕消失，[按此了解](#右鍵功能選單) 

###### Type ＋ Subject

可以根據課堂分類作搜尋關鍵範圍。

![](/images/26.png)

###### Course

可以根據課堂名稱作搜尋關鍵字。

![](/images/27.png)

###### Class Code

可以根據課堂編號作搜尋關鍵字。

![](/images/28.png)

###### 報名
選取課堂並按右鍵及&nbsp;&nbsp;![](/images/30-2.png)&nbsp;&nbsp;報名。  
操作員也可以按&nbsp;&nbsp;![](/images/30-1.png)&nbsp;&nbsp;查看該課堂時間表。

![](/images/30.png)

成功報名後，系統會跳到 Enrollment 頁面。

![](/images/31.png)


> 有關查閱該學員課程報名記錄，[按此了解](#報名記錄（show-enrollments）)  

> 有關查閱所有學員課程報名記錄，[按此了解](enrollment#main) 


####  發送重設密碼郵件（Send Reset Password Email）

如學員忘記密碼，可在EdFun前台網站要求發送重設密碼郵件，並重設設密。操作員亦可在本系統為學員求發送重設密碼郵件，方法如下：<br>
在學員資料上右鍵並按下&nbsp;&nbsp;![](/images/20.png)&nbsp;&nbsp;，系統會詢問要否發送重設密碼郵件。

![](/images/32.png)

按下&nbsp;&nbsp;![](/images/23.png)&nbsp;&nbsp;發送重設密碼郵件。

按下&nbsp;&nbsp;![](/images/24.png)&nbsp;&nbsp;以取消當前操作。

> 有關發送重設密碼郵件按鈕消失，[按此了解](#右鍵功能選單)