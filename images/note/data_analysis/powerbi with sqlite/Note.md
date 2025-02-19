## PowerBi 連線 SQLite

### 注意事項
- 確認電腦是否有安裝 [SQLite ODBC driver for Win64](https://www.ch-werner.de/sqliteodbc/)

<img src="0.png">

### 方法1
1. Windwos 搜尋 **"ODBC資料來源"**
<img src="1_1.png">

2. 新增 **"ODBC 資料來源管理員"** SQLite 資料庫。
    - Data Source Name：設定資料名稱，可以自己設定。
    - Database Name：設定db檔案位置。
<img src="1_2.png">

3. 設定 **"資料來源名稱(DSN)"**
<img src="1_3.png">

4. 匯入 **"資料表"**
<img src="2_4.png">

### 方法2
1. 找尋**ODBC**
<img src="2_1.png">

2. 點選**SQLite3 Datasource**
<img src="2_2.png">

3. **進階** -> 連接字串輸入**database=[檔案位置]**
<img src="2_3.png">

4. 確定資料表狀態
<img src="2_4.png">
