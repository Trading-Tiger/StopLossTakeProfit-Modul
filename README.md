# :rocket: ProfitHunter Modul :rocket:
### No more Cross liquidations with our StopLossTakeProfit module!  
![alt text](https://trading-tigers.com/assets/img/TradingTigers-TIGS-.png)
##### It checks your open positions for take profit and stop loss, if your position has been changed, the old take profit limit order is deleted, and a new one is created  
Trading-Tigers ProfitHunter(StopLossTakeProfits) is able to detect and execute an opportunity on different trading pairs at high speed.  
This is not comparable to the human trader who has to enter an order manually, at the same time, this has no emotions and executes stop loss directly.  
It eliminates the physical aspect of being glued to your screen tracking your currencies.  
You have the power to effortlessly monitor more currencies at once.
### [CHECK MORE MODULES AND INDICATORS](https://Trading-Tigers.com)
### [TradingTigers Token @BSC](https://bscscan.com/token/0x34faa80fec0233e045ed4737cc152a71e490e2e3)
## Your benefits of our software.
#### READY FOR ALL!
Suitable for experienced, advanced and novice traders, perfect for learning.  

#### EARN WHILE YOU SLEEP!
The automated TradingTiger bots work 24/7 so you don't have to.  
#### QUICK AND EASY TO SET UP!
Little to no trading experience or programming knowledge required.  
You can run multiple trading pairs on the same exchange and check for Take Profit and Stop Loss.
#### !!!!PLEASE MAKE SURE TRADING LEVERAGE IS HIGH RISK!!!!!! 

## Preview
![alt text](https://raw.githubusercontent.com/Trading-Tiger/StopLossTakeProfit-Modul/main/preview.PNG) 
## Enter our Community
[![Discord Shield](https://discordapp.com/api/guilds/766340441075089418/widget.png?style=banner2)](https://discord.gg/xAGZHAr)  

## Download  
[Find a version for your system at Releases](https://github.com/Trading-Tiger/StopLossTakeProfit-Modul/releases/)  

## Settings

#### Api Keys  
Never give your API Key authorization to withdrawal, make sure that you enable trading and futures. 
#### coins
"coins" : ["BTCUSDT", "XRPUSDT" , "ADAUSDT" ], -> Pairs to Trade on Binance Future.  
You can find a complete COIN list [HERE](https://github.com/Trading-Tiger/Supported_Trading_Pairs/blob/main/Binance_Future_Pairs.json).
#### bsc_Secret-Key  
Binance-Smart-Chain Private-Key with Trading Tiger Tokens (TIGS).[BUY TIGS Bakeryswap](https://exchange.pancakeswap.finance/#/swap?outputCurrency=0x34faa80fec0233e045ed4737cc152a71e490e2e3) 
#### Take Profit & Stop Loss  
How To Calculate?? E.g. "1% * Leverage" = Real Percent  
"Percent_take_profit" : 1.3 -> Take Profit Percentage Calculated from the entry price without leverage. Its Uses LIMIT orders.  
"Percent_stop_loss" : 3 -> Stop Loss Percentage Calculated from the entry price without leverage. Its Uses MARKET orders and enforces them if they are below their value in percentage terms  
#### Discord  
You want to receive notifications about achieved stop loss, no problem, activate it and add your Discord webhook URL.  
"discord" : true,  
"discord_webhook": "https://discord.com/api/webhooks/7952906218/qOc_NnbAywZecawB0",  
#### Interval  
"interval_time" : 1 -> Sleep Time From Coin to Coin.  E.g. Check BTCUSDT Sleep(1Sec)... Check ETHUSDT Sleep(1sec)... Check BTCUSDT Sleep(1sec)...  
## Optional
Install [Nodejs](https://nodejs.org/en/)  
Open CMD or SHELL with Admin
```javascript
npm install pm2 -g
```
Then you can start your Tiger Tool with:
```javascript
pm2 start <appname> --name "<set_name>"
```
And Monitoring it with:
```javascript
pm2 monit
```
Some more PM2 commands:
```javascript
pm2 status
pm2 restart <APP_Name>
pm2 stop <APP_Name>
pm2 delete <APP_Name>
```

## Greetings, 
## Seven
