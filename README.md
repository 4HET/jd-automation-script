京东购物车监控脚本

爬取京东app购物车，实现购物车监控（商品价格变动、商品到货、新增商品），并且将变动信息发送至手机

work_schedule.py为定时器程序，定时执行监控任务，work_schedule.exe为打包后的软件，直接点击即可启动

因为隐私问题，将send_message中的send函数隐去，需自己完善send函数后才可完整运行

json文件以及txt文件以负责存储数据采集过程中的中间数据以及最低价等，可以删除，但是在程序运行时又会重新产生，为了方便数据共享没有使用数据库，若个人使用可以用数据库替代