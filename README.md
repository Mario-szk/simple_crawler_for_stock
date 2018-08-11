# simple_crawler_for_stock_part1

抓取單月外資買超的股票代號、股票名稱、跟買超張數
注意：本文對於股市的看法僅代表個人意見，股市投資必然需要承擔風險，請投資人自行衡量。

簡介：
  在股票的籌碼面中，外資持續買超可以視為一個先行指標，可視為先行指標的原因基本有二：
  
  第一，外資資金龐大，因此無法一次買齊所需要的部位，所以通常需要分成數次，這其中可能是好幾天，也可能持續數星期，也因此，當外資剛開始持續買入的時候便是     散戶可以跟著上車的機會。
    
  第二，外資對於投資標的的選擇必須是經過仔細研究的，需要依據股票本身的基本面以及該產業的狀況來下決定，而非極短線的炒作，因此，外資持續買入可以被視為一     個中長期的趨勢，並且在基本面及產業上是更有保障的。
    
  既然了解到外資持續買超可視為一先行指標，那下一步自然就是開始觀察哪些股票是外資持續買入的對象，而這個簡單的程式也是專門為此設計的，這個程式能夠抓取單月中每日的外資買超對象前10名，並將其股票代號、股票名稱、買超張數記錄下來。


﻿日期,證券代號,股票名稱,買超張數
2018/3/6,2330,台積電,"15,089,413"
2018/3/6,2303,聯電,"8,919,869"
2018/3/6,2888,新光金,"7,207,000"
2018/3/6,2311,日月光,"6,268,637"
2018/3/6,2474,可成,"4,731,235"
2018/3/6,2337,旺宏,"3,749,918"
2018/3/6,2353,宏碁,"3,292,000"
2018/3/6,2884,玉山金,"2,714,000"
2018/3/6,2399,映泰,"2,602,000"
2018/3/6,2823,中壽,"2,506,000"
2018/3/7,00637L,元大滬深300正2,"19,349,000"
2018/3/7,2915,潤泰全,"8,477,394"
