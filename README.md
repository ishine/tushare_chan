# tushare_chan

使用 [tushare pro](https://tushare.pro/register?reg=7) 的数据进行缠论分析结果展示

## 启动方法

1. 在 `run_web.py` 文件中设置你的 Tushare token
2. 执行 `pip install -r requirements.txt` 安装环境
3. 执行 `python run_web.py` 启动，不要改端口！！！

启动后在本地 8005 端口访问服务，如：
http://localhost:8005/?ts_code=000001.SH&asset=I&trade_date=20200101&freqs=30min

其中，ts_code 为对应的标的代码，支持 tushare 的股票、指数代码；
asset 为标的类型，E表示股票，I表示指数
trade_date 为交易日期，freqs 为K线周期


