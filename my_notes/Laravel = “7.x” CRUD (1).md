# Laravel = "7.x" CRUD (1)  [2020-09-19]
### <font color="#f00">資料庫:</font>
* 集結Laravel跟Composer 套件網站 [packalyst](https://packalyst.com/)(使用套件功能要有安裝Composer )


#### <font color="#f00">新增新的資料庫</font>
![](https://i.imgur.com/hTcNQsX.png)
---

####<font color="#f00"> 創建資料表 </font>
![](https://i.imgur.com/6fU4QIu.png)

![](https://i.imgur.com/IOvZtOP.png)

* Q: 資料庫與project_03專案如何自動串接?
  A: 透過[Laravel Naming Conventions](https://webdevetc.com/blog/laravel-naming-conventions#section_naming-database-tables-in-laravel)(透過命名規範)和.env中設定


---

#### <font color="#f00">.env設定</font>
![](https://i.imgur.com/hqEev38.png)

* 整個專案的設定，是當你用composer建立檔案會自動產生
* 有可能在github下載的檔案可能不會有產生.env，可從.env.example中把需要的複製到新創建.env檔案中

![](https://i.imgur.com/ubWIdDp.png)

---
### <font color="#f00">Laravel UI (login & Register)安裝:</font>
* ui要跟你下載的laravel版本相同
*(此圖laravel 7.x version & ui 2.0)*
![](https://i.imgur.com/1WirH7D.png)

* google搜尋 laravel auth ui vue
![](https://i.imgur.com/OlP40ib.png)

![](https://i.imgur.com/5Ab41bn.png)

(無樣式 )專案中掛載boostrap4.5 CDN
![](https://i.imgur.com/1a5Qa7D.png)

![](https://i.imgur.com/qouPMqm.png)

CDN掛載成功
![](https://i.imgur.com/fdt4aWW.png)

* 專案中的resources File:放置所有的前端資料夾

### <font color="#f00">Laravel針對認證機制所使用的資料表啟動方法</font>
* 下達指令php artisan migrate 後會幫你把database>migrations>檔案(資料表)轉換成SQL語法傳到MySQL(project_3 )

![](https://i.imgur.com/YSxlrzO.png)

![](https://i.imgur.com/Ir1ZLVz.png)
### <font color="#f00">註冊會員</font>
創建好MY SQL資料表，就可以使用[註冊會員](http://localhost/project_03/public/register)
![](https://i.imgur.com/tuxYcq9.png)

資料表能看到已註冊的user
![](https://i.imgur.com/T76ECTL.png)

### <font color="#f00">persons 資料表新增十筆</font>
產生假資料網站: [身份](https://fauxid.com/fake-name-generator/taiwan ),[電話](http://blog.pulipuli.info/2016/06/random-mobile-phone-number-generator.html ),[姓名](http://www.richyli.com/name/index.asp )

* <font color="#f00">新增十筆假資料</font>
![](https://i.imgur.com/IlnwRz5.png)

###### tags: `Laravel` `網頁沙龍課程` `Laravel UI`

