# 個人記帳本
這是一個簡單又好用的記帳Web App，幫助你記錄生活的任何開銷!

![1](https://i.imgur.com/rF2Mc3k.png)
## 基礎環境設定
利用[Node.js](https://nodejs.org/en/)建立伺服器  
利用[mongodb](https://www.mongodb.com/)搭配[Robo 3T](https://robomongo.org/)建立資料庫

## 使用套件 
[express](https://expressjs.com/)   
[express-handlebars](https://www.npmjs.com/package/express-handlebars)   
[body-parser](https://www.npmjs.com/package/body-parser)   
[method-override](https://www.npmjs.com/package/method-override)   
[mongoose](https://mongoosejs.com/)   
[express-session](https://www.npmjs.com/package/express-session)   
[passport](http://www.passportjs.org/)   
[passport-local](http://www.passportjs.org/packages/passport-local/)   
[passport-facebook](http://www.passportjs.org/packages/passport-facebook/)   
[bcryptjs](https://www.npmjs.com/package/bcryptjs)   
[connect-flash](https://www.npmjs.com/package/connect-flash)   
[dotenv](https://www.npmjs.com/package/dotenv)
## 安裝步驟
```bash
1. git clone https://github.com/denny1011133/Expense-tracker.git
```
```bash
2. cd Expense-tracker
```
```bash
3. npm install
```
```bash
4. 新增種子資料
- 終端機上執行 npm run seed
- 確認在 Robo 3T 中的資料已經建立了
```
```bash
5. 建立.env的檔案，自行輸入相關資料
FACEBOOK_ID=<YOUR_FACEBOOK_APP_ID>
FACEBOOK_SECRET=<YOUR_FACEBOOK_APP_SECRET>
FACEBOOK_CALLBACK=<YOUR_FACEBOOK_REDIRECT_URI>
```
```bash
6. 執行程式
終端機輸入: npm run dev
開啟網頁輸入: http://localhost:3000
```
## 測試帳號
  name: Jack
  
  email: Jack@example.com
  
  password: 123456

## 功能
1. 可以瀏覽所有支出的明細及總金額

2. 可以新增一筆支出

3. 可以編輯單筆支出

4. 可以刪除任何一筆支出

5. 可以根據支出「類型」篩選支出

6. 可以根據支出「月份」篩選支出









