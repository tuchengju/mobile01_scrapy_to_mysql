# mobile01_scrapy_to_mysql

資展國際大數據班BDSE26期末專題中使用的程式碼

1.mobile01_article_scraper.py : 爬取mobile01股票版的文章連結
2.check_scrapy.py : 比對現有資料，確認需要補爬的文章連結(第一次爬可以跳過這個步驟，但是要先去改3.的檔案路徑)
3.mobile01_data_scraper.py : 爬取2.產生的連結列表
4.mobile01_data_to_mysql.py : 將3.爬取的文章留言在mysql分別建立table
5.mobile01_rearrange.py : 將3.爬取的資料依照日期分別存成新的.csv(這個步驟也可以透過mysql資料庫取代)
