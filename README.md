# easyquant

基于 `easytrader` 和 `easyquotation` 的简单量化交易框架
事件引擎借鉴 `vnpy` 
有兴趣的可以加群 `429011814` 一起交流

使用 `easyquotation` 每秒推送一次所有股票的五档行情
并调用策略执行

### requirements

* python 3.5
* pip install -r requirements.txt

### 使用 

在 `me.json` 中填入你的华泰信息，然后运行以下命令即可看到效果


```
python test.py
```

### 策略

策略用 `Python` 编写后置于 `strategies` 文件夹下
格式参考其中的 `Demo`
